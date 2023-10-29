# Text Translation Using Hugging Face Transformers

This Jupyter Notebook demonstrates the process of language translation using Hugging Face's Transformers library. The notebook focuses on translating English phrases to Spanish and evaluates the quality of the translations.

## Introduction

The notebook provides a step-by-step guide to using Hugging Face's Transformers library for language translation. It covers the setup of required data, loading of translation models, translation tasks, evaluation metrics, and the assessment of translation quality using BLEU scores.

## Setup and Data Retrieval

The notebook begins by downloading a Spanish-English translation dataset from an external source. The data is unzipped and loaded for translation tasks. The notebook contains code snippets to preprocess and tokenize the phrases for translation.

## Text Translation Process

The notebook utilizes the Hugging Face pipeline for translation tasks. It loads the pre-trained translation model 'Helsinki-NLP/opus-mt-en-es' for English to Spanish translations. It then translates a subset of English phrases into Spanish and evaluates the translation quality.

## Evaluation Metrics

The notebook uses the BLEU (Bilingual Evaluation Understudy) score from the NLTK library to evaluate the quality of the translations. BLEU scores help measure the similarity between the generated translations and human reference translations.

## Results and Analysis

The notebook computes BLEU scores for the translated phrases and visualizes the distribution of scores using a histogram. It demonstrates how the translations compare to human reference translations using the BLEU score as an evaluation metric.

## Notes

The primary focus of this notebook is to provide an introductory guide to language translation using the Hugging Face Transformers library. It includes code snippets to download datasets, load translation models, translate text, evaluate translation quality, and assess translations using BLEU scores.

For detailed information, code explanations, and further insights, refer to the original "01_Pipeline_Translation.ipynb" file. The notebook contains comprehensive comments, explanations, and visualization of translated text from English to Spanish, including evaluation using BLEU scores.
