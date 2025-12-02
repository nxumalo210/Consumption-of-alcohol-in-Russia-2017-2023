Project Title: Analysis and Forecasting of Alcohol Consumption in Russia (2017-2023)

This project provides an in-depth analysis of alcoholic beverage consumption patterns across various regions in Russia from 2017 to 2023. Utilizing a dataset detailing the consumption of wine, beer, vodka, sparkling wine, brandy, cider, and liqueurs, the project cleans the data, performs descriptive analytics, and develops a time series forecasting model for the most consumed beverage.

Key Steps and Analysis:

**1) Data Loading and Initial Exploration:** The project begins by loading consumption data from a CSV file and performing initial inspections to understand its structure and content.
**2) Data Cleaning:**
Comprehensive data cleaning was performed, including:
  · Renaming columns for clarity.
  · Identifying and removing outliers from each alcohol consumption category (Wine, Beer, Vodka, Sparkling Wine, Brandy, Cider, Liqueurs, and Total Alcohol Consumption) using the Interquartile Range (IQR) method.
  · Filling missing values (introduced by outlier removal) with the mean of their respective columns to maintain data integrity for subsequent analysis.
**3) Descriptive Analytics - Time Series Analysis:**
  · Visualizations were generated to show the mean and total consumption of each alcohol type annually from 2017 to 2023.
  · An overview of the total annual alcohol consumption was also presented, revealing overall trends.
  · The analysis highlighted that beer is consistently the most consumed alcoholic beverage in Russia, followed by vodka and wine.
**4) Descriptive Analytics - Regional Consumption:**
  · The mean consumption of each alcohol type per year per region was calculated.
  · Line plots were generated using FacetGrid to visualize year-on-year consumption trends for each region and alcohol type.
  · Bar charts were created to compare the average consumption of each alcohol type across all Russian regions, providing insights into regional preferences.
**5) Time Series Forecasting (ARIMA Model):**
  · Focusing on beer (the most consumed beverage), a time series forecasting model was implemented.
  · The annual total beer consumption data was differenced to achieve stationarity, a prerequisite for ARIMA modeling, confirmed by the Augmented Dickey-Fuller (ADF) test.
  · PACF and ACF plots were used to determine the appropriate order for the ARIMA model.
  · An ARIMA(0,1,0) model was fitted to the data.
  · The model forecasted beer consumption for the next five years (until 2028), providing predictions for future trends.
  · A visualization combining historical and forecasted beer consumption was generated to illustrate the model's predictions.
  · This project offers valuable insights into Russia's alcohol consumption landscape and provides a predictive outlook for future consumption patterns based on historical data.
