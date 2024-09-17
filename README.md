# sentiment_analysis
This project focuses on sentiment analysis of customer reviews from a TeePublic store using Python. The goal is to analyze the emotions behind customer feedback to help the store owners improve products, services, and overall customer satisfaction.

# Introduction
This project performs a sentiment analysis on customer reviews using natural language processing (NLP) techniques. By analyzing customer feedback, we can categorize reviews into positive, neutral, or negative sentiments, helping the store better understand its customers and improve accordingly.

# Libraries Used
• Pandas: For data manipulation and analysis.
• NumPy : For numerical operations.
• Seaborn : For creating visualizations of the sentiment data.
• Matplotlib : To plot charts and visualize trends.
• WordCloud: To create a word cloud showing frequent terms in the reviews.
• TextBlob: For sentiment analysis.
• Warnings: To ignore warnings during execution.

# Dataset
This extensive dataset, comprised of over 250,000 customer reviews, offers a detailed exploration of customer experiences on TeePublic, an online platform renowned for its diverse collection of fashion items. The dataset spans crucial information, including reviewer_id, store_location, latitude, longitude, date, month, year, title, review, and the review-label indicating a rating on a scale of 1 to 5.
Link to the dataset: https://www.kaggle.com/datasets/nelgiriyewithana/shoppersentiments

# Steps
1. Data Cleaning: Remove null values, duplicates, and irrelevant information.
2. Exploratory Data Analysis (EDA): Use visualizations like pie chart and bar plots to understand the distribution of reviews.
3. Sentiment Analysis: Use TextBlob to classify each review as positive, negative, or neutral.
4. Visualization: Plot the sentiment distribution.
5. Word Cloud: Generate word clouds to show the most frequent words in the reviews.
   
# Result
The project produces insightful visualizations, including:

• Sentiment distribution of reviews (positive, negative, and neutral).
• Word cloud of frequently used terms in the reviews.
