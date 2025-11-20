---
title: "Exploration of automatic relation extraction in narrow knowledge domain with limited data"
excerpt: "March 2018 – June 2019<br/>"
collection: portfolio
---
Situation: NCBI Gene contains millions of gene ontology (GO) annotations, but many records include inconsistent or low-quality metadata, and no existing method can evaluate annotation quality at scale.

Task: Develop an automated system that can identify poor-quality GO annotations by leveraging both the semantic information in biomedical literature and the structural knowledge in the GO graph.

Action: Redesigned the backbone of a BERT-based transformer model and integrated it with a Graph Neural Network to jointly model distributional semantics and graph topology. Built the end-to-end system in PyTorch using the HuggingFace Transformers framework, including data preprocessing, GO graph construction, and large-scale evaluation pipelines tailored to biological databases.

Result: Delivered a state-of-the-art quality-assessment model capable of detecting major annotation issues across NCBI Gene, providing the first scalable and effective automated QA solution for GO annotations.

Tech stack: Transformer, BERT, GNN, PyTorch, HuggingFace.

https://findanexpert.unimelb.edu.au/project/104203-automated-assessment-of-data-quality-in-biological-knowledge-resources
