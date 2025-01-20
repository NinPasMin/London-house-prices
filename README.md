# London-house-prices
Economic and Housing Trends in London and the UK, London Property Prices Prediction Model.

## Table of Contents

- [Project Overview](#project-overview)
- [Tools](#tools)
- [Data Preparation](#data-preparation)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Recommendation](#recommendation)
- [Reference](#reference)

--- 

### Project Overview
#### Economic and Housing Trends in London and the UK + London Property Prices Prediction Model.

1. Data Visualisation in Tableau:
  
The first part of the project explores the economic and housing trends in London and the UK, highlighting disparities in salaries, property prices, and growth rates across different areas. It examines how central boroughs like Westminster and the City of London dominate in earnings and property prices, while outer boroughs remain more affordable but experience slower growth. The analysis also identifies trends in property types, growth volatility, and investment potential within London's dynamic real estate market. This part is primarily based on 3 files:
    -  'london_houses_raw_file.csv' - the file containing information about the London's boroughs' property prices. This file was modified in Jupyter Notebook (london_prices.ipynb - saved in my repository - here you can find step by step description of data preprocessing) and exported as an excel file ('london_houses_after cleaning.xlsx') for further visalisation in Tableau Public.
    - 'housing_in_london_yearly_variables.csv' - containing information about mean and median salaries accross London and UK in the time period between 1999 and 2019.
    - 'london_postcodes-lat-long.csv' - placing the location of London boroughs on a map using longitude and latitude of the London postal codes.

Link to the Dashboard in Tableau- [https://public.tableau.com/app/profile/janina.paszek.minshull/viz/Pear/Dashboard1?publish=yes](https://public.tableau.com/app/profile/janina.paszek.minshull/viz/Londonpropertyprices/PropertyMarket?publish=yes)

![london-house-prices-dashboard](https://github.com/NinPasMin/London-house-prices/blob/main/London%20house%20prices%20Tableau%20dashboard.PNG?raw=true)


2. London Price Prediction Model in Jupyter Notebook (Python):
   
The second part of the project is a continuation of data preprocessing in Jupyter Notebook - 'london_prices.ipynb' - please scroll down the file to find the desription of building the price prediction model for London areas - based on the property location, its size, number of bedrooms, number of bathrooms and the number of receptions. This part is primarily based on the file 'london_houses_raw_file.csv' and finishes with few examples of the price prediction based on the given data.  


### Tools

1. Jupyter Notebook (Python):
   - Data Preparation;
       - Data loading and inspection
       - Data cleaning and formatting
       - Filling the missing values
       - Creating additional columns
   - Data Visualisation 
   - Prediction Model (Machine Learning)
2. Tableau Public - Data visualisation, Dashboard Creation.

### Data Analysis



