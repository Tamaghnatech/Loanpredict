# Predicting Insurance Claims Severity

![Predicting Insurance Claims Severity Logo](logo.jpg)


An end-to-end machine learning project aimed at predicting the severity of insurance claims based on various features provided by the Allstate dataset. The goal is to minimize prediction errors to improve business decisions.

## Motivation

With the rise of data-driven decisions in the insurance sector, understanding the potential severity of insurance claims is crucial for optimizing resources and enhancing customer experiences. This project seeks to leverage the power of machine learning, specifically using XGBoost and Neural Networks, to make accurate predictions and assist in informed decision-making.

## Build Status

The project is currently in a stable state. However, further improvements and optimizations are ongoing.

## Code Style

The code adheres to the standard Python PEP 8 style guide.

## Screenshots

![Visualization of one result](ss.png)

## Tech/Framework used

- Programming Language: Python
- Libraries & Frameworks: pandas, sklearn, xgboost, keras, matplotlib, seaborn

## Features

- Comprehensive preprocessing including one-hot encoding and feature scaling.
- Model training using XGBoost for regression.
- Neural Network model with Keras for regression, complete with callbacks like Early Stopping.
- Comprehensive data visualization for understanding feature importance and distribution.
- Evaluation metrics and residual analysis.

## Code Examples
I = (loan.loc[loan["profession"]
         .isin(["Drafter", "Secretary", "Computer_hardware_engineer", "Analyst", "Official"])]
         .loc[:, ["income", "profession", "risk_flag"]])

data = I
title = "Top 5 Profession & Risk Flag"
x = "profession"
y = "income"
hue = "risk_flag"
xlabel = "Top 5 Profession Income"
ylabel = "Income"

mtvboxplot(data=data, title=title, x=x, y=y,
           hue=hue, xlabel=xlabel, ylabel=ylabel);

## Installation
Install Python 3.7 or above.
Use pip to install required libraries:
Copy code
pip install pandas sklearn xgboost keras matplotlib seaborn
Tests
Various tests like feature importance, model evaluation metrics, and residual analysis have been implemented. Each test ensures the model's robustness and accuracy in predicting insurance claim severity.

## How to Use?
Clone the repository.
Install the necessary libraries.
Load your data, following the structure as provided in train.csv and test.csv.
Run the preprocessing and model scripts.
Evaluate and visualize the results using the provided visualization scripts.

## Contribute
Contributions are always welcome! Please read the contribution guidelines first.

## Credits
Thanks to Kaggle for providing the Loan dataset which made this project possible. Special thanks to all open-source communities and contributors who developed the libraries and tools used in this project.

## License
This project is licensed under the MIT License. See LICENSE.md for more details.


## Project Link: https://github.com/Tamaghnatech/Loanpredict

