Walmart Sales Forecasting

This project contains a Jupyter Notebook that performs a detailed sales forecasting analysis for Walmart using the Prophet model from Meta.

Project Structure

    Walmarts_Sales_Forecasting(1).ipynb: The main Jupyter Notebook that contains the entire sales forecasting project.

Key Features

    Data Cleaning and Preprocessing: The notebook handles data cleaning, including converting the 'Date' column to datetime objects and merging multiple datasets into a single dataframe.

    Feature Engineering: The notebook adds one and four-week lags to the Weekly_Sales column as new features to improve the model's performance.

    Modeling: The project uses the Prophet model for sales forecasting. The data is manually split for training and testing the model. The model was manually hyper-tuned to find the best Root Mean Square Error (RMSE) score. The notebook includes a plot showing the actual and forecasted sales using a line plot.

Requirements

To run this notebook, you will need the following libraries:

    numpy

    pandas

    matplotlib

    prophet

    scikit-learn

    seaborn

You can install these dependencies using pip:

!pip install numpy pandas matplotlib prophet scikit-learn seaborn

Dataset

The dataset used for this project is from the Walmart Sales Forecasting on Kaggle (https://www.kaggle.com/datasets/aslanahmedov/walmart-sales-forecast). The model is trained using the train.csv file, which contains historical sales data for 45 Walmart stores across different departments.
