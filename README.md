# Project Title

This project explores the integration of biomedical knowledge into pre-trained language models (PLMs) and large language models (LLMs). The focus is on improving the performance of these models on biomedical tasks by leveraging domain-specific datasets and fine-tuning techniques.

## Overview

The `Disease BERT` model is specifically designed for biomedical applications. It undergoes a two-phase training process:

1. **Pre-training**: The `Disease BERT` model is pre-trained on the [Disease Ontology](https://disease-ontology.org/) dataset for 40 epochs. This step integrates extensive biomedical knowledge into the model, enhancing its ability to understand and process biomedical texts.
2. **Fine-tuning**: Both the `General BERT` and `Disease BERT` models are fine-tuned on the NCBI disease dataset for 10 epochs. This step ensures that the models are specifically adapted to the biomedical domain.

## Final Results

The table below shows the final F1 scores for both models after the fine-tuning process:

| Model         | F1 Score |
|---------------|----------|
| General BERT  | 0.845455 |
| Disease BERT  | 0.846271 |

### Conclusion

Both models achieve very similar F1 scores, indicating that their overall performance in terms of precision and recall is comparable. The `Disease BERT` model has a slightly higher F1 score, suggesting a marginally better performance in balancing precision and recall for specific biomedical tasks. This demonstrates the effectiveness of domain-specific tuning in enhancing model performance for specialized applications.

By leveraging the domain-specific pre-training on the [Disease Ontology](https://disease-ontology.org/) dataset and fine-tuning on the NCBI disease dataset, the `Disease BERT` model achieves superior performance, making it a valuable tool for biomedical natural language processing tasks.
