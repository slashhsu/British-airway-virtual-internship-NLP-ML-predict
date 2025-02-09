# Customer Insights & Predictive Modeling

## Overview
This project focuses on analyzing customer reviews and predicting customer buying behavior using **Natural Language Processing (NLP)** and **Machine Learning (ML)**. The project is divided into two main tasks:
1. **Web Scraping & Sentiment Analysis** – Extracting and analyzing customer reviews.
2. **Predictive Modeling** – Identifying key factors influencing customer purchases.

---

## 1. Web Scraping & Sentiment Analysis
### Data Insights
By cleaning **1,000 customer reviews**, we categorized them into sentiment and subjectivity:
- **Positive Reviews:** 480
- **Negative Reviews:** 413
- **Neutral Reviews:** 107

Subjectivity classification:
- **Subjective Reviews:** 537
- **Objective Reviews:** 463

### Preprocessing Steps:
- **Text Cleaning** – Removing punctuation, special characters, and unnecessary elements.
- **Tokenization** – Splitting text into individual words.
- **Stopword Removal** – Filtering out common words.
- **Stemming/Lemmatization** – Reducing words to their root forms.
- **TF-IDF Vectorization** – Converting text into numerical features.

Additionally, a **word cloud** was generated to visualize frequently used words in the reviews.

---

## 2. Predictive Modeling for Customer Buying Behavior
### Model Implementation
To understand factors influencing customer purchases, we trained a predictive model using:
- **Random Forest Classifier**
- **XGBoost Classifier**

### Model Performance
- **Accuracy:** 85.09%
- **AUC Score:** 0.543 *(needs improvement)*

### Key Features Impacting Customer Buying Behavior:
- **Booking Origin:** Australia, Malaysia, Taiwan
- **Top Routes:** SBWTPE, BKICN

---

## 3. Key Insights
📌 **Sentiment analysis shows a balance between positive and negative reviews.**
📌 **Slightly more subjective reviews than objective ones.**
📌 **Customer booking behavior is significantly influenced by country of origin and specific routes.**
📌 **AUC score improvement is needed for better predictive performance.**

---

## 4. Future Work
🔹 **Enhance AUC score with hyperparameter tuning and additional features.**
🔹 **Experiment with advanced NLP models like BERT for sentiment analysis.**
🔹 **Develop a real-time dashboard for tracking customer sentiment and behavior.**
🔹 **Improve the AUC score of the predictive model**
🔹 **Explore advanced NLP techniques like BERT for sentiment classification**
🔹 **Develop a real-time sentiment and booking prediction dashboard**
🔹 **Expand the dataset to cover a broader range of customer feedback**
