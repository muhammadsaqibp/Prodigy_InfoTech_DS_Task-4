# Prodigy InfoTech Data Science Internship Task 4: Twitter Sentiment Analysis

## Overview

This repository contains the analysis and visualization of sentiment patterns in social media data to understand public opinion and attitudes toward specific topics or brands. Using a Twitter dataset (training and validation sets from Kaggle), the project focuses on exploring overall sentiment distributions, sentiment variations by entity, sentiment intensity (compound scores), tweet length patterns, and insightful word clouds.

## Dataset

The dataset used for this task is the **Twitter Entity Sentiment Analysis** dataset from Kaggle. It consists of two files:
- `twitter_training.csv`
- `twitter_validation.csv`

*Note:* For this task, the training file was primarily used for analysis and visualization.

## Tools and Libraries

- **Python**
- **Jupyter Notebook**
- **Pandas**: For data manipulation and cleaning.
- **NumPy**: For numerical operations.
- **Matplotlib** and **Seaborn**: For creating visualizations.
- **NLTK (VADER)**: For computing sentiment compound scores.
- **scikit-learn (TF-IDF)**: For generating weighted word clouds.
- **WordCloud**: For visualizing text data.

## Visualizations

The following visualizations have been created:

1. **Overall Sentiment Distributions:**
   - Bar chart and donut chart showing the overall proportions of positive, negative, neutral, and irrelevant sentiments.

2. **Sentiment Distribution by Entity:**
   - Stacked bar charts illustrating sentiment counts for each entity.
   - Separate charts for all entities and top 10 entities to understand brand or topic-specific public opinion.

3. **Distribution of Sentiment Compound Scores:**
   - Histograms of compound sentiment scores (obtained using VADER) for all tweets.
   - Separate compound score distributions for each entity and for the top 10 entities.

4. **Tweet Length Distribution by Sentiment:**
   - Histogram and box plots showing the variation in tweet lengths across different sentiment categories.

5. **Collective Word Cloud (TF-IDF Weighted):**
   - A TF-IDF weighted word cloud to emphasize the most informative words across all tweets, reducing the prominence of overly common terms.

6. **Sentiment-Specific Word Clouds:**
   - Separate word clouds for positive, negative, neutral, and irrelevant tweets to highlight key topics and themes within each sentiment category.

## Analysis Summary

- **Overall Sentiment Trends:** The analysis provides insights into how the majority of tweets are distributed across sentiment categories.
- **Entity-Specific Insights:** By examining sentiment distributions for each entity, we can infer public opinion about different brands or topics.
- **Sentiment Intensity:** The compound score distributions offer a nuanced view of sentiment strength and variability.
- **Tweet Characteristics:** Analysis of tweet lengths and word clouds further enriches the understanding of the context behind sentiments.

## Conclusion

This project presents a thorough sentiment analysis of Twitter data, addressing both overall sentiment patterns and public opinion toward specific entities. The visualizations provide a multi-faceted view of the data, laying a strong foundation for deeper analysis and potential predictive modeling.

Thank you for reviewing my submission for Task 4 of the Prodigy InfoTech Data Science Internship.

