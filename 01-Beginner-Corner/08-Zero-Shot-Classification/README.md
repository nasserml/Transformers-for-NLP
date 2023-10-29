# Zero-shot Text Classification on Airline Tweets using Hugging Face Transformers

This Jupyter Notebook showcases zero-shot text classification on a dataset of airline tweets using the Hugging Face Transformers library. It illustrates how to leverage pre-trained models to perform text classification without fine-tuning the model on specific labels.

## Overview

The notebook demonstrates how to use the Transformers library for zero-shot text classification. It focuses on the application of pre-trained models to predict the sentiment of airline-related tweets, showcasing how the model can make predictions without having specific training on the exact sentiment labels.

## Dataset and Setup

The notebook begins by downloading the 'AirlineTweets.csv' dataset, installing the necessary Python packages, and loading the required pre-trained models for text classification. It then reads the dataset and explores the content and labels present in the dataset.

## Zero-shot Text Classification

The notebook uses the zero-shot text classification pipeline to classify the sentiment of airline-related tweets into 'negative,' 'neutral,' or 'positive' categories. It provides code examples and outputs demonstrating the predictions made by the model for different tweet samples from the dataset.

## Evaluation and Metrics

The notebook evaluates the model's performance by calculating metrics such as accuracy, F1 score, and ROC-AUC score. It also generates a confusion matrix to visualize the predicted labels against the actual labels in the dataset.

## Conclusion

The notebook aims to exhibit the capabilities of zero-shot text classification using pre-trained models for sentiment analysis of airline-related tweets. It illustrates how this approach can predict sentiments without fine-tuning the model to specific classes.

For more detailed explanations, in-depth code explanations, and additional insights, refer to the original "03_Pipeline_Zero_Shot_Classification_AirlineTweets.ipynb" file. The notebook contains extensive comments, code snippets, and outputs showcasing the zero-shot classification process using Hugging Face Transformers.
