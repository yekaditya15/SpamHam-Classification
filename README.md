

# Spam Classification using Naive Bayes

This project focuses on classifying emails as spam or ham (non-spam) using the Naive Bayes algorithm. The Jupyter notebook (`spamham.ipynb`) provides a step-by-step walkthrough of the entire process, from data loading to model evaluation.

## Overview

The main steps covered in the notebook include:

1. **Data Loading and Exploration:**
   - The dataset (`spam.csv`) is loaded, and a preliminary exploration of the data is conducted to understand its structure.

2. **Data Preprocessing:**
   - The 'Category' column is transformed into a binary 'spam' column, where spam is represented as 1 and ham as 0.

3. **Text Vectorization:**
   - The emails are transformed into numerical features using the CountVectorizer from scikit-learn. This step is crucial for feeding text data into machine learning models.

4. **Model Training:**
   - A Multinomial Naive Bayes model is trained using the transformed text data to learn patterns and associations between words and spam/ham labels.

5. **Model Prediction:**
   - The trained model is used to predict the classification of sample emails.

6. **Sklearn Pipeline:**
   - A scikit-learn pipeline is introduced, simplifying the workflow by combining text vectorization and model training into a single entity.

7. **Model Evaluation:**
   - The model's performance is evaluated on a test set, providing insights into its accuracy in distinguishing between spam and ham.



Feel free to contribute, provide feedback, or open issues if you have suggestions or improvements!

