# Foodborne Illness
![CDC Logo](./images/st,small,507x507-pad,600x600,f8f8f8.u3.jpg)
![ERS Logo](./images/USDA Economic Research Service.jpg)

## Table Of Contents
* [Summary](#Summary)
* [Motivation](#Motivation)
* [Analytical Approach](#Analytical-Approach)
* [Tools Used](#Tools-Used)
* [Visualizations](#Visualizations)
* [Link to Tableau Dashboard](#Link-to-Tableau-Dashboard)
* [Sources](#Sources)

## Summary
Foodborne illness is a serious but manageable problem in the United States.
This project will be an exploration of the extent, causes and effects of
foodborne illness. Data from the United States Department of Agriculture,
Economic Research Service and the Centers for Disease Control will be analyzed
to explore the effects of foodborne illness on people, the costs associated
with illnesses and hospitalizations. The project will also consider the
distribution of illnesses across the United States and possible sources of
contamination.

## Motivation
I have chosen foodborne illness as the subject for my capstone project. I have
worked in the food manufacturing industry in the past and that experience has
brought about a passion for the subject as well as knowledge I can use to bring
to light the seriousness of this issue. There are a system of programs and
safeguards in place at every step from the farm to the table, but foodborne
illness still occurs. I plan to explore possible reasons for that.

## Analytical Approach
I pulled a dataset on reported cases of foodborne illness from 1998 to 2015 from the CDC.
This dataset included the number of illnesses, hospitalizations and deaths associated
with foodborne illness. The dataset also contained information on causative agents,
state where the illness occurred, location where the food was prepared and the food vehicle
associated with the illnesses that allowed me to filter the illnesses and group them
by these factors. I also pulled a dataset from the USDA ERS that described estimated
monetary costs of foodborne illness. The cost estimates were due to visits to physicians, hospitals, emergency rooms, etc. and also included cost estimates of lost productivity, chronic conditions resulting from the illnesses and premature death.
My analysis of the data centered on three questions:
- What effect does foodborne illness have on the people of the United States?
- What are monetary costs associated with foodborne illness?
- What are possible sources of contamination that can be better controlled to make food safer for consumption?

## Tools Used
- Excel - Original format of data, used for some EDA
- Python - EDA, building dataframes, analysis and visualizations
- Tableau - Visualization dashboard
- Atom - Text editor used to write the ReadMe file
- Git - Used for version control

## Visualizations

![Number of Illnesses Line](./images/no_of_reported_foodborne_illnesses_1998_2015.png)

![Number of Hospitalizations Line](./images/no_of_reported_hospitalizations_foodborne_illness_1998_2015.png)

![Number of Deaths](./images/no_of_deaths_reported_foodborne_illness_1998_2015.png)

## Link to Tableau dashboard

## Sources
https://data.world/cdc/foodborne-outbreak-database/workspace/file?filename=FoodData.xlsx
https://www.ers.usda.gov/data-products/cost-estimates-of-foodborne-illnesses.aspx
