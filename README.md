# House Price Prediction

A machine learning project that uses **Linear Regression** to predict house prices based on property and area-related features. The project includes exploratory data analysis, model training, prediction, visualization, and regression evaluation.

## Project Overview

House prices can be influenced by several factors, including household income, property age, number of rooms, number of bedrooms, and population in the surrounding area.

In this project, a Linear Regression model is trained using historical housing data to learn the relationship between these features and house prices.

The model's predictions are evaluated using several regression metrics, including **MAE, MSE, and RMSE**.

## Objectives

* Explore and understand the housing dataset.
* Perform basic exploratory data analysis.
* Select relevant features for house price prediction.
* Split the dataset into training and testing sets.
* Train a Linear Regression model.
* Generate house price predictions.
* Visualize actual versus predicted prices.
* Analyze prediction errors.
* Evaluate model performance using regression metrics.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Dataset

The project uses a `Housing.csv` dataset containing information about different housing areas.

The features used for prediction are:

* `Avg. Area Income` — average income in the area
* `Avg. Area House Age` — average age of houses in the area
* `Avg. Area Number of Rooms` — average number of rooms
* `Avg. Area Number of Bedrooms` — average number of bedrooms
* `Area Population` — population of the area

### Target Variable

* `Price` — house price to be predicted by the model

## Exploratory Data Analysis

The dataset is inspected using Pandas to understand:

* Dataset structure and data types
* Descriptive statistics
* Available columns
* Feature relationships
* Distribution of prediction errors

The project also includes visualizations using Matplotlib and Seaborn.

## Data Preparation

The following steps are performed:

1. Load the `Housing.csv` dataset.
2. Inspect the first records using `head()`.
3. Check the dataset structure using `info()`.
4. Generate descriptive statistics using `describe()`.
5. Select the relevant input features.
6. Separate the features (`X`) from the target (`y`).
7. Split the dataset into training and testing sets.

The data is divided into:

* **60% training data**
* **40% testing data**

## Machine Learning Model

### Linear Regression

A Linear Regression model is used to learn the relationship between the selected housing features and house prices.

The model estimates how changes in factors such as income, house age, number of rooms, bedrooms, and population are associated with changes in house prices.

The model coefficients are also examined to understand the contribution of each feature to the prediction.

## Model Evaluation

The model is evaluated using three common regression metrics.

### Mean Absolute Error (MAE)

MAE measures the average absolute difference between the actual and predicted house prices.

A lower MAE indicates smaller prediction errors.

### Mean Squared Error (MSE)

MSE calculates the average squared difference between actual and predicted prices. Larger errors receive more weight because the errors are squared.

A lower MSE indicates better performance.

### Root Mean Squared Error (RMSE)

RMSE is the square root of MSE and represents prediction error in the same units as the target variable.

A lower RMSE indicates that the model's predictions are closer to the actual house prices.

## Visualizations

The project includes:

* Actual vs. predicted house price scatter plot
* Distribution of prediction errors
* Exploratory analysis of the housing dataset

The actual-versus-predicted plot helps visually assess how closely the model's predictions match the real house prices.

The error distribution helps identify how prediction errors are distributed around the model's predictions.

## Project Structure

```text
House-Price-Prediction/
│
├── Housing.csv
├── house_price_prediction.ipynb
└── README.md
```

> File names may vary depending on the names used in the repository.

## Results

The Linear Regression model is evaluated using:

* MAE
* MSE
* RMSE

The actual evaluation values are generated when the notebook is executed.

Rather than adding fixed values to this README, the results should be updated with the values produced by the final version of the notebook.

## Key Takeaways

This project demonstrates a complete introductory regression workflow:

* Data loading
* Data inspection
* Exploratory data analysis
* Feature selection
* Train/test splitting
* Linear Regression
* Prediction
* Error analysis
* Model evaluation
* Data visualization

## Future Improvements

Possible improvements include:

* Testing additional regression models such as Random Forest Regression
* Performing feature scaling where appropriate
* Applying cross-validation
* Performing feature engineering
* Comparing multiple models
* Tuning model parameters
* Investigating correlations between features
* Using additional housing-related features to improve prediction accuracy

## Author

**Rahel Belay**

Software Engineering Graduate | Full-Stack & Flutter Developer | Data Analytics Enthusiast
