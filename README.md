# Email Spam Detection

This Python project implements a spam detection system using a Support Vector Machine (SVM) classifier. The system is built upon the popular `pandas` library for data manipulation and `scikit-learn` for machine learning tasks.

## Key Features: ##

1. ### Data Preparation: ###
   The project utilizes the `pandas` library to load a dataset (`spam.csv`) containing text messages labeled as spam or non-spam (ham).

2. ### Text Representation: ###
   Text data is transformed into numerical features using the `CountVectorizer` from scikit-learn, which converts text documents into a matrix of token counts.

3. ### Model Training: ###
   A Support Vector Machine classifier (`svm.SVC()`) is trained on the transformed text features to classify messages as spam or ham.

4. ### Evaluation: ###
   The trained model's performance is evaluated using a test set split from the original data. The accuracy of the model is calculated and printed to assess its effectiveness in classifying spam messages.
