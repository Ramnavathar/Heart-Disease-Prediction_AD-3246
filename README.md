# Heart Disease Prediction using Machine Learning

## 1. Project Overview

Heart Disease Prediction is a machine learning project that predicts whether a person may have heart disease based on medical information.

This project uses **Logistic Regression**, a machine learning classification algorithm, to predict the result.

The project is developed using Python and Google Colab.

## 2. Objective

The main objectives of this project are:

- To understand how machine learning works.
- To predict heart disease using medical data.
- To perform data preprocessing and cleaning.
- To train and test a Logistic Regression model.
- To evaluate the model using accuracy, precision, recall, and F1-score.
- To provide a simple interface where users can enter medical details and get a prediction.

## 3. Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- IPyWidgets

## 4. Dataset

The project uses the **Cleveland Heart Disease dataset** from the UCI Machine Learning Repository.

The dataset contains medical information such as:

- Age
- Sex
- Chest pain type
- Resting blood pressure
- Cholesterol level
- Maximum heart rate
- Exercise-induced angina
- ST depression
- Other medical attributes

The original target values range from 0 to 4. In this project, they are converted into two classes:

- `0` – No heart disease detected in the dataset
- `1` – Heart disease detected in the dataset

## 5. Machine Learning Algorithm

The project uses **Logistic Regression** for classification.

Logistic Regression learns patterns from the training data and predicts whether the input belongs to class 0 or class 1.

## 6. Project Workflow

1. Import required libraries.
2. Load the dataset.
3. Explore the dataset.
4. Handle missing values and duplicate records.
5. Convert the target into binary classes.
6. Separate input features and target.
7. Split the dataset into training and testing data.
8. Apply feature scaling and encoding.
9. Train the Logistic Regression model.
10. Evaluate the model.
11. Enter user details through the prediction interface.
12. Display the prediction result.

## 7. How to Run the Project

1. Open Google Colab.
2. Upload or open the project notebook.
3. Run all code cells in sequence.
4. Wait for the dataset to load and the model to train.
5. Enter the required medical information.
6. Click the **Predict Heart Disease** button.
7. View the prediction result.

## 8. Model Evaluation

The model is evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

These metrics help understand how well the model performs on unseen test data.

## 9. Conclusion

This project demonstrates how machine learning can be used for a heart disease classification task. It includes data preprocessing, model training, evaluation, and user input-based prediction.

The project helped in understanding the basic workflow of a machine learning classification model.

## 10. Disclaimer

This project is developed for educational purposes only. The prediction is not a medical diagnosis and should not be used for making healthcare decisions. Always consult a qualified medical professional for medical advice.

## GitHub Reference
https://github.com/complexiota
