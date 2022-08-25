# UFOs
UFO Sightings with JavaScript

## Project Overview

The purpose of this project was to learn how to take data that is stored as a `JavaScript` array or list and create a table to organize the information that will visually adjust as "events" change (i.e. filtering). In order to react when an element is changed, we use `Javascript` functions to loop through the data to build the table and create a customized dashboard. The customizations include filters with event listeners that will record the information when an element has changed and develop an interactive webpage. Filters can be applied in many ways. In this exercise, we reviewed how to display default data in the table, listen for a button click or trigger the table to update based on the user's input with a select criteria. Finally, we use `HTML`, `Bootstrap` and `CSS` to read the `Javascript` code and create a webpage that is easy to view, includes filters, images, and a synopsis of the topic.

## Results:
### Welcome to UFO Sightings! 

![Pic 1](./static/images/intro.PNG)

### How the filters appear when first landing on the page:
![Pic 2](./static/images/initial_filter.PNG)

### How the filters appear after being used: 
By typing in the suggested placeholder elements as the filters, the result returns 2 matches. Make sure to type everything in lower case letters and do not have spaces at the end of the text. Click off the input box or press enter to initiate the filter. To reset the filter criteria, click the UFO Sightings at the top left of the website. 

![Pic 3](./static/images/fillters_used.PNG)


## Summary: 

### Drawback:
The user must know specific dates, cities, or shapes to search.  Some shapes like "light" might not be as intuitive. The filters require correct lower-case spellings and cannot include spaces at the end. For example, the city that was used could not be typed as "elcajon", “el cajon_”, or "El Cajon". The only acceptable input would be "el cajon".

### Recommendations: 
1. The next addition to the filters should be to add a trim function to catch spaces at the end of words as well as allow for upper and lower cases.


2. A filter on a date range might be preferable than a singular date. Typing 1/2010 did not bring up all the dates for January. UFO Sightings occur more frequently in a specific month instead of a specific day within that month. It is recommended to add in a filter function to include a date range as the filter to aid in the investigation of UFO Sightings. 