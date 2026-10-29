Fake News Detection System

An NLP and Machine Learning project for classifying news text.

A Python-based application that analyzes news text and predicts whether it resembles real or fake news based on patterns learned from training data.

«Disclaimer: Predictions are estimates, not proof of a news article's factual accuracy.»

---

Overview

The project demonstrates how Natural Language Processing (NLP) and machine learning can be combined to classify news text through a web application.

Key Features

- News text classification
- Text preprocessing and TF-IDF feature extraction
- Multiple machine learning models
- Flask-based web interface
- Model training and evaluation scripts
- Optional fact-checking integration

Tech Stack

Technology| Purpose
Python| Core programming
Flask| Web application
Scikit-learn| Machine learning
NLTK| Text processing
Pandas & NumPy| Data handling
TF-IDF| Text feature extraction
Joblib| Saving and loading models
HTML, CSS & JavaScript| User interface

How It Works

1. Input: The user enters news text.
2. Preprocessing: The text is cleaned and prepared.
3. Feature Extraction: TF-IDF converts text into numerical features.
4. Prediction: A trained model classifies the input.
5. Output: The application displays the prediction.

Project Structure

fake-news-detection/
├── app.py
├── config.py
├── train_models.py
├── quick_retrain.py
├── data/
├── models/
├── notebooks/
├── src/
├── templates/
├── tests/
├── screenshots/
├── requirements.txt
├── MODEL_LIMITATIONS.md
└── README.md

Installation

1. Clone the repository

git clone https://github.com/nikhiilatri/fake-news-detection.git
cd fake-news-detection

2. Create and activate a virtual environment

Windows PowerShell:

python -m venv .venv
.\.venv\Scripts\Activate.ps1

3. Install dependencies

python -m pip install -r requirements.txt

4. Start the application

python app.py

If the server starts successfully, open "http://localhost:5000" in your browser.

Machine Learning Models

The repository contains model files and training resources for classification experiments, including:

- Logistic Regression
- Naive Bayes
- Random Forest
- Support Vector Machine (SVM)

Actual performance depends on the dataset, training process, and evaluation method. Refer to the project's evaluation results rather than assuming a particular accuracy.

Limitations

- Predictions may be incorrect or biased by the training data.
- Unseen topics and changing language can reduce reliability.
- A classification is not the same as independent fact verification.
- Optional external fact-checking features may require API configuration.

Future Improvements

- Evaluate models on newer, independent datasets.
- Experiment with transformer-based NLP models.
- Improve prediction explanations.
- Expand fact-checking and source verification.
- Deploy the application for public use.

Credits

This project was adapted from an existing open-source implementation. Credit the original author and retain any attribution required by the original project's license.

Original project: https://github.com/Ujjwal-eng/fake_news_detection

See the "LICENSE" file for applicable terms.

---

Developed for learning and experimentation with NLP and machine learning.
