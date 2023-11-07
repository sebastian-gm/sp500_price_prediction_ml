# S&P 500 Price Prediction Using Machine Learning Techniques

## Author: Sebastian Gonzalez

## Introduction
This repository contains a machine learning project aimed at predicting the S&P 500 stock prices using a variety of machine learning models. The dataset used is sourced from the UCI Machine Learning Repository.

## Dataset Source
The dataset can be downloaded from the following link:
[UCI Machine Learning Repository - CNNpred](https://archive.ics.uci.edu/ml/datasets/CNNpred%3A+CNN-based+stock+market+prediction+using+a+diverse+set+of+variables)

## Project Structure
- `Processed_S&P.csv` - The preprocessed dataset used for model training and evaluation.
- `prediction_models.py` - The Python script containing the machine learning models and pipelines.
- `requirements.txt` - A list of dependencies to install for running the project.
- `figures/` - Directory containing visuals and plots generated from the analysis.

## Setup and Installation
To run this project, please follow these steps:
1. Clone this repository to your local machine.
2. Install the required Python packages using `pip install -r requirements.txt`.
3. Execute the script `python prediction_models.py` to train models and predict S&P 500 prices.

## Results
The Lasso Regression model outperformed other models with an R2 score of 0.8789 and an RMSE of 149.1309. Plots illustrating these results can be found in the `figures/` directory.



## Contact
For any queries, feel free to reach out to me at sebastian.sgm@outlook.com.

## Acknowledgements
- UCI Machine Learning Repository for providing the dataset.

