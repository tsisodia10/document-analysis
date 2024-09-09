# Document Analysis using OpenAI GPT-3
This repository provides a set of examples for performing document analysis using OpenAI's GPT-3 language model. They are:

1. Data Exploration - Explore data used in this repo.
2. Get Embeddings - Generate embeddings from documents using gpt-35-turbo.
3. Classify Documents - Use gpt-35-turbo to classify documents into different categories.

## BBC News Articles Analysis
This project is a data analysis of the BBC news dataset. The goal of this project is to explore the data and classify documents into categories.

## Dataset
The dataset used in this project is the BBC News Archive available from kaggle. It contains 2225 articles from the BBC news website with 5 different categories: business, entertainment, politics, sport and tech. Each article has a category, filename, title and text.

## Language Model
Examples in this repo uses gpt-35-turbo.

## Notebooks
This project consists of notebooks that perform the following tasks:

00-explore-data.ipynb - This notebook explores the data by looking at the distribution of classes, number of words per document, etc.
01-get-embeddings.ipynb - This notebook uses pre-trained word embeddings to create vector representations for each document.
02-classify-documents.ipynb - This notebook builds classification models using gpt-35-turbo to classify each document.

## References
OpenAI repo: https://github.com/openai/openai-cookbook/

Azure Document Analysis reference repository - https://github.com/Azure/azure-openai-samples/tree/main/use_cases/archive/document_analysis
