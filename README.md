# PyBer_Analysis

##Overview

The purpose of this analysis is to create a summary DataFrame of the ride-sharing data by city type which was supplied through PyBer's records of 2019. Using Pandas and Matplotlib, I was able to effectively create a multiple-line graph that shows the total weekly fares for each city type. Finally, I used the summary dataframe and multi-line graph to visualize the differences between the three different city types that PyBer services. I lastly included three business recommendations for the decsion-makers at PyBer headquarters.


##Results

When looking at the data provided we can see in the summary_df of the company data that urban cities provide the predominant businesss sector for PyBer from a perspective of number of rides: 1,625 total rides as compared to 625 for suburban cities, and 125 for rural cities. Additionally the total fares for cities were over double the amount for suburban cities, $39,854.38 to $19,356.33, while Rural cities totalled $4,327.93 for ttoal fares.  
However the number of drivers (2,405) compared to total rides (1,625) made urban cities the only city type with more drivers than rides given. Suburban and Rural cities had 490 and 78 driveers respectively. Average fare per ride and average fare per driver were lowest in urban areas ($24.53, and $16.57) and highest in rural areas ($34.62, and $55.49). Suburban areas had $30.97, and $39.50 in those categories. This shows that distance was most likely highest in rural trips making them theoretically more profitable. 
This data can be backed up looking at our visualization and seeing the line representing 'urban' areas stays signifcantly higher throughout the graphed time frame. One outlier to keep in mind is that the month of May might see a decline in the number of rides given based upon the data we haev access to.
It's also worth noting that in Suburban and Rural areas but not in Urban areas there seems to be somewhat of a decline in total fares after the holidays of Valentine's Day and St. Patrick's Day (Mid February and Mid March). 
![Screenshot (92)](https://user-images.githubusercontent.com/93295751/144758683-d7ce962e-9696-4fa7-9d13-61b6cb9c6888.png)
![PyBer_fare_summary](https://user-images.githubusercontent.com/93295751/144758695-34df3d7f-0bca-4e6e-b13b-550dfc14a5f8.png)

##Summary

Based upon the results of our analysis I would be inclined to recommend a few things for the decision makers at PyBer. My first recommendation would be to look into adding more drivers in rural and suburban areas. As the higher trips per driver, and higher trips per ride; coupled with a much lower number of drivers would seem to suggest there is untapped potential in these markets. My second recommedation would be to try to get more of the exisitng drivers in the urban areas to drive in suburban areas so that way more drivers can focus on these areas while allowing more drivers in urban areas to offer rides within that space.Another suggestion I have is to look into why around certain holidays rural and suburban areas experience a decline in rides, And perhaps offer a post holiday discount to keep ridership more steady. My laast suggestion would be to look into why the month of May seems to have a lower number of rides and if that is a factor that can be eliminated or if it is a natural course of PyBer's business. 
