Lab 6 Web Map
====

#### Map created by Lydia Nowak. 

*Project Outline*

This lab for Web Mapping was focused on the creation of an interactive bivariate map. This map showed the locations of incident wildfires, as well as the state boundaries for the Eastern US. The states are also shaded to correspond with the percent of land area within the state that is taken up by National Park land. An icon for wildfires was chosen (fire) to depict the point data for each fire. On the legend is the class divisions for the percent data of National Parks, shown as a green gradient. The green was chosen to correspond with the greenery of parks. Also included is a scale bar, annotations, and zoom buttons. 

---

*Sources and Process* 

This map was created using data from Leaflet as well as Safe Guard Surfacing and the National Interagency Fire Center, which was downloaded as a .geojson file. This .geojson file was then put into the geojson.io website to edit the data further. Because both of the files I downloaded were so large, this was the majority of this time I spent on this project. I had to manually add percent data to each state polygon. At first I planned to use the data for the entire US, but the process of editing data manually was taking too long. Plus the way the completed GeoJSON file loaded into VisualStudio made it so the entire file was on one line of code, meaning it would not load. Because of these issues, I went back into geojson.io and deleted the data from the western US. I also redownloaded the geojson file of the wildfires to only include the data in the eastern US. After all this, I had functioning geojson files in VisualStudio. 

After loading the map on the web page and centering the map to the eastern US, I edited the code to match the new data. This is when I made edits to the legend and the styling.
