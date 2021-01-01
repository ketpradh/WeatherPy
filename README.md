# WeatherPy by Ketaki
This project helps a user to plan his vacation trip based on weather preferences. This is done in three steps -
- Generate a random list of latitude and longtitude using the random function and find the nearest city using the Python's **citipy module**.We then find the weather information for this dataset of cities using the **OpenWeather API** and save it in a file.
- By using the output from the first step and asking the user for his weather preferences, we list out the possible vacation destinations. Using this smaller destination list, we then commpile a nearby hotel list for the user. This Hotel information is retreived using **Google Maps Places API**.
- Finally, based on the four destinations selected by the user, a Trip Itinerary is generated using **Google Maps Directions API**. We also generate a detailed map with the marker enlisting details of the destinations.
