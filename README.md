# Heart Disease Risk Prediction Model
 This repository contains the full code, data, and interface for my undergraduate thesis project, aimed at predicting heart disease risk using machine-learning models. The project focuses on developing a machine-learning model based on patient data to predict heart disease risk. This work utilizes various classification algorithms and a feature importance analysis to highlight key attributes impacting heart disease prediction. Additionally, a prototype user interface is included to make predictions more accessible.T


## Project Overview
The goal of this project is to create a machine learning-based model that predicts the risk of heart disease. Using key health indicators such as age, cholesterol levels, and blood pressure, this model helps in assessing the likelihood of heart disease. An HTML/CSS-based user interface is included as a prototype for potential user input and prediction display.

### Dataset
File: heart.csv
Description: The dataset, heart.csv, is a clinical dataset containing patient health data used to train and evaluate the machine learning models. It includes features like:
Age: Age of the patient
Sex: Male/Female
ChestPainType: Type of chest pain experienced (e.g., Typical Angina, Asymptomatic)
RestingBP: Resting blood pressure
Cholesterol: Serum cholesterol levels
MaxHR: Maximum heart rate achieved
ST_Slope: Slope of the peak exercise ST segment
HeartDisease: Output class (1 for heart disease presence, 0 for no disease)
This data is used to build and validate different machine-learning models to ensure reliable prediction accuracy.

## Feature Importance
Feature importance is calculated, particularly from Logistic Regression coefficients, to highlight the most impactful attributes in predicting heart disease risk. This analysis helps in understanding which patient characteristics are most critical to the prediction outcomes.

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
These models were evaluated using metrics such as accuracy, precision, recall, and F1 score, to determine the best-performing algorithm for heart disease prediction.

## Feature Importance Analysis
Feature importance was calculated using the coefficients from the Logistic Regression model. This analysis identifies which features most significantly impact prediction accuracy, with findings showing that variables such as age, cholesterol, and maximum heart rate are important indicators.

## Results
The models achieved high accuracy rates, with Logistic Regression and Random Forest performing particularly well. Visualizations and feature importance analysis underscored the predictive value of certain clinical metrics, such as resting blood pressure, serum cholesterol, and ST slope, for assessing heart disease risk.

## Prototype Interface
To improve accessibility, a prototype user interface was developed using HTML and CSS, allowing users to input patient data for heart disease risk assessment. While the interface is not yet connected to the model for real-time predictions, it serves as a prototype for potential future integration with Flask.

## Installation
1. Clone the repository:
bash
git clone https://github.com/yourusername/HeartDiseaseRiskPrediction.git
2. Navigate to the project directory:
bash
cd HeartDiseaseRiskPrediction
3. Install required dependencies:
bash
pip install -r requirements.txt

## Usage
1. Data Preparation: Load and preprocess heart.csv.
2. Model Training: Run the model training code to test different machine learning algorithms and analyze the importance of features.
3. User Interface: Open userinterface.html to view the interface and manually enter sample patient data.

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.

