# Geological-Data-Analysis
## SUMMARY ##
* *Overview,*
* *App in action*
* *Task*
* *Technologies used*


## Overview ##
Welcome to the United States Geological Survey, or USGS for short! The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. As a new hire, you will be helping them out with an exciting new project!
The USGS is interested in building a new set of tools that will allow them visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding..) on issues facing our planet.

## App in Action (with bonus) ##

![](Assets/earthquackes%20maps.gif)

## Task ##
### Basic Visualization ###
* Get your data set
Your first task is to visualize an earthquake data set.
The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the USGS GeoJSON Feed page and pick a data set to visualize. When you click on a data set, for example 'All Earthquakes from the Past 7 Days', you will be given a JSON representation of that data. You will be using the URL of this JSON to pull in the data for our visualization.

* Import & Visualize the Data
Create a map using Leaflet that plots all of the earthquakes from your data set based on their longitude and latitude.
Your data markers should reflect the magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes should appear larger and darker in color.
Include popups that provide additional information about the earthquake when a marker is clicked.
Create a legend that will provide context for your map data.
Your visualization should look something like the map above.
![](Assets/outdoors%20view%20basic.png)
![](Assets/grayscale%20view%20basic.png)
![](Assets/satelite%20view%20basic.jpg)

### More Data ### 
The USGS wants you to plot a second data set on your map to illustrate the relationship between tectonic plates and seismic activity. You will need to pull in a second data set and visualize it along side your original set of data. Data on tectonic plates can be found at https://github.com/fraxen/tectonicplates.
In this step we are going to..
![](Assets/outdoors%20view.png)
![](Assets/grayscale%20view.png)
![](Assets/satelitte%20view.jpg)

## Technologies used ##
* HTML 5
* CSS 3
* Javascript
* Leaflet
* D3.json
* Mapbox
* API JSON
  
## Authors ##
* Sylvain David - Data Analytics Bootcamp - Vanderbilt University - 2020