# ENS Data Challenge: Electricity Price Modeling

## Context
The price of electricity is influenced by numerous factors: climate, energy production, raw materials, geopolitics, and international trade. This project aims to model the daily variation in electricity futures prices in France and Germany, using meteorological, energy, and commercial data.

## Objective
The goal is to explain the daily variation in electricity futures prices using explanatory variables. We use the **Spearman correlation** between predictions and actual price variations as performance metric. 

## Data
Three CSV files are provided:
- `X_train.csv`: Training data (explanatory variables).
- `Y_train.csv`: Training data (target variable).
- `X_test.csv`: Test data (explanatory variables).

The data includes:
- **Economic factors**: Prices of gas, coal, carbon emissions.
- **Meteorological factors**: Temperature, rain, wind.
- **Energy production**: Natural gas, coal, hydro, nuclear, solar, wind, lignite.
- **Electricity usage**: Consumption, import/export of electricity between countries.
