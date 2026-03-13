# Agricultural Advisory AI

## Objective
To develop a Small Language Model capable of answering domain-specific queries regarding crop selection, disease identification, fertilizer application, and weather preparedness in multiple Indic languages.

## Key Datasets Required
- ICAR publications and advisories.
- State agricultural university extension materials.
- Meteorological data archives.
- Agmarknet pricing data.

## Challenges
- Deep multilingual requirement (dialect-level accuracy).
- Need for highly precise, localized recommendations preventing disastrous crop failures.
- Integration constraints with low-bandwidth feature phones or voice interfaces.

## Approach
We will begin by fine-tuning an SLM strictly on Hindi and Marathi advisory data before scaling to other languages. Evaluation will involve agricultural experts manually reviewing generated answers for hallucination and accuracy.
