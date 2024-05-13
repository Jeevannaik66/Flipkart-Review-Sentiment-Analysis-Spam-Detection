# Flipkart Review Sentiment Analysis & Spam Comments Detection

"Flipkart Review Sentiment Analysis & Spam Comments Detection" is a project aimed at analyzing sentiment from Flipkart reviews and detecting spam comments using Python and various libraries.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Steps](#Steps)
- [Visualization](#visualization)
- [Sentiment Analysis](#sentiment-analysis)
- [Spam Comments Detection](#spam-comments-detection)


## Introduction

This project focuses on analyzing sentiment from Flipkart reviews and identifying spam comments. By leveraging Python libraries and natural language processing techniques, the project provides insights into customer sentiments and helps in detecting spammy content.

## Features

- Sentiment analysis of Flipkart reviews.
- Detection of spam comments in the review dataset.
- Visualization of review ratings distribution using Plotly.
- Efficient processing of text data to extract sentiment and detect spam.

##Steps

 Here are the steps for the provided code while maintaining the same format:

Step 1: Importing the Required Packages
The initial step involves importing the necessary Python packages such as Pandas, Seaborn, Matplotlib, NLTK, and others.
Step 2: Importing the Dataset
The code imports a dataset named "flipkart_reviews.csv" using the Pandas library. After importing the dataset, it displays the first 10 rows and checks for any null values using data.head(10) and data.isnull().sum() respectively.
Step 3: Cleaning the Dataset
The code defines and executes a function for cleaning the review text by performing tasks such as lowercasing, removing URLs, handling special characters, and stemming the words.
Step 4: Visualizing the Rating Pie Chart
To visualize the distribution of ratings, the code utilizes Plotly Express to create a pie chart reflecting the number of ratings in the dataset.
Step 5: Sentiment Intensity Analysis
Using the NLTK Vader sentiment analyzer, the code computes the positive, negative, and neutral scores for each review text.
Step 6: Overall Sentiment Score
The code calculates the overall sentiment score based on the sum of positive, negative, and neutral scores and prints whether the sentiment is positive, negative, or neutral.
Step 7: Conclusion
The code concludes the sentiment analysis process with a determination of the overall sentiment.


## Visualization

The project includes visualizations of the review ratings distribution via pie charts, providing an overview of the sentiment distribution in the dataset.
![image](https://github.com/Jeevannaik66/Flipkart-Review-Sentiment-Analysis-Spam-Detection/assets/117274229/287e9c12-6b8e-461b-8dc8-5672d9c8caa2)

## Sentiment Analysis

The sentiment analysis module utilizes NLTK's Vader sentiment analyzer to calculate positive, negative, and neutral sentiments for each review in the dataset.

## Spam Comments Detection

The spam comments detection functionality aims to identify and flag comments that exhibit characteristics commonly associated with spam or irrelevant content, contributing to the overall data cleaning process.


