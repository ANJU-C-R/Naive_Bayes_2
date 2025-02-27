# Drug Classification Using Naive Bayes Algorithm
## Introduction
Medication prescription plays a crucial role in healthcare, ensuring patients receive the most effective treatment based on their medical conditions. However, selecting the appropriate drug for a patient depends on several factors, including age, sex, blood pressure levels, cholesterol levels, and the sodium-to-potassium ratio in the body. In this study, we leverage machine learning techniques to classify drugs based on these patient attributes, aiming to improve accuracy in medication recommendations.
## Nayes Bayes Algorithm
The Naïve Bayes algorithm is a probabilistic classification technique based on Bayes' Theorem. It assumes that the features are independent of each other, making it a "naïve" assumption. Despite this simplification, Naïve Bayes performs well in many real-world applications, especially in text classification, spam detection, and medical diagnosis. The algorithm calculates the probability of each class given the input features and selects the class with the highest probability. It is computationally efficient, works well with small datasets, and is particularly useful for categorical data.
## Dataset Overview
Dataset is taken from kaggle, which is uploaded as "drug_classification.csv",link:https://www.kaggle.com/datasets/prathamtripathi/drug-classification
The dataset used in this project contains information about different drug types and their corresponding patient profiles. The target variable is the drug type, while the feature set includes age, sex, blood pressure levels (BP), cholesterol levels, and sodium-to-potassium ratio. 

| **Column Name**        | **Description**                                              |
|------------------------|--------------------------------------------------------------|
| **Age**               | The age of the patient (numerical).                          |
| **Sex**               | The gender of the patient (`Male` or `Female`).              |
| **BP (Blood Pressure)** | The blood pressure level of the patient (`Low`, `Normal`, `High`). |
| **Cholesterol**       | The cholesterol level of the patient (`Normal`, `High`).     |
| **Na to Potassium Ratio** | The ratio of sodium to potassium in the blood (numerical). |
| **Drug Type**         | The type of drug prescribed to the patient (target variable). |

By applying classification algorithms, we aim to develop a predictive model that can assist in recommending the most suitable drug for a patient.
