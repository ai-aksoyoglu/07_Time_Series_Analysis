---

<h1 align="center">Short-term Temperature Forecast 
    <h2 align="center">~ Analyzing Time Series with ARIMA ~
</h2>

---
__1) The Goal:__ Create a short-term temperature forecast based on the Mean temperature data provided by ECA\&D (European Climate Assessment \& Dataset) for Berlin-Tempelhof.    

__2) Get the Data:__ Download the data for Berlin-Tempelhof from ECAD following the instructions provided under the challenge called ["Read the data"](https://krspiced.pythonanywhere.com/chapters/project_temperature/README.html).

__3) Clean \& Prepare the Data (EDA \& Train-Test-Split):__ Transform the dates to timestamp and drop the dates before 1945-11-06 because there are missing values.   
     
__4) Feature Engineering (FE):__ A special kind kind of feature engineering: **Time Series Decomposition**.
    
__6) Train a Model:__ A special variant of the Linear Regression: **Linear Autoregression** (Autoregressive Model)   
    
__7) Evaluate the Model:__ Cross-Validation and AIC (Akaike Information Criterion)  

- ARIMA model **(Thursday Afternoon)**
    - Autoregressive Integrated Moving Average Model  
    
    
The AR model (Linear Autoregression) and the ARIMA model are ONLY USEFUL for short-term forecasts!!!

__10) Test the Model:__    
    
---
