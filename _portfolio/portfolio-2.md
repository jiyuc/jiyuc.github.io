---
title: "SuicideWatch: A Clpsych-2024 Shared Task"
excerpt: "December 2023 – Jan 2024<br/>"
collection: portfolio
---
**Situation:** Posts on [*r/SuicideWatch*](https://www.reddit.com/r/suicidewatch) often contain severe self-harm or suicidal ideation. Existing safeguard systems can flag high-risk posts but provide little transparency about which parts of the text triggered the alert.

**Task:** Build a privacy-preserving, interpretable system that can highlight the specific text segments that correspond to suicidal ideation risk categories.

**Action:** Deployed a locally hosted, quantized 70B LLM model to ensure data privacy and efficient inference. Used prompt engineering to align the model with a psychological suicidal-ideation coding framework, and integrated the workflow using LangChain to extract fine-grained text segments that match the flagged risk signals.

**Result:** The system produced the most precise and interpretable risk explanations in the evaluation, outperforming all competing participants and achieving the top ranking.

Tech stack: LLM(LLaMA), quantization, LangChain.


[Technical Report](https://aclanthology.org/2024.clpsych-1.17/)
