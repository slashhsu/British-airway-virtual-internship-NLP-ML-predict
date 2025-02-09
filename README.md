# British Airways NLP & ML Prediction

## Overview
This project leverages **Natural Language Processing (NLP)** and **Machine Learning (ML)** to analyze and predict customer insights for British Airways. The project is divided into two key areas:
1. **Customer Sentiment Analysis** – Using NLP techniques to extract and classify sentiments from customer reviews.
2. **Customer Buying Behavior Prediction** – Implementing machine learning models to understand key factors influencing booking decisions.

---

## 1. Customer Sentiment Analysis
### Data Insights
By cleaning **1,000 customer reviews**, the dataset was divided into:
- **Positive Reviews:** 480
- **Negative Reviews:** 413
- **Neutral Reviews:** 107

Additionally, the subjectivity analysis classified:
- **Subjective Reviews:** 537
- **Objective Reviews:** 463

### Preprocessing Steps:
- **Text Cleaning** – Removing punctuation, special characters, and unnecessary elements.
- **Tokenization** – Splitting text into individual words.
- **Stopword Removal** – Filtering out common words that do not add meaning.
- **Stemming/Lemmatization** – Reducing words to their root forms.
- **TF-IDF Vectorization** – Converting text into numerical features for model training.

![Data Preprocessing](https://github.com/slashhsu/British-airway-NLP-ML-predict/assets/137000188/6f6dca5b-d643-4b13-8fdd-b794071ab351)

---

## 2. Customer Buying Behavior Prediction
### Model Implementation
A predictive model was developed to analyze the **factors influencing customer booking behavior**. The dataset was trained using:
- **Random Forest Classifier**
- **XGBoost Classifier**

### Model Performance
The highest achieved scores:
- **Accuracy:** 85.09%
- **AUC Score:** 0.543 (Requires improvement)

### Key Features Impacting Customer Booking Behavior:
- **Booking Origin:** Australia, Malaysia, Taiwan
- **Top Routes:** SBWTPE, BKICN

![Model Implementation](https://github.com/slashhsu/British-airway-NLP-ML-predict/assets/137000188/cd738115-12eb-4de7-8001-c9a3e53ebbb9)

---

## 3. Model Performance
Each model was evaluated using key performance metrics:
- **Accuracy** – Measures overall classification performance.
- **Precision & Recall** – Evaluates model sensitivity.
- **F1-Score** – Balances precision and recall.
- **Confusion Matrix** – Provides insights into false positives and false negatives.

The **deep learning model (LSTM)** demonstrated the highest accuracy for sentiment classification, while Random Forest and XGBoost provided insights into customer booking behavior.

![Model Performance](https://github.com/slashhsu/British-airway-NLP-ML-predict/assets/137000188/f455bf39-29ee-4145-8519-b09d784c14f7)

---

## 4. Key Insights
📌 **Customer sentiment is nearly balanced between positive and negative**
📌 **Objective reviews slightly outnumber subjective ones**
📌 **Booking origin and travel routes significantly influence customer purchasing behavior**
📌 **Deep learning models perform well for sentiment analysis, while tree-based models are effective for booking prediction**

![Key Insights](https://github.com/slashhsu/British-airway-NLP-ML-predict/assets/137000188/83c839e2-dae0-472a-984a-261000666440)

---

## 5. Future Work
🔹 **Improve the AUC score of the predictive model**
🔹 **Explore advanced NLP techniques like BERT for sentiment classification**
🔹 **Develop a real-time sentiment and booking prediction dashboard**
🔹 **Expand the dataset to cover a broader range of customer feedback**
