# Kaggle Python Data Science Foundation

This repository contains my beginner data science projects focused on Python, Pandas, data visualization, and machine learning foundations.

The goal of this repository is to document my learning journey from Python basics to data analysis and machine learning projects.

---

## Learning Goals

* Learn Python fundamentals for data science
* Practice data analysis with Pandas
* Create visualizations using Matplotlib and Seaborn
* Build beginner-friendly machine learning portfolio projects
* Prepare for real-world machine learning projects

---

## Tools

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* Kaggle Notebook
* GitHub

---

## Project Structure

```text
kaggle-python-data-science-foundation/
├── README.md
├── requirements.txt
├── .gitignore
├── notebooks/
│   ├── 01_python_mini_sales_analyzer.ipynb
│   ├── 02_pandas_sales_analysis.ipynb
│   └── 03_data_visualization_sales_dashboard.ipynb
├── images/
│   └── sales_dashboard_overview.png
└── data/
    └── README.md
```

---

## Projects

### 1. Mini Sales Analyzer with Python

This is my first Python project.

The project analyzes simple product sales data using Python basics without using Pandas.

Main tasks:

* Create product sales data using lists and dictionaries
* Calculate revenue for each product
* Calculate total revenue
* Find the best-performing product
* Calculate average revenue
* Classify product performance
* Generate a simple sales report

Skills practiced:

* Variables
* Lists
* Dictionaries
* Loops
* Functions
* Conditional statements

---

### 2. Pandas Sales Analysis

This project analyzes product sales data using Pandas.

The project improves the first sales analyzer by using a Pandas DataFrame for structured data analysis.

Main tasks:

* Create a Pandas DataFrame
* Explore data using `head()`, `shape`, `info()`, and `describe()`
* Calculate revenue, total cost, and profit
* Calculate profit margin
* Analyze sales by product
* Analyze sales by category
* Analyze sales by region
* Classify product performance
* Export processed data to CSV

Skills practiced:

* Pandas DataFrame
* Data exploration
* Feature engineering
* Grouping data with `groupby()`
* Sorting data with `sort_values()`
* Filtering data
* Exporting CSV files

---

### 3. Sales Dashboard with Data Visualization

This project creates a simple sales dashboard using Pandas, Matplotlib, and Seaborn.

The project focuses on visualizing sales performance and writing business insights from charts.

Main tasks:

* Calculate revenue, total cost, profit, and profit margin
* Create a KPI summary
* Analyze revenue by product
* Analyze profit by category
* Analyze revenue by region
* Visualize monthly revenue trends
* Analyze quantity sold by product
* Create revenue share by category
* Create a price vs quantity scatter plot
* Build a dashboard using multiple charts
* Save dashboard output as an image

Key visualizations:

* Bar chart
* Line chart
* Pie chart
* Scatter plot
* Dashboard overview

Skills practiced:

* Matplotlib
* Seaborn
* Data visualization
* Dashboard-style reporting
* Business insight writing
* Saving charts as image files

---

## Current Progress

* [x] Set up GitHub repository
* [x] Add README.md
* [x] Add requirements.txt
* [x] Add .gitignore
* [x] Create project folders
* [x] Upload first Python mini project
* [x] Upload Pandas sales analysis project
* [x] Upload sales dashboard visualization project
* [ ] Complete Kaggle Python course
* [ ] Complete Kaggle Pandas course
* [ ] Complete Kaggle Data Visualization course
* [ ] Build Titanic EDA project
* [ ] Build first machine learning model

---

## Key Learning Path

This repository follows this learning path:

```text
Python Basics
↓
Pandas Data Analysis
↓
Data Visualization
↓
Exploratory Data Analysis
↓
Machine Learning Basics
↓
Portfolio Projects
```

---

## Next Projects

The next planned projects are:

### 4. Titanic Exploratory Data Analysis

This project uses the real Titanic dataset from Kaggle to perform exploratory data analysis.

Main tasks:

- Load real CSV data from Kaggle
- Explore dataset structure
- Analyze missing values
- Calculate survival rates
- Analyze survival by gender
- Analyze survival by passenger class
- Analyze age and fare distributions
- Create new features such as FamilySize, IsAlone, and AgeGroup
- Create visualizations using Matplotlib and Seaborn
- Export cleaned dataset for future machine learning

Key visualizations:

- Survival count chart
- Survival rate by gender
- Survival rate by passenger class
- Age distribution
- Fare distribution
- Correlation heatmap
- Titanic EDA dashboard

Skills practiced:

- Real dataset analysis
- Missing value analysis
- Feature engineering
- Exploratory data analysis
- Data visualization
- Business/data insight writing

## Current Progress

- [x] Set up GitHub repository
- [x] Add README.md
- [x] Add requirements.txt
- [x] Add .gitignore
- [x] Create project folders
- [x] Upload first Python mini project
- [x] Upload Pandas sales analysis project
- [x] Upload sales dashboard visualization project
- [x] Upload Titanic EDA project
- [ ] Complete Kaggle Python course
- [ ] Complete Kaggle Pandas course
- [ ] Complete Kaggle Data Visualization course
- [ ] Build first machine learning model

### 5. Titanic Survival Prediction

This project builds machine learning models to predict Titanic passenger survival.

Main tasks:

- Load train and test datasets from Kaggle
- Handle missing values
- Create new features such as FamilySize and IsAlone
- Encode categorical variables
- Select features for machine learning
- Split data into training and validation sets
- Train Logistic Regression model
- Train Random Forest model
- Compare model accuracy
- Analyze feature importance
- Generate Kaggle submission file

Models used:

- Logistic Regression
- Random Forest Classifier

Skills practiced:

