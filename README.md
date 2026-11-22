# Advertising Sales Prediction using Simple Linear Regression

## Project Overview
This project uses **Simple Linear Regression** to predict product sales based on TV advertising expenditure.

The project uses Python and Machine Learning libraries to analyze the relationship between TV advertising budgets and sales, train a regression model, evaluate its performance, and predict sales for a given advertising budget.

## Objective
- Analyze the relationship between TV advertising and sales.
- Build a Simple Linear Regression model.
- Predict sales based on TV advertising expenditure.
- Evaluate model performance using regression metrics.

## Dataset
**Dataset Name:** Advertising.csv

The dataset contains 200 records and 5 columns.

| Column | Description |
|---|---|
| Unnamed: 0 | Index column |
| TV | TV advertising budget |
| Radio | Radio advertising budget |
| Newspaper | Newspaper advertising budget |
| Sales | Product sales |

**Independent Variable:** TV

**Dependent Variable:** Sales

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Project Workflow
1. Import required Python libraries.
2. Upload and load the Advertising dataset.
3. Perform Exploratory Data Analysis (EDA).
4. Check missing values and duplicate records.
5. Select TV as the independent variable.
6. Select Sales as the dependent variable.
7. Visualize the relationship using a scatter plot.
8. Calculate correlation.
9. Split data into training and testing sets (80:20).
10. Train the Linear Regression model.
11. Predict sales using test data.
12. Evaluate model performance.
13. Generate predictions for new TV advertising budgets.

## Linear Regression Equation

The Simple Linear Regression equation is:

`Y = b0 + b1X`

Where:
- Y = Predicted Sales
- X = TV Advertising Budget
- b0 = Intercept
- b1 = Regression Coefficient

**Trained Model:**

`Sales = 7.11964 + (0.04653 × TV)`

## Model Evaluation

The model achieved the following results:

| Evaluation Metric | Result |
|---|---:|
| MAE | 2.444 |
| MSE | 10.205 |
| RMSE | 3.194 |
| R² Score | 0.677 |

**Correlation between TV and Sales:** 0.7822

## Sample Prediction

Example TV advertising budget: `150`

Predicted Sales: `14.10`

The model predicts sales based on the entered TV advertising budget.

## Visualizations
The project includes:
- TV Advertising vs Sales Scatter Plot
- Regression Line Visualization
- Actual vs Predicted Sales Plot

## Conclusion

This project demonstrates how Simple Linear Regression can be used to predict sales based on TV advertising expenditure.

The model achieved an R² score of 0.677, showing that TV advertising explains approximately 67.7% of the variation in sales on the test dataset.

This project helped develop practical knowledge of data analysis, data visualization, machine learning, model training, and prediction using Python.

## Future Improvements
- Implement Multiple Linear Regression using TV, Radio, and Newspaper.
- Compare different machine learning algorithms.
- Improve model accuracy.
- Perform cross-validation.
- Deploy the model using Flask or Streamlit.

---

**Project Type:** Machine Learning – Regression

**Algorithm:** Simple Linear Regression

**Language:** Python
