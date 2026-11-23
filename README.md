
# E-commerce Price Prediction

A machine learning project that uses Linear Regression to predict the final price of e-commerce products after discount.

## Project Overview

This project explores an e-commerce dataset and uses product price and discount percentage to predict the final price. It demonstrates basic data exploration, visualization, model training, and evaluation using Python.

## Dataset

The dataset contains 3,660 purchase records with these columns:

- User ID
- Product ID
- Category
- Price (Rs.)
- Discount (%)
- Final Price (Rs.)
- Payment Method
- Purchase Date

## Machine Learning

- **Problem type:** Regression
- **Algorithm:** Linear Regression
- **Features:** Price and discount
- **Target:** Final price
- **Train-test split:** 80% training and 20% testing

## Project Workflow

1. Loaded the dataset using pandas.
2. Checked the data and its numeric columns.
3. Created a correlation heatmap.
4. Split the features and target into training and test sets.
5. Trained a Linear Regression model.
6. Evaluated predictions using MAE and R².
7. Compared actual and predicted prices with a graph.

## Results

- **Mean Absolute Error (MAE):** 15.14 Rs.
- **R² Score:** 0.965

The model's predictions fit the test data well. MAE represents the average prediction error in rupees.

## Technologies

- Python
- Jupyter Notebook
- pandas
- scikit-learn
- Matplotlib
- Seaborn

## Important Note

The final price in this dataset is calculated from the original price and discount. This project demonstrates the regression workflow, but the target is mathematically related to the input features.

## How to Run

1. Download or clone this repository.
2. Install the required libraries:

   ```bash
   pip install pandas scikit-learn matplotlib seaborn
