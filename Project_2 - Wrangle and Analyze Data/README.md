## Introduction
This project's objective was to gather WeRateDogs Twitter data in order to produce insightful and reliable analysis and visualizations.

This project is primarily focused on manipulating data from the WeRateDogs Twitter account using Python. A final notebook (wrangle act.ipynb) was produced after the data wrangling process.

## Process Overview

### Gathering the Data
Three different forms of data were used for this project, and they were acquired as described below:

- WeRateDogs Twitter Archive File: Udacity made twitter archive enhanced.csv available for usage.

- Image Predictions File: The [URL](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2adimage-predictions/imagepredictions.tsv) was used to programmatically download the file (image predictions.tsv), which was hosted on Udacity's server.

- Twitter API & Tweet JSON File: Using the tweet IDs from the WeRateDogs Twitter archive, I used Python's tweepy module to query the Twitter API for each tweet's JSON data, and I saved the whole set of JSON data for each tweet in a file called tweet json.txt.


## Skills
- Gathered data by downloading from the net programmatically using the requests library and scraping tweets from Twitter using the Tweepy library. 
- Assessed the data visually and programmatically to detect tidiness and dirtiness issues.
- Cleaned the dataset and combined the tables into one.
- Prepared a report outlining the data wrangling process and showcasing all the insights and visualizations produced from the wrangled data


## Summary of Findings
1. Only 937 dogs out of 1477 predicted dogs, were predicted with confidence greater than 50%. In second and third predictions, no dog was predicted with confidence greater than 50%
2. The most favorite and most popular dog classes are doggo and pupper with a combined score of over 80%
3. Golden_retriever, Labrador_retriever, and Pembroke are the most popular and favorite dog breeds
