# Salary Prediction

## Introduction

This repository contains code for predicting salary based on years of experience using the Linear Regression algorithm. The dataset used is the "Salary_Data.csv" available on Kaggle.

## Prerequisites

Make sure you have the required libraries installed. You can install them using the following:

```bash
pip install pandas matplotlib scikit-learn
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/FarzizYassine/salary-prediction.git
cd salary-prediction
```

2. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/devchauhan1/salary-datacsv) and place it in the project directory with the name "Salary_Data.csv".

3. Run the code:

```bash
python salary_prediction.py
```

## Code Explanation

- The script reads the dataset using Pandas and displays the first few rows and summary statistics.
- It uses the `LinearRegression` model from Scikit-Learn to predict salary based on years of experience.
- The dataset is split into training and testing sets using the `train_test_split` function.
- A scatter plot of the data and the regression line is plotted using Matplotlib.
- Predictions are made on the test set, and new data points are predicted using the trained model.

## Results

The script displays a scatter plot of the data with the regression line. Additionally, it predicts salaries for the test set and provides predictions for new data points.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
