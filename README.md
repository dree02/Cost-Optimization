<h1>Linear Regression with Multiple Variables</h1>

<p>
This repository contains a machine learning project that demonstrates the use of linear regression with multiple variables to predict home prices in Monroe, New Jersey, USA. The project focuses on predicting home prices based on three independent variables: square footage (area), number of bedrooms, and the age of the home.
</p>


<p>
<h2>Project Overview</h2>
We tackle the problem of predicting home prices using a linear regression model. We have a dataset containing home prices in Monroe Township, New Jersey, where the price depends on the area (in square feet), the number of bedrooms, and the age of the home (in years). Our goal is to predict the prices of new homes based on these features.

<br>

We use the following equation to calculate the home price: <br>
<b>Price = (Area * a) + (Bedrooms * b) + (Age * c) + d</b><br>
Area, Bedrooms, and Age are the independent variables or features.<br>
a, b, and c are coefficients, and d is the intercept.<br>
Price is the dependent variable that we aim to predict.
</p>

<p>
<h3>Data Preprocessing</h3>
Before training the linear regression model, we perform some data preprocessing steps:<br>
We fill any missing values in the "bedrooms" column with the median value.<br>
The dataset is loaded into a Pandas DataFrame for further analysis.
</p>

<p>
<h3>Training the Model</h3>
We use scikit-learn's linear regression implementation to train the model.<br> 
The code snippet for training the model is provided in the repository.<br>
We get the values of coefficients and the intercept.
</p>

<p>
<h3>Making Predictions</h3>
After training the model, we can make price predictions for new homes by providing the values of area, bedrooms, and age as input. Two example predictions are provided in the repository for reference.
</p>

<p>
<h3>Conclusion</h3>
This project serves as an example of using linear regression with multiple variables for predictive modeling. Feel free to explore the code and dataset to gain a better understanding of how linear regression can be applied to real-world problems. 
</p>
