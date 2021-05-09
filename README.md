# UFO Analysis

## Overview of the Analysis
The purpose of this analysis was to create dynamic content on webpage with UFO sighting information using Javascript and a CSS framework called Bootstrap. 

## Results of the Analysis

### Analysis Resources
* Data Sources: [UFO Sighting Data](https://github.com/dwwatson1/UFOs/blob/main/static/js/data.js)
* Software: Javascript, [Bootstrap 4.0.0](https://getbootstrap.com/docs/4.0/getting-started/introduction/)

### Overview of Results 
To make the analysis of UFO sightings easier and more user-friendly, we needed to build an HTML page with dynamic (Javascript) content that will allow the user to filter through hundreds of sightings for multiple criteria at the same time. 

The top half of the webpage displays a neatly displayed navigation bar, a jumbotron header, and a two-column section below [stylized in CSS](https://github.com/dwwatson1/UFOs/blob/main/static/css/style.css).

![module_page_display](https://github.com/dwwatson1/UFOs/blob/main/module_page_display.PNG)

The bottom half of the page is where users can filter through the hundreds of UFO sightings based on date, city, state, country, or sighting shape. The user can choose none, one, or many. By default, the page will list all sightings. In my example, I wanted to display all UFO sightings in Massachusetts. To do this, I typed in the state initial "ma" and it returned 7 sightings. 

![challenge_filter_example](https://github.com/dwwatson1/UFOs/blob/main/challenge_filter_example.PNG)

I can drill-down my analysis further by adding another filter. I chose the shape field and entered "light." The number of results decreased from 7 to 2.

![challenge_filter_example_2](https://github.com/dwwatson1/UFOs/blob/main/challenge_filter_example_2.PNG)

## Summary of the Analysis

### Drawbacks

While this webpage is clean, easy to navigate, and perform UFO sighting filters, it's limited by not having that much data. All sighting data is from only 2010, which is not only old data, but also limiting being from 2010. In addition, every single data entry is a UFO sighting within the United States. This makes the 'Enter Country' filter essentially useless. 

### Recommendations for Further Analysis

This webpage would benefit from an updated and larger dataset that includes UFO sightings from all over the world. It would also benefit from a list dropdown so the user wouldn't have to guess which countries or shape to filter by. The data could also benefit from cleaning up the duration data. Some entries are listed in seconds, some in minutes, and others with different formats: "approx. 1 sec." for example. To add this as a filtering section, we would need to convert the entries to a uniform format. I would suggest having all of them in seconds as some UFO sightings were quite short.
