# Heart Disease Risk Prediction Model
This repository contains the code and documentation for my undergraduate thesis project. The project focuses on developing a machine-learning model based on patient data to predict heart disease risk. This work utilizes various classification algorithms and a feature importance analysis to highlight key attributes impacting heart disease prediction. Additionally, a prototype user interface is included to make predictions more accessible.


## Project Overview
This thesis project aims to create an accurate, interpretable model to predict heart disease risk based on clinical and demographic data, supporting healthcare providers in early diagnosis and patient management. The model analyzes key health indicators and produces risk assessments while offering insight into the importance of different predictive features.

## Motivation
Heart disease remains one of the primary causes of mortality worldwide, making early detection critical for improving treatment outcomes and patient care. This project leverages machine learning to provide more accurate and interpretable insights into heart disease risk, highlighting predictive features that could help clinicians in decision-making.

## Data
The project uses the Heart Disease UCI dataset, a publicly available dataset on Kaggle. It includes detailed information on patient demographics and clinical results, including features like age, sex, blood pressure, cholesterol levels, chest pain type, and others related to heart disease risk.

## Models and Methods
The thesis explores various classification models to predict heart disease, including:

Logistic Regression
Random Forest
Decision Tree
K-Nearest Neighbors
Support Vector Classifier
These models were evaluated using metrics such as accuracy, precision, recall, and F1 score, with the goal of determining the best-performing algorithm for heart disease prediction.

## Feature Importance Analysis
Feature importance was calculated using the coefficients from the Logistic Regression model. This analysis identifies which features most significantly impact prediction accuracy, with findings showing that variables such as age, cholesterol, and maximum heart rate are important indicators.

## Results
The models achieved high accuracy rates, with Logistic Regression and Random Forest performing particularly well. Visualizations and feature importance analysis underscored the predictive value of certain clinical metrics, such as resting blood pressure, serum cholesterol, and ST slope, for assessing heart disease risk.

## Prototype Interface
To improve accessibility, a prototype user interface was developed using HTML and CSS, allowing users to input patient data for heart disease risk assessment. While the interface is not yet connected to the model for real-time predictions, it serves as a prototype for potential future integration with Flask.

## Installation
Clone the repository:
bash
git clone https://github.com/tugbacakmak/HeartDiseaseRiskPrediction.git
Install dependencies:
bash
pip install -r requirements.txt

## Usage
Load the dataset and preprocess the data.
Run model training and evaluation scripts to test different algorithms.
View feature importance analysis and results from various models.
Open the prototype interface by running the index.html file in a web browser to input sample patient data.

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.

