# 5 Day Weather Forecast Dashboard

My motivation was to create an application where you could search a city and then in return the results would should third-party weather data via API. Why I built this project was to practice what I learned in class and apply it in a real life situation. The problem I solved was to set up a 5 day weather dashboard using third party API's, CSS, HTML, and Javascript. What I learned was how to set specific parameters based of the technical API documentation in order to get the specific data I was needing to display.


## User Story

    AS A traveler
    I WANT to see the weather outlook for multiple cities
    SO THAT I can plan a trip accordingly

## Acceptance Criteria

    GIVEN a weather dashboard with form inputs
    WHEN I search for a city
    THEN I am presented with current and future conditions for that city and that city is added to the search history
    WHEN I view current weather conditions for that city
    THEN I am presented with the city name, the date, an icon representation of weather conditions, the temperature, the humidity, the wind speed, and the UV index
    WHEN I view the UV index
    THEN I am presented with a color that indicates whether the conditions are favorable, moderate, or severe
    WHEN I view future weather conditions for that city
    THEN I am presented with a 5-day forecast that displays the date, an icon representation of weather conditions, the temperature, and the humidity
    WHEN I click on a city in the search history
    THEN I am again presented with current and future conditions for that city
    WHEN I open the weather dashboard
    THEN I am presented with the last searched city forecast 


## Visuals:
![Screenshot of loaded weather dashboard](WeatherDashboard/media/weather-dashboard-screenshot.jpg)


## Data

The application uses the following data inputs:
* Weather information is provided by the OpenWeather [OpenWeatherMap API](https://openweathermap.org/). [Documentation](https://openweathermap.org/api) 


## Build

* In HTML semantic tags have been used to aid with accessibility.
* The site is built using Bulma CSS framework.
   * The use of Bulma minimises the need for media queries. 
   * See [Bulma documentation](https://bulma.io/documentation/) for customizing the site with their provided options
* [jQuery](https://api.jquery.com/) powers the dynamic rendering of the html content based on user input
* [moment.js](https://momentjs.com/) is used to manipulate date values for historic data extraction from APIs


## Setup
Download the zipped folder or clone the repository. 
To clone the repo: https://github.com/karafaris/WeatherDashboard.git


