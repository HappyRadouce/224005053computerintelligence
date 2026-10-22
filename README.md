# Lab 1: Telco Customer Churn Analysis

## 1. Introduction

This project focuses on analyzing the Telco Customer Churn dataset using Python. The purpose is to explore customer information and understand the relationships between customer churn and different demographic characteristics, services, contracts, billing, and payment methods.

## 2. Objectives

The main objectives of this project are to:

* Load and inspect the Telco Customer Churn dataset.
* Examine the first and last records of the dataset.
* Preprocess the data by converting the Churn attribute from Yes/No to 1/0.
* Display and adjust the data types of attributes where necessary.
* Identify and handle missing values.
* Explore the relationship between customer churn and selected customer attributes.
* Interpret the results obtained from the analysis.

## 3. Dataset Description

The dataset contains information about telecommunications customers, including demographic details, subscribed services, contract types, billing preferences, payment methods, and customer churn status.

The target attribute is **Churn**, which indicates whether a customer has left the company.

## 4. Tools and Technologies

The following tools and libraries are used in this project:

* **Python:** Programming language used for the analysis.
* **Pandas:** Used for data loading, preprocessing, manipulation, and analysis.
* **Matplotlib:** Used to create visualizations of the results.
* **Kaggle Notebook:** Environment used to write and execute the Python code.

## 5. Data Preprocessing

The preprocessing stage includes:

* Loading the dataset into the notebook.
* Displaying the first and last records.
* Converting the Churn values from Yes/No to 1/0.
* Displaying and checking the data types of the attributes.
* Converting attributes to appropriate data types where necessary.
* Identifying missing values and removing records containing missing values, as required by the assignment.

## 6. Exploratory Data Analysis

The analysis explores the relationship between customer churn and the following attributes:

### Demographic Analysis

* Gender
* SeniorCitizen
* Partner
* Dependents

### Service Analysis

* PhoneService

### Contract and Payment Analysis

* Contract
* PaperlessBilling
* PaymentMethod

Tables, charts, and percentage calculations are used to examine the distribution of churn across these categories. Each analysis is followed by an interpretation of the results.

## 7. Expected Outcomes

The project aims to identify patterns in customer churn and determine which customer characteristics, service arrangements, contract types, and payment preferences are associated with higher or lower churn rates.

The findings may help a telecommunications company better understand customer behavior and identify areas where customer retention strategies could be improved.

## 8. Conclusion

This project demonstrates the use of Python for data preprocessing and exploratory data analysis. By examining customer churn alongside demographic, service, contract, billing, and payment attributes, the analysis provides insights into customer behavior. However, the observed relationships do not necessarily prove that any particular attribute causes customer churn.
