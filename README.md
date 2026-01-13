
# Predicting Depression Tendencies from Twitter Posts

## Project Overview
This project focuses on predicting whether a Twitter user shows a tendency toward depression based on the textual content of their posts. Using machine learning and natural language processing techniques, the model classifies tweets into two categories: **No Depression (0)** and **Depression (1)**.

The goal of this project is to support early mental health screening, contribute to academic research, and demonstrate practical applications of machine learning in social and emotional analysis.

## Dataset Description
- **Source**: Kaggle – Mental Health Social Media Dataset  
- **Dataset Size**:  
  - Rows: 20,000  
  - Columns: 11  
- **Missing Values**: None  
- **Target Labels**:  
  - 0: No Depression (10,000 samples)  
  - 1: Depression (10,000 samples)  

The dataset is well-balanced, which helps reduce bias during model training. Only the text-related columns were used in this project.

## Methodology

### Step 1: Data Collection
The dataset was downloaded from Kaggle. The analysis focused solely on textual data from social media posts.

### Step 2: Exploratory Data Analysis (EDA)
EDA was performed to understand data distribution, label balance, and general text characteristics.

### Step 3: Preprocessing and Cleaning
Text preprocessing included:
- Expanding abbreviations using a custom dictionary
- Lemmatization to convert words to their base forms
- Part-of-speech tagging and conversion to WordNet format
- General text cleaning (lowercasing, noise removal)

### Step 4: Feature Extraction
Text data was converted into numerical features using vectorization techniques (e.g., TF-IDF).

### Step 5: Feature Selection
Feature selection methods applied:
- ANOVA
- LASSO

These techniques helped reduce dimensionality while maintaining model performance.

### Step 6: Train-Test Split
The dataset was split into training and testing sets to evaluate generalization performance.

## Model Experiments
Several machine learning models were tested and compared using the following criteria:
- Accuracy
- Difference between training and testing accuracy (overfitting check)
- Log Loss

Models evaluated:
- Logistic Regression
- Linear Support Vector Classifier (LinearSVC)
- Decision Tree
- Multinomial Naive Bayes
- MLPClassifier (Neural Network)
- XGBoost

## Final Model Selection
The **MLPClassifier** was selected as the final model due to:
- High accuracy
- Low overfitting (small train-test accuracy gap)
- Acceptable log loss

## My Responsibilities
My primary responsibilities in this group project included:

### Logistic Regression
- Implemented and trained the Logistic Regression model
- Evaluated model performance using accuracy and log loss
- Analyzed overfitting by comparing training and testing results

### Support Vector Machine (SVM)
- Experimented with the Linear Support Vector Classifier (LinearSVC)
- Tuned parameters and evaluated performance
- Compared results with other models to support final model selection

These experiments contributed to the overall comparison and justification of the final selected model.

## Applications and Benefits
- Early mental health screening
- Support for mental health research
- Sentiment and emotion analysis
- Improved understanding of social media communication patterns
  
## Presentation
- Google Drive: https://drive.google.com/file/d/1nxnddFqV4rAfXOuRf62AKU-wL4S19yYn/view?usp=drive_link
  
## Team Members
- วริยาพร  
- ฐิติชญา  
- พิมพ์วรีย์  
- พัชรี  







