# UFOs

## Overview
The objective of this assignment was to use Javascript to create a web page that can filter data stored in a Javascript array in a clean and organized table using ES6+ for of use and Bootstrap for customization of the web page.

## Results
The web page is quire easy to navigate and use. Once loaded the user will see a table containing all of the UFO sightings showing the Date, City, State, Country, Shape, Duration, and Comments about the sighting. (See image below) </br>
![This is an image](https://github.com/smwhng/UFOs/blob/main/Images/no_filter_cap.PNG) </br>
On the left side there are inputs for the date, city, state, coutry, and shape. The user can enter a query into any number of these filters to find more specfic infromation. (See Images below) </br>
![This is an image](https://github.com/smwhng/UFOs/blob/main/Images/one_filter_cap.PNG) </br>
*One filter added, State: ca* </br>
![This is an image](https://github.com/smwhng/UFOs/blob/main/Images/two_filter_cap.PNG) </br>
*Two filters added, State: ca, City: el cajon* </br>

## Summary
One major drawback of these filters is that they are case senstive, which means that, for example, the proper way of inputing a state like California as CA would return no data. One recommendation would be to make a change to the placeholder tag on the index.html file and add that each of the filters are case senstive which would require very little effort on the programming side, but the better fix would probably be to make the filters not case sensitive. A second recommendation is to filter out some of the comments on t he sighitng. As you can see in the two filter image, some of the comments retrieved from the Javascript array seem to be broken and should probably be filtered out and replace with either N/A or a fixed description.
