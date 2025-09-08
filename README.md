# Automated Assessment of Information Loss in Simple English Wikipedia

This repository contains the final materials of my Master’s Thesis:
Automated Assessment of Information Loss in Simple English Wikipedia
(University of Mannheim, September 2025)

## Abstract
This thesis investigates information loss in text simplification, focusing on English Wikipedia and Simple English Wikipedia. While simplification improves accessibility, it often omits or alters factual details, reducing the reliability of simplified knowledge. To address this, we constructed a dataset of 10,000 aligned article pairs with topic labels and developed an automated framework to quantify information loss. This framework applies three Large Language Models (LLaMA-3-8B-Instruct, Mistral-7B-Instruct-v0.3, and Gemma-2-9B) to generate semantic retention scores and lists of retained and lost facts for fact-level comparisons. Internal validation was performed through consistency checks and pairwise correlation, while external validation involved a human-annotated subset of 50 article pairs from diverse topics. Results show that LLMs identify broad patterns of information loss but often struggle with balanced fact extraction, reducing precision and recall. Further analysis reveals topic-specific trends: Culture and Geography articles tend to preserve information, whereas STEM and History/Society articles show greater loss. These findings indicate that while LLMs are useful for recognizing general trends in information loss, significant challenges remain for their reliability in detailed assessments.

## Repository Contents
- data/
  - final_dataset.csv – Final aligned dataset used in the thesis
  - human_validation_dataset.csv – Anonymized dataset for human validation
- codebook/FinalCodebook.ipynb – Analysis codebook (end-to-end)
- thesis/
  - MasterThesis_SeoyoungYoo.pdf – Final thesis PDF
  - latex/ – Complete LaTeX sources
- human_validation/README.md – Google Drive links (overview Excel, summary slides)

## Human Validation
- Human Validation Overview(Excel): [Open](https://docs.google.com/spreadsheets/d/1wfQZiM_U0BEts2q37a_Dv4QuGHkImtnYW3S10GL99us/edit?usp=sharing)
- Details of Results (Slideㄴ): [Open](https://docs.google.com/presentation/d/18S-WZAQQgLKUqyyIYnzbPGmvQ6a6C9MEEI4fB_NAWto/edit?usp=sharing)

## Reproducibility
1. Open codebook/FinalCodebook.ipynb.
2. Start from the section titled Final Analysis and run cells in order.
3. Input data is read from data/, outputs are described in the notebook.


## Contact
For questions, please contact: seoyoung.yoo@students.uni-mannheim.de