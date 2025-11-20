---
title: "Developing Culturally Grounded Multilingual LLM for Emotion Detection"
excerpt: "Sep 2024 – Jan 2025<br/>"
collection: portfolio
---
**Situation:** Emotion signals in social media form the basis for large-scale behavioral and trend analysis, but multilingual LLMs struggle with emotion detection across languages due to cultural subjectivity and inconsistent emotional expression.

**Task:** Develop a culturally grounded, multilingual emotion-detection system capable of handling diverse languages with limited training resources.

**Action:** Performed instruction-based supervised finetuning of a multilingual LLM (mT5/GPT-based variants) separately for each target language to encode language-specific and culture-specific emotional cues. Implemented parameter-efficient adaptation using LoRA and quantization to reduce computational cost. Managed large-scale training on a cluster environment using Slurm and integrated the workflow with HuggingFace for data pipelines, model training, and evaluation.

**Result:** Produced culturally aligned LLM variants that substantially improved cross-lingual emotion detection accuracy, demonstrating that effective multilingual finetuning is feasible even with limited data and resources.

Tech stack: HuggingFace, GPT, mT5, Slurm & cluster computing, LoRA, quantization.


[Technical Report](https://aclanthology.org/2025.semeval-1.48/)
