# Australia-Rain-Falls

## Dataset:
The name of the dataset is Rain in Australia, we got it from the Kaggle datasets website. This dataset contains 145460 rows and 23 columns.

## Link to Dataset:
https://www.kaggle.com/jsphyg/weather-dataset-rattle-package

Source of Dataset: Kaggle.com

## Dataset description:
The dataset is about the 10 years of daily weather observations from many different locations throughout Australia. The data was collected to predict the next rain and its target is the rain-tomorrow variable. The statistical descriptions of variables that we are going to use are: 

   1. Location: Because there are about 49 unique locations and the most common one is Canberra with an occurrence of 2%. Location is the common name of a weather station.
   2. MaxTemp: Maximum temperature in degrees celsius. The total count for MaxTemp is 144199 and its mean value is about 23.22 with a standard deviation of 7.1. Its min value is -4.8 and its max value is 48.1.
   3. MinTemp: The minimum temperature is in degrees celsius. The total count for min_temp is 143975 and its mean value is about 12.19 with a standard deviation of 6.4. Its min value is -8.5 and max value is 33.9.
   4. Rainfall: Amount of rainfall recorded for the day in millimeters(mm). The total count for rainfall is 142199 and its mean value is about 2.36 with a standard deviation of 8.5. Its min value is 0 and max value is 371

There are many other variables other than the mentioned above which are following: Evaporation, Sunshine, WindGustDir, WindGustSpeed, WindDir9am, WindDir3pm, WindSpeed9am, WindSpeed3pm, Humidity9am, Humidity3pm, Pressure9am, Pressure3pm, Cloud9am, Cloud3pm, Temp9am, Temp3pm, RainToday and RainTomorrow. We are not planning to use any of these variables but if we have to show better visualization and it is possible with that variable then we will try to utilize it too.


## Target audience:
The targeted audience for our projected visualization is going to be all the people living in Australia, people going to travel to Australia, and the Australian cricket board(ACB) and its related affiliations. They may be interested in predicting tomorrow’s weather forecast so they can plan their game day and make Australian people aware of the rains in terms of travel trips.

## Questions:
1. What is the amount of rainfall recorded in this location?
2. What was the temperature recorded during the rainfall?
3. What was the recorded temperature after the rainfall?
4. What was the maximum temperature recorded in this particular location?
5. Which location has the most rainfall?

These are some of the questions that the audience might be curious about our data that we will try to answer through visualization.

## Design:

 We are thinking about making a scatter plot graph that will show different temperature values at a certain time. We will also show a visualization of a bar graph that shows which variables are important from our dataset that can help predict rain_tomorrow. We are also planning to use another bar graph to show the relationship between location and the mean value of minimum temperature, and another two more the same graph but instead it will visualize maximum temperature and amount of rainfall. All this relationship will be a good implementation for the visualization that we are planning to do.
 
 ## Visualization format:

The format of our visualizing is going to be .ipynb which is jupyter notebook format.

## Data variables:

Location, MinTemp, MaxTemp, and Rainfall are the variables we are planning to use. Three of the variables are numerical which are MinTemp, MaxTemp, and Rainfall.

## Data variables & visual patterns:

Axes, size, color, and shape are the visual patterns that will be used to map data variables. In Axes - MinTemp, MaxTemp and amount of rainfall will be used. While in Size - Bar graph height is going to be based on min, max temp, and amount of rainfall. In Color - to show the difference between two variables and finally in Shape - circle to show scatter plots points based on data values

