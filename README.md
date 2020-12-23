# Information Visualization - D3

Hosted link: https://information-visualization.netlify.app/

Data: https://data.gov.in/resources/stateut-wise-funds-released-and-utilised-under-smart-cities-mission-2015-16-2019-20

## Name of Project

Fund Released under Smart Cities Mission during 2015-16 to 2019-20

## About Data

The data is about funds released by the central government for the smart cities mission. The Ministry of Housing and Urban Affairs (MoHUA) facilitates and assists States/Union Territories (UTs), through ‘smart cities mission’ to improve urban infrastructure and enhance the quality of life in cities and towns covered under the mission. 

Smart cities mission was launched with a total central government outlay of Rs. 48,000 crore for developing 100 cities as smart cities.

The total fund of Rs. 18,614.1 crore was released under smart cities mission in India during 2015-16 to 2019-20; out of which Rs. 1,469.2, 4,492.5, 4,499.5, 5,856.8 and 2,296.1 crore was released from 2015-16 to 2019-20 respectively. The top 5 States/UTs with respect to central funds released under smart cities mission during 2015-16 to 2019-20 were Tamil Nadu, Madhya Pradesh, Maharashtra, Gujarat, and Uttar Pradesh.

## Problem Statement

We mainly address three issues in our visualization,

- Visualizing of total funds and further displaying Used Funds and Available Funds for each state (stacked bar chart - states vs funds)

- Visualizing of total funds and further displaying Used Funds and Available Funds for each city of a state (stacked bar chart - funds vs cities)

- Depicting the percentage of ‘funds released in a particular year’ in total funds for each state from the year 2015 to 2020 (pie chart)


## Visualization selection for Problems

### Stacked bar graph - States vs Funds & Funds vs Cities

We wanted to signify the numerical values of total funds and values of used funds and available funds which can be best signify by visual channel ‘position’. For this, we use a stacked bar graph where the length of the bar represents total funds, and parts of this total fund (available and used funds) denoted by stacking them over each other.

### Pie Chart - Funded Years vs Funds

We also want to visualize how much each year’s released fund contributes to the total fund so we have used a pie chart for this. Here the pie chart is used because it immediately and easily sells the idea of the percentage of one part in the whole. On the other hand for eg, If a bar chart or line chart is used it doesn’t immediately represent the percentage of a part in the whole, and may require annotations of percentages specifically.

## Strength and weakness of the visualization
  
### Stack bar graph
    
Strength: It gives the sense and information about how a whole amount is divided into its subcategories and what’s the relationship each part has on the total amount. It easily explains the quantitative data using positions.

Weakness :  But if there are more and more segments ( subcategories ) on the bar  then it becomes much difficult to read the each segment and sometimes the same segments are not aligned in the same line so, it  becomes difficult to compare them. 
   
### Pie chart

Strength :  It depicts and distinguishes more clearly how much each part contributes to total and we can compare roughly like “which slice contributes most” or “which slice contributes least” or “which slices can be ignored” in total etc. 

Weakness  : Since the pie chart doesn’t have any annotations it becomes difficult to  compare the group of slices of equal sizes. We can best say that  they are similarly sized but becomes hard to say that which is strictly greater. To handle this problem we used tooltips in our visualization.

