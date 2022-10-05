# World Weather Analysis

## Overview of the Project

### Overview:

In this project, we worked with a travel company called PLANMYTRIP to create a program that collects and presents data to customers. This program will return data that meets the customer's preffered travel criteria. This program will then return a list of hotels all over the world that meets this criteria, as well as present the opportunity to create their itinerary based on the hotels found.

### Purpose:

The purpose of this project is to create a program that will generate an x amount of latitudes and longitudes that will be used to find cities near those points and use the Open Weather Map API to find the weather of those cities. With these cities found, we will have the customer input their preferred weather for their vacation and return a map with markers of the cities that meet that criteria as well as a list of hotels in those cities. Finally, the program will return an itinerary that includes 4 cities that are near each other that meet the customer's criteria as well as a route they can take based on the transportation option they choose.


Results:

To test our program and ensure it is returning the correct values , we allowed the minimum temperature to be 40 degrees and the maximum temperature to be 90 degrees. With this criteria, we found a total of 578 cities the customers could visit, and after cleaning out our data, we found a total of 539 cities with hotel options that they could base their itinerary on:

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/111034667/194146733-d0834798-7dc4-4776-a32e-949edfc8a8d5.png)

To make their vacation more efficient, we chose their itinerary to have 4 cities within the same country and choose their traveling method as driving. The country they will be visiting is Argentina and the cities they will visit are:

  - Santa Fe
  - Rosario
  - Mercedes
  - Moron
  
 The Itinerary map looks as follow, where Santa Fe is the starting and ending point:
 
 ![WeatherPy_travel_map](https://user-images.githubusercontent.com/111034667/194147591-85f6facd-7c98-4683-9b96-bd3dd92c1864.png)

and the map that shows all the information of the hotels in each city is the following:

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/111034667/194147712-d794a921-5ee4-493b-8a8f-2632f2e5c499.png)

Summary:

The program runs succesfully, and the company will be able to meet the customer's criteria for their vacation. To improve the program so that it is more customizable to the customer's request, I wowuld suggest to include the same tactic we used to allow the user to input their desired minimum and maximum temperature to allow the user to input the desired continent/country they want to visit as well as input the desired transportation they want to use. An extra input they could allow customers to type in would be to include the minimum rating they will be accepting for the hotels.By allowing the customers to input their desired choices, the itinerary will be more personalized to each customer and they will be able to choose whether they want to look for more options or not. 
 
 



