# WIDS-Project
An end-to-end NLP and machine learning project for classifying news as fake or real. Covers
text preprocessing, feature extraction, Logistic Regression with scikit-learn, train–test
workflows, pipelines, and evaluation using accuracy and classification metrics.

# Fake News Detection using Natural Language Processing

This repository contains the work completed for the **Mid-Term Assignment** of the
**Winter in Data Science Programme**.  
The project focuses on understanding and implementing an end-to-end data science and
machine learning workflow for **Fake News Detection** using **Natural Language Processing (NLP)**.

---

## 📌 Project Overview

The rapid spread of misinformation through digital platforms has made fake news detection
an important problem in data science. This project explores how data-driven techniques and
machine learning models can be applied to classify news articles as *fake* or *real* based
on textual content.

The current phase (mid-term) emphasizes **foundational understanding**, including data
handling, exploratory analysis, preprocessing, model building, and evaluation.

---

## 📖 Introduction to Machine Learning

Machine Learning (ML) is a branch of artificial intelligence that enables systems to learn
patterns from data and make predictions without being explicitly programmed for every rule.
Instead of fixed instructions, models improve their performance by learning from examples.

### Supervised Learning
Supervised learning involves training a model on labeled data, where each input is paired
with a known output. The model learns a mapping between features and labels. Common tasks
include classification and regression.

This project primarily uses **supervised learning**, where the input consists of news
article text and the labels indicate whether the article is *fake* or *real*. Logistic
Regression is used as a baseline supervised classification model.

### Unsupervised Learning
Unsupervised learning works with unlabeled data and focuses on discovering hidden patterns
or structures in the data. Typical applications include clustering and dimensionality
reduction.

Although unsupervised learning is not the main focus of this project, understanding it is
useful for tasks such as exploratory analysis and topic modeling in text-based problems.

---

## 🧠 What This Project Covers

The work in this repository is organized across multiple Jupyter notebooks, each focusing
on a specific stage of the workflow:

- **Data Understanding and Loading**
  - Reading CSV and TSV datasets using pandas
  - Handling different delimiters and formats
  - Inspecting data using `head()`, `info()`, and `shape()`

- **Exploratory Data Analysis (EDA)**
  - Descriptive statistics
  - Grouping and aggregation using `groupby()`
  - Identifying patterns and trends in data

- **Data Manipulation and Integration**
  - Creating DataFrames from raw data structures
  - Index handling and alignment
  - Row-wise and column-wise concatenation using `pd.concat()`

- **Visualization and Interpretation**
  - Basic plots using `matplotlib`
  - Interpreting relationships and anomalies
  - Understanding limitations of visual analysis

- **Machine Learning and NLP**
  - Text preprocessing and cleaning
  - Train–test split for supervised learning
  - Logistic Regression as a baseline model
  - Use of scikit-learn Pipelines
  - Model evaluation using:
    - Accuracy score
    - Confusion matrix
    - Classification report (precision, recall, F1-score)

---

## 🛠 Libraries and Tools Used

- Python
- pandas
- NumPy
- matplotlib
- scikit-learn
- Jupyter Notebook

---

## 📈 Learning Outcomes

Through this project, I developed a clear understanding of:
- End-to-end machine learning workflows
- Handling and preprocessing real-world text data
- Proper use of training and testing splits
- Model fitting, transformation, and prediction
- Interpreting evaluation metrics beyond accuracy
- The importance of pipelines and validation to avoid data leakage

These learnings form a strong foundation for extending the project to more advanced NLP
techniques in later stages.

---

## 🚧 Current Status

This repository represents the **mid-term progress** of the project.  
Future work will focus on advanced feature extraction (e.g., TF-IDF) and improving model
performance using more sophisticated NLP approaches.

---

