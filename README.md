# AdvancedGIS

Link to site:
https://serganttinkers.github.io/AdvancedGIS/

# Prior GIS Work

Link to Previous Project: "Higher Education’s Effect on Brain Drain in Wyoming"
https://storymaps.arcgis.com/stories/5614c323d9e14ebabd233e86afb8962c

------------------------------------------------------------

# About Me

I am completing my Masters in Public Policy and Management degree at Carnegie Mellon University this May. I have always had an interest in foreign policy and so my degree concentrates in human rights and global development. I am currently pursuing career opportunities in policy think tanks, international development organizations, and the US federal government to begin upon completion of my degree. 

I initially began taking GIS because my academic advisor said it would be a highly marketable skill and few public policy schools provide it. After completing a semester-long course on GIS, I learned how useful geospatial analysis is for understanding human behavior. My specialization in global development and human rights means I credible or consistent data can be difficult to obtain in this area. However, the emergent nature of geospatial data exploration gives a unique perspective on existing data that can help an anlyst fill in the blanks that would otherwise be a headache on a mere Excel sheet.

# What I Hope to Learn

I have already applied to several positions which would greatly benefit from geospatial analysis skills. For example, I recently applied for a position with Human Rights Watch to perform research on ethnic/racial minorities in a specific region. GIS analysis makes it possible to more meaningfully understand the environment and circumstances of certain groups of people that simply would not be feasible with mere census data. I hope to expand on my current understanding of GIS and apply this experience in a variety of human rights contexts. I am particuarly interested in learning to use tools other that ArcGIS, as expensive GIS software is not as accessible in in human rights and development work. 

--------------------------------------------------------------------

# Advanced GIS Coursework

<h3>Introductory Custom Basemap</h3>
<style>.embed-container {position: relative; padding-bottom: 80%; height: 0; max-width: 100%;} .embed-container iframe, .embed-container object, .embed-container iframe{position: absolute; top: 0; left: 0; width: 100%; height: 100%;} small{position: absolute; z-index: 40; bottom: 0; margin-bottom: -15px;}</style><div class="embed-container"><iframe width="500" height="400" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" title="Summerfest 2022" src="//carnegiemellon.maps.arcgis.com/apps/Embed/index.html?webmap=b2bcb01a373148ea99667013ab7e30e2&extent=-80.019,40.4191,-79.9292,40.4549&zoom=true&previewImage=false&scale=true&disable_scroll=true&theme=light"></iframe></div>


<h3>Assignment 1: Custom Basemap</h3>

# Assignment Description

For this assignment, I created a custom basemap for Human Rights Watch using the Google Maps Styling Wizard. I began by using Canva's color palatte generator and extracted the four following colors to use in the basemap. 
- Ecstasy: FG4C61C
- Mine Shaft: 302D2D
- Science Blue: 0870C5
- Bali Hai: 7D9EB6

In addition, a dull white color is used (#F0EBEB) because white is commonly used for text and to fill blank spaces throughout the website. A shade of brown was also identified by the palatte tool, but this color was clearly taken from the skin color of people in pictures found throughout the website and this was not appropriate. A screenshot of the map is found below. The JSON code is also found in this repository. 

# Snip of Basemap

![HWR Map Snip](https://github.com/serganttinkers/AdvancedGIS/blob/main/HRW%20Map%20Snip.JPG?raw=true)

# Design Process

Knowing that Human Rights Watch (HRW) operates worldwide and likely focuses on large geographic areas, I made a map that uses the bright orange and blue colors to highlight some of the more important geographic features to society. Orange is used to highlight major highways and public transportation options and blue indicates natural resources like parks, national forests, and wildlife reserves. The less saturated dark grey and light blue colors are for more minior features like political borders, minor road outlines, and water features. The white color mentioned earlier is also used to establish hierarchy in the basemap. While major highways are solid orange, arterial roads are filled white with an orange outline. Most transit features are also colored like major roads, using an orange fill with no outline. However, airports are given a transparent dark grey color to make them visually distinct without distracting from other map features. 

Most labels are white with a dark grey outline, which matches the style of the HRW website while ensuring the text stands out among the white, orange, and blue features. However, label outlines for natural resources are blue to match the resources to which they apply and make them easily distinguishable. Note that minor roads are outlined with dark grey, but these features have been removed from the map using the "Roads" setting. This is because HRW often works in areas where data on minor roads is inconsistent or unreliable and is likely not as important. 

Because the map prioritizes transportation and natural resources, most other features use the previously mentioned white color with no outline. This ensures they are visible but do not clutter the map. Finally, the "Silver" theme was used as a starting point for basemap design. The white and light grey base colors complement the saturated orange and blue colors and are appropriate for the HRW website, which is dominated by white, blue, and orange colors. 
