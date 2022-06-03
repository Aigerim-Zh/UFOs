# UFOs

# Project Overview

In this project, I am tasked with creating a dynamic webpage displaying information about UFOs sightings. 

I will display a table with hundreds of rows of UFO sightings. Given the amount of available information on the topic, it is necessary to provide users a feature allowing users to get a more in-depth analysis of UFO sightings by filtering for multiple criteria at the same time. I will create the following search criteria:
* Date
* City
* State
* Country
* Shape

## Coding

- [data.js](): the provided data of UFO sightings stored as a ```JavaScript``` array. 
- [app.js](): the code that builds a ```JavaScipt``` table and fills it with data from [data.js]().
- [index.html](): ```HTML``` file used to build the webpage. ```Bootstrap``` is used to customize the webpage and add several fully functional filters that will allow users to interact with the table data. 
- [style.css](): ```CSS``` file to style the page.

While ```JavaScript``` is increasingly used in advanced programming and machine learning settings, in this project, we are using it because it can make websites more functional and dynamic. 

There have been many updates to JavaScript but they are not as large as ```ES6```.Our focus is on basic ```JavaScript``` and ```ES6``` capabilities such as arrow functions, which are one of the most popular aspects of the ```ES6``` update. Any standard function can be refactored into an arrow function.


## Dependencies
```D3``` JavaScript library

# Results 

The final webpage is available here: https://aigerim-zh.github.io/UFOs/

![](https://github.com/Aigerim-Zh/UFOs/blob/main/Images/Unfiltered_Table_View.png)

- The JavaScript array is now displayed as a dynamic table. 
- Users can filter the table on multiple criteria such as date, state, country, and shape of UFO sightings. 
- The search box shows an example of how the search needs to be entered. 
- Once the search is defined, the table's information is updated as can be seen below. 
- The search can be cleared by clicking on the "UFO Sightings" button on the top left. 

![](https://github.com/Aigerim-Zh/UFOs/blob/main/Images/Filter_for_date.png)

![](https://github.com/Aigerim-Zh/UFOs/blob/main/Images/Filter_for_city.png)

# Summary
There has been a lot of work done to take the JavaScript array and display it as a dynamic table. However, the webpage has drawbacks and areas for future improvement. 

**Major Drawbacks**:
- The search criteria are case-sensitive. For example, for a search of the city of Benton, it will show results only if "benton" is entered but not "Benton".
- The data is most likely outdated and it might not be the best practice to update the JavaScript array each time a new sighting is added. 

**Further Development Recommendations**:
- Adding a "Submit" button after the search criteria are defined. Currently, it is not clear right away that the search will work once the Enter is clicked on the keyboard.
- Adding a drop-down menu for the filter can present the user with more choices, especially if the user wants to explore the data in general and not look for only specific sightings.
- Adding a "Refresh" button as it is not clear that the "USO Sightings" button is for refreshing the webpage.
- Making the search case-insensitive. 
- Finally, connecting the table data to a live source. 