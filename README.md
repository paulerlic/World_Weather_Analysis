# World Weather Analysis Overview
Help develop hypothetical PlanMyTrip app. Retrieve weather data, have beta testers use input statements to filter data for weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary, and then using the Google Maps Directions API, create a travel route between the four cities as well as a marker layer map with city, hotel, and weather information.

* 1 
In this challenge we are creating an app to help people plan their trips, it is called the PlanMyTrip app. We will be retriving weather data via an api call to openweather.org which is an open source weather data site. First we will generate a set of 2,000 random latitudes and longitudes. Next we will retrieve the nearest cities to these points, and perform an API call with the OpenWeatherMap. We will also be pulling down the current weather description for each city. We will then use this info to create a new DataFrame containing the 'live' data.

* 2 
Next we ask the user for what kind of weather they like and based off their input (min max) we will identify travel destinations that match their input and return a map with pop up markers that contain info about what country and city the travel destination is as well as the current weather conditions and max temp. Lastly we will provide them with a hotel they could stay at while vactioning. 

* 3 
Finally we will generate a a travel itinerary for the user, this will be done through the google directions API. Our travel itenirary shows the route between four cities chosen from the customer’s possible travel destinations. Along the route we will display a pop up travel marker for each city on the trip.  