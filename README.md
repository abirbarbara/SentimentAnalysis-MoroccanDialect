# Sentiment Analysis on Moroccan Dialect Comments

This repository contains a sentiment analysis project focused on comments written in the Moroccan dialect, collected from press websites. The project aims to classify these comments as either **positive or negative** using different machine learning techniques.

## Project Overview

### Data Collection and Annotation
- **Data Source**: Comments were scraped from Moroccan press websites using Python (Selenium + BeautifullSoup).
- **Annotation**: The scraped comments were manually annotated as either positive or negative in a spreadsheet.

### Notebooks Included
1. **Sentiment Analysis using SVM** (`sentiment-analysis-using-SVM.ipynb`)
   - Applies the Term Frequency-Inverse Document Frequency (TF-IDF) vectorization method to transform the text data into numerical features.
   - Uses these features to train the machine learning model SVM to classify the sentiment of the comments.

2. **Sentiment Analysis using Chi-Square Feature Selection** (`sentiment-analysis-using-selectbest-chi2.ipynb`)
   - Applies the Term Frequency-Inverse Document Frequency (TF-IDF) vectorization method to transform the text data into numerical features.
   - Implements feature selection using the Chi-Square (Chi2) statistical test to identify the most relevant features for sentiment classification.
   - Uses the selected features to train SVM to predict sentiment.

3. **Sentiment Analysis using Logistic Regression** (`sentiment-analysis-using-logisticregression.ipynb`)
   - Applies the Term Frequency-Inverse Document Frequency (TF-IDF) vectorization method to transform the text data into numerical features.
   - Applies the Logistic Regression algorithm to the dataset for sentiment analysis.
  
**All the notebooks Include steps for data preprocessing, model training, and evaluation.**

## Getting Started

To replicate the analysis or experiment with the notebooks:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/abirbarbara/SentimentAnalysis-MoroccanDialect.git
