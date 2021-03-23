# UFO Sightings

## Overview
 
The purpose of this project was to create a UFO Sightings website using Javascript, HTML, and CSS. In addition, the site features a filterable UFO sighting table.

## Results

The table on this site contained a lot of UFO sightings, which would be a lot of data to comb through. To address this, I added a filter feature that allows the user to easily search through the data. The available filters are: date, city, state, country, and UFO shape. For example, if a user only wanted to view sightings that occurred in the United States and/or sightings where the UFO appeard to be a triangle they could easily get to that info like so:

<img src="https://github.com/kimcheese33/UFOs/blob/main/static/images/filter.png" />

## Summary  

While this site seems to work great for our purposes, one drawback is that it does not have anything in place to control user input. For example, in the state filter if a user put 'TX' instead of 'tx' the table would not return anything. To address this, one change that could be implemented is to programmatically alter the user input to lower case. Another change could be to add a drop down list of available options for every filter. That way, the user can't input something that doesn't exist or is in the wrong format.
  
  
