# 🎓 Student Feedback Analytics Using NLP & Machine Learning

An end-to-end data science project that analyzes student course evaluation data using **Exploratory Data Analysis (EDA)**, **Natural Language Processing (NLP)**, and **Machine Learning** to identify patterns in student feedback and predict student satisfaction.

---

## 📌 Project Overview

Student feedback is an important source of information for evaluating teaching quality and improving learning experiences. This project explores structured student evaluation data and textual feedback to uncover meaningful insights through data analysis and predictive modeling.

The workflow includes data preprocessing, feature engineering, exploratory data analysis, sentiment analysis, text feature extraction, and supervised machine learning.

---

## 🎯 Objectives

- Clean and preprocess student feedback data.
- Perform exploratory data analysis to identify trends and relationships.
- Apply Natural Language Processing (NLP) techniques to textual feedback.
- Engineer meaningful features for predictive modeling.
- Train and compare multiple machine learning classification models.
- Evaluate model performance using standard classification metrics.

---

## 📂 Dataset

The dataset contains **1,001 student course evaluations** with numerical ratings and textual feedback.

### Features include:

- Attendance (%)
- Study Hours
- GPA
- Subject Knowledge
- Concept Explanation
- Presentation Quality
- Assignment Difficulty
- Instructor Responsiveness
- Course Structure
- Student Support
- Course Recommendation
- Student Feedback

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- WordCloud
- TextBlob
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis (EDA)

The project includes:

- Data quality assessment
- Missing value analysis
- Feature engineering
- Correlation analysis
- Distribution analysis
- Student satisfaction visualization
- Attendance and GPA analysis
- Instructor performance analysis

---

## 📝 Natural Language Processing (NLP)

The text analysis pipeline includes:

- Text cleaning
- Tokenization
- Lemmatization
- Stop-word removal
- Sentiment analysis
- TF-IDF Vectorization
- Keyword extraction
- Word frequency analysis
- Word cloud visualization

---

## 🤖 Machine Learning Models

The following supervised learning models were trained and evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- XGBoost

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score

---

## 📈 Results

| Model | Accuracy |
|--------|---------:|
| Logistic Regression | **98.67%** |
| XGBoost | **97.00%** |
| Random Forest | **95.67%** |
| SVM | **95.00%** |
| KNN | **90.00%** |
| Decision Tree | **89.67%** |

Logistic Regression achieved the highest predictive performance on the synthetic dataset, followed by XGBoost and Random Forest.

> **Note:** The dataset used in this project contains engineered features and synthetic feedback. Consequently, the reported performance should be interpreted within the context of the dataset rather than generalized to real-world educational environments.

---

## 📁 Project Structure

```
Student-Feedback-Analytics/

│── data/
│   ├── student_feedback.csv
│   └── student_feedback_nlp.csv
││── models/
│   ├── best_model.pkl
│   ├── scaler.pkl.csv
│── notebooks/
│   ├── 01_Data_Preprocessin & EDA.ipynb
│   ├── 02_NLP_and_Text_Analytics.ipynb
│   └── 03_Machine_Learning_Models.ipynb
│
│── README.md

```

---

## 🚀 Key Skills Demonstrated

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Natural Language Processing (NLP)
- Sentiment Analysis
- Machine Learning
- Classification
- Model Evaluation
- Data Visualization

---

## 🔮 Future Improvements
- Implement Explainable AI (SHAP) for model interpretability.
- Deploy the model as a Streamlit web application.
- Incorporate deep learning models such as BERT for sentiment classification.
- Build an interactive dashboard for educational stakeholders.




## ⭐ If you found this project useful, consider giving it a star!