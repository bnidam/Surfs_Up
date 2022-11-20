![Surfing Ice Cream Cone](https://github.com/bnidam/Surfs_Up/blob/main/Resources/Surfing_Icecreamcone_vecteezy.png)
image from Vecteezy https://www.vecteezy.com/vector-art/7071905-ice-cream-cone-surfing-on-the-beach
# Surfs Up Challenge

## Overview of Project
Owning a surf and ice cream shop in Oahu, Hawaii sounds like more fun than work... but is this business sustainable year-round? This Challenge attempts to assist Mr. W.Avy in answering that question.

### Purpose
The purpose of this project is to extract, analyze, and present temperature data for the months of June and December between 2010-2016, noting key temperature differences between the two months.

### Tools
The tools used for this project include Python and jupyter notebook: pandas, numpy, and matplotlib, plus a SQL file of temperature data for Hawaii.

## Analysis 
### Background Information
In order to assist Mr. W. Avy, it's a good idea to know somethings about Hawaii, surfing, and ice cream.

 The Big Wave season for the best surfing in Hawaii, according to gohawaii.com, is from November to February, although surfing is possible throughout the year. 
 
 The peak of the tourist season is from mid-December to the end of March; May to September is considered the "Off Season", and June, July and September are the months with the best weather in Hawaii - warm water temperatures and the least amount of rainfall - according the travel website thepointsguy.com.

 While ice cream is eaten throughout the year, worldatlas.com reports that ice cream consumption reaches its peak in June.

### Key differences in temperatures between June and December

- Summary Statistics: 
    Below are the summary statistics tables for the temperature data for June and December.

    While June has 11% more counts than December, there are more than enough counts in December to make a viable comparison. These statistics show that overall June is a few degrees warmer than December with the mean, maximum, standard deviation, and the 25th, 50th, and 75th percentile temperatures varying only two to four degrees.  The minimum temperatures, however, vary by eight degrees with the cooler temps in December.

![Summary Statistics for June and December Temperatures](https://github.com/bnidam/Surfs_Up/blob/main/Resources/Temperatures_SummStats_June_Dec.png)

- Box and Whisker Plot: 
    The box and whisker plot below is a visual display of the summary statistics show in the tables above. 

    The boxes in the middle of the image show the 50-percentile temperatures (those between 25% to 75%)  for June on the left and December on the right with the median temperature indicated by the green line. The lines extending up and down from the box display the maximum temperature (up) and minimum temperature (down) for each month. And the circles indicate the number and temperature value of any data outliers.

    While the numbers shown in the table seemed to be relatively close between the two months for all but one of the statistics, this plot shows extent to which the temperatures in December are cooler and more variable than those in June.

![Box and Whisker Plot for June and December Temperatures](https://github.com/bnidam/Surfs_Up/blob/main/Resources/TemperaturesBoxWhisk_June_Dec.png)

- Histograms: 
    The two figures below are histograms for the June and the December temperature data. 

    The two charts show the frequency distribution of the temperature count data for each month. By using the same scale for both data sets, it is easy to see that
    - there are more warmer temperature counts in June than in December
    - the highest frequency temperature for June is between 77.5-80 degrees, while the highest frequency temperature for December is between 70-72.5 degrees
    - June has no counts in the cooler temperatures (left side of the charte) and December has no counts in the hottest temperature (right side of the chart)

![Histograms for June Temps and Dec Temps](https://github.com/bnidam/Surfs_Up/blob/main/Resources/TemperaturesHistogram_June_Dec.png)

## Summary 
From the analysis of the temperature data and what we learned about Hawaii, surfing and ice cream, it looks like Mr. W. Avy's surf and ice cream shop idea would be sustainable year-round. While sales of surfing items and ice cream are both used and consumed throughout the year, each appear to have a peak season at different times. 

However, this conclusion comes from just temperature data alone. I would recommend further analysis with the following two analysis:

    - Precipitation - the number of days with rain and the amount of rain, along with the correlation, if any, with temperature. Rain could keep the customers away and impact the viability of the surf and ice cream store at any time of year.  This analysis could look at these same months of June and December or could look first at impacts during a calendar year to pinpoint which months should be analyzed with the temperature data.

    - Storm length and severity - the number of days with severe storms and the severity of the storms. The impacts of climate change are frequently in the news headlines. Tropical storms and hurricanes could keep the surf and ice cream store closed. This analysis should look at data for the past decade to see if there are any trends for these storms increasing in frequency, severity, and length of time. If any trends are identified, then potential seasonal trends should be analyzed to see if they correspond to temperature and/or precipitation data.
