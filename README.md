# Sentiment Analysis for JPMorgan Chase's LOXM System

## Project Description
This project implements semantic analysis to enhance JPMorgan Chase & Co.'s LOXM system, a sophisticated AI platform for equity trading. The goal is to improve LOXM's ability to interpret financial sentiment, enabling more accurate trade execution decisions.

## Features
- **Data Sources**: Financial PhraseBank and FiQA datasets for annotated financial sentiment analysis.
- **Models Used**:
  - Naive Bayes Classifier
  - Support Vector Machine (SVM)
  - Random Forest Classifier
- **Visualizations**:
  - Word Cloud
  - Pie Chart of Sentiment Distribution
  - Confusion Matrix
  - ROC Curve

## Project Objectives
1. Collect financial data from diverse sources.
2. Develop machine learning models to analyze financial sentiments.
3. Test and validate models for accurate predictions.
4. Integrate models into the LOXM system for real-time analysis.

## Data Preprocessing
- Cleaning: Remove irrelevant characters and convert text to lowercase.
- Tokenization: Split text into meaningful tokens.
- Lemmatization: Standardize words to their base form.
- Feature Extraction: Use TF-IDF and Word2Vec for numerical representation.

## Results
- **Best Performing Model**: Support Vector Machine (SVM), achieving high accuracy and stability across data subsets.
- **Insights**:
  - Neutral sentiments dominate financial texts.
  - Positive sentiments indicate optimism, while negative sentiments are less frequent.

## Requirements
- Python 3.x
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `nltk`, `seaborn`
