# Review_Analysis
📌 Project Overview

This project focuses on analyzing real user reviews of ChatGPT to understand public perception, evaluate sentiment trends, and extract meaningful insights from user feedback. Using Natural Language Processing (NLP) techniques, the project classifies reviews into Positive, Neutral, and Negative sentiments, identifies common keywords, and uncovers trends across time.

The analysis combines text preprocessing, sentiment scoring, visualization, and trend analysis to build a complete sentiment intelligence report.

🎯 Project Objectives

Clean and preprocess review text data.

Perform sentiment analysis using polarity scores.

Classify reviews into Positive, Neutral, and Negative categories.

Identify most common words in each sentiment bucket.

Visualize sentiment trends over time.

Understand rating distribution and correlations with sentiment.

Allow users to input custom words and compute their average polarity score.

Build clear, user-friendly plots to support decision-making.

🛠️ Tech Stack
Category	Tools Used
Programming Language	Python
Libraries	pandas, numpy, matplotlib, seaborn, nltk, wordcloud, textblob
Visualizations	Bar charts, line charts, distribution curves
Data Processing	Tokenization, stopword removal, lemmatization
📂 Key Steps of the Project
1️⃣ Data Loading

Import and load the ChatGPT reviews dataset.

Inspect data shape, missing values, and distributions.

2️⃣ Data Cleaning & Preprocessing

Includes:

Lowercasing

Removing punctuation, numbers & special characters

Stopword removal

Tokenization

Lemmatization
This step ensures high-quality input for NLP models.

3️⃣ Sentiment Analysis

Using TextBlob, each review receives:

Polarity Score (−1 = negative, +1 = positive)

Sentiment Label (Positive / Neutral / Negative)

These classifications are later used for visual insights.

4️⃣ Exploratory Data Analysis (EDA)
✔ Common Words by Sentiment Category

Top 20 frequently used words in:

Positive reviews

Negative reviews

This helps understand what drives satisfaction or dissatisfaction.

✔ Sentiment Distribution

Bar charts showing count of:

Positive reviews

Neutral reviews

Negative reviews

✔ Trend Over Time

Line charts analyzing:

Daily average ratings

Daily sentiment counts

Relationship between review volume and sentiment changes

✔ Correlation Between Rating & Time

Helps detect periods where user sentiment sharply changed.

✔ Polarity Statistical Summary

A descriptive statistics table covering:

Mean polarity

Std deviation

Min & max polarity

5️⃣ User-Provided Word Polarity Analysis

A unique interactive feature:
Users can input any words, and the notebook returns:

Average polarity score per word

A comparison bar chart

Summary table of scores

Example input:
helpful, slow, excellent, bug

📈 Visualizations Created

Sentiment distribution bar chart

Positive vs Negative common words bar chart

Sentiment trends over time

Rating trends over time

Word polarity comparison bar chart

Word clouds (if included in your notebook)

These visualizations make the project highly presentable and insight-driven.

🧠 Insights Extracted

(You may customize this based on the actual outputs.)

Some example insights:

Positive reviews often contain words like "helpful", "amazing", "efficient".

Negative reviews frequently include terms like "slow", "incorrect", "confusing".

Sentiment and rating patterns indicate specific dates where user satisfaction spiked or dropped.

Neutral reviews form a substantial portion, indicating balanced feedback.

Custom word polarity tool helps understand user sentiment around product-specific terms.
