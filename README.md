# Amazon Product Reviews Analysis

This repository contains a Jupyter Notebook script for analyzing Amazon product reviews using Python. The script performs sentiment analysis and generates word clouds to visualize the most frequent positive and negative words in the reviews.

## Prerequisites

Before running the script, ensure you have the following libraries installed:

- NumPy
- pandas
- spaCy
- spaCy TextBlob
- wordcloud
- matplotlib

You can install these libraries via pip:
`pip install numpy pandas spacy spacytextblob wordcloud matplotlib`

## Usage

Clone the repository to your local machine:

`git clone https://github.com/yourusername/amazon-product-reviews-analysis.git`

Navigate to the repository directory:
`cd amazon-product-reviews-analysis`

Place your Amazon product reviews dataset in CSV format in the repository directory with the filename amazon_product_reviews.csv.
Open the Jupyter Notebook amazon_product_reviews_analysis.ipynb using Jupyter Notebook or JupyterLab:
jupyter notebook amazon_product_reviews_analysis.ipynb
Run each cell in the notebook to execute the script step by step.

## Description

Importing Libraries: The script begins by importing necessary libraries including NumPy, pandas, spaCy, spaCy TextBlob, and others.
Loading Dataset: The Amazon product reviews dataset is loaded into a pandas DataFrame for analysis.
Data Cleaning: Rows with missing values are dropped from the dataset.
Text Preprocessing: A function is defined to preprocess the text data by removing stopwords, punctuation, and lemmatizing words.
Sentiment Analysis: Another function is defined to perform sentiment analysis using spaCy TextBlob.
Word Cloud Generation: Word clouds are generated to visualize the most frequent positive and negative words in the reviews.
