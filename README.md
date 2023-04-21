# The COVID-19 Pandemic’s Impact on Domestic Food Production 

## Project 1 - Group 8 
## Members: Ashley Song, Ajay Gopalkrishna, Akhyar Zaman, Bruce Skaar, Mwohania Taylor, Ryan Kincheloe

### Problem Overview
This project investigated the effects of the COVID-19 pandemic on domestic food production, agricultural supply chain, 
farm labor, and prices. The study will focus on four key food categories, namely produce, fruits, cereal, and livestock. The project will seek to answer 4 research questions and build out our hypotheses around how the pandemic has affected food production, supply chain, and labor, and how these factors have affected domestic food prices.

### Introduction
Our group (Ashley, Ajay, Akhyar, Bruce, Nia, and Ryan) took on this project to understand the pandemic's impact on food production, supply, prices and draw inferences from the analysis. We looked at the following questions - 
1. How has the pandemic impacted domestic food production, specifically in certain commodities (livestock, cereal, grains)?
2. What are some of the supply chain challenges that have arisen due to the pandemic's impact on food production?
3. How did the pandemic impact farm labor costs?
4. How have changes in food production, supply chain, and labor affected domestic food prices?

### Why the above questions?
* Grains are the main dietary source of energy, carbohydrates, and plant proteins world-wide. 
* We took the time to find all the variables that represents food availability and affordability. 
* The Food and Agriculture Organization (FAO) provides us with the Food Price Index.
* These indices are important because they provide insight into the productivity and efficiency of food production.
* All of which can impact food security, trade, and the environment.

### Data Sources
Many of datasets came from government websites like - 
1. USDA
    https://www.usda.gov/oce/commodity/wasde
    https://www.ers.usda.gov/data-products/
    https://agtransport.usda.gov/
    https://fdc.nal.usda.gov/api-guide.html
2. World Bank
    http://wdi.worldbank.org/table
    https://data.worldbank.org/indicator/AG.PRD.FOOD.XD?most_recent_year_desc=false
3. Food and Agriculture Organization (FAO)
    https://www.fao.org/worldfoodsituation/foodpricesindex/en/
4. Bureau of Labor Statistics (BLS)
    https://www.bls.gov/cpi/

### Analysis
1. *How has the pandemic impacted domestic food production, specifically in certain commodities (livestock, cereal, grains)?*<br>
As mentioned above, we looked ay grains as they are the main dietrary source of energy, carbohydrates, and plant protien. We looked at the production numbers for grain like wheat, soybean, sorghum, barley, oats, and rice for a 5 year time period starting from 2018 to 2022. There were no significant changes in grain production output during and after the peak of the pandemic.
In addition, we looked at red meat and poultry production. There was some impact on red meat production, it dropped in Apr and May of 2020. However, there was a lot more meat produced in the year, the mean production volume was higher than the previous and next two years. One inference is that the demand for red meat increased during the peak of the pandemic as people were sheltered at home and restaurants were shutdown.

