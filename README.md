# Air Quality in Durban - Part 2: Linear Regression with Time Series Data from MongoDB

## Project Overview
This project focuses on analyzing air quality data from Durban using **time series analysis** and applying a **Linear Regression model** to predict **PM2.5** values. The dataset is stored and queried from **MongoDB**, and the analysis is performed using **Python, Pandas, Scikit-learn, and visualization libraries**.

- **Dataset Source:** [Open Africa - Sensors.Africa Air Quality Archive (Durban)](https://open.africa/dataset/sensorsafrica-airquality-archive-durban)  
- **Tools Used:** Python, Pandas, MongoDB, Scikit-learn, Matplotlib, Seaborn, Plotly  
- **Author:** Dumisani Maxwell Mukuchura  
- **Contact:** dumisanimukuchura@gmail.com | [LinkedIn](https://www.linkedin.com/in/dumisani-maxwell-mukuchura-4859b7170/)  

## Project Structure
Air-Quality-in-Durban-Part-2-Linear-Regression-with-TimeSeries-Data-from-MongoDB/ 
│── data/ # Contains the dataset 
│── notebook/ # Jupyter Notebook with the analysis 
│── README.md # Project documentation

# Air Quality in Durban - Part 2: Linear Regression with Time Series Data from MongoDB

This project continues the exploration of the air quality dataset for Durban, South Africa, focusing on predicting PM2.5 values using a Linear Regression model. The dataset contains time series data collected from sensors, including particulate matter (P2), humidity, and temperature.

## Dataset Source
The dataset is sourced from [Sensors.Africa Air Quality Archive - Durban](https://open.africa/dataset/sensorsafrica-airquality-archive-durban).

## Project Overview
The project focuses on:
- Preparing and wrangling time series data from MongoDB.
- Performing Exploratory Data Analysis (EDA) to understand the dataset.
- Building and evaluating a Linear Regression model to predict PM2.5 values.
- Visualizing the results to communicate findings effectively.

## Tools and Technologies
- **MongoDB**: A NoSQL database used to store and query the dataset.
- **MongoDB Compass**: A GUI for MongoDB to visualize and interact with the data.
- **MongoDB Shell (`mongosh`)**: A command-line interface for MongoDB.
- **Python**: Used for data analysis, modeling, and visualization.
- **Pandas**: A Python library for data manipulation and analysis.
- **Scikit-learn**: A Python library for machine learning, used to build the Linear Regression model.
- **Matplotlib and Plotly**: Libraries for data visualization.

## Project Structure
The project is divided into the following steps:

### 1. Prepare Data
- **Connect to MongoDB**: Establish a connection to the locally hosted MongoDB instance.
- **Wrangle Data**: Extract and transform the data into a suitable format for analysis.
- **Resample Time Series Data**: Aggregate the data to an hourly frequency and handle missing values.

### 2. Exploratory Data Analysis (EDA)
- **Visualize Data Distribution**: Use box plots to understand the spread of PM2.5 values.
- **Check for Missing Values**: Ensure the dataset is complete and handle any anomalies.
- **Correlation Analysis**: Explore the relationship between PM2.5 values and their lagged values.

### 3. Build and Evaluate the Model
- **Split Data**: Divide the dataset into training and test sets, ensuring no data leakage.
- **Baseline Model**: Establish a baseline model using the mean PM2.5 value.
- **Linear Regression Model**: Train and evaluate a Linear Regression model to predict PM2.5 values.
- **Model Evaluation**: Compare the model's performance using Mean Absolute Error (MAE).

### 4. Communicate Results
- **Model Formula**: Display the Linear Regression equation.
- **Visualize Predictions**: Plot the actual vs. predicted PM2.5 values to assess model performance.

## Next Steps
- Improve feature engineering (seasonality, moving averages).
- Try advanced time series models (**ARIMA, XGBoost, LSTMs**).
- Include external factors (weather, traffic) for better predictions.