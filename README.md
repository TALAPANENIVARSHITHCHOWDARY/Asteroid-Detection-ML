# Asteroid Detection Using Machine Learning

This project leverages Machine Learning techniques to detect and classify asteroids based on their trajectory, size, and velocity. The goal is to identify Potentially Hazardous Asteroids (PHAs) that could pose a threat to Earth, thereby aiding in Near-Earth Object (NEO) detection and planetary defense.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Machine Learning Models](#machine-learning-models)
- [Model Evaluation](#model-evaluation)
- [Usage](#usage)

## Introduction

Asteroids that come close to Earth, known as Near-Earth Objects (NEOs), can pose significant threats depending on their size and trajectory. This project aims to classify such asteroids as "Threat" or "No Threat" using supervised Machine Learning models. By analyzing various features of asteroids, we can predict their potential hazard level and take necessary precautions.

## Dataset

The dataset used in this project is obtained from Kaggle and contains information about various asteroids, including their orbital parameters and physical characteristics.

- **Source:** [Asteroid Dataset on Kaggle](https://bit.ly/3Sl3E6p)

## Data Preprocessing

Data preprocessing steps include:

- Handling missing values
- Encoding categorical variables
- Normalizing numerical features
- Splitting the data into training and testing sets

## Exploratory Data Analysis (EDA)

EDA involves visualizing and understanding the distribution of data features, relationships between variables, and identifying any anomalies or patterns that could influence the model's performance.

## Machine Learning Models

Several supervised learning algorithms were employed:

- **Logistic Regression:** A linear model for binary classification.
- **Decision Tree Classifier:** A non-linear model that splits data based on feature values.
- **Random Forest Classifier:** An ensemble of decision trees to improve accuracy and control over-fitting.
- **K-Nearest Neighbors (KNN):** A non-parametric method that classifies based on the majority class among the k-nearest neighbors.

Hyperparameter tuning was performed using Grid Search Cross-Validation to optimize model performance.

## Model Evaluation

Models were evaluated based on metrics such as accuracy, precision, recall, and F1-score. The Random Forest Classifier emerged as the best-performing model with the highest accuracy and balanced precision-recall scores.

## Usage

To run the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/TALAPANENIVARSHITHCHOWDARY/Asteroid-Detection-ML.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Asteroid-Detection-ML
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Asteroid_Threat_Detection.ipynb
   ```

