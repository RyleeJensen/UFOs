# UFOs

## Overview
The purpose of this project was to create a dynamic webpage in which users can input their own filters in order to adjust the table to display information about UFO sightings. Users will be able to filter the UFO sightings table based on the date, city, state, country, and even the shape of the UFO sighting. 

## Resources
- Data Source: data.js (UFO sighting data)
- Software: JavaScript, HTML/CSS, VisualStudio Code, Bootstrap

## Results
We have edited the html and javascript code in order to update the filter search box and provide an array of options available for user input. In the image below, we can see a screenshot of how the webpage looks before any filters have been added. If you notice the "UFO Sightings" in the upper left corner, this button will reset the webpage back to the default if any filters have been added. The text we see in the filter search boxes are simply there as examples for the user so they know the correct text format to use.

![Webpage](https://github.com/RyleeJensen/UFOs/blob/main/static/images/Webpage_1.png)

When a user wants to add a filter, they can either add inputs to all the boxes, a few, or just one. In the image below, we use the example of searching for UFO sightings in the state of Arizona by typing "az" into the "State" filter box. We can see how the table changed on the right, and is now only showing us recorded UFO sightings in Arizona. And again, if we wish to erase our filters and return to the default table, we would click the "UFO Sightings" button in the upper left corner. Any of the other filter boxes can be used in the exact same way as this example.

![Webpage2](https://github.com/RyleeJensen/UFOs/blob/main/static/images/Webpage_2.png)

## Summary
We can see that for the most part, the dynamic webpage is fairly user friendly and we can see the results from our filter search very quickly. The one drawback to this type of design, is that the user doesn't know all the parameters of the search boxes. For example, not every state has recorded UFO sightings, so not every state that gets inputed into the filter box will show results. And the shape filter box can be a little confusing and vague, as some of the shapes include "light" (which isn't really a shape). So a way to make the filters even easier to use would be to inlcude a drop-down menu for each input box. That way the user would know exactly what dates, cities, states, countries, and shapes to input in order to get results, rather than having to guess.
