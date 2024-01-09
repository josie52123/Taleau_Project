# Final-Project-Tableau

## Project/Goals
Overview:
The project centers on analyzing the Canadian Housing Market and offering insights into its trends over the last four decades.
Available dataset: Housing Price Index,Consumer Index, Office Reale State Index, Real Estate numbers, Real Estate Prices

Goal:
1. Explore six different datasets
2. Observe trends and patterns
3. Provide visualization to the questions 

## Process
1. Review Files: Review each file provided to understand the data structure, variables, and contents.
2. JSON to CSV Conversion (weekly_earnings.ipynb): Use a Jupyter Notebook (weekly_earnings.ipynb) to parse through the weekly_earnings.json file and convert it into a CSV format. This step is necessary as Tableau is more adept at handling data in CSV format.
3. Import Data into Tableau: Import each of the data sets (including the CSV file created in step 2) as data sources into Tableau.
4. Data Types Formatting: Format the data types in Tableau to ensure proper categorization and analytical functionality, especially data format.
5. Data Linking: Establish connections between the data sets. The housing price index table is chosen as the primary table for linking.
6. Visualization Creation: Create visualizations on separate sheets for each question being asked. Utilize appropriate charts, graphs, and visual elements.
7. Additional Features: Incorporate calculated fields, parameters, filters (both static and interactive), animations, etc., as required for each visualization to enhance analytical capabilities.
8. Dashboard Design: Combine the visualizations, filters, and other elements on dashboards. Create one dashboard per question to ensure clarity and relevance.
9. Story Creation: Combine all dashboards into a single story within Tableau. Ensure a logical flow of information and insights.
10. Review and Refinement: Review the overall analysis, visualizations, and story. Make refinements as needed to improve clarity and effectiveness.

## Results
### Option 1 - Canadian Housing Market
- Show the trend of house prices across Canada in the last 40 years (table housing_price_index). Line Chart.
    - **2 line graphs: housing price index vs time & % difference in index value vs time**
- Compare the trend after 2005 with actual benchmark prices in table real_estate_prices to see if there are any differences.
    - **Barchart and line chart: HPI and benchmark price**
- Compare this trend with the trend of office prices. Which one is getting more expensive, faster? housing changes more
    - **Line chart: compare HPI and Office Price Index over time period.**
- Create a heatmap of Canada with current house prices for each available district.
    - **Heatchart on map and bubble chart to show top 5 cities.**
- Are the price differences between different districts increasing?
    - **2 line graphs: housing price change vs time and % difference in housing price vs time.**
- Compare the trend of house prices with earnings. 
    - **2 line graphs: housing and earnings over time period and % difference of housing and earning over time.**
- Did people spend more of their earnings in 2014 than they did in 2001? 
    - **Line chart and bar chart: HPI vs CPI and % difference of CPI change overtime.**
- There were several economic crises in the world in the last 40 years, including these four: Black Monday (1987), Recession (early 1990s), dot com bubble (2000 - 2002), Financial crisis (2007 - 2009). Show the effect of these crises on:
  - Earnings
  - House prices
  - Office prices
  - House constructions
  - Consumer index
  - **2 set of area charts showing value change and % change.**
- Plot consumer_index together with housing_price_index and fit the regression line between them. Can we predict consumer_index from the housing_price_index?
    - **1 scatter plot - HPI vs CPI**
    - **linear regression line**
## Challenges 
Choose Baseline Visualization Type: start with a baseline visualization that suits the nature of the data and the question asked.


## Future Goals
Further Investigation Needed: Additional investigation is required to understand the factors contributing to the widening regional disparities in home prices.
