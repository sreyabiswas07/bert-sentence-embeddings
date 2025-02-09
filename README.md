# bert-sentence-embeddings
A simple example of generating sentence embeddings using BERT and Hugging Face Transformers
This repository contains a basic example of generating sentence embeddings using BERT with the transformers library in Python. The script tokenizes input sentences, passes them through a pre-trained BERT model (bert-base-uncased), and computes embeddings using mean pooling.

#Features
Uses Hugging Face Transformers (BertTokenizer & BertModel)
Tokenizes and processes multiple sentences
Extracts contextual embeddings for each sentence
Implements mean pooling to generate fixed-size sentence vectors

#Usage
Run the script in Google Colab or locally after installing dependencies
!pip install transformers torch
