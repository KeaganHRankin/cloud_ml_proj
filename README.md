# cloud_ml_proj
cloud ml project: this project develops an ML model for 1-day ahead forecasting of power demand and prices in Ontario given open data on historical energy time-series and climatic conditions in the province. We deploy the model in Azure ML and used AutoML to tune hyperparameters <br>

![alt text](https://www.power-technology.com/wp-content/uploads/sites/21/2023/05/P2-Img-8.jpg) 
<i> from IESO <i>

## Data
power data: https://ieso.ca/en/Power-Data/Data-Directory <br>
other weather data: https://climate.weather.gc.ca/historical_data/search_historic_data_e.html <br>
inflation data: https://doi.org/10.25318/1810020401-eng

## Method
We employ a linear model and gradient boosting models on training data between 2018-2022, then test the model on data from 2022-present.

## Future
improved feature engineering (sinusoidal dates), supply data, expanded, hourly climatic, deep architecture (LSTM, CNN)

