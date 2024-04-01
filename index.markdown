---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

Burglary is a significant concern in urban areas like San Francisco, and understanding the crime trends can provide valuable insights into patterns and potential factors influencing crime in the city. The state of California, with San Francisco being one of its largest cities, has the 8th highest burglary rate in the US as per [Statista](https://www.statista.com/statistics/232580/burglary-rate-in-the-us-by-state/). Nowadays, San Francisco's residents claim that there's not a place in the city that's actually safe, with crime rates increasing in neighbourhoods considered as safe so far [(NY Post article)](https://nypost.com/2024/02/28/us-news/now-nowhere-in-san-francisco-is-safe-from-crime/). Examining last years statistics, we can see that number of burglary incidents was as high as 7600 in 2021. But is the situation really this bad comparing to previous years?


To investigate this issue, we used data from a historical collection of crime incidents that happened from 2003 to 2017 in San Francisco. The dataset is provided by City and County of San Francisco and can be accessed [here](https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry/about_data). It includes information about incidents' types (with 37 unique types in total), location (including address as well as longitude and latitude), and time of occurrence (including date, time and day of week).

Let's begin our analysis by examining trend in the burglary rates throughout the years. 

<img align="left" width="500" src="assets/burglary_years.png" style="padding-right: 20px">
<!-- *Burglary Incidents per Year (2012-2017)* -->

As observed in the plot on the left, the number of burglary incidents is quite stable throughout the years. There was a visible drop in the number of crimes between 2007 and 2011, that might have given some hope to SF's redidents, but later the numbers increased again. We can clearly see that the situation was a bit better than in mentioned before year 2021, but with the rates going up to over 7000 in 2005, one can wonder if the situation is significantly worse nowadays. 

Now that we've gained some insight on the overall burglary rates per year in the city it's time to take a look at where the crimes are appearing. Understanding where burglary incidents are occurring is crucial for identifying hotspots and deploying targeted interventions to mitigate risk. 

<iframe src="assets/map.html" 
    align="right" 
    width="600" 
    height="400"
    scrolling="no" 
    seamless="seamless" 
    frameborder="0">
</iframe>

The map on the right illustrates ratio of burglaries per area in SF districts in different days of week. Since districts in SF have significantly different areas, it was important to include this information instead just showing number of occurences in each district. When investigating patterns throughout the week, it's easy to see that Tenderloin district is the most dangerous one. Although the ratio of incidents is quite stable throughout the week, there is a peak on Fridays visible especially in Tenderloin and Central districts. It suggests that allocating more police forces in those regions on Fridays could possibly prevent some of those incidents happening.


Seeing as the crime rates are quite stables throughout the years with some visible trends in specific districts thorughout the week, it makes one wonder how does the situation changed in districts over the years. The normalized distribution of crimes per district can be seen in the bar plot below.

<iframe src="assets/districts_years.html"
    sandbox="allow-same-origin allow-scripts"
    align="left"
    width="100%"
    height="500"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>

As observed above, the crime rate in Tenderloin started decreasing since 2015, suggesting that the city might have taken appropriate measures to deal with the most problematic district. At the same time, there's a district like Mission, which although generally follows a similar trend as a whole San Francisco, it seems that the crime rates started slowly increasing there after 2011 and even exceeded numbers from 2005. It highlights the need to remember that when dealing with one district's issues, one has to still be cautious with what's happening in other places as the crimes might just spread to other parts of the city, as shown in NY Post article mentioned before.

This analysis shows that, despite to some beliefs, the overall situation in San Francisco isn't necessarily that much worse than it used to be in the past. At the same time, focusing on crime prevention in certain areas might have led to a worse situation in different ones. It seems that there's still a lot to be done in terms of safety in SF, and the police could try and focus their efforts on specific districts, or days of the week, while monitoring situation in other parts of the city.