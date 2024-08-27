# NLP Senator Recommendation Project
## Overview
This project aims to recommend the most suitable senator based on their legislative activities. It involves crawling bills from the 국회 (National Assembly) website, processing the text data using Natural Language Processing (NLP) techniques, and applying Word Embedding and Word2Vec to create vector representations for each bill. The project then aggregates these vectors to create a profile for each senator and uses clustering techniques to visualize and recommend senators.

## Features
### Data Crawling: 
Automatically fetches bills per senator from the 국회 website using BeautifulSoup.
### Text Processing:
Tokenizes the data using Mecab
Removes stopwords
Trains Word2Vec to generate vector representations for each bill and its tokens.
### Senator Vector Creation: 
Aggregates vectors for each senator based on their bills using a weighted average.
### Silhouette Analysis: 
Applies **Silhouette** analysis to determine the optimal number of clusters.
### Clustering and Visualization: 
Uses the optimal number of clusters from Silhouette analysis in the K-Means algorithm to visualize the senators’ vectors.
![image](https://github.com/user-attachments/assets/f1de15aa-84b1-44ac-bb1b-a2ce468d737e)
![image](https://github.com/user-attachments/assets/b390b558-6a54-4c7c-8d94-883fbbabf95a)

