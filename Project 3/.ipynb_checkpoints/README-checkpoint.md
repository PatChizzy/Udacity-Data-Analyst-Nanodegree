# Diamonds Data Exploration

## Dataset

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.
The data, which was made up of 183412 rows and 16 columns was gotten fron [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv).


## Summary of Findings

In the exploration, i found that the data contained information for bike riders over the age of 100, which is nearly impossible to have such an age group riding bikes.
The data features do not have a high correlation, which was a limitation for further investigation.

Some feature extraction was performed in order to generate timeseries features that could aid in the generation of more insight.

I also found that The data records spans only 
- one year (2019)
- one month (February)
- one season of the year (winter)


## Key Insights for Presentation

For the presentation, I mapped out some questions that piqued my interest and used that as a guide for my anaysis.
Some of the questions include:

1. Distribution of age grade
2. Most busy part of day  
3. Most busy day of the week
4. Most popular station by longest ride duration
5. Gender by membership type
6. Age grade with membership type
7. Age grade by prefered hour for rides
8. Most busy hour of the day
9. Average ride per day
10. Ratio of ride sharing

Afterwards, I began with univariate anaylsis and subtlely delved into more complex analysis.
As a timeseries data with majorly categorical features, i used lineplots and barplots to show my analysis.

With the analysis on the different age groups, i uncovered that
- Vast population of users is made up of young adults and adults
- Young adult, adults and elderly like to ride into the night, whereas older adults and senior citizens like to ride before midnight

For general anaysis, i uncovered
- Most rides occur in the morning and evenings
- Most rides occur on saturdays and sundays with the least on tuesdays
- The most popular station is located at Powell St BART Station (Market St at 4th St)
- There are more male riders than female of which nost are registered customers
- The most busy hour of day is usually midnight
- For rides recorded (in february), most exceeds the average ride duration in seconds with the highest between days 15 and 18
- The longer the ride duration, the more unlikely it is a shared ride

