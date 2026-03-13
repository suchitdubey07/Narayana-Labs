# Small Language Model (SLM) Architecture

## The SLM Philosophy
At Narayan Labs, SLMs are defined as models typically ranging from 1B to 8B parameters. These models are small enough to be deployed locally but, when trained on extremely high-quality, domain-specific data, can punch above their weight class on targeted tasks.

## Base Models
We heavily utilize and experiment upon existing efficient open-weight models as our foundational starting points:
- **Mistral v0.2 / v0.3 (7B)**
- **Meta Llama 3 (8B)**
- **Microsoft Phi-3 (3.8B)**
- **Qwen-2 / Qwen-2.5 (1.5B, 7B)**

## Fine-Tuning Strategy
- **Continual Pre-Training (CPT)**: Expanding the tokenizer to efficiently represent Indic scripts and continually pre-training on our massive regional datasets.
- **Supervised Fine-Tuning (SFT)**: High-quality instruction following based on domain-specific pairs.
- **DPO / RLHF**: Preference tuning specifically aligned with Indian values, safety standards, and factual groundings.

## Domain Specialization
Instead of one massive generalized model, we create distinct expert models. A base 4B parameter model is cloned and selectively fine-tuned for Agriculture, Law, etc., allowing for lightweight, swappable "expert architectures" during deployment.

## Multilingual Training Approach
Tokenizers are expanded initially to support Devanagari, Bengali-Assamese, and Dravidian scripts to reduce token parity issues (where typing in Hindi costs 4x the tokens compared to English).
