# laptop_price_prediction

## Project Overview
This project analyzes a laptop dataset and builds machine learning models to predict laptop prices based on technical specifications such as CPU, RAM, storage, and GPU.

The workflow covers the full data science pipeline: data cleaning, exploratory data analysis (EDA), feature engineering, and model building using regression techniques.

## Objectives

### Main Objectives
- Load and clean the dataset using pandas
- Perform exploratory data analysis (EDA)
- Identify key features influencing price
- Build regression models to predict price
- Improve model performance using Ridge Regression

### Detailed Workflow

#### Data Preparation
- Handle missing values
- Correct data types
- Standardize and normalize features
- Encode categorical variables

#### Exploratory Data Analysis
- Feature visualization
- Statistical summaries
- Correlation analysis (Pearson)
- Grouping and pivot tables

#### Modeling
- Simple Linear Regression
- Multiple Linear Regression
- Polynomial Regression
- Pipeline implementation (scaling + polynomial + regression)

#### Evaluation & Optimization
- Model evaluation using MSE and R²
- Train/test split and cross-validation
- Overfitting analysis
- Ridge Regression tuning
- Hyperparameter optimization using Grid Search

## Tools
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn

## Project Structure
laptop_price_prediction.ipynb  → Full analysis with explanations

## How to run
- Clone the repository
- Install dependencies:
```bash
pip install -r requirements.txt
```
- Open the notebook and run all cells
