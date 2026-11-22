---
type: source
title: RAGAS- Automated Evaluation of Retrieval Augmented Generation.txt
source_path: raw/RAGAS- Automated Evaluation of Retrieval Augmented Generation.txt
ingested: '2026-11-22'
created: '2026-11-22'
tags: []
---
# Ragas: Automated Evaluation of Retrieval Augmented Generation

The paper introduces Ragas, a framework designed for the reference-free evaluation of Retrieval Augmented Generation (RAG) systems. RAG systems combine retrieval and language model (LM) components to enhance the capabilities of LMs by providing them with relevant context from external databases. This integration aims to reduce hallucinations—instances where LMs generate incorrect or nonsensical information. The authors highlight the challenges in evaluating RAG architectures, emphasizing the need for metrics that assess the retrieval system's effectiveness, the LMs' ability to utilize retrieved passages, and the overall quality of the generated content.

Ragas proposes a suite of metrics that can evaluate these dimensions without relying on human annotations, thereby facilitating quicker evaluation cycles. The framework integrates with popular tools like llama-index and Langchain, making it accessible for developers. The authors also discuss the limitations of traditional evaluation methods, which often depend on human-annotated datasets, and present their new dataset, WikiEval, to support the evaluation of RAG systems based on faithfulness, answer relevance, and context relevance. The results indicate that Ragas aligns closely with human judgments, particularly in assessing faithfulness and answer relevance.
