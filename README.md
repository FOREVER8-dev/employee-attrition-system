# employee-attrition-system
Machine Learning Based Employee Attrition Analysis

## Overview

This project aims to predict employee attrition using Machine Learning techniques and identify the key factors that influence employee turnover. The analysis is intended to support HR teams in detecting employees who may be at risk of leaving the company.

## Business Problem

Employee attrition can increase recruitment and training costs, reduce productivity, and lead to the loss of experienced talent. Therefore, companies need a data-driven approach to identify employees at risk of resignation and support retention strategies.

## Dataset
* url of the dataset can be visited in here: https://raw.githubusercontent.com/nelson-wu/employee-attrition-ml/master/WA_Fn-UseC_-HR-Employee-Attrition.csv
* Total Employees: 1,470
* Target Variable: Attrition (Yes/No)
* Domain: Human Resources Analytics

## Models Evaluated

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)

## Results

| Model               | Accuracy | Recall |
| ------------------- | -------: | -----: |
| Logistic Regression |   57.48% | 80.85% |
| KNN                 |   39.46% | 80.85% |
| SVM                 |   84.69% | 19.15% |

Logistic Regression was selected because it achieved the target attrition recall while maintaining better overall performance compared to KNN.

## Key Findings

### Main Risk Factors

* Overtime
* Business Travel Frequently
* Laboratory Technician

### Protective Factors

* Education Field: Life Sciences
* Total Working Years
* Years with Current Manager

## Business Impact

* Support early detection of employees at risk of attrition
* Improve employee retention strategies
* Reduce recruitment and training costs
* Support HR decision-making with data-driven insights

## Tools & Libraries

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn

## Author

Syahdu Zahara Dewo Putri
