# Fine-Tuning Recognizing Textual Entailment (RTE) with Hugging Face Transformers

This Jupyter Notebook demonstrates the process of fine-tuning a transformer-based model for the Recognizing Textual Entailment (RTE) task using the Hugging Face Transformers library.

## Introduction

The notebook focuses on fine-tuning the transformer model `distilbert-base-cased` for the RTE task. Recognizing Textual Entailment involves determining whether a given statement entails another statement, contradicts it, or neither. The dataset used in this notebook combines data from RTE challenges (RTE1, RTE2, RTE3, and RTE5).

## Data Processing

The notebook starts by loading the RTE dataset using the Hugging Face `datasets` library and inspects the structure of the dataset. It showcases the sentence pairs along with the labels and gives insights into the text data from the training set.

## Model Preparation

Using the `AutoTokenizer` and `AutoModelForSequenceClassification`, the notebook initializes the model for sequence classification and its tokenizer to process the sentence pairs. It provides examples of tokenizing the sentence pairs and decoding the token IDs back into text.

## Training the Model

The notebook sets up the training arguments and the Trainer object to fine-tune the model. It defines a custom metric function using accuracy and F1 score for evaluation during training. The training process is initiated, detailing training epochs, loss, accuracy, and F1 scores.

## Requirements

To execute the notebook, make sure the following libraries are installed:

- `transformers` and `datasets` by Hugging Face
- `torch` (PyTorch) version 1.13.1
- `accelerate` for faster model training
- `sklearn` for metrics computation

## Note

The notebook showcases a complete pipeline for fine-tuning a model for the RTE task. However, it's encouraged to explore and customize the notebook according to specific project needs, like experimenting with different models, hyperparameters, or using other datasets.

For a comprehensive understanding of the notebook, refer to the original "01_Fine_Tuning_RTE.ipynb" file. Additional insights and comments are available within the notebook itself.
