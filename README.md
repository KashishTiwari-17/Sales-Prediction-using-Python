# Sales Prediction using Python
# Objective of the Task
The objective of this project is to develop a Linear Regression model that predicts product sales based on advertising budgets allocated to TV, Radio, and Newspaper. The model helps understand the effectiveness of each advertising medium and provides an estimate of expected sales based on given inputs.

# Steps Performed
1. Data Loading and Exploration
Loaded the Advertising.csv dataset containing advertising spends and sales data.
Inspected data structure, data types, and verified the absence of missing values.
Displayed summary statistics for numeric insight.
2. Data Visualization
Created scatter plots:
TV vs Sales
Radio vs Sales
Newspaper vs Sales
Plotted a correlation heatmap to evaluate the relationships between features and the target variable.
3. Model Building
Selected features: TV, Radio, Newspaper.
Split data into training and test sets (80/20 split).
Trained a Linear Regression model on the training data.
4. Model Evaluation
Evaluated performance using:
R² Score (Goodness of fit)
Root Mean Squared Error (RMSE)
5. Model Saving
Saved the trained model using joblib as sales_prediction_model.pkl.
6. Interactive Prediction Tool
Developed a CLI-based tool where users input advertising budgets.
The model predicts and displays the expected product sales.

# Tools & Technologies Used
1. Language: Python 
2. Libraries:
pandas, numpy – Data analysis and preprocessing
matplotlib, seaborn – Visualization
scikit-learn – Linear regression model, evaluation metrics, and train-test splitting
joblib – Model serialization

# Outcome / Results
✅ Built a regression model that accurately predicts sales based on ad spend.
📊 Insightful visualizations reveal that TV and Radio have stronger correlations with sales than Newspaper.
📦 Final model saved as: sales_prediction_model.pkl
🧠 Includes an interactive CLI tool for real-time sales predictions based on user inputs.
