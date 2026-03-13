# Indian Legal AI

## Objective
To build an SLM specialized in understanding, summarizing, and querying the Indian legal landscape, including the Constitution, IPC/BNS, CrPC/BNSS, and prominent case laws.

## Key Datasets Required
- Supreme Court judgments (e-SCR).
- High Court judgments.
- Bare Acts (Central and State).
- Law Commission reports.

## Challenges
- Complex legal jargon and long-context documents.
- The critical necessity of avoiding legal hallucinations.
- Frequent references to older colonial terminologies alongside modern amendments.

## Approach
The primary strategy is Continual Pre-Training (CPT) on an Indian legal corpus, followed by instruction fine-tuning using synthetically generated legal queries and expert-annotated responses. Retrieval-Augmented Generation (RAG) architecture is mandatory for deployment.
