---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

Burglary is a significant concern in urban areas like San Francisco, and understanding its trends over this period can provide valuable insights into patterns and potential factors influencing crime in the city. The state of California, with San Francisco being one of its largest cities, has the 8th highest burglary rate in the US as per Statista (https://www.statista.com/statistics/232580/burglary-rate-in-the-us-by-state/). Nowadays, San Francisco's residents claim that there's not a place in the city that's actually safe (https://nypost.com/2024/02/28/us-news/now-nowhere-in-san-francisco-is-safe-from-crime/). Examining last years statistics, we can see that number of burglary incidents was as high as 7600 in 2021. But is the situation really this bad comparing to previous years?


To investigate this issue, we used data from a historical collection of crime incidents that happened from 2003 to 2017 in San Francisco. The dataset is provided by City and County of San Francisco and can be accessed [here](https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry/about_data). It includes information about incidents' types (with 37 unique types in total), location (including address as well as longitude and latitude), and time of occurrence (including date, time and day of week).

Let's begin our analysis by examining trend in the burglary rates throuhout the years. 

<img align="left" width="500" src="assets/burglary_years.png">
<!-- *Burglary Incidents per Year (2012-2017)* -->

As observed in the plot on the left, the number of burglary incidents is quite stable throughout the years. There was a visible drop in the number of crimes between 2007 and 2011, that might have given some hope to SF's redidents, but later the numbers increased again. We can clearly see that the situation was a bit better than in mentioned before year 2021, but with the rates going up to over 7000 in 2005, one can wonder if the situation is significantly worse nowadays. The consistent trend indicates a relatively stable rate of burglary occurrences over this six-year period in San Francisco. This finding sets the stage for a more detailed analysis to uncover any underlying factors or patterns that may contribute to quite consistent levels of burglary activity throughout these years.

Now that we've gained some insight on the overall burglary rates per year in the city it's time to take a look at where the crimes are appearing. Understanding where burglary incidents are occurring is crucial for identifying hotspots and deploying targeted interventions to mitigate risk. By examining the geographical locations of these incidents, we aim to uncover patterns and trends that may shed light on factors influencing burglary activity in specific areas of the city.

<iframe src="assets/map.html" 
    align="right" 
    width="600" 
    height="400"
    scrolling="no" 
    seamless="seamless" 
    frameborder="0">
</iframe>

The map above illustrates that the northern and central districts of San Francisco are characterized by the highest rates of burglary incidents.Understanding these geographical patterns is essential for directing resources and implementing targeted crime prevention measures in the neighborhoods most affected by burglary. 


Transitioning from the spatial analysis, our investigation now turns towards examining the temporal distribution of burglary incidents throughout the week. By exploring the frequency of burglaries across different weekdays, we aim to uncover patterns in the timing of these crimes. 

<iframe src="assets/districts_years.html"
    sandbox="allow-same-origin allow-scripts"
    align="left"
    width="100%"
    height="500"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>

As observed above, burglaries in San Francisco predominantly occur on weekdays as opposed to weekends. This finding suggests a distinct temporal pattern in burglary activity, with perpetrators being more active during the weekdays.

We trust that this paper has offered valuable insights into the broader landscape of burglary in San Francisco. By examining burglary rates over a specific timeframe and exploring spatial and temporal patterns, we've gained a deeper understanding of the dynamics of this crime within the city.