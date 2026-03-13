# Dataset Guidelines

High-quality datasets are the foundation of Narayan Labs' Small Language Models. We adhere to strict guidelines for data collection, cleaning, and publication.

## 1. Licensing and Provenance
- All data must have clear provenance. We only accept data that is in the public domain, licensed under permissive licenses (e.g., CC BY, CC0), or scraped under strict fair-use / academic exceptions tailored for India.
- Document the source URL, retrieval date, and original language for every record.

## 2. Quality and Representation
- **Multilingual Support**: Prioritize parallel corpora between Hindi/English and regional languages.
- **Toxicity and Bias filtering**: All datasets must pass through our automated and manual bias/toxicity filters designed for the Indian cultural context.

## 3. Format
We standardize on Parquet for large tabular datasets and JSONL for conversational/instruction-tuning datasets.

## 4. Privacy
- PII (Personally Identifiable Information) must be scrubbed using automated NER models before any dataset is saved to our central repositories.
