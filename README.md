# world-weather-analysis

## Overview and Summary

The purpose of this project is to provide a tool for planning vacation travel based on the weather preferences of the user.  The tool uses APIs for OpenWeather as well as Google in order to accomplish this task.  CityPy is used to generate a list of cities and then google places API calls are made to gather information about the cities.  City information is then run through the OpenWeather API to request weather information for those cities.  The end-user is then able to input a desired temperature range for a vacation and receive options for trip planning.  The final tool in the Vacation_Itinerary folder then allows a trip to be planned with driving directions as called from Google's API for gmaps directions.