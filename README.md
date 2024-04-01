<img src="https://capsule-render.vercel.app/api?type=waving&color=BDBDC8&height=150&section=header" />
### Instructions
This activity is broken down into two deliverables, WeatherPy and VacationPy.

### Part 1: WeatherPy
In this deliverable, you'll create a Python script to visualize the weather of over 500 cities of varying distances from the equator. You'll use the citipy Python libraryLinks to an external site., the OpenWeatherMap APILinks to an external site., and your problem-solving skills to create a representative model of weather across cities.

For this part, you'll use the WeatherPy.ipynb Jupyter notebook provided in the starter code ZIP file. The starter code will guide you through the process of using your Python coding skills to develop a solution to address the required functionalities.

To get started, the code required to generate random geographic coordinates and the nearest city to each latitude and longitude combination is provided.

## Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
To fulfill the first requirement, you'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:

  - Latitude vs. Temperature
  - Latitude vs. Humidity
  - Latitude vs. Cloudiness
  - Latitude vs. Wind Speed

## Requirement 2: Compute Linear Regression for Each Relationship
To fulfill the second requirement, compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). You may find it helpful to define a function in order to create the linear regression plots.

  -  Northern Hemisphere: Temperature vs. Latitude
     ![image](https://github.com/tarsian/python-api-challenge/assets/24801648/d8746170-f162-42dc-8b4f-55dc507e0910)
    
  -  Southern Hemisphere: Temperature vs. Latitude
     ![image](https://github.com/tarsian/python-api-challenge/assets/24801648/28d480f1-8a89-4a8a-a6da-730fbda23038)
          
  -  Northern Hemisphere: Humidity vs. Latitude
     ![image](https://github.com/tarsian/python-api-challenge/assets/24801648/95b84f9f-5c50-4d7a-97f2-b8dba092396c)

  -  Southern Hemisphere: Humidity vs. Latitude
     ![image](https://github.com/tarsian/python-api-challenge/assets/24801648/93af5559-81da-495a-9883-007f29a0bf59)

  -  Northern Hemisphere: Cloudiness vs. Latitude
     ![image](https://github.com/tarsian/python-api-challenge/assets/24801648/3c1b0fb2-6b65-48d4-be71-d5c4f5569707)

  -  Southern Hemisphere: Cloudiness vs. Latitude
     ![image](https://github.com/tarsian/python-api-challenge/assets/24801648/1c5c24f3-8c1d-41d5-9536-4140c3b1ff4f)

  -  Northern Hemisphere: Wind Speed vs. Latitude
     ![image](https://github.com/tarsian/python-api-challenge/assets/24801648/4d6ae0a7-9de0-413f-a0a9-5a633ae47bc5)

  -  Southern Hemisphere: Wind Speed vs. Latitude
     ![image](https://github.com/tarsian/python-api-challenge/assets/24801648/70a657d1-3ffb-4b43-916d-f2d87637b9b8)

### Part 2: VacationPy
In this deliverable, you'll use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.

The code needed to import the required libraries and load the CSV file with the weather and coordinates data for each city created in Part 1 is provided to help you get started.

Your main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.

To succeed on this deliverable of the assignment, open the VacationPy.ipynb starter code and complete the following steps:

  - Create a map that displays a point for every city in the city_data_df DataFrame. The size of the point should be the humidity in each city.
  - Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:

    - A max temperature lower than 27 degrees but higher than 21
    - Wind speed less than 4.5 m/s
    - Zero cloudiness
      
  - Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
  - For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
  - Add the hotel name and the country as additional information in the hover message for each city on the map.


<img src="https://capsule-render.vercel.app/api?type=waving&color=BDBDC8&height=150&section=footer" />
