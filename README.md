# World_Weather_Analysis
### Overview
This analysis looks at different weather patterns around the global and offers insights to travelers who want to book a trip. There are three folders here that offer different levels of analysis: weather database, vacation search, and vacation itinerary.

---
### Weather Database
This folder uses Open Weather Map API to pull weather information on over 720 different cities around the world. That information consists of:

Maximum Temperature
Cloudiness
Wind Speed
Humidity
Current Weather Description
These different categories of information make it easy for travelers to choose exactly what they are looking for in a travel destination.

---
### Vacation Search
This folder takes the information gained in the weather database and uses Google Maps API to plot different travel destinations with a hotel at each location. For example, the image below shows the locations of all the places in the database that have an daily maximum temperature between 75 and 95 degrees farinheit.
<img width="1018" alt="Screen Shot 2022-04-12 at 2 40 39 PM" src="https://user-images.githubusercontent.com/98849217/163663608-6e194fbd-ed9e-4133-bd5e-514771112aae.png">

---
### Vacation Itinerary
This folder takes the search information from the search folder and uses Google Maps directions API to create a vacation itinerary. For example, the image below shows a 4 stop itinerary
<img width="1028" alt="WeatherPy_travel_mao" src="https://user-images.githubusercontent.com/98849217/163663694-07e70f1a-d571-4bd7-b07b-8376b1c8f7cd.png">


---
Also, as with the vacation search folder, there is a hotel at each location.

---
<img width="1053" alt="WeatherPy_travel-mapmarker" src="https://user-images.githubusercontent.com/98849217/163663686-2e5ce10a-b87e-4efc-b196-b0d3913fca3f.png">
