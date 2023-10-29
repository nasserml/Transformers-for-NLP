# Sentiment Analysis Using Hugging Face Transformers Pipeline

This Jupyter Notebook demonstrates sentiment analysis on airline tweets using the Hugging Face Transformers library and its pre-built sentiment-analysis pipeline.

## Introduction

The notebook focuses on performing sentiment analysis on airline tweets obtained from the Kaggle dataset titled "Twitter US Airline Sentiment." The sentiment analysis is done using the Hugging Face Transformers library's pre-trained sentiment-analysis pipeline.

## Data and Setup

The notebook begins by installing the required `transformers` library and downloading the dataset containing airline tweets. The notebook utilizes the sentiment-analysis pipeline from the Hugging Face Transformers library to analyze the sentiment of the tweets.

## Model Usage

The notebook showcases how the sentiment-analysis pipeline can evaluate sentiment in text, including both positive and negative sentiments. It demonstrates using single sentences, multiple inputs in a list, and leveraging the GPU for faster inference.

## Sentiment Analysis on Airline Tweets

Using the sentiment-analysis pipeline, the notebook performs sentiment analysis on the provided airline tweets. It uses the classifier to predict sentiment and compute probabilities. Furthermore, it evaluates the accuracy of the sentiment predictions, calculates the F1 score, and generates a confusion matrix for the sentiment predictions.

## Evaluation Metrics

The notebook computes various evaluation metrics, including the F1 score and ROC AUC score. It also explores the confusion matrix to visualize the true positives, true negatives, false positives, and false negatives in sentiment predictions.

## Note

The notebook provides a comprehensive overview of how to perform sentiment analysis on airline tweets using Hugging Face's pre-trained sentiment-analysis pipeline. It's encouraged to adapt and explore this notebook to conduct sentiment analysis on different datasets or modify for specific project needs.

For a detailed understanding, refer to the original "02_PipelineSentimentAnalysis.ipynb" file. The notebook itself contains additional insights, comments, and visualizations for each step of the sentiment-analysis process.
