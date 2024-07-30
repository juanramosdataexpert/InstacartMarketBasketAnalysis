<p align="center">
  <img src="https://staffingamericalatina.com/wp-content/uploads/2023/08/instacart-logo-wordmark-4000x1600-e4f3c6f-1.jpg?auto=compress&cs=tinysrgb&w=315&h=187&dpr=1" alt="Instacart Logo" width="35%">
</p>

## Overview
This project involves analyzing a dataset provided by Instacart and building a machine learning model to predict which products will be purchased in future orders. The initial exploration yielded significant insights into the platform, users, products, and general consumption habits. Based on this analysis, a Logistic Regression model was constructed to determine if a product previously ordered by a user would be purchased again.

## Main Challenges
The primary challenge was handling the large volume of available data, which included all previously purchased products with their respective order numbers. To address this, an intermediary dataframe was created to combine different data sources and generate correlations in customer consumption habits.

## Recommendations
Throughout the three notebooks, several recommendations are provided for the company in terms of storage, platform optimization, scheduling, and product suggestions to help grow the business.

## Repository Structure
The repository is organized into two main folders:

### 1. Data
- **Raw**: Contains all the original data provided by Instacart.
- **Processed**: Contains the intermediary dataframe created for training the machine learning model.

### 2. Notebooks
- **EDA.ipynb**: Contains all the exploratory data analysis for each file.
- **features.ipynb**: Includes all correlations and the construction of the training dataframe.
- **model.ipynb**: Involves the training of the model, predictions, and the creation of the `submission.csv` file, which is the final deliverable for the company.

## How to Use
1. **Data Preparation**: Place the raw data files in the `Data/Raw` directory.
2. **Exploratory Data Analysis**: Run `EDA.ipynb` to understand the data and its structure.
3. **Feature Engineering**: Execute `features.ipynb` to build the training dataframe and identify important features.
4. **Model Training and Prediction**: Use `model.ipynb` to train the Logistic Regression model, make predictions, and generate the final `submission.csv` file.

## Conclusion
This analysis provides valuable insights and actionable recommendations for Instacart to enhance its platform and better understand customer purchasing behavior. The Logistic Regression model serves as a predictive tool to anticipate future orders, contributing to more efficient inventory and marketing strategies.
