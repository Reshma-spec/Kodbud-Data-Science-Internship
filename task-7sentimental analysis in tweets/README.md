# Sentiment Analysis on Tweets

## Overview

This project performs Sentiment Analysis on a dataset of tweets using Natural Language Processing (NLP). The tweets are classified into three categories:

* Positive
* Negative
* Neutral

The project uses the VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analyzer to determine the sentiment of each tweet.

## Dataset

* Dataset File: `test.csv`
* Features:

  * `tweets` : Tweet text
  * `class` : Original dataset label

## Technologies Used

* Python
* Pandas
* VADER Sentiment Analyzer
* Matplotlib
* Seaborn
* WordCloud

## Project Workflow

1. Load and explore the dataset.
2. Perform sentiment analysis using VADER.
3. Create a new `Sentiment` column.
4. Classify tweets as Positive, Negative, or Neutral.
5. Visualize sentiment distribution using charts.
6. Generate word clouds for text analysis.
7. Save the final analyzed dataset.

## Visualizations

* Bar Chart of Sentiment Distribution
* Pie Chart of Sentiment Distribution
* Word Cloud of Most Common Words

## Results

The tweets were successfully analyzed and categorized into Positive, Negative, and Neutral sentiments. The visualizations provide insights into the overall sentiment distribution and frequently used words in the dataset.

## Conclusion

This project demonstrates how Natural Language Processing techniques can be used to analyze public sentiment from social media text data. Sentiment analysis can help organizations understand customer opinions, trends, and reactions to various topics.

## Author

Reshma Reddy Ambati
