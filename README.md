# The_Cuisine_Project
International Cuisine Guide for Multi-Cuisine Restaurants in Toronto

INTRODUCTION

The multi-cultural city like Toronto will be having people from around the world, migrated for better quaility of life and living standards. Eventhough on one can't forget their own homely food. Most people prefer to going restaurants serving cuisines they interested in. Now a days multi-cuisine restaurants are very common in cities, but to develop efficient and economical menu always challenging. To attract more customers, restaurants should try to study their surroundings. About possible cuisine options based on customer requirements. In this project I am trying to find different cultural groups on Toronto neighbourhoods, based on second most using language on local area. If such customer segment can be identified, we can propose nearby restaurants to upgrade their menu.

I am trying to plot customer segments & restaurants location on map to determine any un-occupaid location for new restaurants OR suggestion for existing restautants to improve businesses.

DATA SOURCES

We need two data sets to complete this project.

1. Population and Cultural data of Totonto neighbourhoods
2. Location details of existing restaurants in Toronto neighbourhoods

Fortunatly, on wikipedia page Demographics of Toronto neighbourhoods available, which contains population density and "second most common language" with population percentage using that language. Since second language of people related to their mother land, it will help up to predict their cultural difference and food habits. 

Following Wiki page provide sufficient details 

https://en.wikipedia.org/wiki/Demographics_of_Toronto_neighbourhoods

Geocoder will help to find neighbourhood location to plot on map.


Using Foursquare API we can find nearby venues contains restaurants. 


METHOD OF ANALYSIS

Using above mentiond data sets, we can perform Kmeans Clustering methods to find Second language cluster groups, which in turn will show different cultural groups. This clusters will be ploted on map along with existing restaurants. So that we can get idea about how well restaurants are placed, any chance for new restautants, Can we give suggestions to existing restaurants to upgrade their menu to increase their business. 
