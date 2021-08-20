# Foodborne Illness

## Table Of Contents
* [Summary](#Summary)
* [Motivation](#Motivation)
* [Analytical Approach](#Analytical-Approach)
* [Tools Used](#Tools-Used)
* [Analysis](#Analysis)
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
This dataset included the reported number of illnesses, hospitalizations and deaths associated
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
- Excel/CSV - Original format of data, used for some EDA
- Python - EDA, building dataframes, analysis and visualizations
- Tableau - Visualization dashboard
- Atom - Text editor used to write the ReadMe file
- Git - Used for version control

## Analysis
#### Number of Illnesses per Year
- Mean number of illnesses over this timeframe was 20,752 per year
- Change in reporting process in 2009
![Number of Illnesses Line](./images/no_of_reported_foodborne_illnesses_1998_2015.png)

#### Number of Hospitalizations per Year
- Mean number of hospitalizations over this timeframe was 816 per year
![Number of Hospitalizations Line](./images/no_of_reported_hospitalizations_foodborne_illness_1998_2015.png)

#### Number of Deaths per Year
- Mean number of deaths over this timeframe was 19 per year
![Number of Deaths](./images/no_of_deaths_reported_foodborne_illness_1998_2015.png)

#### Cost of Foodborne Illness
- Salmonella ssp. is pathogen with the highest estimated cost of $4.1 billion
- Total estimated costs associated with foodborne illness for the top 15 foodborne pathogens in 2018 is $17.6 billion
![Top 15 Pathogens Cost](./images/cost_top15pathogens_2018.png)

#### Foodborne Illness per Capita by State
- States with a higher population have a higher foodborne illness per capita rate
![Top 10 States](./images/top10_states_by_illnessespercapita.png)

#### Foodborne Illnesses by Causative agents
- Highest occurring causative agent is Norovirus
![Top 10 Causative Agents](./images/top10_causative_agents_by_no_illnesses.png)

#### Foodborne Illnesses by Location of Preparation
- Highest occurring preparation location is a restaurant
![Top 10 Location of Preparation](./images/top10_location_preparation_by_no_illnesses.png)

#### Foodborne Illnesses by Food vehicle
Highest occurring food vehicle is multiple foods
![Top 10 Food Vehicle](./images/top10_food_vehicles_by_no_illnesses.png)

## Link to Tableau Dashboard
Click the following link to see the interactive dashboard on Tableau Public:
https://public.tableau.com/app/profile/ryan.butler1292/viz/FoodborneIllnessDashboard_16293827026280/Dashboard1?publish=yes

## Sources

CDC Dataset:
https://data.world/cdc/foodborne-outbreak-database/workspace/file?filename=FoodData.xlsx

USDA ERS Dataset:
https://www.ers.usda.gov/data-products/cost-estimates-of-foodborne-illnesses.aspx

Annual Cost of Illness and Quality-Adjusted Life Year Losses in
the United States Due to 14 Foodborne Pathogens:
https://pubag.nal.usda.gov/pubag/downloadPDF.xhtml?id=59522&content=PDF
