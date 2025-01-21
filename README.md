# London-house-prices
Economic and Housing Trends in London and the UK, London Property Prices Prediction Model.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Key Takeaways](#key-takeaways)
- [Reference](#reference)

--- 

### Project Overview 
#### Economic and Housing Trends in London and the UK + London Property Prices Prediction Model.

1. The first part of the project explores the economic and housing trends in London and the UK, highlighting disparities in salaries, property prices, and growth rates across different areas. It examines how central boroughs like Westminster and the City of London dominate in earnings and property prices, while outer boroughs remain more affordable but experience slower growth. The analysis also identifies trends in property types, growth volatility, and investment potential within London's dynamic real estate market.
   
#### The detailed description of London's property prices' data preparation is included in the file 'london_prices.ipynb' saved in this repository.

#### Link to the Dashboard in Tableau Public
[https://public.tableau.com/app/profile/janina.paszek.minshull/viz/Pear/Dashboard1?publish=yes](https://public.tableau.com/app/profile/janina.paszek.minshull/viz/Londonpropertyprices/PropertyMarket?publish=yes)

![london-house-prices-dashboard](https://github.com/NinPasMin/London-house-prices/blob/main/London%20house%20prices%20Tableau%20dashboard.PNG?raw=true)

2. The second part of the project focusus on building 2 price prediction models for London areas - based on the property location, its size, number of bedrooms, number of bathrooms and the number of receptions and veryifing which model performs better - with or without the identified outliers.

#### The detailed description of building the models is included in the 'london_prices.ipynb' saved in this repository.

### Data Source

   - 'london_houses_raw_file.csv' - the file containing information about the London's boroughs' property prices -           modified in Jupyter Notebook, 
   - 'housing_in_london_yearly_variables.csv' - containing information about the changes in the mean and median              salaries accross London and UK over the years (1999 - 2019) - used in Tableau Public,
   - 'mean_price_of_houses_in_london_uk' - containing information about the changes of average property prices in            London and across UK over the years (2006 - 2024) - used in Tableau Public,
   - 'london_postcodes-lat-long.csv' - placing the location of London boroughs on a map using longitude and latitude         of the London postal codes - used in Tableau Public,
   - 'london_houses_after cleaning.xlsx' - the file exported from Jupyter Notebook used for the visualisation in             Tableau Public.

### Tools

1. Jupyter Notebook (Python):
   - Data Exploration;
      - Loading the dataset and inspecting its properties,
      - Identifying columns with missing values.
   - Data Cleaning;
      - Removing irrelevant columns and ensuring consistency in column names,
      - Handling missing values,
      - Standardizing location names and correcting inconsistencies using regular            expressions and string matching,
      - Merging the dataset with additional geographical information,
      - Replacing missing values.
    - Data Preparation;
      - Creating a new DataFrame with only the necessary columns for further                 analysis,
      - Handling zero value,
      - Creating new column (calculation).
   - Data Visualisation;
      -  Displaying histogram - visualizing the distribution of property prices to            understand the common price ranges for properties in London and identify             any skewness in the data.
   - Feature Engineering;
     - Preparing the dataset for building 2 price prediction models (including and          exluding outliers) by ensuring all relevant features are clean and consistent,
     - Encoding Categorical Variables,
     - Handling outliers. 
2. Tableau Public:
    - Data visualisation,
    - Dashboard Creation.

### Data Analysis

Data analysis involved exploring the data in order to answer key questions, such as:

1. Salaries and Affordability:
     - How do average salaries in London boroughs compare to the rest of the UK?
     - Are salaries in certain London areas aligned with the property prices in those areas?

2. Property Price Trends:
     - How have average monthly property prices changed in London compared to the UK over time (2006–2024)?
     - Which London areas experienced the most significant price growth in the last two decades?

3. Annual Growth Rate:
     - What are the periods of high and low growth in property prices in London versus the UK?
     - How volatile are the property prices in London compared to the overall UK market?

4. Regional Differences:
     - Which London areas have the highest and lowest property prices in February 2024?
     - How does the distribution of house prices per square foot vary across London boroughs?

5. Property Types and Value:
     - What is the average price and price per square foot for different property types in London (bungalows,                  duplexes, etc.)?
     - Which property type offers the best value for money in terms of price per square foot?

6. Buyer Preferences:
     - How do property prices vary based on size (square footage), number of bedrooms, bathrooms, or receptions?
     - Which areas in London provide properties in specific price ranges or sizes that meet certain criteria?


### Data Analysis Result

1. Salaries and Affordability - London / UK Average Salaries (1999 - 2002)
   - Salaries in London are significantly higher than the UK average across all years displayed.
     Certain areas in London, such as the City of London, Westminster, and Islington, consistently show higher average      salaries compared to other boroughs.
   - Salaries have been increasing steadily from 1999 to 2002, with notable jumps in the City of London (from £48.9K        in 1999 to £56.5K in 2002) and Islington (from £34.2K to £54.1K).

2. Property Price Trends (2006 - 2024)
   - London consistently shows a higher average sales price compared to the UK as a whole.
   - Property prices in London experienced steady growth until around 2020, after which growth slowed down slightly.
     The UK follows a similar upward trajectory, but the price difference between London and the UK is widening over        time.

3. Annual Growth Rate (2006 - 2024)
   - London's property market demonstrates more volatile growth compared to the UK, with sharp peaks and dips.
   - Significant dips occurred during the 2008 financial crisis and other market corrections.
   - A rebound in growth is visible post-2020, although volatility persists.

4. Regional Differences - Property Prices in London Areas (Feb 2024)
   - The map highlights significant variation in property prices across London, with certain areas reaching up to           £39.75M.
   - Higher-priced properties are concentrated in central boroughs like Kensington and Chelsea and Westminster.

5. Property Types and Value - Size and Price of Property Types in London (Feb 2024)
   -  Bungalows are the most affordable type (£904,444 average price), whereas Penthouses are the most expensive          (£13.1M average price).
   -  Flats/Apartments offer the lowest price per square foot (£1,232 per sqft), making them relatively cost-efficient.

6. Buyer Preferences - Distribution of House Prices per Square Foot
   - The majority of properties fall between £750 and £1,750 per square foot, with a steep decline in properties            priced   beyond this range.
   - Higher density in mid-tier pricing suggests balanced affordability for a significant portion of buyers.


### Key Takeaways:

### Reference:

