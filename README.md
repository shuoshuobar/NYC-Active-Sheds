# City Council Cracks Down on Sidewalk Sheds
 
## Goal:
Analyze and visualize the distribution of sidewalk sheds across New York City and examine whether recent policy changes by the City Council are reducing their presence.

## Findings:
1. This week, the Department of Buildings reported 8,547 active sheds, as the City Council passed new rules limiting how long sheds remain standing to reclaim public space.
2. Active sidewalk sheds drop 17% in a year.
3. Manhattan dotted the city landscape with the most sidewalk sheds. And the city’s current oldest shed — still standing on Second Avenue in Manhattan — has been in place for 15 years.

## Process of Data Collection:
1. Active sidewalk shed data up to date was downloaded from the NYC Department of Buildings: https://www.nyc.gov/assets/buildings/html/sidewalk-shed-map.html
2. Active shed counts from 2023 and 2024 were based on data from previous analyses.
3. Socio and demographic data at the census tract level was retrieved from the 2021 American Community Survey.

## Process of Data Analysis:
1. Geocoded active shed coordinates to identify their associated census tracts using the U.S. Census Geocoder API.
2. Merged geocoded shed data with socio and demographic indicators such as population, income, housing and race.
3. Compared total shed counts over time to evaluate policy impact.

## Skills/Approaches in Use:
1. R - tidycensus: Socio and demographic data acquisition
2. Python - Pandas: data cleaning, navigating and merging data
3. Python - Matplotlib/Plotly: Interactive map creation
4. Illustrator: Responsive chart editing and exporting with ai2html
5. HTML: Webpage design

## Limitation/Looking Ahead:
1. Thinking about how to automatically track the number of active sidewalk sheds along with time
