# Bike Sharing Demand Prediction
This is a project that predicts the demand for bike sharing based on various attributes such as weather conditions, time of day, and user demographics. The dataset used in this project is publicly available.

## Project Goal
The main goal of this project is to build a machine learning model that can accurately predict the demand for bike sharing based on various input features.

## Dataset
The dataset used in this project contains hourly bike rental data spanning two years. It includes information such as date, time, temperature, humidity, wind speed, and the number of bikes rented in that hour. There are a total of 18760 obervations and 14 features in the dataset.

## Exploratory Data Analysis
The dataset was first analyzed to gain insights into the distribution of data, correlations between attributes, and missing values. The analysis showed that the data was mostly normally distributed and there were some correlations between attributes. Additionally, there were no missing values in the dataset.

## Data Pre-processing
The data was pre-processed by removing unnecessary attributes. I've enhanced the DataFrame's usability by replacing column names with more descriptive and readable labels. Additionally, I converted the 'Date' column to a datetime data type, enabling access to various time-related properties and columns. To provide more insights, I introduced new columns, including 'Year,' 'Month,' 'Day,' and a pivotal 'Week' column categorized as 'weekend' or 'weekday.' To optimize data representation, I transformed the 'Hour,' 'Month,' 'Week,' 'Functioning_day,' 'Seasons,' and 'Holiday' columns into categorical data types, simplifying data analysis and visualization.

## Model Building
Several machine learning algorithms were used to build the prediction model, including linear regression, ridge regression, lasso regression,random forest. Each model was evaluated using various performance metrics such as mean squared error (MSE) and root mean squared error (RMSE).

## Conclusion
The results of the model evaluation showed that the random forest algorithm performed the best with the lowest MSE and RMSE. The final model was trained on the entire dataset and can be used to predict the demand for bike sharing given various input features.
