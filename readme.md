# Ford-GoBike-Data-Exploration-and-Visualization-of-insights-Feb2019
## 1. Overview 
This project demonstrate the importance of data visualization techniques in the data analysis process which is as project part of the Udacity Data Analysis Nanodegree course.

In the followong part, i will use Python visualization libraries to wrangle and explore a Feb-2019-fordgobike-tripdata datafile, starting from plots of single variables and building up to plots of multiple variables.

In the following second part of the project, i will produce a short presentation that illustrates interesting properties, trends, and relationships that I discovered in the selected dataset.

## 2. Dataset Overview 
The Dataset consists of anonymized information regarding all bike trips during Feb-2019, including its timing and geolocation of the start and end of each trip

## 3. Data Cleaning and Wrangling 
I've created several start_variables with different time-resolution (start_hour_of_day, start_time_weekday, month, day). Plus corrected some data_types.

## 4. Summary of Findings of Data Exploration
* It is clear that each of these graphs support the hypothesis that customers are more like recreational users and subcribers tend to use them to go to work or school.

* Customers hire especially in the weekend.

* The bike trip duration of Customers is about the double of Subscribers.

* A significant higher trip duration during weekend days by Customers.

* Slightly higher trip duration during weekend days by subscribers.

* The bike trips by Customers take long in "The Embarcadero at Sansome St"

## 5. Key Insights for Presentation Slides
* In the presentation I focus on the relationship between bikes ride count and trip duration and user_types.

* I started with a the distribution of trip count between the customers and subscribers.

* Then, the distribution of biketrip duration for each user type.

* Finally, i showed a clustered barplot of trip duration by both (start day of week) and top 10 (end station name). This illustrates that also the location of the end destination station is very important variable to explaine bike usage and trip duration.
