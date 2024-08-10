### Bike Share Project
### Date created
Project created on: February 25, 2023
README file created on: Aug 9, 2024

### Suggested Requirements
- Python 3.11 or above
- pandas, numpy, and time libraries
  
### Files used
This project imports data from the .csv files "chicago.csv", "new_york_city.csv", and "washington.csv" to gather information about a bike share program. 
The chicago.csv and the new_york_city.csv will include details about the users including gender, birth date, and type. The will also include data about the bie rentals including:
  rental start hour and day, rental start location and end location.
### Description
The data is processed through multiple definitions defined in this file, inlcuding:
  1. get_filters() will ask the user to specify a city, month, and day to analyze. It will then print the city, month, and day that the user requested.
  2. load_data() will load the data for the specified city and filters by month and day. It then will return a Pandas DataFrame containing city data filtered by month and day.
  3. time_stats() wakes the DataFrame from the definiation just defined and will display the statistics on teh more frequesnt times of travel. This includes the most popular month, day, and start hour.
  4. station_stats() will load the df from load_data and will display statistics on the most popular stations and trip. This includes the most popular starting station, end station, and the most commonly used combination of stations.
  5. trip_duration_stats() takes in df and displays statistics on the total and average trip duration. This includes the total travel time in minutes and in seconds.
  6. user_stats() takes teh df and displays statistics on bikeshare users. THis includes the user type count, the gender count as well as the most common, earliest, and most recent birth year.
  7. main() runs all the previosly mentioned definitions.
TO use this project, you must have away to run Python code and will have to use the .csv's that I given to use from Udacity. 
