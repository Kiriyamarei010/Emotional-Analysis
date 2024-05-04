# Emotional-Analysis
Project Summary:
Project Title: Emotional Analysis of Ex-Military Soldiers' Podcast Conversations

Objective: The main goal of this project was to analyze the emotions expressed during conversations among ex-military soldiers discussing their struggles on a podcast.

Techniques Used:

Sentiment Analysis:
Utilized the Afinn library to calculate sentiment scores for each article in the podcast transcripts.
Emotional Analysis:
Employed a Naive Bayes classifier for emotional analysis of the podcast conversations.
Dependencies: Pandas, NumPy, Matplotlib, Neattext for data handling, numerical operations, visualization, and text preprocessing.
Methodology:

Data Preprocessing:
Read in text data from various files.
Split the text into individual articles.
Sentiment Analysis:
Calculated sentiment scores for each article using the Afinn library.
Emotional Analysis:
Converted text data to tokens using bert-tokenizer.
Trained a BERT algorithm to predict emotion probabilities for each sentence after transforming them into tokens.


Dependencies:
Pandas
NumPy
Matplotlib
Neattext
