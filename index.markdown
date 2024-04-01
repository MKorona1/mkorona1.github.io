---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

Data used in a following analysis is a historical collection of crime incidents that happened from 2003 to May 2018 in San Francisco. The dataset is provided by City and County of San Francisco and can be accessed [here](https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry/about_data). It includes information about incidents' types (with 37 unique types in total), location (including address as well as longitude and latitude), and time of occurrence (including date, time and day of week). Since we don't have full set of data from 2018, we decided to discard this year in our analyses and focus on years 2003-2017.

Burglary is a significant concern in urban areas like San Francisco, and understanding its trends over this period can provide valuable insights into patterns and potential factors influencing crime in the city. For our analysis, we have chosen to focus specifically on burglary rates from 2012 to 2017. By narrowing our scope to these years, we aim to capture a snapshot of burglary activity within a recent timeframe while ensuring a sufficient dataset for meaningful analysis. This timeframe also allows us to examine any changes or trends in burglary rates over a relatively stable period preceding our analysis. Furthermore the state of California has the 8th Highest Burglary rate in the US as per Statista, so we thought it would be interesting to have a look at the recent trends and developments regarding this focus-crime. 

Let's begin our analysis by examining the burglary rates per year from 2012 to 2017 in San Francisco. 

<!-- ![Burglary Incidents per Year](Burglary Incidents per Year (2012-2017).png) -->
<img align="left" width="500" src="assets/burglary_years.png">
*Burglary Incidents per Year (2012-2017)*

As observed in the plot above, there are no significant changes in the number of burglary incidents from 2012 to 2017. The consistent trend indicates a relatively stable rate of burglary occurrences over this six-year period in San Francisco. This finding sets the stage for a more detailed analysis to uncover any underlying factors or patterns that may contribute to the consistent level of burglary activity throughout these years.

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