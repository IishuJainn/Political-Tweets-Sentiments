# Sentiment Analysis of Political Leaders in India

## Introduction
This project is aimed at performing sentiment analysis on tweets related to political leaders in India. The project uses python libraries like pandas, numpy, re, matplotlib, nltk, TextBlob, and wordcloud to clean, preprocess, and analyze the tweets.

The project takes tweets related to Mr. Narendra Modi, Mr. Rahul Gandhi, and Mr. Arvind Kejriwal and performs sentiment analysis on them to find the public's perception towards these leaders.

## Data Collection
The data is collected from a dataset named "201k Tweets on Mr. Modi, Mr. Rahul, Mr. Kejri, and EleCanal" available on Kaggle. The dataset contains tweets related to the mentioned political leaders and has been collected between 2017 and 2021.

## Data Cleaning and Preprocessing
The tweets contain a lot of irrelevant information like URLs, usernames, and emojis. To clean the data, these irrelevant elements are removed using regular expressions and the data is preprocessed for analysis.

## Sentiment Analysis
Sentiment analysis is performed on the tweets using the TextBlob library. The TextBlob library provides a sentiment property that returns a named tuple of form (polarity, subjectivity). Polarity is a float that lies in the range of [-1,1], where -1 represents a negative sentiment, 0 represents a neutral sentiment, and 1 represents a positive sentiment. Subjectivity is also a float that lies in the range of [0,1], where 0 represents a very objective text and 1 represents a very subjective text.

## Word Cloud
To visualize the most frequently used words in the tweets, a word cloud is created using the wordcloud library.

## Conclusion
The sentiment analysis and word cloud visualization give us an insight into the public's perception towards the political leaders. The results of the analysis can be used to understand the sentiment of the people towards these leaders and to make informed decisions.

## Requirements
The following packages are required to run the code:

pandas

numpy

re

matplotlib

nltk

TextBlob

wordcloud

## To install the required packages, run the following command in your terminal or command prompt:
![image](https://user-images.githubusercontent.com/102272183/218268240-99388d92-b066-45b4-a67c-0e2369449507.png)

## How to Run the Code
To run the code, you need to have the required packages installed and the dataset stored in your local system. After that, you can run the code in your terminal or command prompt using the following command:
![image](https://user-images.githubusercontent.com/102272183/218268266-96da0149-11a2-4f23-b82d-b3ea9cf67703.png)


