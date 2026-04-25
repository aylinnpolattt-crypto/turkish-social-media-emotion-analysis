# Emotion Analysis in Turkish Social Media Comments

[Open in Google Colab](https://colab.research.google.com/drive/1DCmQYvO53LXB2s55J8VwxgMcP68yGkJq?usp=sharing)

This project was developed as part of a data science assignment to analyze Turkish social media comments and classify them as positive or negative.

## Project Overview
- Dataset: 11,119 manually labeled Turkish comments  
- Task: Binary sentiment classification  
- Methods: TF-IDF, Logistic Regression, Linear SVM  
- Result: Around 86% accuracy  

## What I did
- Cleaned and prepared raw text data  
- Converted text into numerical features using TF-IDF  
- Trained and compared two models (Logistic Regression and SVM)  
- Evaluated model performance using accuracy and F1-score  
- Analyzed model errors to understand where predictions fail  

## Key Observations
- Both models performed similarly, with Logistic Regression slightly better  
- Most errors happened in short or unclear comments  
- TF-IDF worked well as a simple feature method for Turkish text  

## Tools
Python, Pandas, scikit-learn, TF-IDF

## Note
The dataset is not shared publicly due to privacy reasons.
