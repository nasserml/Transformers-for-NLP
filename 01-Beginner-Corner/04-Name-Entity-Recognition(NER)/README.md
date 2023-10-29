# Named Entity Recognition (NER) Using Hugging Face Transformers

This Jupyter Notebook is an illustrative guide to performing Named Entity Recognition (NER) using Hugging Face's Transformers library. It focuses on leveraging the `ner` pipeline for entity recognition and assessing model performance.

## Introduction

The notebook demonstrates the usage of the Hugging Face Transformers library to perform Named Entity Recognition (NER) tasks. It covers data retrieval, processing, evaluation of model performance, and an in-depth explanation of the NER process using a pre-trained language model.

## Setup and Data Retrieval

The notebook begins by installing the Transformers library using pip. It fetches a pre-trained NER model and datasets (ner_train.pkl, ner_test.pkl) from an external source to utilize in the NER task.

## Named Entity Recognition (NER) Process

The notebook uses the pre-trained NER model from Hugging Face's Transformers library to recognize named entities in the test dataset. It processes the data, tokenizes text, and performs NER predictions on the dataset using the `ner` pipeline.

## Model Evaluation

The notebook evaluates the model's performance by calculating accuracy scores and F1 scores. It showcases how the model's predicted tags compare to the actual targets for named entities, providing insights into the model's accuracy and precision in recognizing entities.

## Notes

The primary focus of this notebook is to demonstrate the NER process using the Hugging Face Transformers library. It covers data loading, model prediction, performance evaluation, and result interpretation for named entity recognition.

For comprehensive details, code walkthroughs, and insights, refer to the original "02_Pipeline_NER.ipynb" file. The notebook contains detailed comments, explanations, and results at each step of the NER process.
