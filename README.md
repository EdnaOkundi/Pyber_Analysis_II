# Pyber_Analysis_II

Overview
The goal of this analysiwas to compare quantity and fares of rides in every city type: urban, suburban and rural; create a 
visualization with matplotlib library and provide recommendation for addressing any disparities among the city type. 
Using Pandas and Matplotlib, I was to create a multiple-line graph that shows the total weekly fares for each city type.

Results
In order to perform the analysis, I merged datasets using left join based on the city column and got a one dataset with all available data. 
I then created summary dataframe by city type. It has revealed first insight - there are few drivers and rides in rural 
cities with higher average fares compare to urban cities:

There are 13 times more rides in urban cities compare to rural cities (1,625 vs 125 rides)
The average fare per ride is 1.4 times less and average fare per driver is 3.4 times less in urban cities compare to 
rural cities ($24.53 vs $34.62 and $16.57 vs $55.49). The total fares in urban cities is 9 times higher than in rural cities and 2 times 
higher than suburban cities. ($39,854.38 vs $4,327.93).

Summary
While the urban cities rides make more revenue, the rural cities rides are more profitable. The focus would be on 
improving profitability of urban cities rides.I would recommend to reduce number of drivers in urban cities. 
There are 2,405 drivers which made only 1,625 rides. That means not every driver has done at least one ride. 
Reducing number of drivers will increase average fare per driver, as now it is 3.4 times less compare to rural cities.

If the fare for 1 minute of ride in rural cities is significantly higher than fare in urban cities, 
ride fare may be increased for urban city types. 
It helps to increase average fare per ride in urban cities and get even more revenue.