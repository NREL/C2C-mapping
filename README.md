# Vernon county, Wisconsin EV Planning Map

## Access
The best way to view the map is by opening the html file in the browser of your choice. You will then be able to zoom, scroll, and click the map to view details. To remove layers on the map, use the button in the upper right with the layer icon.

Note: if you can't see a popup when you click on an icon or area, try toggling that layer off and back on, the popups work best when the feature is the "top" or most recently added layer. 

## Layers
There are three main coponents of this map:

1) POIs
The POIs provided in a Google Map have been scraped and added as markers on the map. They are color coded according to category, click each icon to view details about the location.

2) [Census Data](https://data.census.gov/)
Data from the census at the tract level is presented with polygons on the map. The polygons are shaded according to median HH income, the darker the color the higher the median income. Other census data is accessible by clicking each area, including population, the percentage of housing classified as multifamily, number of owned and rented units, and average HH size of owned and rented dwellings. 

3) [LODES Data](https://lehd.ces.census.gov/data/)
The Census Beureau also publishes "Origin-Destination Employment Statistics" Data. This data presents the number of jobs at the census block level by resident and employment, ie there are 5 people who live in block A and work in block B. The LODES layer presents a processed version of this data at the census block group level. The processed data includes number of jobs, average commute distance for people who work in a census block in that group, the average commute distance for people who live in a census block in that group, and potential energy and emissions reductions if each of those commutes were electrified. The commute distances were estimated by the distance between the centers of a given home and work block. These block level distances were aggregated to block groups with a weighted average. The energy and emissions estimates draw from [CHEER](https://github.com/JGreenlee/e-mission-common), and represent the difference between a single occupancy gas car trip and a single occupancy electric car trip of the average commute length. These calculations account for the emissions attributed to electricity generation in the appropriate [eGRID](https://www.epa.gov/egrid) region. The polygons are shaded according to the potential daily energy savings for an average worker in the region if they switched to an EV. 