![Annual Wheat Production](https://github.com/ajoyg/covid19_food_prod_impact/blob/main/food_production_analysis/output/wheat_box_plot.png)
![Annual Red Meat Production](https://github.com/ajoyg/covid19_food_prod_impact/blob/main/food_production_analysis/output/redmeat_box_plot.png)

2. *What are some of the supply chain challenges that have arisen due to the pandemic's impact on food production?*<br>
The COVID-19 pandemic disrupted food production and supply chains, leading to various challenges. One of the key areas we examined is how food products get from wholesalers to local grocery stores in the US. It's no surprise that trucking is the primary mode of transportation, accounting for about two-thirds of product shipments. We analyzed two key metrics: Total Food Refrigerated Truck Volume and Total Food Trucking Costs. The data showed a slight decline in refrigerated truck volume during the early part of the pandemic in 2020, which led to lower food trucking costs. Additionally, shortages of non-refrigerated products, such as cleaning supplies, paper products, cereal, and other staples, resulted in suppressed total food trucking costs in 2020. However, as the US began to emerge from the pandemic consumer demand and inflationary factors such as diesel fuel costs increased, the data showed subsequent increases in both refrigerated truck volume and total food trucking costs. In 2021 there was a spike in refrigerated truck volume, indicating a high demand for food products as the country reopened. This demand tapered off in 2022, nearly two years after the start of the pandemic, however, Total Food Trucking Costs remain high primarily due to higher diesel fuels prices that persist today compared with prior to the pandemic.

![Regrigerated Trucking Volume](https://github.com/ajoyg/covid19_food_prod_impact/blob/main/food_production_analysis/output/total_refrigerated_truck_vol.png)
![Food Trucking Cost](https://github.com/ajoyg/covid19_food_prod_impact/blob/main/food_production_analysis/output/trucking_cost_index.png)

3. *How did the pandemic impact farm labor costs?*<br>
We looked at labor price per acre of corn, wheat, oats, barley, sorghum, and soybeans for a 5 year period from 2018 to 2022. Labor price in for grain production have gone up YoY, especially for wheat(85%), soybeans(68%), and corn(26%). We also looked at labor prices for milk (26%) beef(-8%) and pork(11%). Our inference is that more labor intensive crops require more cost over time. Increase in labor price has a direct relation to food cost at the wholsale and retail stages of the supply chain, we will see that as we answer the next question. 

![Labor price for grains per acre](https://github.com/ajoyg/covid19_food_prod_impact/blob/main/food_production_analysis/output/grain_labor_price.png)
![Labor price for pork](https://github.com/ajoyg/covid19_food_prod_impact/blob/main/food_production_analysis/output/pork_labor_price.png)

4. *How have changes in food production, supply chain, and labor affected domestic food prices?*<br>
For this question we looked at two sets of data. Firstly, we have the food price index for 5 major categories of food commodities (Meat, Dairy, Cereals, Oils, Sugar) over the previous 5 years. Here, we can clearly see a sharp increase in price across all commodities from 2020 onward. While some begin to stabilize (i.e. sugar and oils) after 2021, the rest continue this trend. Going a step deeper, when we look at the cost of pork and beef from farm, to wholesaler, to consumer; it is interesting to see that the increase in prices is mostly on the consumer side. Prices for farmers and wholesalers increased after 2020 but they hold steady in 2022 for the most part (while consumer prices continue rising). Our conclusion is that changes (as a result of covid-19) in our food system, have lead to an increase in domestic food prices at the consumer level. It is important to acknodledge that inflation is also a confounding factor here. 


![Food Price Index](https://github.com/ajoyg/covid19_food_prod_impact/blob/main/food_production_analysis/output/food_price_index.png) 
![Port - Historical prices](https://github.com/ajoyg/covid19_food_prod_impact/blob/main/food_production_analysis/output/pork_historical_price.png)

### Data Challenges
* Some of the datasets we identified only went up to 2019, limiting our analysis
* Due to time constraint we had to limit our analysis to the US market
* Some of the commodity data ahd different measurement units that made it challenging to provide a consolidated analysis.

### Future Plans
In summary, we analyzed food production volumes, farm labor costs, food transportation costs and their impact on food prices for the years before and after the pandemic. We found the the largest impact from the COVID-19 pandemic was in food transportation cost that were transfered to the wholesale and retail food prices, there was some increase in farm labor costs however our data suggets that those costs were increasing year over year prior to the pandemic as well. In addition, there was minimal impact on food production. As a follow-on study we propose the following: 
* Analyze the cost drivers for transportation (eg. fuel, labor)
* Look into trends leading up to the pandemic (patterns prior to the pandemic to see changes)
    * Identify trends after the pandemic, what is the new “normal”
* Analyze data for trends in spending for families 
* Impact of changing climate patterns on food production


