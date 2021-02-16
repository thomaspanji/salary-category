# Neural Network Model to Predict One's Salary Category: Project Overview
* Created a neural network model to classify one's salary category.
* Feature engineering on some features to group by categories.
* Selection on features which has low correlation to target.
* Found the best model by customizing model's layers.

# Resources Used
Python Version=3.7

Packages: NumPy, pandas, matplotlib, TensorFlow, Keras, sklearn.

Data: https://www.kaggle.com/c/sanbercode-data-science/data

# Data Cleaning


# Exploratory Data Analysis
I looked at the distributions of the data and the value counts for the various categorical variables. Below are a few highlights.
![](images/jumlah-tahun.png)
![](images/status-gaji.png)
![](images/salary-corr.png)

# Model Building
I one-hot encoded all category features to make it numeric and can be accepted by the model. I split the data into two parts: training and validation data with a proportion of 70:30 using `train_test_split`. At first, I build a simple neural network sequential model with three hidden layers with 10 nodes each. Then I insert a normalization layer between hidden layers. Here are the visualization of the model I made.
![](model)

I evaluated the model by choosing AUC as the model's metric.

# Model performance


# Prediction

