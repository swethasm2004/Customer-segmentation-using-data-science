# Age based customer segmentation using data science  README

This Jupyter Notebook provides a data science model to predict Age  based on various customer features. The code includes data preprocessing, exploratory data analysis, data cleaning, and model building. Below are the steps to run this code:

## Prerequisites
1. You need to have Python installed on your system.
2. Install Jupyter Notebook and the required libraries using pip:
   bash
   pip install jupyter numpy pandas seaborn matplotlib scikit-learn scipy
   

## Steps to Run the Code
1. Clone or download the Jupyter Notebook file and the dataset ('Mall_Customers.csv') to your local machine.
2. Open a terminal and navigate to the directory containing the Jupyter Notebook and the dataset.
3. Start a Jupyter Notebook session:
   bash
   jupyter notebook
   
4. In the Jupyter Notebook dashboard, open the 'ADS_Phase4.ipynb' file.
5. Run the code cells in the notebook sequentially by clicking on each cell and pressing Shift + Enter.
6. You can interact with the code, view visualizations, and see model performance metrics as the code executes.
7. The final model, a Decision tree classifier, is saved as 'Mall_Customers' and can be used for customer segmentation.

## Dataset Used
In this project, we used a Mall_Customer dataset obtained from Kaggle. The dataset contains a wealth of information about customers age. It is essential to understand how various factors, such as customerID,Gender,Age,Annual income,spending scores. You can access the dataset on Kaggle at the following URL: [customers details Dataset] (https://www.kaggle.com/datasets/akram24/mall-customers)
## About the Dataset
The dataset consists of 5 columns, providing comprehensive information about cuatomers and their details about age. IMDb score is a crucial metric for assessing a movie's success. A higher IMDb score often indicates a more successful movie, while a lower score may imply less success. The dataset allows us to analyze various factors that can influence that age to helps as to better prediction. 

The key features in the dataset include:
-Customer ID
-Gender
-Age
-Annual income
-Spending Score

We utilized this dataset to build data science models for to predict the age based customers details. The code and Jupyter Notebook provide a step-by-step guide on how to preprocess the data, perform exploratory data analysis, clean the data, build regression models, and even to segment age based customer strategies.

Feel free to explore and modify the code to gain a deeper understanding of  customers age analysis using this rich dataset.


## Understanding the Code
The code consists of the following sections:
- Importing necessary libraries and reading the dataset.
- Data preprocessing, cleaning, and feature engineering.
- Exploratory data analysis with visualizations.
-Using PCA Algorithm It is used to identify patterns in the data, which can  be used to reduce the dimensionality of the data, making it easier to visualize and interpret.
- Building and evaluating regression models:
  - Linear Regression
  - Decision Tree Regression
  - Support vector machine
- Building and evaluating a classification model for customers age categories.
- Saving the trained Random Forest Classifier model for age based customers details prediction.

## Data Sources
The dataset used in this code ('Mall_Customers.csv') is assumed to be available in the same directory as the Jupyter Notebook. This dataset contains various features like Age,Annual income,Spending Score, which are used to train and evaluate the models.
