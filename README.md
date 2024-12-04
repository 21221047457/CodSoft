# CodSoft                           

# 📱 SMS Spam Detection,  Movie Genre Classification  and Customer Churn Prediction 🚀

This repository contains multiple machine learning projects aimed at solving real-world problems using classification algorithms. Below is an overview of the included projects.


## 📂 Project 1: SMS Spam Detection  
A machine learning solution to classify SMS messages as either **Spam** or **Ham** (not spam) using text preprocessing and a Support Vector Machine (SVM) model.  

### 🔑 Key Features
- Dataset cleaned and labeled (spam/ham).
- TF-IDF vectorizer for feature extraction.
- SVM model with classification reports and accuracy.
- Real-time user interaction for message classification.

### 📄 How to Run
1. Ensure the `spam.csv` dataset is in the project directory.
2. Execute the Python script.
3. Enter SMS messages interactively to classify as spam or ham.


## 📂 Project 2: Movie Genre Classification  
A project to predict the genre of a movie based on its plot description using Logistic Regression.  

### 🔑 Key Features
- Utilizes **TF-IDF** for text processing.
- Encodes genres into numeric labels.
- Confusion matrix visualization for evaluation.
- Real-time predictions using user-provided movie plot descriptions.

### 📄 How to Run
1. Place `train_data.txt` and `test_data.txt` files in the same directory.
2. Run the script to train and evaluate the model.
3. Enter plot descriptions interactively to predict genres.


## 📂 Project 3: Bank Customer Churn Prediction  
This project predicts whether a customer is likely to leave the bank based on demographic and transactional data using a **Random Forest Classifier**.  

### 🔑 Key Features
- Encodes categorical data (e.g., Geography, Gender).
- Standardizes features for model input.
- Interactive mode to predict churn using user inputs.

### 📄 How to Run
1. Run the script to load the sample dataset or replace it with your own (`dataset.csv`).
2. Use the interactive mode to provide customer details and receive churn predictions.


## 🛠️ Requirements
Install the following Python libraries before running the scripts:
```bash
pip install pandas scikit-learn matplotlib seaborn
```



## ✨ Features and Models
| **Project**         | **Algorithm**         | **Tools**      |
|----------------------|-----------------------|----------------|
| SMS Spam Detection   | SVM                  | TF-IDF, sklearn |
| Movie Genre Prediction | Logistic Regression | TF-IDF, matplotlib, seaborn |
| Customer Churn       | Random Forest        | sklearn        |


## 🤝 Contributing
Feel free to fork the repository, add improvements, and create pull requests. Your contributions are welcome!


