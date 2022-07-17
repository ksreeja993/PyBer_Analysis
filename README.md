# PyBer_Analysis
Ride sharing Data Analysis using Matplotlib in pandas.

## Background:
Using Python skills and knowledge of Pandas, a summary DataFrame of the ride-sharing data by city type is created. Then, using Pandas and Matplotlib, a multiple-line graph that shows the total weekly fares for each city type is created. 

## Overview of the analysis:
* In this analysis, the pyber dataframe was created by merging the city data and ride data dataframes.
* Calculated the total rides for each city type, total drivers for each city type and the total amount of fares for each city.
* Using these, the average the fare for each city type and for each friver were calculated.
* With these values a new data frame was created. 
* Using groupby and pivot, the dataframe is set to the required format. 
* A new dataframe was created for dates ranging from 2019-01-01':'2019-04-29.
* The data frame is then updated to combine the data weekly.
* A chart is created to show the Fares from months January to May for each city type as follows.



## Results:

* The average fare per ride is highest in the Rural cities and lowest in Urban cities.
* The average fare per driver is highest in the rural cities and lowest in the irban cities.

![Screenshot 2022-07-16 214010](https://user-images.githubusercontent.com/105166481/179380519-12c84966-174d-4d45-a06b-0e3b5e1688a2.png)

## Summary:

From this analysis, we can say that as the demand for ride share is lower in the rural areas, the fare tends to be higher compared to the urban and the suburban areas. ![Pyber_Plot](https://user-images.githubusercontent.com/105166481/179380526-2e398564-3ee2-47f2-a0cd-a3cd59cf8fb5.png)
