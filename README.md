# Facebook Posts Sentiment Analysis

## Author Information
- **Name:** DHARSAN KUMAR R
- **Register No:** 212223240028
- **Date:** November 9, 2025

## Project Overview
This project analyzes the sentiment of Facebook posts using NLTK's VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analyzer. It processes posts from an Excel file and provides sentiment scores indicating whether each post expresses positive, negative, or neutral sentiment.

## Objective
To develop a Python-based sentiment analysis system that can:
1. Read Facebook posts from an Excel file
2. Analyze the sentiment of each post using NLTK's VADER
3. Provide detailed sentiment scores and interpretation
4. Generate summary statistics of sentiment distribution

## Features
- Reads Facebook posts from an Excel file
- Performs sentiment analysis using NLTK's VADER
- Provides detailed sentiment scores for each post
- Generates summary statistics of overall sentiment distribution
- Creates a sample dataset if no input file is provided

## Prerequisites
- Python 3.x
- Jupyter Notebook/Lab or VS Code with Jupyter extension
- Required packages (automatically installed by notebook):
  - pandas (for data handling)
  - nltk (for sentiment analysis)
  - openpyxl (for Excel file support)

## Program Usage
1. Ensure you have an Excel file named `FacebookPosts.xlsx` with a 'Timeline' column containing posts
   - If no file exists, the notebook creates a sample file automatically
2. Open and run `FaceBookSentimentAnalysis.ipynb` in sequence
3. View sentiment analysis results for each post

## Sample Output
```
Post 1: I love this product! Highly recommend.
  Sentiment scores:
    neg: 0.000, neu: 0.242, pos: 0.758, compound: 0.836
------------------------------------------------------------
```

## Learning Outcomes
Through this project, I have learned:
1. Natural Language Processing (NLP) fundamentals
2. How to perform sentiment analysis using VADER
3. Data handling with pandas and Excel files
4. Python package management in Jupyter notebooks
5. How to create robust, error-handling code
6. The interpretation of sentiment scores and their significance
