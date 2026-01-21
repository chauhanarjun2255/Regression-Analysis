
Task 4: House Price Prediction using Linear Regression

Project Overview
This project focuses on building a **Linear Regression model** to predict **house prices** based on multiple influencing factors such as:
- House Size
- Location
- Number of Rooms

This project is suitable for:
- Academic submission
- Data Analytics / Data Science internships
- Beginner to intermediate ML learners

Objective
To develop a regression model that accurately predicts house prices using historical data and evaluates the model using standard performance metrics.

Dataset:`house_prices.csv`

Tools & Technologies Used
- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

 Project Workflow

1.Data Loading & Exploration
- Loaded dataset using Pandas
- Checked dataset shape, data types, and missing values
- Generated statistical summaries

2.Data Preprocessing
- Removed missing values
- Encoded categorical variable Location using One-Hot Encoding
- Scaled numerical features using StandardScaler

3.Feature Selection
- Selected relevant independent variables
- Defined Price as the dependent variable

4.Train-Test Split
- Dataset split into:
  - 80% Training Data
  - 20% Testing Data
- Random state fixed for reproducibility

5.Model Training
- Applied Linear Regression
- Trained the model using training data

6.Model Evaluation
- Evaluated model performance using:
  - RMSE (Root Mean Square Error)
  - R² Score
- Visualized Actual vs Predicted Prices

Evaluation Metrics

Higher R² and lower RMSE indicate better model performance.

How to Run the Project
1. Download all project files
2. Ensure `house_prices.csv` is in the same directory as the notebook
3. Open `House_Price_Regression.ipynb` in Jupyter Notebook / VS Code
4. Run all cells sequentially

---

## 📁 Project Files
- `House_Price_Regression.ipynb` → Jupyter Notebook (Code + Output)
- `house_prices.csv` → Dataset
- `README.md` → Project Documentation

