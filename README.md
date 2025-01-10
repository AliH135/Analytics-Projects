# My Projects

| Project Name                         | About                                                                 | Tools Used                             | Link                                                   |
|--------------------------------------|-----------------------------------------------------------------------|----------------------------------------|--------------------------------------------------------|
| Airline Customer Ratings Visualization | Created a dashboard in Tableau to visualize customer ratings for an Airline company | Tableau (Visualizations, Parameters, Calculations) | [Here](https://github.com/AliH135/Analytics-Projects/tree/main/Airline%20Ratings%20Visualization)     |
| Stocks Portfolio Optimization        | Generated optimal portfolios for a combination of 5 stocks, displayed as an Efficient Frontier | Python, Yahoo Finance                 | [Here](https://github.com/AliH135/Analytics-Projects/tree/main/Stocks%20Portfolio%20Optimization)      |
| Supermarket Analysis - SQL           | Used SQL queries on the database of a supermarket to address various business questions | SQL                                    | [Here](https://github.com/AliH135/Analytics-Projects/tree/main/Supermarket%20Analysis%20SQL) |


## Airline Customer Reviews Visualization

In this project, I used Tableau to create a visualization dashboard of customer ratings data for an airline company. The dashboard is accessible by clicking on the project title above.

The dashboard allows the user to get a quick idea of the average customer ratings across a variety of important dimensions. A world map allows viewing how the ratings vary across regions. In addition, other charts allow analyzing the ratings over time and by aircraft type & seat type.

The dynamic nature of the dashboard allows an easy visualization of how all metrics change by selecting any specific criteria. Few screenshots are given below.

- The user can select from a host of filters given in the pane on the right, and the dashboard updates accordingly:

![Airlines Ratings Dashboard](https://github.com/AliH135/Analytics-Projects/blob/main/Airline%20Ratings%20Visualization/Airline%201.png)

- The user can also select any criteria from within the visualizations, and the dashboard updates accordingly. For example, selecting "United States" on the map:

![Airlines Ratings Dashboard](https://github.com/AliH135/Analytics-Projects/blob/main/Airline%20Ratings%20Visualization/Airline%202.png)

## Stocks Portfolio Optimization

In this project, I used Python to perform portfolio optimization on a portfolio of 5 stocks. I selected the stocks of the companies listed below and extracted their historical share price movement data from the Yahoo Finance library in Python from Jan 2023 to June 2024.

- Apple Inc.
- Tesla Inc.
- Microsoft Corporation
- Amazon.com Inc.
- Alphabet Inc.

![Chart 1](https://github.com/AliH135/Analytics-Projects/blob/main/Stocks%20Portfolio%20Optimization/2.png)

I generated 10,000 random portfolios and plotted them to visualize the Expected Return vs. Volatility (risk) of the random portfolios. I also generated the Efficient Frontier, representing the portfolios with the lowest level of risk for a given level of expected return. 

Lastly, the optimal portfolio allocation was also calculated for a target return of 25%. Optimal allocations can be calculated similarly for different target return values and other selections of companies.

![Chart 2](https://github.com/AliH135/Analytics-Projects/blob/main/Stocks%20Portfolio%20Optimization/3.png)

## Supermarket Analysis - SQL

In this project, done as part of my Master's coursework, I used SQL queries on the database of a supermarket to answer different business questions.

Some of the questions addressed, the relevant SQL queries, and their outputs are given in pictures below.

1) Total Quantity sold per product**, ordered by the highest quantity
   ![Query 1](https://github.com/AliH135/Analytics-Projects/blob/main/Supermarket%20Analysis%20SQL/Query%201.png)
  
2) Getting a list of all items sold on a specific date (e.g. 2021-09-20 in this case) along with their quantity sold and total amount
   ![Query 2](https://github.com/AliH135/Analytics-Projects/blob/main/Supermarket%20Analysis%20SQL/Query%202.png)
   
3) Getting a list of products which had no sales
   ![Query 3](https://github.com/AliH135/Analytics-Projects/blob/main/Supermarket%20Analysis%20SQL/Query%203.png)
   
4) Getting the count of distinct products within each category
   ![Query 4](https://github.com/AliH135/Analytics-Projects/blob/main/Supermarket%20Analysis%20SQL/Query%204.png)
   
5) Getting the total sales amount for each category
   ![Query 5](https://github.com/AliH135/Analytics-Projects/blob/main/Supermarket%20Analysis%20SQL/Query%205.png)

