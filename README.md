# Trendy Location Hotspots

 The Twin Cities cover a large area of land, making keeping up with popular or currently
 trendy areas difficult. Trendier areas will have more visitors and thus are more likely to receive
 more recent reviews. My goal is to use review data from Google combined with a parallel
 computing approach, in order to create a heatmap of ‘trendy’ locations around the Twin Cities in
 a time effective way

This MVP is designed to generate a heatmap of the Twin Cities area, showing 'trendy' locations. Trendy locations tend to have more people visitng the stores, as well as more people reviewing stores and shops in the area. So, a place with more recent reviews will be more 'trendy'. The Google's Places API was used to find locations of coffee shops and gift shops within the Twin Cities area. From there a heatmap was created, based on the average time of the 5 most recent reviews. This program used Dask to split up the API calls across the Twin Cities area, so we could 'talk' with Google many times at once, in order to ensure the project map could be created within a timely manner.

### Run this application
Open the Binder link below, wait a minute or two, and it will launch an interactive Jupyter Notebook containing my code. Input your own Google API Key, then run all the cells (click Run at the top--> Run All Cells) and the program will run. Warning: with default settings, this costs about $70 in Google Cloud Credits! After some time, the project will save an output map. 

https://mybinder.org/v2/gh/briollaure/TrendyHotspots/main?labpath=TrendyHotspots.ipynb

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/briollaure/TrendyHotspots/main?labpath=TrendyHotspots.ipynb)

### View the results
View the results of the project at this link! 

https://briollaure.github.io/TrendyHotspots/
