# TripAdvisor Hotel Reviews - NLP Analysis

This project performs Natual Language Processing (NLP) on hotel reviews from TripAdvisor using Python. 

The goal is to clean, tokenize, lemmatize and analyze the most frequently used words and word pairs
(unigrams and bigrams) to gain insights into customer feedback. 

## Dataset

-**Source:** `tripadvisor_hotel_reviews.csv`
-**Columns:**
	-`Review` (text): Customer review of the hotel
	-`Rating` (int): Review rating (1-5)

## What This Notebook Does

### Data Cleanup and Preprocessing
-Convert reviews to lowercase
-Remove English stopwords (e.g: "the", "is", "and") except "not"
-Replace special characters like `*` with 'star'
-Tokenize text into individual words
-Lemmatize words to their base form (e.g: "running" -> "run")

### Text Analysis
-Generate unigrams and bigrams from the lemmatized tokens
-Visualize the top 10 most frequent unigrams and bigrams using bar charts

## Libraries Used
-`Pandas1 - for data manipulation
-`nltk` - for tokenization, stopword removal, lemmatization and n-gram generation
-`re` - for regez-based text cleaning
-`matplotlib` - for visualization

## Key Insights
-Common unigrams include: **"hotel"**, **"room"**, **"great"**, **"not"**
-Common bigrams include: **"great location"**m **"space needle"**, **"staff friendly"**

These patterns reveal recurring themes in customer sentiment and hotel features frequently mentioned in 
reviews.

## How to run
1- clone the repo
2- Make sure Python + required libraries installed
3- Run `trip_advisor_reviews.ipynb` in Jupyter Notebook


