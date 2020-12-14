# UFO

## Overview

This project is focused on building a dynamic webpage that will take user inputs and display the adjusted data aboout UFO sightings. To assist users with their analysis, they are now able to filter UFO sightings with several options such as country, state, city, and date.

## Results

### How to Search

#### Refreshing the Page
This is the homepage and can be refreshed by clicking on the navbar on the top left as shown by the red box in the image below.
<p align="center">
	<img src="https://github.com/Changscorner/UFO/blob/main/static/images/home%20page.png">
</p>

#### Searching by Date
You can search by date by entering the desired date into the input box and the code will filter the table for that date. As you can see by the example below:
<p align="center">
	<img src="https://github.com/Changscorner/UFO/blob/main/static/images/Filtered%20results.png">
</p>

#### Search by City
You can search by city by entering in the desired city where UFO sighting have been seen as shown below:

<p align="center">
	<img src="https://github.com/Changscorner/UFO/blob/main/static/images/city%20search.png">
</p>

#### Search by State
You can search for UFO sighting by state as shown by the example below:

<p align="center">
	<img src="https://github.com/Changscorner/UFO/blob/main/static/images/state%20search.png">
</p>
#### Search by Country
You can search for UFO sighting by country by following the example below:

<p align="center">
	<img src="https://github.com/Changscorner/UFO/blob/main/static/images/country%20search.png">
</p>
#### Search by Shape
You can search for UFO sighting by light shape by following the example below:
<p align="center">
	<img src="https://github.com/Changscorner/UFO/blob/main/static/images/shape%20search.png">
</p>

### Summary
One major flaw is that if the user enters a query that has no result the table just blanks out without any feedback to the end user. Another major issue alongside the previous is that the end user does not really know what parameters they can seach from this particular dataset.
The way to solve both these issues is to:
- Use a dropdown table option for the user to select from since the dataset is finite.

#### Improvements
1.) One improvement to add is a clear filter function to erase any current existing filters on the dataset.

2.) Another is to add a feedback response if the dropdown table functionality is not added to let the user know that they query that they have entered is not valid or returns no data.
