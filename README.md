# Prediction-of-Product-Sales
This first project will be a sales prediction for food items sold at various stores

Altayeb Abu-Alfayaa


### The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined

## Data Source: 
Data Science Product-Sales

https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/#ProblemStatement

For this dataset, there were 8523 rows and 12 columns.

## Data Dictionary

<p align = "center"> 
  
  <img src = "https://github.com/Al-Tayeb96/Prediction-of-Product-Sales/blob/main/Capture2.PNG">
  
</p>



## To prepare this data, the data was cleaned, and the following processes were performed:

### Exploratory Data Analysis
    - During the exploratory data analysis, a boxplot and histogram was visualized for each numeric datatype column. 
    - Also, a barplot was visualized for each categorical column. 
    - This gave a good baseline for all of the numeric and categorical columns for univariate EDA.
    

<p align = "center"> 
  <img src = "https://github.com/Al-Tayeb96/Prediction-of-Product-Sales/blob/main/hist_out_salse.PNG">
</p>

This histogram shows that the majority of the sales are decreasing if the price of sales high"exponential decay curve" and the highest majority of  sales prices in range 0-2000 

 ### Expanatory Data Analysis
    - To visualize the data for explantory purposes, two bargraphs were chosen.
    - The bargraphs were chosen to show how the data compare to each other. 

## Explanatory Visuals

<p align = "center"> 
  <img src = "https://github.com/Al-Tayeb96/Prediction-of-Product-Sales/blob/main/bar_plot%20.PNG">
</p>


this bargraph show us the most sales the outlet 'Outlet_Type' if its a grocery store or some sort of supermarket for  products in the particular store 'Item_Outlet_Sales' and the lowest one :

-the most Outlet_Type is Supermarket Type3 in range 3500-4000

-the lowest Outlet_Type is Grocery Store in range 0-500


<p align = "center"> 
  <img src = "https://github.com/Al-Tayeb96/Prediction-of-Product-Sales/blob/main/Capture3%20(2).PNG">
</p>

this bargraph show us the most goods seles for ecah Outlet_Type.

the most products is :

-for Supermarket Type1 is seafood

-for Supermarket Type2 is seafood

-for Supermarket Type3 is breakfast

-for  Grocery is breakfast

 ### Maching Learning Using the Following Models:

    - Linear Regression Model
    - Random Forest Regressor Model
    - Tuned Random Forest Regressor Model
    
 ## Models Evaluated & Results
- Linear Regression Model (Testing Set):
    - MAE = 805.116
    - MSE = 1,197,969.401
    - RMSE = 1,094.518
    - R^2 = 0.566
- Random Forest Regressor Model (Testing Set):
    - MAE = 795.514
    - MSE = 1,311,943.814
    - RMSE = 1,145.401
    - R^2 = 0.524
- Tuned Random Forest Regressor Model (Testing Set):
    - MAE = 728.593
    - MSE = 1,096,529.829
    - RMSE = 1,047.153
    - R^2 = 0.603

- The Final Model Chosen was a `Random Forest Regressor Model` with the n_estimators tuned to 500 and max depth= 5 .
- For the testing set on the model, `60.3%` of the variance in y was explained by x. 
- The Mean Absolute Error was off by about `$728.593`.
- The Mean Squared Error was `$1,096,529.829`.
- The Root Mean Squared Error had a calculation of `$1,047.153`.


Using this model to make predictions about the rate of salse for any big market would not be a very reliable but there is still some room for improvement, especially considering the MAE, MSE, and RMSE values . or we should take care on data it self.

## Recommendations

this data of big market need an update to make this model improved 
if we notic there is a convergence between metrics model so i thenk this is an limitations in predction .

Overall, the best model is definitely the tuned Random Forest Regressor Model. There was still some bias in the model, but by far it outperformed the linear regression model.


## Limitations & Next Steps
From here, a student or any data scientist at BigMart use the insights from the visuals on how the sales of each product at a particular outlet wuold be. 


## For Further Information

For any additional questions, please contact: 
- AL-tayeb Abu-Alfayaa. (Data Science student)
- taib_17@hotmail.com



 







