# Pandemic Analytics Pilot – Forecasting US COVID-19 Cases

## Objective
This project forecasts new COVID-19 cases in the United States using historical data. The goal is to provide short-term predictions that can help public health officials anticipate healthcare demand.

## Data Source
- Our World in Data COVID-19 Dataset: [https://covid.ourworldindata.org/data/owid-covid-data.csv](https://covid.ourworldindata.org/data/owid-covid-data.csv)

## Methodology
- Time series forecasting using **Prophet**, a machine learning library for forecasting.  
- Daily new cases are modeled to predict the next 30 days.  

## Results
The forecast plot is saved in the `results` folder:  
![Forecast Plot](results/covid_forecast_plot.png)

- **Blue line:** Predicted new cases  
- **Light blue band:** Prediction uncertainty interval  

## Folder Structure
