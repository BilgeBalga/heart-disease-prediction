# Heart Disease Prediction Project

This project aims to predict the risk of heart disease using the **Logistic Regression** algorithm. The dataset contains various health and lifestyle factors, and preprocessing steps have been applied to prepare the data for accurate predictions.

## Table of Contents

- [About the Project](#about-the-project)
- [Dataset](#dataset)
- [Libraries Used](#libraries-used)
- [Model Training](#model-training)
- [Results](#results)
- [Installation](#installation)
- [License](#license)

## About the Project

This project analyzes health data to predict the risk of individuals developing heart disease. Heart disease is one of the most common health issues worldwide, and early diagnosis and identification of risk factors can be life-saving. The main objective of the project is to develop a model that accurately predicts the risk levels of individuals based on their health conditions and lifestyle factors.

The dataset includes various health and lifestyle factors, such as age, gender, daily cigarette consumption, total cholesterol, systolic blood pressure, and blood glucose levels. These factors are critical in assessing susceptibility to heart disease. The model uses this data to learn from past cases and applies statistical and machine learning techniques to determine the risk levels of future individuals.

In the initial phase of the project, the dataset is examined, and necessary preprocessing steps are performed. This process includes checking for missing values, detecting outliers, and normalizing the data. Subsequently, the data is split into training and test sets to evaluate the model's performance.

Ultimately, this project aims to develop a model capable of predicting the risk of heart disease. Such a model can provide health professionals and individuals with information to take preventive measures against heart disease, thereby enhancing quality of life.

## Dataset

The dataset includes the following features:
- `age`: Age of the individual
- `Sex_male`: Gender (0: Female, 1: Male)
- `cigsPerDay`: Daily cigarette consumption
- `totChol`: Total cholesterol level
- `sysBP`: Systolic blood pressure
- `glucose`: Blood glucose level
- `TenYearCHD`: Risk of coronary heart disease within 10 years (0: No, 1: Yes)

## Libraries Used

- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical computations.
- `matplotlib`: For data visualization.
- `seaborn`: For advanced data visualizations.
- `sklearn`: For machine learning algorithms and metrics.

## Model Training

1. **Data Loading**: The dataset is loaded using `pandas`.
2. **Data Preprocessing**: Missing values are checked and removed if necessary.
3. **Normalization**: The features are standardized.
4. **Train/Test Split**: The dataset is split into 70% training data and 30% test data.
5. **Model Training**: A Logistic Regression model is trained on the training set.
6. **Model Evaluation**: The accuracy of the model is evaluated using the test set.

## Results

The model's accuracy was evaluated using the test set, allowing us to assess its performance in predicting heart disease risk.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/BilgeBalga/heart-disease-prediction.git
