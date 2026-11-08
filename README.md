# Internship-Project
# News Article Authentication and Fraud Detection

## Overview
An end-to-end Machine Learning and Natural Language Processing (NLP) project that classifies news articles as **Real or Fake** using text analysis and multiple classification algorithms.

## Dataset
- **Source:** [Fake and Real News Dataset – Kaggle](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)
- **Total Articles:** 44,898
- **Files:** `Fake.csv` and `True.csv`
- **Features:** Title text,subject,date and target label.

## Tools Used
- Python
- Pandas and NumPy
- Scikit-learn
- NLTK / TextBlob
- Matplotlib and Seaborn
- Regular Expressions

## Project Workflow
1. Data ingestion and merging
2. Exploratory Data Analysis (EDA)
3. Text cleaning and preprocessing
4. Outlier detection using word count
5. TF-IDF feature extraction (5,000 features)
6. Logistic Regression classification
7. K-Means clustering and TruncatedSVD
8. Sentiment analysis
9. Random Forest classification with 5-fold cross-validation
10. Multi-Layer Perceptron (MLP)
11. Hyperparameter optimization
12. Confusion matrix,business cost evaluation and ROC-AUC analysis

## Model Performance

| Model | Evaluation Metric | Score |
|---|---|---:|
| Logistic Regression | F1-Score | 0.9890 |
| Random Forest | Mean CV Accuracy | 0.9973 |
| MLP | Accuracy | 0.9800 |
| MLP | ROC-AUC | 0.9967 |

## Key Findings
- Supervised models achieved excellent classification performance.
- K-Means produced an ARI of 0.0258, indicating weak alignment between natural clusters and actual labels.
- A custom business cost function assigned a penalty of 5 to False Negatives and 1 to False Positives.
- The MLP achieved a total business cost of 72 units.

## Conclusion
The project demonstrates how NLP and machine learning techniques can be used to identify fake news articles through textual patterns and classification models.
