# Data Pipeline Architecture

Our data pipeline processes raw text into clean, model-ready training corpora using distributed processing.

## Scraping and Ingestion
- Scalable, specialized spiders using Scrapy to gather data from state government portals, legal repositories, and open educational sources.
- Rate limiting and respect for `robots.txt` are mandatory.

## Cleaning and Normalization
1. **Deduplication**: MinHash/LSH for exact and near-deduplication.
2. **Language Identification**: FastText-based filtering to ensure language purity.
3. **Script Normalization**: Handling variations in Indic scripts (e.g., zero-width joiners) and unicode normalization.

## Labeling Methods
- **Synthetic Augmentation**: Bootstrapping initial instruction-tuning datasets using larger open models.
- **Expert Annotation**: Final phase verification and RLHF scoring strictly performed by domain experts (e.g., lawyers for legal data, agronomists for agriculture data).

## Example Sources
- **Legal judgments**: e-Courts, IndiaCode.
- **Financial regulations**: RBI circulars, SEBI master directions.
- **Public Policy Docs**: PIB releases, Ministry yearly reports.
