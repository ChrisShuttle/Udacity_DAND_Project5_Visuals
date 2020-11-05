# Exploration of the Ford-go bike share system for February 2019
## by Christine Shuttleworth


## Dataset

The data set includes information about approximately 180 000 individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The data comprises all data points for February 2019. Duration of the trips, start time and location information of the trip and user information of the riders are included in the data set. The data was clean and some data points of riders age, which were impossible were removed. The data contains many outliers, which were incorporated into the analysis.


## Full Analysis:

Univariate Analysis:

- Distribution of trip duration and trip distance (i.e. distance between the start and end station)
- List of most popular bike share stations and their location
- Countplots of categorical variables: 
    - user gender,
    - user age, 
    - user type,
    - if the user completed the whole trip with the bike share system
    - Subdivided location of start and end station of the trip into four quardrant over San Francisco Bay: NW, SW, NE, SE
    - Added categorical variable of start and end quadrant of the trip NESW, NWSW, etc.
    - Day of the week
    - Hour of the day

Bivariate Exploration:

- Correlation and scatter plot between trip length and duration
- Average min speed of trips
- Relationship between:
    - Duration and member gender
    - Duration and user age (using age group categories for this comparison)
    - Duration and customer type
    - Duration and start and end quartile
    - Distance and start and end quartile
    - Duration and start quartile
    - Distance and start quartile
    - Duration and day of the week
    - Round trips, duration and day of the week
    - Duration and trip start hour
    - Investigation of bike use for round trips 
    - Duration and bike share for all trip
- Interaction between categorical variables: customer type, weekday, trip start hour, bike share for all trip, user age, start point quadrant
    
    Multivariate Exploration:
    
    Relationship between:
        - Duration, day of week and trip start hour
        - Duration, weekday and customer type
        - Duration, trip start hour and customer type
        - Duration and distance, weekday and start point quadrant
        - Duration and distance, weekday and start and end quadrant
        - Regression between duration and distance for all start and end quadrants
        - Duration and distance, weekday and age group

## Key Insights for Presentation

Not many of the subgroups based on the variables investigated, showed pratical differences in mean bike ride duration, e.g. gender, age. There were three noticable subgroups and two areas of interest for further research:

1. Subscribers and as you go customers showed a noticable difference in mean trip duration. 
2. Trip duration and bike hire behaviour also varied with rides taken on weekdays and weekends
3. Trips starting on different times of the day depending on the day of the week also varied

Two areas of further research are:

1. Geographical analysis: There was some trend that showed that trips starting and ending in different areas of San Francisco Bay, varied in trip duration. This could be investigated further, looking at the individual station locations.
2. Roundtrips, i.e. trips that start and end at the same station show two different user groups. One user group, rides the bike on average around 30 min before returning the bike and another rides the bike for only up to 2 min before returning the bike. This warrants further research to find out what motivates the second group and if there is a problem with the bicycle.
