# Dataset Overview
 
___Who eats and who supplies the food we grow in Africa?___
 
The project focuses on finding insights, patterns and trends through visualizations on food Production and Supply data in Africa.
 
**Do all African countries have equal access to food items as regards to food supply?**

**Do all African countries equally produce the food we eat in Africa?**

**Were there food Surpluses which eventually led to food shortages in Africa?**
 
In this project, we will be analyzing two different datasets namely food production and food supply datasets. These two datasets have information about food production and food supply in 45 African countries between (2004 - 2013) respectively and it was sourced from [FAO](https://www.fao.org/faostat/en/#data) (Food and Agriculture Organization of United Nations)'s website.
 
Later on in the project, we will carry out a hypothesis testing where we compared the growth of certain food produce with the population growth of the African countries.
 
The population dataset that we will use is the population data gotten from the [World Bank Open Data Portal](https://data.worldbank.org/indicator/SP.POP.TOTL). The data holds the population data of 267 countries from 1960 to 2021 and we will extract the population data for the African countries we were working with in the Food Production and Supply dataset. With this data, we will be able to carry out some hypothesis testing.
 
# Metadata
 
## Food Production Data
 
The first dataset that we wil analyze is the Food Production dataset. This dataset has 23110 rows and four columns. The columns include:
 
 - Country: The name of the African Country
 
 - Item: The particular food item produced
 
 - Year: The year in which a particular food item was produced
 
 - Value: The measured value of the produced food item in Kiloton
 
## Food Supply Data
 
The second dataset that we will analyze is the Food Supply dataset. This dataset has 450 rows and three columns. The columns include:
 
 - Country: The name of the country
 
 - Year: The particular year a food item was supplied
 
 - Value: The measured value of the food item in kcal/person/day
 
## Population Data
 
The third dataset which we will also analyze and then use for our hypothesis testing would be the World Bank Population Data. We will use this dataset together with extracted food production data of certain food items, and we will carry out a hypothesis testing stating that the production of these food items increased with increase in population. This dataset initially consists of 266 rows and 67 columns and after extracting the data we needed for the African countries we were working with, we finally had 40 rows and 11 columns. The columns include:
 
 - Country Name: The name of the African Country
 
 - 2004: the population of the country in 2004
 
 - 2005: the population of the country in 2005
 
 - 2006: the population of the country in 2006
 
 - 2007: the population of the country in 2007
 
 - 2008: the population of the country in 2008
 
 - 2009: the population of the country in 2009
 
 - 2010: the population of the country in 2010
 
 - 2011: the population of the country in 2011
 
 - 2012: the population of the country in 2012
 
 - 2013: the population of the country in 2013
 
# Summary of Findings:
 
 - Food production in Africa increased as the year increased.
  
 - Nigeria 1628030 (kt), Egypt 877498 (kt), and South Africa 597592 (kt) were the three top food producing countries in Africa between 2004 and 2/13. Majority of other countries did not produce even up to half of what what Nigeria produced.
 
  - The most produced food item were Cassava, Sugar Cane, Maize and products, Yam, Vegetables, and Milk (excluding butter).
 
 - The least produced food items were Cloves, Pepper, Molluscs, Fish, Liver oil, and aquatic animals.
 
 - Food Supply in Africa increased as the year increased.
 
 - Egypt, Tunisia and Morroco had the largest food supplies between 2004 and 2013. This proves the country that being largest Foo producer doesn't equate to having this highest food supply.
 
 - In detection of an outlier country in 2012, Egypt was an outlier country, having substantially bigger supply of food accessible for consumption.
 
 - The result of our hypothesis testing states there's a strong linear correlation between rice and cassava production with the increase in African population.
 
 - Nigeria was the top Cassava and products producing country, producing an average of 45.288 (kt) of Cassava. Ghana, Angola and Mozambique were other Cassava producing countries but didn't produce half of what Nigeria produced.
 
 - The top beverage producing country was Nigeria followed by Burkina Faso and Uganda but who weren't producing half of what Nigeria produced.

 - The highest food producing countries had the highest food surpluses which weren't utilized leading to food shortages.
