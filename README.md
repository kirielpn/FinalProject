
<center><h1>Unemployment duration forecast</h1></center>
<center><h2>Kiriel Pena-Navarro</h2></center>
<center><h3>Spring 2024 ECON294A Final Project</h3></center>

## Description:

Using ARIMA and SARIMAX models to forecast weekly average unemployment duration in the United States, using quartely data from FRED. 
The exogeneous variables used for unemployment duration forecast are unemployment rate, labor force participation rate, real investment, real GDP, real earnings, productivity (index), consumption, population level, and average weekly hours worked by non-farm business employees.
To forecast unemployment duration with the exogeneous variables, first the variables are each forecasted individually using an ARIMA model. With the forecasted variable data, a SARIMAX model is used to forecast unemployment duration 5 years out (from 2024). 

## Data:

The data used was retrieved as quarterly and monthly. For analysis, the monthly data was converted to quarterly using the mean of the monthly data over a quarter. The labor productivity as well as average weekly hours worked are data excluding the farming sector. The real consumption data measures personal consumption expenditures per capita. 
Along with the variables mentioned above, lagged variables were also created for fitting the SARIMAX model. Labor force participation, unemployment rate, real consumption, and real investment were all lagged by one quarter and used as additional variables in estimating the unemployment duration. 






