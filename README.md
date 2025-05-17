# Basic-Exploratory_Data_Analysis_On_Titanic_Dataset
A complete data preprocessing and EDA workflow on the Titanic dataset to prepare it for machine learning model training. Includes handling missing values, outliers, encoding, scaling, and dataset splitting.

🚢 Titanic Dataset – Data Preprocessing & EDA
This repository contains a complete data preprocessing and exploratory data analysis (EDA) workflow performed on the Titanic dataset. The goal is to clean, transform, and prepare the dataset for training a machine learning model by applying industry-standard preprocessing techniques.

📌 Objective
To study and apply data preprocessing techniques on the Titanic dataset, enabling it for effective machine learning model training.

🛠️ Tasks Performed
✅ 1. Basic Exploratory Data Analysis
Displayed initial records using head() and tail().

Summarized data using describe(), info(), and shape.

✅ 2. Handling Missing Values
Identified missing values using isnull().sum().

Imputed missing values using:

Mean/Median for numerical features.

Mode for categorical features.

✅ 3. Handling Duplicates
Checked for duplicate rows using duplicated().sum().

Removed duplicates to ensure data quality.

✅ 4. Outlier Detection and Handling
Identified outliers using IQR method and visualizations (boxplots).

Removed or capped outliers for specific numerical attributes.

✅ 5. Data Encoding
Applied encoding techniques such as:

Label Encoding for binary categorical variables.

One-Hot Encoding for multi-class categorical variables (e.g., Embarked).

✅ 6. Univariate, Bivariate, and Multivariate Analysis
Univariate analysis: Distribution plots and countplots.

Bivariate analysis: Correlation matrix and scatterplots.

Multivariate analysis: Pairplots and heatmaps.

✅ 7. Feature Scaling
Applied StandardScaler / MinMaxScaler to continuous variables to normalize data.

✅ 8. Data Splitting
Split the dataset into training and testing sets in an 80:20 ratio using train_test_split.

📁 Dataset
The Titanic dataset used in this project is available on Kaggle – Titanic: Machine Learning from Disaster

💻 Technologies Used
Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

📊 Outputs
Cleaned and preprocessed Titanic dataset ready for machine learning.

Visual insights from EDA.

No missing data, no duplicates, scaled numerical features, and encoded categorical variables.
