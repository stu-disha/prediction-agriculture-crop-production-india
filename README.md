# 🌾 Prediction of Agriculture Crop Production in India

##  Project Overview

This project focuses on analyzing agricultural crop data from India and predicting **crop yield** using Machine Learning.

The project follows the complete **Data Science and Machine Learning workflow**, including:

* Data loading
* Data exploration
* Data cleaning and validation
* Exploratory Data Analysis (EDA)
* Data visualization
* Correlation analysis
* Feature and target selection
* Train-test splitting
* Linear Regression model
* Model prediction
* Model evaluation

The main objective is to understand the relationship between different agricultural factors and crop yield and build a Machine Learning model that can predict crop yield.

---

## Objective

The primary objective of this project is to:

1. Analyze agricultural crop data from different states of India.
2. Understand crop yield patterns.
3. Compare average crop yield across different crops and states.
4. Analyze the relationship between cultivation cost and crop yield.
5. Identify correlations between numerical features.
6. Build a Machine Learning model to predict crop yield.
7. Evaluate the performance of the prediction model.

---

## 🛠️ Technologies & Libraries Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

### Environment

* Jupyter Notebook
* Anaconda

---

## 📂 Dataset

The project uses the dataset:

`crop_yield.csv`

The dataset contains agricultural information such as:

* Crop
* State
* Cost of Cultivation
* Crop Yield
* Other agricultural-related features

The target variable used for prediction is:

**Yield (Quintal/Hectare)**

---

## Exploratory Data Analysis

The following data analysis operations were performed:

### Dataset Information

* Displayed the complete dataset
* Checked the first few records
* Checked dataset shape
* Generated descriptive statistics
* Checked data types and information
* Checked missing values
* Checked duplicate records
* Examined dataset columns

### Categorical Analysis

Unique values and frequency distributions were analyzed for:

* Crop
* State

Crop frequency was also calculated using `value_counts()`.

---

##  Data Visualization

Several visualization techniques were used to understand the dataset.

### 1. Average Yield by Crop

A bar chart was created to compare the average yield of different crops.

### 2. Average Yield by State

A bar chart was created to compare average agricultural yield across different states.

### 3. Distribution of Crop Yield

A histogram was used to understand the distribution and frequency of crop yield values.

### 4. Box Plot

A box plot was created to identify the spread of crop yield and possible outliers.

### 5. Cost of Cultivation vs Yield

A scatter plot was created to analyze the relationship between:

**Cost of Cultivation (C2)**

and

**Crop Yield**

### 6. Correlation Heatmap

A correlation heatmap was created to understand relationships between numerical variables.

---

## Machine Learning Model

### Target Variable

The target variable is:

`Yield (Quintal/ Hectare)`

### Features

All other columns were initially selected as input features.



### Train-Test Split

The dataset was divided into:

* **80% Training Data**
* **20% Testing Data**



---

## Linear Regression

A **Linear Regression** model was used for crop yield prediction.



The trained model predicts crop yield based on the input features.

---

## Model Evaluation

The model performance is evaluated using the following metrics:

### Mean Absolute Error (MAE)

Measures the average absolute difference between actual and predicted values.

### Mean Squared Error (MSE)

Measures the average squared difference between actual and predicted values.

### Root Mean Squared Error (RMSE)

Measures the square root of the Mean Squared Error.

### R² Score

Shows how well the model explains the variation in the target variable.



---

##  Actual vs Predicted Values

A comparison between actual and predicted crop yields was created:


This helps to understand how closely the model predictions match the actual values.

---

## 📁 Project Structure

```text
Prediction-of-Agriculture-Crop-Production-in-India/
│
├── crop_yield.csv
├── Crop_Yield_Prediction.ipynb
├── README.md

```

> File names can be changed according to the actual files in the repository.

---

##  How to Run the Project

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the Project

Open the project folder in **Jupyter Notebook** or **Anaconda Jupyter**.

### 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 4. Open the Notebook

Open:

```text
Crop_Yield_Prediction.ipynb
```

### 5. Run the Cells

Run the notebook cells sequentially to perform:

**Data Analysis → Visualization → Model Training → Prediction → Evaluation**

---

## 📊 Machine Learning Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Exploration
   ↓
Data Cleaning
   ↓
EDA & Visualization
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Linear Regression
   ↓
Prediction
   ↓
Model Evaluation
```

---

##  Future Improvements

The project can be improved further by:

* Applying proper categorical encoding for Crop and State.
* Performing feature engineering.
* Comparing multiple Machine Learning algorithms.
* Using Random Forest Regression.
* Using Decision Tree Regression.
* Hyperparameter tuning.
* Improving model accuracy.
* Creating an interactive prediction application.
* Deploying the model as a web application.

---

## 👩‍💻 Author

**Disha Panchal**

**Domain:** Data Science & Machine Learning

**Project:** Prediction of Agriculture Crop Production in India

---

## ⭐ Conclusion

This project demonstrates the implementation of a complete **Data Science and Machine Learning workflow** for agricultural data.

Through exploratory data analysis and visualization, important patterns and relationships in crop production data were studied. A **Linear Regression model** was then implemented to predict crop yield and evaluated using MAE, MSE, RMSE, and R² Score.

The project provides a foundation for developing more advanced agricultural prediction systems using Machine Learning.
