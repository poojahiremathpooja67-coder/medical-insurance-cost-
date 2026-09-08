# medical-insurance-cost-
  Medical Insurance Cost Prediction is a machine-learning project developed using Python. The project predicts a person's medical insurance cost based on factors such as age, gender, BMI, number of children, smoking status, and region.
# Medical Insurance Cost Prediction

## 1. Project Overview

Medical Insurance Cost Prediction is a machine learning project that predicts medical insurance costs using customer information such as age, gender, BMI, number of children, smoking status, and region.

The project demonstrates how machine learning can be used to analyze data and predict insurance costs.

## 2. Objectives

* Analyze medical insurance customer data.
* Identify factors that affect insurance costs.
* Clean and prepare the dataset.
* Visualize relationships between different factors and insurance costs.
* Build a machine learning regression model.
* Predict insurance costs for new customers.
* Evaluate the performance of the model.

## 3. Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## 4. Dataset Features

The dataset contains the following columns:

* `customer_id` – Unique customer identification number
* `age` – Age of the customer
* `gender` – Gender of the customer
* `bmi` – Body Mass Index
* `children` – Number of children
* `smoker` – Smoking status
* `region` – Customer's region
* `insurance_cost` – Medical insurance cost

### Target Variable

`insurance_cost` is the target variable that the model predicts.

## 5. Data Preprocessing

The project performs the following preprocessing steps:

1. Loads the dataset using Pandas.
2. Checks for missing values.
3. Fills missing numerical values using the median.
4. Fills missing categorical values using the most frequent value.
5. Standardizes numerical features using `StandardScaler`.
6. Converts categorical features into numerical form using `OneHotEncoder`.
7. Splits the dataset into training and testing data.

## 6. Machine Learning Algorithm

The project uses **Linear Regression**.

Linear Regression is a supervised machine-learning algorithm used to predict a continuous numerical value. In this project, it is used to predict medical insurance costs based on the customer's information.

## 7. Model Evaluation

The model is evaluated using:

### Mean Absolute Error (MAE)

Measures the average difference between actual and predicted insurance costs.

### Root Mean Squared Error (RMSE)

Measures prediction error while giving greater weight to larger errors.

### R² Score

Shows how well the model explains the variation in insurance costs. A value closer to 1 generally indicates better performance.

## 8. Visualizations

The project generates four graphs:

* Age vs Medical Insurance Cost
* BMI vs Medical Insurance Cost
* Average Insurance Cost by Smoking Status
* Actual vs Predicted Insurance Costs

These graphs help understand relationships between customer characteristics and insurance costs.

## 9. Prediction

The trained model can also predict the insurance cost for a new customer using information such as:

* Age
* Gender
* BMI
* Number of children
* Smoking status
* Region

## 10. Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Cleaning
   ↓
Feature Selection
   ↓
Data Preprocessing
   ↓
Train-Test Split
   ↓
Linear Regression
   ↓
Model Training
   ↓
Prediction
   ↓
Model Evaluation
   ↓
Visualization
```

## 11. How to Run the Project

### Step 1: Install Python

Make sure Python is installed on your computer.

### Step 2: Install Required Libraries

Run:

```bash
pip install -r requirements.txt
```

### Step 3: Run the Program

Run:

```bash
python medical_insurance_cost_prediction.py
```

## 12. Output

The program displays:

* First five rows of the dataset
* Dataset size
* Missing-value information
* MAE
* RMSE
* R² Score
* Actual vs predicted insurance costs
* Predicted cost for a new customer
* Important factors affecting insurance cost

It also creates four image files containing the generated graphs.

## 13. Dataset Note

The included dataset is synthetic and is intended for educational and classroom machine-learning practice. It does not contain real customer or medical records.
