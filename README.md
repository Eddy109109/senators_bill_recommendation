# NLP Senator Recommendation Project
## Overview
This project aims to recommend the most suitable senator based on their legislative activities. It involves crawling bills from the 국회 (National Assembly) website, processing the text data using Natural Language Processing (NLP) techniques, and applying Word Embedding and Word2Vec to create vector representations for each bill. The project then aggregates these vectors to create a profile for each senator and uses clustering techniques to visualize and recommend senators.

## Features
Data Crawling: Automatically fetches bills per senator from the 국회 website.
Text Processing: Cleans and tokenizes the text data from the bills.
Word Embedding: Uses Word2Vec to generate vector representations for each bill and its tokens.
Senator Vector Creation: Aggregates vectors for each senator based on their bills using a weighted average.
Silhouette Analysis: Applies Silhouette analysis to determine the optimal number of clusters.
Clustering and Visualization: Uses the optimal number of clusters from Silhouette analysis in the K-Means algorithm to visualize the senators’ vectors.

## Usage
Data Crawling: Run the crawl_bills.py script to fetch bills from the 국회 website.
Text Processing: Use the process_text.py script to clean and tokenize the text data.
Vector Creation: Execute the create_vectors.py script to generate vectors for each bill and aggregate them for each senator.
Clustering and Visualization: Run the cluster_senators.py script to apply Silhouette analysis, perform K-Means clustering, and visualize the results.
