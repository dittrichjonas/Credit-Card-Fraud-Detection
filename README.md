Credit Card Fraud Detection

Project Overview

This project aims to address the pressing issue of credit card fraud, a prevalent problem where unauthorized individuals engage in financial transactions using someone else’s credit card details. Such activities have surged with the growth of online shopping and digital payments, accentuated by global shifts in consumer behavior due to the COVID-19 pandemic. Financial institutions face billions in losses annually due to these fraudulent activities. This project seeks to leverage machine learning to distinguish between fraudulent and legitimate transactions effectively.

Objective

The primary goal is to develop a model that can accurately classify transactions into two categories: fraudulent and legitimate. This involves tackling the challenge presented by the significantly imbalanced nature of the dataset where fraudulent transactions are very rare.

Dataset Description

The dataset comprises credit card transactions from European cardholders in September 2013, captured over a period of two days. Out of 284,807 transactions, 492 were fraudulent. This stark imbalance highlights the rarity of fraud occurrences, making it a challenging but crucial task to identify such activities accurately.

Attributes
	•	V1 to V28: These are anonymized numerical features generated from a Principal Component Analysis (PCA) to protect sensitive information.
	•	Time: This feature measures the seconds elapsed between each transaction and the first transaction in the dataset.
	•	Amount: It represents the monetary value of each transaction.
	•	Class: Indicates the transaction class, where ‘1’ denotes fraud and ‘0’ denotes a legitimate transaction.

Notebook Contents
	•	Overview of the Dataset
	•	Data Visualization Techniques
	•	Feature Selection Strategies
	•	Techniques for Balancing Data
	•	Model Development and Evaluation
	•	Conclusion and Future Directions

Learning Outcomes

Participants will learn about:
	•	The application of Synthetic Minority Over-sampling Technique (SMOTE) for addressing dataset imbalance.
	•	The use of statistical tests to select meaningful features.
	•	Comparing models based on the features selected through statistical tests.
	•	The entire process of building and visualizing the performance of machine learning models.
