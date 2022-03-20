# Assignment 1: Custom Basemap

## Introduction

For this assignment, I created a custom basemap for Human Rights Watch using the Google Maps Styling Wizard. I began by using Canva's color palatte generator and extracted the four following colors to use in the basemap. 
- Ecstasy: FG4C61C
- Mine Shaft: 302D2D
- Science Blue: 0870C5
- Bali Hai: 7D9EB6

In addition, a dull white color is used (#F0EBEB) because white is commonly used for text and to fill blank spaces throughout the website. A shade of brown was also identified by the palatte tool, but this color was clearly taken from the skin color of people in pictures found throughout the website and this was not appropriate. A screenshot of the map is found below. The JSON code is also found in this repository. 

## Snip of Basemap

![HWR Map Snip](https://github.com/serganttinkers/AdvancedGIS/blob/main/HRW%20Map%20Snip.JPG?raw=true)

## Design Process

Knowing that Human Rights Watch (HRW) operates worldwide and likely focuses on large geographic areas, I made a map that uses the bright orange and blue colors to highlight some of the more important geographic features to society. Orange is used to highlight major highways and public transportation options and blue indicates natural resources like parks, national forests, and wildlife reserves. The less saturated dark grey and light blue colors are for more minior features like political borders, minor road outlines, and water features. The white color mentioned earlier is also used to establish hierarchy in the basemap. While major highways are solid orange, arterial roads are filled white with an orange outline. Most transit features are also colored like major roads, using an orange fill with no outline. However, airports are given a transparent dark grey color to make them visually distinct without distracting from other map features. 

Most labels are white with a dark grey outline, which matches the style of the HRW website while ensuring the text stands out among the white, orange, and blue features. However, label outlines for natural resources are blue to match the resources to which they apply and make them easily distinguishable. Note that minor roads are outlined with dark grey, but these features have been removed from the map using the "Roads" setting. This is because HRW often works in areas where data on minor roads is inconsistent or unreliable and is likely not as important. 

Because the map prioritizes transportation and natural resources, most other features use the previously mentioned white color with no outline. This ensures they are visible but do not clutter the map. Finally, the "Silver" theme was used as a starting point for basemap design. The white and light grey base colors complement the saturated orange and blue colors and are appropriate for the HRW website, which is dominated by white, blue, and orange colors. 