- Data preprocessing
- Feature engineering
- Classification modeling
- Model evaluation
- Accuracy score
- Confusion matrix
- Classification report
- Feature importance
- Kaggle submission workflow

## Current Progress

- [x] Set up GitHub repository
- [x] Add README.md
- [x] Add requirements.txt
- [x] Add .gitignore
- [x] Create project folders
- [x] Upload first Python mini project
- [x] Upload Pandas sales analysis project
- [x] Upload sales dashboard visualization project
- [x] Upload Titanic EDA project
- [x] Build first machine learning model
- [ ] Learn cross-validation
- [ ] Learn hyperparameter tuning
- [ ] Build improved Titanic ML model

### 6. Titanic Model Improvement

This project improves the Titanic survival prediction model using a more professional machine learning workflow.

Main tasks:

- Create advanced features such as FamilySize, IsAlone, FarePerPerson, Title, and Deck
- Build a preprocessing pipeline
- Process numeric and categorical features separately
- Use SimpleImputer for missing values
- Use OneHotEncoder for categorical variables
- Use cross-validation to evaluate models
- Compare Logistic Regression, Random Forest, and Gradient Boosting
- Tune Random Forest hyperparameters with RandomizedSearchCV
- Evaluate the tuned model on a validation set
- Analyze feature importance
- Generate an improved Kaggle submission file

Models used:

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

Skills practiced:

- Feature engineering
- Pipeline
- ColumnTransformer
- Cross-validation
- Hyperparameter tuning
- Model comparison
- Feature importance
- Kaggle submission workflow

## Current Progress

- [x] Set up GitHub repository
- [x] Add README.md
- [x] Add requirements.txt
- [x] Add .gitignore
- [x] Create project folders
- [x] Upload first Python mini project
- [x] Upload Pandas sales analysis project
- [x] Upload sales dashboard visualization project
- [x] Upload Titanic EDA project
- [x] Build first machine learning model
- [x] Improve Titanic machine learning model
- [ ] Learn XGBoost
- [ ] Learn LightGBM
- [ ] Learn model deployment

### 7. House Price Prediction with Regression

This project builds regression models to predict house prices using the Kaggle House Prices dataset.

Main tasks:

- Load a real regression dataset
- Analyze the SalePrice target variable
- Apply log transformation to SalePrice
- Analyze missing values
- Explore correlation with SalePrice
- Create new features such as TotalSF, TotalBathrooms, HouseAge, RemodAge, HasGarage, and HasBasement
- Process numeric and categorical features using Pipeline and ColumnTransformer
- Train multiple regression models
- Compare models using RMSE, MAE, and R2 Score
- Use cross-validation for more reliable evaluation
- Generate a Kaggle submission file

Models used:

- Linear Regression
- Ridge Regression
- Random Forest Regressor
- Gradient Boosting Regressor

Skills practiced:

- Regression modeling
- Target transformation
- Feature engineering
- Pipeline
- ColumnTransformer
- RMSE evaluation
- Cross-validation
- Kaggle submission workflow

## Current Progress

- [x] Set up GitHub repository
- [x] Add README.md
- [x] Add requirements.txt
- [x] Add .gitignore
- [x] Create project folders
- [x] Upload first Python mini project
- [x] Upload Pandas sales analysis project
- [x] Upload sales dashboard visualization project
- [x] Upload Titanic EDA project
- [x] Build first machine learning model
- [x] Improve Titanic machine learning model
- [x] Build first regression model
- [ ] Learn XGBoost
- [ ] Learn LightGBM
- [ ] Learn model deployment

### 8. House Price Model Improvement

This project improves the house price regression model using advanced feature engineering, outlier handling, gradient boosting models, and hyperparameter tuning.

Main tasks:

- Analyze and remove outliers
- Apply log transformation to SalePrice
- Create advanced features such as TotalSF, TotalBathrooms, HouseAge, RemodAge, HasGarage, HasBasement, and OverallQual_TotalSF
- Process numeric and categorical features using Pipeline and ColumnTransformer
- Compare Ridge, Random Forest, Gradient Boosting, XGBoost, and LightGBM
- Use cross-validation for more reliable evaluation
- Tune Gradient Boosting with RandomizedSearchCV
- Evaluate tuned model using RMSE, MAE, and R2 Score
- Generate an improved Kaggle submission file

Models used:

- Ridge Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor
- LightGBM Regressor

Skills practiced:

- Outlier handling
- Advanced feature engineering
- Regression model improvement
- Cross-validation
- Hyperparameter tuning
- XGBoost
- LightGBM
- Kaggle submission workflow

## Current Progress

- [x] Set up GitHub repository
- [x] Add README.md
- [x] Add requirements.txt
- [x] Add .gitignore
- [x] Create project folders
- [x] Upload first Python mini project
- [x] Upload Pandas sales analysis project
- [x] Upload sales dashboard visualization project
- [x] Upload Titanic EDA project
- [x] Build first machine learning model
- [x] Improve Titanic machine learning model
- [x] Build first regression model
- [x] Improve house price regression model
- [ ] Learn model deployment
- [ ] Build a machine learning web app

## How to Run This Project

Clone this repository:

```bash
git clone https://github.com/tuananhsaigon/kaggle-python-data-science-foundation.git
```

Install required libraries:

```bash
pip install -r requirements.txt
```

Open the notebooks:

```bash
jupyter notebook
```

Or view the notebooks directly on GitHub.

---

## Requirements

The main Python libraries used in this repository are:

```text
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
```

---

## About This Repository

This repository is part of my learning journey in Python, data science, and machine learning.

I use this repository to practice coding, organize my projects, and build a beginner-friendly data science portfolio.

---

## Author

Created by Tuan Anh Pham

GitHub: tuananhphamcoder-ctrl
