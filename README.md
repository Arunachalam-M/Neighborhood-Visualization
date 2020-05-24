# Neighborhood-Visualization
A D3 based Neighborhood comparison and visualization tool for NYC

# Motivation
Renters and homebuyers new to a city will often find it challenging to find the best neighborhood for them. Existing real estate databases, such as Zillow or Apartments.com, filter homes based on features like price, amenities, and home type but assume that users know which areas of the city they are interested in moving. They also focus almost exclusively on current status, with little to no information of how the neighbourhood will change over the next few years. Therefore, many users are left clueless about the initial phase of searching for a home: finding a suitable neighbourhood.

# Data
Safety: Arrests Data at a daily level aggregated across years and major crime types based on frequency for individual neighborhoods Price: Data at a monthly level aggregated across years for individual neighborhoods Air Pollution: Annual Average pollutant concentration data gathered for individual neighborhoods Map: Neighborhood, Latitude and Longitude information used across all datasets to maintain consistency

# Sherlock Homes
An interactive frame that suggests the best neighborhoods based on a combination of the factors: rent costs, safety, air pollution, and distance from locations of interest to the user. Each factor’s values are forecast for the next five years. Looking into the future allows users to make a more informed decision by anticipating how each neighborhood is going to evolve in the next few years. Values are weighted based on user preferences, then averaged to determine the most desirable neighborhoods for the user.

# D3 Visualization

![D3 Visualization UI](https://github.com/Arunachalam-M/Neighborhood-Visualization/blob/master/Sherlock_homes1.png)

The user interface was built using the d3.js library, with sliding scales and mouse-clicks as methods of user interaction. A Likert-scale based user interface evaluation survey was completed by nine test users from the project team’s friends and family. Results indicated most users first use real estate aggregation websites when searching for a new place to live and prefer a more holistic approach that accounts for several features (while still including price).

