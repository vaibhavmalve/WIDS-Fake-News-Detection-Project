# WIDS-Project
An end-to-end NLP and machine learning project for classifying news as fake or real. Covers
text preprocessing, feature extraction, Logistic Regression with scikit-learn, train–test
workflows, pipelines, and evaluation using accuracy and classification metrics.

# Fake News Detection using Natural Language Processing

This repository contains the work completed for the **Winter in Data Science Programme**.  
The project focuses on understanding and implementing an end-to-end data science and
machine learning workflow for **Fake News Detection** using **Natural Language Processing (NLP)**.

---

## 📌 Project Overview

The rapid spread of misinformation through digital platforms has made fake news detection
an important problem in data science. This project explores how data-driven techniques and
machine learning models can be applied to classify news articles as *fake* or *real* based
on textual content.

The project progressed from foundational machine learning concepts to the implementation
of complete NLP pipelines suitable for real-world text classification problems.

---

## 📖 Introduction to Machine Learning

Machine Learning (ML) is a branch of artificial intelligence that enables systems to learn
patterns from data and make predictions without being explicitly programmed. Models improve
their performance by learning from examples rather than following fixed rules.

### Supervised Learning
Supervised learning involves training a model on labeled data, where each input is paired
with a known output. The model learns a mapping between features and labels.

In this project, supervised learning is applied where the input consists of news article
text and the output label indicates whether the article is *fake* or *real*. Logistic
Regression is used as a baseline model, and the final classification is performed using a
**Passive Aggressive Classifier**, which is well suited for large-scale text data.

### Unsupervised Learning
Unsupervised learning works with unlabeled data and focuses on identifying hidden patterns
or structures. While not used for final classification, its concepts support exploratory
analysis and understanding the structure of textual data.

---

## 🧠 Project Workflow

The project is organized across multiple Jupyter notebooks, each addressing a key stage of
the machine learning and NLP pipeline:

### 🔹 Data Understanding and Loading
- Reading CSV datasets using pandas
- Inspecting datasets using `head()`, `info()`, and `shape()`
- Separating textual features and class labels

### 🔹 Exploratory Data Analysis (EDA)
- Analyzing class distribution
- Identifying patterns and imbalance in the dataset
- Using grouping and aggregation techniques

### 🔹 Data Manipulation
- Creating and modifying DataFrames
- Handling indices and alignment
- Combining datasets using concatenation

### 🔹 Text Preprocessing (NLP)
- Text cleaning and normalization
- Stop-word removal
- Preparing text for feature extraction

### 🔹 Feature Extraction
- Understanding Bag-of-Words representations
- Applying **TF-IDF Vectorization** to capture term importance
- Working with high-dimensional sparse text features

### 🔹 Machine Learning Models
- Train–test split with reproducibility
- Logistic Regression as a baseline classifier
- **Passive Aggressive Classifier for final model training**
- Proper use of pipelines to prevent data leakage

### 🔹 Model Evaluation
- Accuracy score
- Confusion matrix
- Classification report including precision, recall, and F1-score
- Interpretation of results using multiple evaluation metrics

### 🔹 Model Persistence and Interaction
- Saving trained models using `joblib`
- Building a basic interactive interface using **Gradio** for predictions

---

## 🛠 Libraries and Tools Used

- Python  
- pandas  
- NumPy  
- matplotlib  
- scikit-learn  
- joblib  
- Gradio  
- Jupyter Notebook  

---

## 📈 Learning Outcomes

Through the completion of this project, I developed a clear and practical understanding of:

- End-to-end NLP and machine learning workflows
- Handling and preprocessing real-world textual data
- Feature extraction techniques such as TF-IDF
- Selecting appropriate models for text classification
- Evaluating classification models using multiple performance metrics
- Designing pipelines that ensure reliable and reproducible results

This project represents the successful completion of an applied NLP and machine learning
task as part of the **Winter in Data Science Programme**.

---

### ✅ Final Result
A complete, well-structured **Fake News Detection system** implemented using NLP and
supervised machine learning techniques.
