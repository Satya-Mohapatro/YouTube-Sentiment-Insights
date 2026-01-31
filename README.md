# YouTube Sentiment Insights 

An end-to-end NLP and MLOps-based system to analyze sentiment from YouTube comments using Machine Learning, MLflow, DVC, and a Flask API, with a Chrome Extension frontend.

---

## Features
- Sentiment analysis of YouTube comments (Positive / Negative / Neutral)
- NLP preprocessing and TF-IDF feature extraction
- Machine learning models including LightGBM and XGBoost
- Experiment tracking and model registry using MLflow
- Data and pipeline versioning using DVC
- REST API built with Flask
- Chrome Extension for real-time sentiment prediction

---
##  Project Architecture

The following diagram illustrates the end-to-end architecture of the YouTube Sentiment Insights system, covering data ingestion, model training, MLOps workflow, deployment, and frontend integration.

![Project Architecture](Documents/Architecture_Diagram.png)

---

##  Tech Stack
- Python
- Scikit-learn
- LightGBM, XGBoost
- MLflow
- DVC
- Flask
- JavaScript (Chrome Extension)

---

## Results
- Best model: TF-IDF + LightGBM
- Evaluation metric: F1-score (to handle class imbalance)

---

## Future Improvements

- Transformer-based models (BERT)
- Dockerization
- Batch inference support
- Multilingual sentiment analysis

---

## Author
Satyanarayan Mohapatro
