# RNN, LSTM, and Data Augmentation Techniques for Text Classification Using Spam and Ham Dataset

## Introduction
This repository contains a Python notebook that demonstrates the use of Recurrent Neural Networks (RNN) and Long Short-Term Memory (LSTM) models for classifying emails as spam or non-spam (ham). The notebook explores various data augmentation techniques to improve model performance and reduce overfitting.

## Skills Employed
- Tokenization and Padding Sequences
- RNN and LSTM Model Development
- Dropout Regularization
- Data Augmentation Techniques: Synonym Replacement, Sentence Shuffling, Back Translation
- TensorFlow and Keras

## Files
- `RNN_Backtranslation.ipynb`: The main notebook containing the code and analysis.
- `email_classification.csv`: The dataset used for training and evaluation.

## Getting Started
1. Clone this repository.
   ```sh
   git clone https://github.com/gmzmercado/spam-ham-classification.git
   ```
2. Install the required libraries.
   ```sh
   pip install -r requirements.txt
   ```
3. Run the notebook.
   ```sh
   jupyter notebook RNN_and_LSTM_Classification.ipynb
   ```

## Dataset
The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/prishasawhney/email-classification-ham-spam). It contains two columns:
- `Email`: The textual content of the email.
- `Label`: The classification label (spam or ham).

## Summary
In this project, we develop and compare RNN and LSTM models for email classification. We implement dropout and data augmentation techniques to enhance model robustness and generalization, achieving reliable and accurate text classification.