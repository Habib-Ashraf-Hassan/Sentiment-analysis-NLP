# Sentiment Analysis using NLP and RandomForestClassifier

## Project Overview

This project is a **Sentiment Analysis** tool built using **Natural Language Processing (NLP)** techniques and a **RandomForestClassifier** to classify text which are in different tones of: _joy, surprise, love, anger, sadness and hate_ into **positive** or **negative** sentiments. The project trains the model using labeled data and evaluates it on a separate test set, achieving an accuracy of approximately **~96%**.

### Key Features:
- **Text Preprocessing**: Removes stopwords, performs lemmatization, and transforms text into a format suitable for model training.
- **Vectorization**: Converts preprocessed text data into numerical features using **CountVectorizer** with bigrams (1,2 n-grams).
- **Model Training**: Utilizes a **RandomForestClassifier** to build the sentiment classification model.
- **User Input Testing**: Allows users to input custom text to predict sentiment in real-time.
- **Model Evaluation**: The model's performance is evaluated using **accuracy score**, confusion matrix, precision, recall, and F1-score.

## Results

The model was tested with custom user input, and it successfully classified both positive and negative sentiments. The accuracy of the model on the test dataset was around **96%**, demonstrating the effectiveness of the model for sentiment analysis tasks.

### Example of User Input Test:
![User Input Test Result](path_to_screenshot.png)

The above image shows a successful classification of user input using the trained sentiment analysis model.

## How to Use

1. **Install Dependencies**:
   Ensure you have all required libraries by running:
   ```bash
   pip install -r requirements.txt
