# LSTM Next Word Prediction

## Overview

This project predicts the next word in a text sequence using a trained Long Short-Term Memory (LSTM) model.

The application uses Streamlit to provide an interactive interface where users can enter text and receive a next-word prediction.

## Technologies Used

* Python
* TensorFlow / Keras
* LSTM
* Streamlit
* NumPy

## Project Structure

* `app.py` — Streamlit application.
* `lstm_model.h5` — Trained LSTM model.
* `tokenizer.pkl` — Tokenizer used to convert text into numerical sequences.
* `maxlen.pkl` — Stores the sequence length configuration.
* `dataset.csv` — Dataset used in the original training process.
* `requirements.txt` — Required Python libraries.

## Installation

1. Clone this repository.

2. Create and activate a Python virtual environment.

3. Install the dependencies:

   `pip install -r requirements.txt`

4. Start the application:

   `streamlit run app.py`

## Model Attribution

The original trained model was created by my mentor. The application and other contributions should be described according to the work actually completed.

## Limitations

Predictions depend on the model's training data, vocabulary, and preprocessing configuration.
