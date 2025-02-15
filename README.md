# Machine Learning Lab (CSE-5211)<br>
# Project Name : Credit Card Fraud Detection Using Machine Learning<br>
Supervised By:<br>
Md. Mynoddin<br>
Assistant Professor<br>
Department of CSE<br>

Submitted By:<br>
Sadia Naznin Ananna (2018-15-13)<br>
Tasnia Nawshin Meem (2018-15-04)<br>
# About Project<br>
This project aims to detect fraudulent credit card transactions using machine learning algorithms, specifically Logistic Regression and Random Forest. The model is trained on real transaction data, distinguishing between legitimate and fraudulent transactions based on various features such as transaction amount, time, and location.
# Introduction<br>
Credit card fraud is a growing concern in the present world with the growing fraud in the government offices, corporate industries, financial industries and many other organizations. Credit card fraud detection is the process of identifying and preventing unauthorized or fraudulent transactions made using credit cards. This is done using a combination of rule-based systems, machine learning algorithms, and real-time monitoring to analyze transaction patterns and detect suspicious activities.
# Problem Statement<br>
Credit card fraud is a major challenge that affects financial institutions, merchants, and customers.Credit card fraud leads to significant financial losses worldwide. Fraudsters use various techniques, including stolen card information, phishing, and identity theft, to make unauthorized transactions. The challenge is to develop effective fraud detection and prevention mechanisms that minimize financial risks while ensuring a seamless experience for genuine customers.
# Objectives<br>
1.Detect Fraudulent Transactions<br>
2.Handle Imbalanced Data<br>
3.Minimize False Positives<br>
4.Improve Fraud Detection Accuracy<br>
5.Increase Security in Online Payments<br>
6.Reduce Financial Losses<br>
# About the Dataset<br>
The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents 284,807 transactions.
It contains only numerical input variables which are the result of a PCA transformation.
The only features which have not been transformed with PCA are 'Time' and 'Amount'.<br>
Data set link:https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud 
#  Machine Learning Algorithms Used<br>
# Logistic Regression :<br>
The method of modelling the probability of a discrete result given an input variable is known as logistic regression. The most frequent logistic regression models have a binary outcome, which might be true or false, yes or no, and so forth. Logistic regression is a handy analysis tool for determining if a fresh sample fits best into a category in classification tasks. Because components of cyber security, such as threat detection, are classification problems, logistic regression is a valuable analytic tool.<br>
1.Uses a sigmoid function to classify transactions as fraud or not.<br>
Simple and fast, but struggles with complex fraud patterns.<br>
![image](https://github.com/user-attachments/assets/fca15035-84cc-4e0e-9a65-74459d9a4c67)<br>
# Random Forest :<br>
A Random Forest is a collection of decision trees that work together to make predictions.Random Forest builds multiple decision trees using random samples of the data. Each tree is trained on a different subset of the data which makes each tree unique.
When creating each tree the algorithm randomly selects a subset of features or variables to split the data rather than using all available features at a time. This adds diversity to the trees.
Each decision tree in the forest makes a prediction based on the data it was trained on. When making final prediction random forest combines the results from all the trees.For classification tasks the final prediction is decided by a majority vote. This means that the category predicted by most trees is the final prediction.
For regression tasks the final prediction is the average of the predictions from all the trees.
The randomness in data samples and feature selection helps to prevent the model from overfitting making the predictions more accurate and reliable.<br>
![image](https://github.com/user-attachments/assets/19c1ef9d-565b-4167-9717-bcba57ce05d5)<br>
# Methodology<br>
1. Data Collection<br>

This step involves gathering real or synthetic transaction data from banks, financial institutions, or publicly available datasets (e.g., Kaggle, IEEE-CIS).<br>
The dataset includes transaction details such as amount, location, time, merchant type, and cardholder information.<br>
The goal is to collect a large and diverse dataset to train the model effectively.<br>

2. Preprocessing<br>

Removing duplicates, handling missing values. Then converting data into a uniform format.Encoding categorical data
Proper preprocessing ensures high-quality input data for the model.<br>

3. Handling Imbalance:<br>

Oversampling: Creating synthetic fraud samples.<br>
Undersampling: Reducing the number of normal transactions to balance the dataset.<br>
Cost-sensitive learning: Penalizing misclassification of fraud more than normal cases.<br>
This step improves fraud detection without increasing false alarms.<br>

4. Feature Selection:<br>

Identifying the most important features that influence fraud detection.<br>
Example features:<br>
Transaction amount (sudden high spending can indicate fraud).<br>
Time of transaction (unusual hours may be suspicious).<br>
Location mismatch (transaction in a different country than usual).<br>
Feature selection improves model performance and reduces computational cost.<br>

5. Model Training:<br>

Common algorithms used:<br>
Logistic Regression: Simple and interpretable.<br>
Decision Tree: Finds rules for detecting fraud.<br>
Random Forest: An ensemble of decision trees for better accuracy.<br>
KNN (K-Nearest Neighbors): Detects fraud based on transaction similarity.<br>
Neural Networks (Deep Learning): Advanced model for complex fraud patterns.<br>
Training involves feeding the data to these models so they learn to differentiate normal vs. fraudulent transactions.<br>

6. Model Evaluation: <br>

After training, the model’s performance is tested using metrics like:<br>
Accuracy: Overall correctness. <br>
Precision: How many detected frauds are actually fraud? <br>
Recall (Sensitivity): How many fraud cases were correctly identified? <br>
F1-score: A balance between precision and recall. <br>
Confusion Matrix: A visual representation of correct and incorrect predictions. <br>

7. Fraud Detection & Deployment: <br>
   
The trained model is integrated into a real-world system for detecting fraud.
This step ensures that fraud detection is automated, efficient, and scalable. <br>
![image](https://github.com/user-attachments/assets/9629d1b5-ab95-4eaa-a0b8-058083d2d42b)<br>

# Result<br>
Logistic Regression<br>

![image](https://github.com/user-attachments/assets/518f61bf-fba1-4cce-a068-c80d4bf43464)<br>

Random Forest Classifier<br>

![image](https://github.com/user-attachments/assets/d8eec69c-a210-4733-bde4-8d3355b55b52)<br>

![image](https://github.com/user-attachments/assets/099c9d16-cf99-4c09-b160-624eb86166c0)<br>

# Future Work<br>
1. Improving model performance & accuracy<br>
2. Adapting to emerging fraud techniques<br>
3. Blockchain & Federated Learning for secure transactions<br>
4. Explainable AI for Fraud Investigation<br>
5. Integration with advanced cybersecurity measures<br>


                                                                                            


















