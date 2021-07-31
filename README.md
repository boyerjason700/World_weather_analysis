# World_weather_analysis
![WeatherPy_vacation_map](https://user-images.githubusercontent.com/74840026/127267465-3ee47ef1-b432-49bb-8b2d-145f8470c574.PNG)

# Overview
Using multiple API sources, create an app that allows users to filter through random locations based on their temperature range choices.  

## Process
### CitiPy and OpenWeather API
With a random list of 2000 latitudes and longitudes, we used citipy to locate the nearest city and then looped through the OpenWeather API to gather weather data about each city and formatted into a DataFrame.

![citipy_openweather_df](https://user-images.githubusercontent.com/74840026/127587709-898ebb4f-69d5-4e21-854d-b875cb8f98a2.PNG)

### Google API 
After cleaning the DataFrame of any null values, we ask the user to input their desired temperature min and max values and then using the .loc method, we created a new DataFrame to include cities that fell in the users temperature range.  Using Gooles 'nearbysearch' endpoint API, we inserted a hotel from each city in our DataFrame and  
# Results

