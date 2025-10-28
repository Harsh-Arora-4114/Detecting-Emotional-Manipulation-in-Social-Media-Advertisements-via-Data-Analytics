# Detecting-Emotional-Manipulation-in-Social-Media-Advertisements-via-Data-Analytics

## Overview

This project aims to detect **emotional manipulation** in **social media advertisements** using **data analytics and machine learning techniques**. With the rapid growth of digital marketing, advertisers often use emotional cues to influence users’ decisions. This project analyzes text-based ad content to classify and identify emotionally manipulative patterns, promoting ethical and transparent advertising practices.

---

## Objectives

* Identify and quantify emotional manipulation in advertisements.
* Apply **data analytics, NLP, and machine learning** to detect persuasive emotional tones.
* Visualize emotional trends and manipulation intensity across datasets.
* Encourage ethical communication practices in digital marketing.

---

## Key Features

* **Data Preprocessing:** Cleans and structures social media ad datasets.
* **Text Analytics:** Tokenization, lemmatization, and sentiment analysis.
* **Feature Engineering:** Extraction of linguistic and emotional cues.
* **Modeling:** Classification using ML algorithms (e.g., Logistic Regression, Random Forest, SVM).
* **Visualization:** Emotion distribution plots and model performance metrics.
* **Ethical Insights:** Interpretation of manipulative versus neutral ad content.

---

## Technologies Used

| Category             | Tools / Libraries     |
| -------------------- | --------------------- |
| Programming Language | Python                |
| Data Processing      | Pandas, NumPy         |
| NLP                  | NLTK, SpaCy, TextBlob |
| Machine Learning     | Scikit-learn          |
| Visualization        | Matplotlib, Seaborn   |
| Environment          | Jupyter Notebook      |

---

## Dataset

The dataset consists of **social media advertisements** labeled according to their emotional tone (e.g., fear, happiness, guilt, excitement).
Each entry contains:

* `Ad_Text` — textual content of the ad
* `Emotion_Label` — detected or assigned emotional category
* `Manipulation_Score` — level of manipulation (0–1 scale)

> 🔹 Dataset can be customized or replaced with publicly available ad datasets (e.g., Kaggle or scraped social media data).

---

## Project Workflow

1. **Data Collection & Preprocessing**

   * Text cleaning, stopword removal, tokenization.
2. **Exploratory Data Analysis (EDA)**

   * Frequency analysis, sentiment trends, emotion distribution.
3. **Feature Engineering**

   * TF-IDF, sentiment polarity, subjectivity features.
4. **Model Building & Evaluation**

   * Train/test split, accuracy, F1-score, confusion matrix.
5. **Result Visualization**

   * Emotional trends, model performance charts.
6. **Interpretation & Ethical Analysis**

   * Identifying manipulative ad traits and insights.

---

## Sample Results

* Accuracy achieved: **~85% (varies by model and dataset)**
* Emotional categories identified: *Fear, Guilt, Happiness, Sadness, Anger*
* Key indicators: Use of emotional keywords, urgency cues, and sentiment polarity.

---

## Ethical Considerations

This project emphasizes **AI ethics in marketing analytics** by:

* Promoting **transparent ad content**.
* Identifying **psychological exploitation** in advertisements.
* Supporting **user awareness and informed decisions**.

---

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/Emotional-Manipulation-Detector.git
   cd Emotional-Manipulation-Detector
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter notebook:

   ```bash
   jupyter notebook "Emotional_Manipulation_Detector.ipynb"
   ```
4. Run all cells sequentially to see results.

---

## Future Scope

* Integration with **real-time ad monitoring APIs**.
* Deep learning models (BERT, RoBERTa) for emotion detection.
* Development of a **dashboard or web app** for ad scanning.

---

## Author

**Developed By Harsh Arora**

---
