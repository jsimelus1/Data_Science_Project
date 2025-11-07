# Sentiment Analysis of Reddit Users

This repository contains a two-part project that performs sentiment analysis on Reddit user data, demonstrating the full data science workflow from raw text extraction to machine-learning-based sentiment classification.

The analysis showcases skills in natural language processing (NLP), text cleaning, feature engineering, and supervised learning, using Python and open-source data science tools.

### Repository Contents
          File                                        Description
          1) Final-Project-Part-I.ipynb               Data acquisition and preprocessing. Connects to Reddit’s API, scrapes posts/comments, and performs text cleaning—removing stopwords, punctuation, emojis, and links. Includes exploratory data analysis (EDA) on word frequency and sentiment distribution.
          2) Final-Project-Part-II.ipynb              Model training and evaluation. Implements machine learning models (e.g., Logistic Regression, Naive Bayes, and/or BERT-based classifiers) to predict sentiment labels (positive, negative, neutral). Evaluates model accuracy, precision, recall, and confusion matrices.
          
### Project Objectives
          - Collect and Prepare Text Data from Reddit users using the Pushshift or PRAW API.
          - Explore Linguistic Patterns to understand public sentiment and keyword trends.
          - Develop and Evaluate Models that classify text sentiment effectively.
          - Visualize and Interpret Results to provide actionable insights on user attitudes or topics.

### Methods and Workflow
#### Data Extraction: 
          - Retrieve Reddit posts/comments from selected subreddits or search queries.
#### Text Preprocessing:
          - Tokenization, stopword removal, lemmatization
          - Handling of URLs, emojis, and punctuation

#### EDA and Visualization:
          - Word clouds and frequency plots
          - Sentiment score distributions

#### Modeling:
          - Classical models (Logistic Regression, Naive Bayes, SVM)
          - Optionally fine-tuned transformer models (e.g., BERT)

#### Evaluation:
          - Accuracy, Precision, Recall, F1-score, and ROC-AUC
          - Comparison of model performance

### Tools and Technologies
          Category                    Libraries / Frameworks
          Core Python                 pandas, numpy, re, json
          NLP                         nltk, textblob, vaderSentiment, transformers, scikit-learn
          Visualization               matplotlib, seaborn, wordcloud, plotly
          Environment                 jupyter, nbstripout
          APIs                        praw (Python Reddit API Wrapper), requests

### Expected Outcomes
          - A cleaned and structured Reddit text dataset.
          - Sentiment classification models capable of identifying tone and polarity.
          - Visualization of sentiment trends by topic, user group, or subreddit.
          - A reproducible end-to-end pipeline for social media sentiment analysis.

### Learning Objectives
          - Apply NLP preprocessing techniques to real-world social data.
          - Implement and evaluate supervised learning models on textual data.
          - Interpret and communicate machine learning results effectively.
          - Explore ethical considerations in social media data collection and sentiment inference.
