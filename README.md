# webhook implementation in Python

simple webhook implementation that gets Dialogflow classification JSON and returns a fulfillment response.


# What does the service do?
It's a weather information fulfillment service that uses [Yahoo! Weather API](https://developer.yahoo.com/weather/).

The services takes the `geo-city` parameter from the action, performs geolocation for the city and requests weather information from Yahoo! Weather public API.
