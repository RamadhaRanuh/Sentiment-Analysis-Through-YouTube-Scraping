# YouTube Sentiment Analysis

This project analyzes sentiments in YouTube comments scraped using the **Google Cloud YouTube API v3**. By employing three different machine learning models, it offers a comprehensive understanding of audience sentiments.  

## Features
- Scraping YouTube comments using **Google Cloud YouTube API v3**.
- Sentiment analysis using three models:
  - **Random Forest** with Word2Vec features.
  - **Logistic Regression** with TF-IDF features.
  - **LSTM** with TF-IDF features.
- Average train-test accuracy of **85-90%** across all models.

## Requirements
Before running the project, ensure you have the following:
- Python 3.10 or higher
- A Google Cloud account and API key for YouTube Data API v3

## Project Structure  

```plaintext
youtube-sentiment-analysis/  
├── preprocess.ipynb                   # Notebook for preprocessing and modeling  
├── requirements.txt                   # File listing required libraries  
├── scrapping.ipynb                    # Notebook to scrape YouTube comments  
├── YoutubeCommentScrapDataset.csv     # Dataset created from scrapping.ipynb  
```

## Results
The project demonstrates the following performance:

    Random Forest with Word2Vec: Test Accuracy ~ 79%
    Logistic Regression with TF-IDF: Test Accuracy ~ 87%
    LSTM with TF-IDF: Test Accuracy ~ 90%
