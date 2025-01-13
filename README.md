# BERT Sentiment Analysis  
This repository contains a sentiment analysis project using a BERT model after training it on a dataset of UCI ML Drug Reviews from Kaggle (https://www.kaggle.com/datasets/jessicali9530/kuc-hackathon-winter-2018).
All credit for the dataset goes to the respective owners. There is also a seperate dataset for testing the model.

The notebook can be tweaked to give labeled and/or probabilistic sentiment score of a review. The model itself is sophisticated but I would say there is significant room for improvement given more resources for training the model.

It can also be ammended to perform sentiment analysis on other product categories by retraining the model.
Currently due to resource limitations the model was ran on a small batch size of 32 iterations per batch with 2 epochs.

## Files
- `bert_sentiment_analysis.ipynb`: Python notebook for sentiment analysis.

## Requirements
- Python 3.x
- Transformers library
- PyTorch (or TensorFlow)

## Usage
Run the notebook to reproduce the sentiment analysis results.
Replace the hugging face user api with your own credentials. The notebook will ask you to input a Weights and Biases API as well. It can be obtained through a trial or an academic license(I used the latter).

## Licenses
- Hugging Face API for BERT access
- Weights and Biases API for BERT model training and storage
