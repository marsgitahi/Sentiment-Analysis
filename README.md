# Amazon Review Sentiment Analysis using Natural Language Processing

## Project Overview

This project applies Natural Language Processing (NLP) and supervised machine learning techniques to classify Amazon customer reviews into Positive, Neutral, and Negative sentiment categories.

The project demonstrates an end-to-end NLP workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering using TF-IDF, model development, evaluation, and visualization.

Among the evaluated models, the Support Vector Machine (SVM) achieved the highest classification performance, making it the best-performing model for this dataset.

---

## Objectives

- Perform exploratory data analysis on Amazon customer reviews.
- Clean and preprocess textual data.
- Apply NLP techniques including tokenization, POS tagging, chunking, and TF-IDF vectorization.
- Train multiple machine learning classifiers.
- Compare model performance using standard evaluation metrics.
- Identify the best-performing sentiment classification model.

---

## Dataset

The dataset contains Amazon customer reviews together with numerical metadata such as:

- Overall rating
- Review text
- Helpful votes
- Total votes
- Wilson Lower Bound score

These features were used to explore customer opinions and build sentiment classification models.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn

---

## NLP Techniques

- Text Cleaning
- Tokenization
- Part-of-Speech (POS) Tagging
- Chunking
- Label Encoding
- TF-IDF Vectorization

---

## Machine Learning Models

The following supervised learning models were evaluated:

- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Naive Bayes

---

## Model Performance

| Model | Accuracy | Precision | Recall | F1 Score |
|-------|---------:|----------:|--------:|---------:|
| Decision Tree | 87.69% | 86.86% | 87.69% | 87.25% |
| Random Forest | 90.64% | 88.97% | 90.64% | 86.29% |
| **Support Vector Machine** | **93.18%** | **90.61%** | **93.18%** | **91.26%** |
| Naive Bayes | 90.23% | 81.95% | 90.23% | 85.89% |

---

## Key Findings

- Most customer reviews were positive.
- TF-IDF effectively represented textual data for machine learning.
- SVM achieved the best overall classification performance.
- ROC curves and confusion matrices confirmed the effectiveness of the selected model.
- The project demonstrates a complete NLP pipeline from raw text to model evaluation.

---

## Future Improvements

- Apply transformer models such as BERT.
- Perform multilingual sentiment analysis using English and Swahili.
- Address class imbalance using resampling techniques.
- Deploy the model as a web application.

---

## Repository Structure

```
Sentiment-Analysis/
│
├── Amazon_Review_Sentiment_Analysis.ipynb
├── README.md
├── requirements.txt
└── dataset.csv
```

---

## Author

**Mercy Wambui Gitahi**

Aspiring AI & NLP Engineer | Machine Learning Enthusiast | Data Scientist | Aspiring Full Stack Developer 
