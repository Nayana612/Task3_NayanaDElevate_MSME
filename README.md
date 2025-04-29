## **Housing Price Prediction using Linear Regression**
**This project aims to predict housing prices using a dataset of various home features. It includes data preprocessing, exploratory data analysis (EDA), 
model training using linear regression, and performance evaluation with regression metrics.**

### 📂 Dataset
The dataset contains housing data with the following features: 
  > click here to download dataset

1. **Numerical Features:**
* area, bedrooms, bathrooms, stories, parking

2. **Categorical Features:**
* mainroad, guestroom, basement, hotwaterheating,airconditioning, prefarea, furnishingstatus

33. **Target Variable:**
* price

### Objective
To build a multiple linear regression model that accurately predicts house prices based on a mix of numerical and categorical features.

### Workflow Summary
* Data Loading
* Loaded data from CSV using pandas.
* Data Preprocessing
* Handled missing values (if any)
* Encoded categorical variables using LabelEncoder/OneHotEncoder
* Scaled features using StandardScaler
* Exploratory Data Analysis (EDA)
* Plotted histograms, correlation heatmaps, pairplots
* Visualized regression relationships using scatter and line plots
* Model Training
* Trained a Linear Regression model
* Evaluated using:

* * Mean Absolute Error (MAE)

* * Mean Squared Error (MSE)

* * R-squared (R² Score)

* Model Interpretation

* Plotted Actual vs Predicted values

* Visualized feature importance through coefficient plots

### 🧠 Key Learnings
Features like area, bathrooms, and airconditioning have a strong impact on housing price.

Categorical variables significantly influence model performance and must be encoded properly.

The model performs best when inputs are normalized and categorical variables are well-engineered.
