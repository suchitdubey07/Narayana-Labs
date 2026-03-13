# Model Training Pipeline

This document details the software and hardware stacks for training our open models.

## Stack
- **Frameworks**: PyTorch, Hugging Face `transformers`, `accelerate`.
- **Training Libraries**: Unsloth, TRL, Axolotl (for configuration-driven distributed fine-tuning).

## Phases

### 1. Data Processing
Tokenization is handled offline via Apache Spark or Ray, creating highly compressed, chunked Memmap datasets.

### 2. Parameter-Efficient Fine-Tuning (PEFT)
For low-resource experiments and specific task architectures, we utilize LoRA and QLoRA. This allows contributors to train domain adapters on single consumer GPUs (e.g., RTX 3090/4090).

### 3. Full Fine Tuning and CPT
Executed across our distributed clusters utilizing FSDP (Fully Sharded Data Parallel) to shard model states across multiple GPUs efficiently. 

### 4. Evaluation
Automated evaluation using Lighteval and LM-Eval-Harness against localized benchmarks like IndicGLUE, translated MMLU, and our custom internal domain test sets.
