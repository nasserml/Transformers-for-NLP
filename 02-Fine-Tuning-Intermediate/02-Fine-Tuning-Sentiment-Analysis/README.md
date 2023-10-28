# Fine-Tuning Sentiment Analysis with Hugging Face Transformers

This Jupyter Notebook demonstrates how to fine-tune a pre-trained transformer model for sentiment analysis using the Hugging Face Transformers library.

## Introduction

The notebook primarily focuses on utilizing Hugging Face's `transformers` library to fine-tune a transformer model for sentiment analysis on the SST-2 (Stanford Sentiment Treebank) dataset. The model used is `distilbert-base-uncased` and is fine-tuned to perform sentiment analysis on sentence-level data.

## Data Processing

The notebook starts with loading the SST-2 dataset from the Hugging Face `datasets` library and explores the structure of the training dataset. It then uses the `AutoTokenizer` to preprocess the text data for the model's consumption.

## Fine-Tuning the Model

It fine-tunes the transformer model by preparing the training arguments, initializing the model for sequence classification, and sets up the training with a custom metric function based on accuracy. The notebook demonstrates how to utilize the `Trainer` from the `transformers` library to conduct the fine-tuning process.

## Evaluation and Inference

The fine-tuned model is evaluated using the validation dataset, and it computes metrics such as accuracy for the sentiment classification task. The notebook also showcases how to save the fine-tuned model for future use and demonstrates how to load and utilize the saved model using the Hugging Face `pipeline`.

## Model Inspection

Towards the end, the notebook inspects the model's parameter differences before and after fine-tuning, providing insights into the changes that occurred during the training process.

## Requirements

To execute the notebook, ensure you have the necessary libraries installed. The key dependencies are:

- `transformers` and `datasets` by Hugging Face
- `torch` (PyTorch) version 1.13.1
- `accelerate` for faster model training
- `torchinfo` for model summary

## Note

The notebook is designed as an educational guide and demonstrates a concise yet comprehensive workflow for fine-tuning a sentiment analysis model. It's highly recommended to further explore and customize the notebook based on specific project requirements.

For a detailed understanding of the notebook, refer to the original "01_Fine_Tuning_Sentiment_Analysis.ipynb" file.
