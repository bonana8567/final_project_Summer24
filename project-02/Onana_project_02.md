---
title: "Mini-Project 02"
> Berthe Onana
---

# Data Visualization Project 02

The purpose of this project is to summarize and visualize the data selected for this project (All_Starbucks_Locations_in_the_US_-_Map.csv). This data set contains lots of missing values but can still be used to showcase how different starbucks locations are interconnected. 
Plot 1: 
The goal was to see which starbucks location has a specific ownership type or doesn’t depending on it's resident state. I used group_by to arrange the data based omn the ownership types (drive through or non). I also selected variables helpful to understand the visual plot such as state to understand which one has the ownership type. Results show that between NH, ME and MA only the state of NH has drive through starbucks
Plot 2: 
For plot 2 i used filter, in additional to the summary types listed above, to focus specifically on Florida state. I used mapview to showcase the starbuck location in Fl based on the 5O samples located. Although there were many other ways to do this i believe mapview was the simplest in this case since we have the latitude and longitude locations
Plot 3:
For plot 3 I was creating one visualization of a model to see how far each starbucks zip codes are from each other. The lm function was very usefule for this one since i simply needed to precice the data i wanted to focus on (Zipcode) and align it with Longitude + Latitude. Results show that most starbucks locations are concentrated in west then slightly in the east based on the 40 sample selected.
Story:
There are starbucks locations in different states in the US, however not all of them are drive through.Majority of the starbucks are located in the west while others are more in the east and few in theUS central based on the sample selected

