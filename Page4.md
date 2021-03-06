# Spatial Data Analysis, Part II

## Assignment Description
This assignment guided students through an exercise demonstrating the forest-based classification tool in ArcGIS. For the uninitiated, the tool is a classification method where data are algorithmically categorized using a large number of simple decision trees that make up a "forest." A portion of the data set is used as "training" data and the rest is used to create and test a model. Combined, the large number of trees make it possible to sort large numbers of unclassified data. Combining relevant variables can be done to improve model accuracy, but note that adding too many can create an over-fitting problem where the model is too specialized to predict unfamiliar data.

In this exercise, county-level voting information (such as voter education level,voter income, voter turnout, election competitiveness, etc.) was used to predict tract-level voter turnouts in Iowa. Below is a map of the predicted values.
![Iowa Map](https://github.com/serganttinkers/AdvancedGIS/blob/main/Iowa%20prediction.JPG?raw=true)

Several tools are available to learn how relevant certain variables may be to model functioning. The Distribution of Variable Importance tool shows how different variables included in the model may be impacting model outputs. Below, Per Capita Income and State Percent Votes Difference are the most influential variables in the analyis while State Voting Requirements Laws appear to be a much less effective predictor for voting turnout.
![Distribution of Variable Importance](https://github.com/serganttinkers/AdvancedGIS/blob/main/distribution%20of%20variable%20importance.JPG?raw=true)

The model also compares the predicted values with a chart of their confidence intervals. The Prediction Interval generated for this exercise is shown below.
![Prediction Interval](https://github.com/serganttinkers/AdvancedGIS/blob/main/Prediction%20Interval.JPG?raw=true)

A separate exercise was included as a stretch goal, which guided students through using the Build Balanced Zones tool to assign a "Get The Vote Out" canvassing effort to five people. While not related to the forest-based classification tool, the exercise was also used in the course final project. A map output of the tool is shown below.
![Build Balanced Zones](https://github.com/serganttinkers/AdvancedGIS/blob/main/zones.JPG?raw=true)

## Response
I am a very big fan of algorithmic prediction tools in data analysis. For example, I used clustering analysis in my systems project to determine which census tracts are particularly underserved by Pennsylvania???s Department of Transportation. Because of this, I was pretty eager to learn about the forest-based method. I have never used or heard of this predictive model, but the same concepts used in cluster analysis, regression analysis, and other forecasting and predictive models apply. By feeding different data into a model, the model generally becomes more accurate. However, adding too many variables creates an overfitting issue where the model is so fine-tuned with the data provided that it can only provide accurate predictions for data it already has.

I think the most important thing to note about predictive software is that they are never perfect. It is basically impossible to perfectly predict what will happen in a future data set. Additionally, that???s not even the point of using predictive software. The real value is in exploration. Algorithms are not tied down to the biases and reasoning used by humans and are capable of generating suggestions which a human mind may be less likely to consider. In this module???s case, the prediction made was not perfect and I had noticed some differences between the model???s prediction for tract-based turnouts in Iowa compared to the county-level data, but the data would still be helpful. I could see the map of estimated voter turnouts in Iowa being helpful for local political surveyors, maybe a local representative trying to better understand voter preferences or something.

I also could have used this sort of method for a project last semester. I was trying to analyze the Human Rights Measurement Index (HRMI) for missing values in my Intro to R for Analytics course. The strategy I used was a simple regression model between two variables, calculating the value of a missing data pointy with the measured value of another. Because the data set has so many variables, it would have been easy to pick which variables were meaningful using the Distribution of Variable Importance tool. The HRMI is not a geospatial dataset, of course, but the same principle applies and I think the forest-based predictive method isn???t limited to geospatial analysis. What???s more, there are likely countless other situations in the human rights arena where this would be useful due to how frequent inconsistent data collection is.

[Return to main page](https://serganttinkers.github.io/AdvancedGIS/)
