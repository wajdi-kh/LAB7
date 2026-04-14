LAB7 
Name : Wajdi Essam
Group: 6MY02

Here is a concise summary designed for a GitHub `README.md` file:

---

# Logistic Regression - Advertisement Click Prediction

## Project Overview
This project involves building a **Logistic Regression** model to predict whether or not an internet user will click on an advertisement based on their demographic and usage data. 

## Dataset
The dataset `advertising.csv` contains 1,000 entries with the following features:
* **Daily Time Spent on Site**: Consumer time on site (minutes).
* **Age**: Customer age (years).
* **Area Income**: Average income of the consumer's geographical area.
* **Daily Internet Usage**: Average minutes per day the consumer is online.
* **Male**: Gender indicator (0 for Female, 1 for Male).
* **Clicked on Ad**: Target variable (0 = No, 1 = Yes).

## Key Steps
1. **Exploratory Data Analysis (EDA)**: Used Seaborn to visualize age distributions, area income vs. age correlations, and internet usage patterns.
2. **Data Preprocessing**: Split the data into training and testing sets (33% test size).
3. **Model Training**: Implemented a `LogisticRegression` model using Scikit-Learn.
4. **Evaluation**: Assessed model performance using a classification report, achieving an accuracy of approximately **91%**.

## Requirements
* Python 3
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-Learn

---
