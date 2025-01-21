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
   
   #### The detailed description of London's property prices' data preparation is included in the           file 'london_prices.ipynb' saved in this repository.

   Link to the below Dashboard in Tableau Public:
   https://public.tableau.com/app/profile/janina.paszek.minshull/viz/Londonpropertyprices/PropertyMarket?publish=yes

![dashboard](https://github.com/NinPasMin/London-house-prices/blob/main/london-house-prices-tableau-dashboard.PNG?raw=true)

3. The second part of the project focusus on building 2 price prediction models for London areas - based on the property location, its size, number of bedrooms, number of bathrooms and the number of receptions and veryifing which model performs better - with or without the identified outliers.

   #### The detailed description of building the models is included in the 'london_prices.ipynb' saved in this                 repository.

### Data Source

1. 'london_houses_raw_file.csv' - the file containing information about the London's boroughs' property prices -           modified in Jupyter Notebook,
2. 'housing_in_london_yearly_variables.csv' - containing information about the changes in the mean and median              salaries accross London and UK over the years (1999 - 2019) - used in Tableau Public,
3. 'mean_price_of_houses_in_london_uk' - containing information about the changes of average property prices in            London and across UK over the years (2006 - 2024) - used in Tableau Public,
4. 'london_postcodes-lat-long.csv' - placing the location of London boroughs on a map using longitude and                  latitude of the London postal codes - used in Tableau Public,
5. 'london_houses_after cleaning.xlsx' - the file exported from Jupyter Notebook used for the visualisation in             Tableau Public.

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

1. Salaries and Affordability - London / UK Average Salaries (1999 - 2019)
   - Salaries in London are significantly higher than the UK average across all years displayed.
     Certain areas in London, such as the City of London, Westminster, and Islington, consistently show higher average      salaries compared to other boroughs.
   - Salaries in London have experienced steady growth from 1999 to 2019, with certain areas, such as Hammersmith,          Fulham, Kensington, and Chelsea, seeing more rapid increases. This upward trend is mirrored in the high property       prices within these boroughs. In contrast, areas like Greenwich and Ealing have experienced more modest salary         growth, which aligns with their comparatively lower property prices. There are also London boroughs like Camden        with rapidely growing salaries almost reaching the London avarage one, while the prices of the properties remain       relatively low - those areas could be interesting for the investors.

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
   - Higher-priced properties are concentrated in central boroughs like Kensington, Mayfair, Chelsea or Westminster.

5. Property Types and Value - Size and Price of Property Types in London (Feb 2024)
   -  Bungalows are the most affordable type (£904,444 average price), whereas Penthouses are the most expensive          (£13.1M average price).
   -  Flats/Apartments offer the lowest price per square foot (£1,232 per sqft), making them relatively cost-efficient.

6. Buyer Preferences - Distribution of House Prices per Square Foot
   - The majority of properties fall between £750 and £1,750 per square foot, with a steep decline in properties            priced beyond this range.
   - Higher density in mid-tier pricing suggests balanced affordability for a significant portion of buyers.


### Key Takeaways

1. Economic Disparity:
   - Salary Divide: Salaries in London are significantly higher than the UK average, but this gap is especially             pronounced in central London, reflecting the higher concentration of high-paying industries like finance, tech,        and legal services.
   - Property Divide: Property prices highlight a similar divide. Central boroughs such as Westminster and Kensington       and Chelsea are unaffordable to most, while outer boroughs like Greenwich or Ealing offer more                          affordable options, albeit with fewer high-paying job opportunities. This disparity underscores the                    socioeconomic polarization within London.
3. Property Market Resilience:
      - Despite global economic challenges, London's property market remains robust, though more volatile compared to          the broader UK market.
4. Affordability Challenges:
      - London remains a high-demand market, keeping property prices elevated. The rising price per square foot,               especially in central London, indicates growing affordability concerns for average buyers.
      - Luxury properties (beyond £2,000 per sqft) such as penthouses and house remain a niche market segment
5 . Investment Opportunities:
   - Apartments and flats present opportunities for cost-efficient investments, while luxury properties cater to high-      net-worth individuals. 
   - Certain areas of London have experienced rapid salary growth, yet property prices in these locations have not          risen at the same pace. This disparity could present attractive opportunities for investors, as these areas may        offer strong potential for future property value appreciation.


### Reference

