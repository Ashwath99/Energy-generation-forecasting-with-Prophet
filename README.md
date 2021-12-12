<h1>Energy Generation Forecasting with Prophet</h1>

<h3>Dependencies</h3>

```
#For importing STL function
!pip install git+https://github.com/statsmodels/statsmodels.git
```

<h3>About the dataset</h3>

- Australia energy generation data<br>
- energy generation using coal as the fuel source<br>
- includes all coal facilities in Australia<br>
- compiled data from January 2014 - September 2021

---
**Citation:** *Data obtained from Australian Energy Market Operator Limited (AEMO) National Electricity Market (NEM) website*

The Jupyter Notebook contains the following steps:
 1. Data preparation
 2. Exploratory Data Analysis
 3. Model building
 4. Training, validation and testing
 5. Evaluation
 6. Hyperparameter tuning
 7. Re-training and testing
 8. Cross validation
 9. Complete training, testing and evaluation
10. Comparison

<br>**Learning Outcome:**<br><br>
This project demonstrates the limited capability of the Prophet model in fitting data with minimal seasonal effects or trends. This is seen through the initial less-than-desired accuracy in forecasting as well as the lack of improvement even after hyperparameter tuning.<br><br>
It is possible that the accuracy may improve to a slight extent with a certain combination of hyperparameters but the difference will most likely be very negligible unless clear seasonal or holiday effects are present and extracted from the data. However, through this program we can understand the extent to which the Prophet model gives accurate results for non-seasonal datasets in terms of its RMSE and MAPE scores.
