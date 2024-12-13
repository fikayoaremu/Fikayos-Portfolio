# Fikayo's-Portfolio

# Project 1: Covid-19 Data Exploration

This project explores the Covid-19 data with an emphasis on global death rates, infection rates, population impact, and vaccination trends. The data is pulled from a Covid-19 dataset, and multiple SQL queries are executed to derive insights using various SQL techniques, including joins, Common Table Expressions (CTEs), temporary tables, window functions, and aggregate functions. This data exploration is visualized and prepared for further analysis in tools like Tableau.

The project demonstrates the following SQL skills:

Joins: Combining data from multiple tables to extract meaningful insights.
CTEs (Common Table Expressions): Organizing complex queries for better readability and reusability.
Temp Tables: Storing intermediate results to perform additional calculations.
Windows Functions: Analyzing data within partitions, such as calculating rolling sums of vaccinations.
Aggregate Functions: Performing calculations like SUM, MAX, and COUNT on grouped data.
Creating Views: Defining views for consistent data access and visualization.

# Project 2: Stock Sentiment Analysis using News Headlines
This project focuses on analyzing stock sentiment using news headlines to predict stock market movements. The dataset consists of news headlines and their associated labels (positive or negative sentiment), collected over time. Using Natural Language Processing (NLP) techniques, the project applies text cleaning, tokenization, and feature extraction to convert the raw text data into a format suitable for machine learning models. The project demonstrates sentiment classification using a Random Forest Classifier.

The project demonstrates the following skills:

Data Preprocessing: Handling text data by removing punctuation, converting text to lowercase, and joining multiple headline columns into a single string for each row.
Text Vectorization: Applying the Bag of Words model using CountVectorizer to convert text data into numerical features.
Random Forest Classifier: Training a Random Forest model with the preprocessed data to predict stock sentiment labels (positive/negative).
Model Evaluation: Using classification metrics such as accuracy, precision, recall, and F1-score to evaluate model performance, along with confusion matrix analysis.

# Project 3: Customer Personality Analysis for Marketing Campaign Segmentation
Objective: The goal of this project is to analyze customer data to identify distinct customer segments for targeted marketing campaigns. By clustering customers based on their behaviors, preferences, and demographics, businesses can optimize their marketing efforts and improve customer engagement. This analysis aims to provide insights into which customer segments are most likely to respond to specific offers and to guide businesses in modifying products and services based on these insights.

Clustering Analysis:

The primary technique employed in this analysis is clustering, with the goal of identifying customer segments that exhibit similar purchasing patterns and characteristics.
The dataset will be used to group customers into clusters, providing insights into how different customer segments interact with the company's offerings.

Conclusion:
The customer base can be effectively divided into three groups with distinct characteristics:

Highly Active Customers show strong engagement, a higher number of children, and moderate income.
Moderately Active Customers are characterized by higher income but lower engagement and fewer children.
Least Active Customers are younger, have minimal income, and demonstrate low engagement with the company.

