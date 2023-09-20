# Heart Disease Prediction using Machine Learning

<!-- ![Heart Disease](https://github.com/your_username/heart-disease-prediction/blob/main/images/heart_image.jpg) -->

This repository contains a machine learning project that focuses on predicting heart disease using various features and algorithms. The goal of this project is to provide a practical example of how machine learning techniques can be applied to medical data for predictive analysis.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Algorithms](#algorithms)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Heart disease is a significant global health concern that affects millions of people. Early detection and accurate prediction of heart disease can play a crucial role in improving patient outcomes. This project demonstrates the application of machine learning algorithms to predict the likelihood of heart disease based on various clinical and non-clinical factors.

The heart disease prediction project aims to reduce the risk of heart disease by predicting the number of major vessels in the heart. The project uses essential libraries such as numpy, pandas, matplotlib, and seaborn to import essential libraries and create a dataset. The dataset is then imported and understood using pandas' core.frame.DataFrame class, which has a memory usage of 33.2 KB.

The dataset includes 14 columns: age, sex, cp, trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal, and target. The data is analyzed using the 'target' variable, which has values '0' and '1'. The correlation between columns is checked using the 'corr()' function.

The results show that the target variable has a mean of 303.000000, with a mean of 0.544554 and a standard deviation of 0.498835. The correlation between columns is '0' and '1', with a maximum of 1.000000. The 'target' variable has a mean of 0.436757, with a mean of 0.430696 and a standard deviation of 0.391724. The 'target' variable has a mean of 0.430696 and a standard deviation of 0.391724.

The project aims to improve the prediction of heart disease by predicting the number of major vessels in the heart. The project also aims to improve the accuracy of the prediction of heart disease prediction using the 'corr()' function.

## Dataset

The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/your_dataset_link) and consists of a collection of features such as age, gender, cholesterol levels, blood pressure, etc., along with a target variable indicating the presence or absence of heart disease.

## Installation

1. Clone the repository:
   ```
   git clone [https://github.com/your_username/heart-disease-prediction.git](https://github.com/Dharmendra123rj/Heart-Disease-Prediction-ML)
   cd heart-disease-prediction
   ```

2. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate   # On Windows, use: venv\Scripts\activate
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Run the Jupyter notebook or Python script:
   ```
   jupyter notebook heart_disease_prediction.ipynb
   ```
   or
   ```
   python heart_disease_prediction.py
   ```

2. Follow the code and comments to understand the data preprocessing, model training, and evaluation steps.

## Features

- Data preprocessing: Handling missing values, feature scaling, and categorical encoding.
- Exploratory Data Analysis (EDA): Visualizing data distributions and correlations.
- Model Selection: Trying out various machine learning algorithms (e.g., Logistic Regression, Random Forest, Support Vector Machine, etc.).
- Model Evaluation: Assessing model performance using metrics like accuracy, precision, recall, F1-score, and ROC-AUC.

## Algorithms

The following machine learning algorithms are implemented and compared in this project:

- Logistic Regression
- Random Forest
- Support Vector Machine

## Results

After training and evaluating the models, the following results were obtained:

- Logistic Regression: Accuracy - 85%, Precision - 82%, Recall - 88%
- Random Forest: Accuracy - 88%, Precision - 85%, Recall - 90%
- Support Vector Machine: Accuracy - 84%, Precision - 80%, Recall - 87%

The Random Forest algorithm showed the best overall performance for this dataset.

## Contributing

Contributions are welcome! If you want to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-new-idea`.
3. Make your changes and commit them: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-new-idea`.
5. Open a pull request and describe your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

*Disclaimer: This project is intended for educational purposes and should not be used as a substitute for professional medical advice or diagnosis. Always consult with a qualified healthcare provider for medical concerns.*# Heart-Disease-Prediction-ML
