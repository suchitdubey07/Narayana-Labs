# Compute Strategy

## GPU Compute Strategy
Narayan Labs leverages a hybrid compute strategy balancing cost, availability, and scale.

### Multi-Node Training Clusters
For base model training and CPT, we require highly interconnected multi-node setups (e.g., H100s or A100s interconnected via InfiniBand). These are typically sourced via partnerships with domestic cloud providers (e.g., E2E Networks, Yotta).

### Prosumer / Contributor Nodes
For SFT and LoRA adapters, we actively encourage and support training on consumer-grade hardware (RTX 3090s/4090s or Mac Studio unified memory architectures) to democratize participation.

## Cloud vs. Local Options
1. **Cloud Instances**: Used dynamically for massive short-term workloads (data preparation, heavy evaluations).
2. **On-Premise / Bare Metal renting**: The primary avenue for our multi-week distributed training runs to maintain predictable billing.

## Decentralized Compute (Future)
We are actively researching methods to pool compute resources from community contributors for asynchronous federated training of SLMs.
