# California Housing Price Prediction Using Linear Regression

## Project Overview

This project aims to predict California housing prices using the Linear Regression algorithm. The project demonstrates the complete Machine Learning workflow, including data loading, exploratory data analysis (EDA), model training, evaluation, and model saving using Python and Scikit-Learn.

---

## Project Objective

The objective of this project is to build a Machine Learning model that can predict house prices based on housing-related features from the California Housing Dataset. This project helps understand the end-to-end machine learning lifecycle and serves as a beginner-friendly regression project.

---

## Dataset Information

The California Housing Dataset is provided by Scikit-Learn and contains housing information collected from California census data.

### Features

- MedInc – Median income in the area
- HouseAge – Median house age
- AveRooms – Average number of rooms
- AveBedrms – Average number of bedrooms
- Population – Area population
- AveOccup – Average occupancy
- Latitude – Geographic latitude
- Longitude – Geographic longitude

### Target Variable

- HousePrice – Median house value

---

## Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand the dataset and identify patterns before model training.

### EDA Steps Performed

- Examined dataset shape and structure
- Checked data types of all features
- Checked for missing values
- Checked for duplicate records
- Generated statistical summaries
- Created histograms for feature distributions
- Analyzed target variable distribution
- Built correlation heatmaps
- Visualized feature relationships using scatter plots
- Identified outliers using boxplots

### Key Findings

- The dataset contains 20,640 records and 9 columns.
- No missing values were found in the dataset.
- No duplicate records were detected.
- Median Income (MedInc) has the strongest positive correlation with house prices.
- Geographic features such as Latitude and Longitude also influence housing prices.
- Several features contain outliers.
- House prices show a moderately right-skewed distribution.

---

## Model Development

### Algorithm Used

**Linear Regression**

Linear Regression was chosen as the baseline model because it is simple, interpretable, and effective for predicting continuous numerical values.

### Data Splitting

- Training Data: 80%
- Testing Data: 20%

### Training Process

The dataset was divided into training and testing sets using train_test_split(). The Linear Regression model was trained using the training dataset and evaluated on the testing dataset.

---

## Model Evaluation

The model was evaluated using the following metrics:

### Mean Absolute Error (MAE)

Measures the average absolute difference between actual and predicted values.

### Root Mean Squared Error (RMSE)

Measures the square root of the average squared prediction errors.

### R² Score

Measures how well the model explains the variance in the target variable.

### Results

| Metric | Value |
|----------|----------|
| MAE | Add Your Result |
| RMSE | Add Your Result |
| R² Score | Add Your Result |

---

## Visualizations

The following visualizations were generated during Exploratory Data Analysis and Model Evaluation:

- Correlation Heatmap
- Feature Distribution Histograms
- House Price Distribution Plot
- Median Income vs House Price Scatter Plot
- Actual vs Predicted House Price Plot

These visualizations help understand the data and evaluate model performance.

---

## Conclusion

A Linear Regression model was successfully developed to predict California housing prices. The project demonstrates the complete machine learning pipeline from data exploration to model evaluation.

The model provides reasonable predictions and serves as a strong baseline solution for house price prediction tasks.

---

## Future Improvements

The following improvements can be implemented to achieve better performance:

- Feature Engineering
- Feature Scaling and Transformation
- Hyperparameter Tuning
- Polynomial Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor
- Cross-Validation Techniques

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---


