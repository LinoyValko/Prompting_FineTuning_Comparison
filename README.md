# Fine-Tuning vs Prompting – A Comparative NLP Study
This project explores and compares two popular approaches in NLP model adaptation: **fine-tuning** and **prompting**. Using the IMDB movie review dataset for sentiment classification, I evaluate the effectiveness, accuracy, and efficiency of each method.

## Project Objectives

- Compare zero-shot and few-shot prompting against traditional fine-tuning.
- Evaluate performance on sentiment classification (positive/negative).
- Analyze trade-offs in accuracy, inference time, and complexity.

## Dataset

- **IMDB Movie Reviews** – A well-balanced dataset with 50,000 labeled movie reviews (binary sentiment).
- You can access the dataset via [Hugging Face Datasets – IMDB](https://huggingface.co/datasets/stanfordnlp/imdb).

## Methods Used

- **Fine-Tuning**: Adapted pre-trained Transformer models on labeled data.
- **Prompting**: Zero-shot and few-shot prompting using pre-trained language models (e.g., T5, GPT-based).
- **Metrics**: Accuracy, F1 score, inference time, resource usage.

## Key Results

- **Fine-Tuning** generally yields higher accuracy but requires more training time and compute.
- **Few-shot prompting** offers a good balance between performance and resource usage.
- **Zero-shot prompting** is fast and flexible, but less accurate in nuanced cases.

## Conclusions

Prompting is a powerful and efficient alternative to fine-tuning, especially when resources or labeled data are limited. However, fine-tuning remains the best option when performance is the top priority.

