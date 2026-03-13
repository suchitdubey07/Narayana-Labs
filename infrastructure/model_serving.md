# Model Serving

## Deployment Approach
Inference latency and cost are the primary barriers to AI adoption in India. Our model serving architecture is designed to address this.

## Inference Engines
- **vLLM**: The primary engine for cloud-based inference, offering high throughput via PagedAttention.
- **llama.cpp**: Utilized for edge deployments, quantized models (GGUF), and environments lacking dedicated GPU accelerators.

## Serving Architecture
- Models are packaged into containerized services exposing an OpenAI-compatible API.
- We implement strict dynamic batching and speculative decoding where possible to maximize hardware utilization.
- Heavy use of INT8, FP8, and 4-bit quantization allows models like an 8B SLM to comfortably serve requests on relatively inexpensive hardware with minimal degradation in domain-specific tasks.
