# Create a Suitability Model

This exercise required students to use the Suitability Model in ArcGIS. The tool combines raster classes used in a project and combines them based on desirability-based weights chosen by the analyst. The tool converts those raster classes into a common scale that makes comparing otherwise incomparable data types feasible, and then uses those values to generate a map of suitable pixels. In addition to being the focus of this assignment, the tool was also used as a major component of the final project of the course. 

This assignment required students to choose suitable locations for a new corporate headquarters based on a variety of variables. It starts with the generation of new raster variables using existing data. Below, a raster map of slope is shown. 
![Slope](https://github.com/serganttinkers/AdvancedGIS/blob/main/Slope.JPG?raw=true)

Another variable created was the distance away from main roads. This raster is shown below.
![Distance_MRoads](https://github.com/serganttinkers/AdvancedGIS/blob/main/Distance_MRoads.JPG?raw=true)

Below is the total list of variables and the weights applied to each of them. Note that LandUse is categorical while the rest are continuous. 
- Land Use                              1.6
- Aspect                                1.35
- Dist_Airport                          1
- Dist_Biol                             1.5
- Dist_Elect                            1.7
- Dist_Protect                          1.6
- Dist_Rec                              1
- Dist_Resident                         1.35
- Dist_Streams                          1.2
- Dist_Wetlands                         1.4
- Solar                                 1.6
- Slope                                 1.6

These variables are combined using the Suitability Model tool to create a new raster map with a common value scale. The map is shown below, alongside the range and color of suitability values. 
![Suitability](https://github.com/serganttinkers/AdvancedGIS/blob/main/Suitability%20Map.JPG?raw=true)
![Range](https://github.com/serganttinkers/AdvancedGIS/blob/main/Range.JPG?raw=true)

Using several perameters including total size, site location, and relative distance, five ideal locations were chosen and are shown below. 
![SiteLocations](https://github.com/serganttinkers/AdvancedGIS/blob/main/SiteLocations.JPG?raw=true)

Closer look at chosen locations:
![SiteCloser](https://github.com/serganttinkers/AdvancedGIS/blob/main/SitesClose.JPG?raw=true)

The chosen locations can be further analyzed based on narrower, localized data to chose ideal locations between them or consider local factors. It is important to note that the weights provided by the module are not scientifically-derived and are based on the needs of the client. Changing the weights could lead to very different results. 
