# Tableau Dashboard: Apple's Carbon Emissions

![](https://www.apple.com/newsroom/images/values/environment/Apple_commits-100-percent-carbon-neutrality-for-supply-chain-and-products-by-2030-solar-farm_07212020_big.jpg.large_2x.jpg)

This project is aimed at creating a dashboard in Tableau to visualize KPIs and trends on Apple’s carbon emissions from 2015 to 2022. This could help business stakeholders monitor important KPIs, or highlight trends in the data to support data-driven decision-making within the organization. 

To enable full interactivity and functionality, the following Tableau features were used in this dashboard:

- Filters
- Parameters
- Drill-down visualizations
- Add visuals to tooltips
- Forecast (here Tableau’s custom multiplicative model without seasonality was used as it produced the best forecast)
- Info button
- ... and many more!

![](https://github.com/user-attachments/assets/6d9f78d1-1939-4fd4-9f4c-bef10ec98858)

## Data Source

The data used in this project comes from Apple itself, and provides a summary of Apple’s greenhouse gas emissions from 2015 to 2022. It contains information on each source of emissions from both their corporate emissions and product life cycle, the carbon footprint of their baseline iPhone released in each year, and normalizing factors like revenue, market capitalization and number of employees. These reports come amidst Apple’s plan to achieve zero net emissions by the year 2030. 

The data contains three files: `carbon_footprint_by_product.csv`, `greenhouse_gas_emissions.csv` and `normalizing_factors.csv`, complete with `data_dictionary.csv` that explains each variable in the three datasets.  All data can be found [here](https://mavenanalytics.io/data-playground?page=5&pageSize=5) (click on Apple’s Greenhouse Gas Emissions).

## Post-Project Insights 

- Apple’s net carbon emissions are on a decreasing trend from 38.3 million in 2015 to 20.2 million metric tons in 2022, accompanied by an overall decrease in gross emissions and increase in carbon removals in the same time period.
  
- Product life cycle emissions are the major contributors of Apple’s gross emissions, exceeding corporate emissions substantially. 

- Out of all Apple’s sources of greenhouse emissions, the manufacturing category has made the best improvement as it cut its emissions by more than half from 29.6 million in 2015 to 13.4 million metric tons in 2022.
  
- Apple’s business growth seems to be sustainable as well, as it managed to reduce its net carbon emissions while expanding its overall revenue, market capitalization and number of employees from 2015 to 2022.
  
- Despite Apple’s efforts to reduce its carbon footprint, it seems like its goal of zero net carbon emissions by 2030 will unlikely be realised. Tableau has forecasted its net carbon emission in 2030 to be 12.9 million metric tons. 


