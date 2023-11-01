# Electricity Price Prediction README 

# Prerequisites
1) You need to have Python installed on your system.
2) Install Jupyter Notebook and the required libraries using pip:
 
    pip install jupyter numpy pandas seaborn matplotlib sk.learn


# Steps to Run the Code
1)Clone or download the Jupyter Notebook file and the dataset ('electricity.csv') to your local machine.

2)Open a terminal and navigate to the directory containing the Jupyter Notebook and the dataset.

3)Start a Jupyter Notebook session:

      jupyter notebook
4)In the Jupyter Notebook dashboard, open the 'Electricity Price Prediction.ipynb' file.

5)Run the code cells in the notebook sequentially by clicking on each cell and pressing Shift + Enter.

6)You can interact with the code, view visualizations, and see model performance metrics as the code executes.

7)The final model, a Random Forest Classifier, is have highest accuracy model

# Dataset Used
In this project we uses dataset from kaggle containing electricity data for various dates and times between 2012 and 2013. Each row represents a specific date and time, and the columns represent different measurements such as energy consumption, cost, and other related data points. The data is organized in columns, with each column representing a different measurement. The table includes information such as the date and time, energy consumption, and other related data points.You can access the dataset on Kaggle at the following URL:

[https://www.kaggle.com/datasets/chakradharmattapalli/electricity-price-prediction/](url)

# About the Dataset
The document is a table containing electricity data for various dates and times between 2012 and 2013. Each row represents a specific date and time, and the columns represent different measurements such as energy consumption, cost, and other related data points. The data is organized in columns, with each column representing a different measurement. 

The key features in the dataset include:

    *DateTime
    
    *Holiday
    
    *HolidayFlag
    
    *DayOfWeek
    
    *WeekOfYear
    
    *Day
    
    *Month
    
    *SMPEP2
    
    *Andmore
    
We utilized this dataset to build machine learning models for Electricity Price Prediction. The code and Jupyter Notebook provide a step-by-step guide on how to preprocess the data, perform exploratory data analysis, clean the data, build regression models, and even predict IMDb score categories.

Feel free to explore and modify the code to gain a deeper understanding of Electricity Price Prediction using this rich dataset.

# Understanding the Code

 * Importing necessary libraries and reading the dataset.

*  Data preprocessing, cleaning, and feature engineering.
  
*Exploratory data analysis with visualizations.

*Building and evaluating regression models:

      Linear Regression
      Decision Tree Regression
      Random Forest Regression
      
*Building and evaluating a classification model for Electricity Price Prediction.

*Saving the trained Random Forest Classifier model for Electricity Price Prediction.

# Save and Export:

You can save the Notebbook with your changes and export the results as needed.
