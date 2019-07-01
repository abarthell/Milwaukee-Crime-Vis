# Milwaukee Crime Visualization 
*Copyright (c) 2019* **Anthony Barthell**

## Motivation
Boasting a population of [nearly 600,000 residents](http://www.city-data.com/city/Milwaukee-Wisconsin.html), Milwaukee is the largest city in Wisconsin. Unfortunately, Milwaukee has been consistently ranked as [one of the most dangerous cities in America](https://www.cbsnews.com/pictures/the-most-dangerous-cities-in-america/40/). As a student at the University of Wisconsin-Madison, I analyzed [Milwaukee's criminal data](https://data.milwaukee.gov/dataset/wibr/resource/87843297-a6fa-46d4-ba5d-cb342fb2d3bb) from the past five years (2014 - Present). The dataset consists of 22 columns, displaying critical information such as **reported date and time, location, district number, and type of crime**. Rigorous data analysis of the records may translate to insightful correlations and potential remedies.

## Data Analysis of Trends
**Assault Offence** was by far the most committed crime in Milwaukee between January 1st, 2014 and June 30, 2019, with a total of 57899 incidents. The subsequent three most committed crimes were **Theft, Vehicle Theft, and Burglary**, which totaled in 35847, 32031, and 29229 incidents, respectively. There is another sharp decline to the next three most committed crimes, which were **Locked Vehicle, Criminal Damage, and Robbery**, totalling 21555, 21330, and 16808 incidents, respectively. Lastly, the three least committed crimes were **Sex Offense, Arson, and Homicide**, which amounted in 4849, 1539, and 603 reported incidents, respectively.
![Picture](https://github.com/abarthell/Milwaukee-Crime-Vis/blob/master/img/aplot.png)

## Which Hours Are the Most Dangerous?
I initially assumed that most crimes occur during the night, but this surprisngly turned out to be false. The number of crimes steadily decreases from around 10 PM (hour 22 on the plot) with 10336 reported crimes until it levels out from 4 AM to 5 AM with around 3500 crimes. Afterwards, the number of crimes sharply increases to around 10000 by 8 AM. For the remainder of the day until 10 PM (hour 22 on the plot), the number of crimes committed interestingly stays relatively constant, hovering between 10000 to 11900 crimes. The highest number of crimes committed is at 5 PM (hour 17 on the plot), totalling 11883 crimes.
![Picture](https://github.com/abarthell/Milwaukee-Crime-Vis/blob/master/img/bplot.png)

## Which Districts Are the Worst?
Displayed below are the number of crimes committed in the [15 different Milwaukee Aldermanic Districts](https://city.milwaukee.gov/Directory/How-to-Run-for-Public-Office/Nomination-Packet-Forms/District-Maps/Map-City-of-Milwaukee-Alderman.htm#.XRlhjpNKjOQ). On the right hand side, we have District 15 as our winner with 21542 total crimes in the past five years. The next six worst districts (7, 6, 1, 4, 12, 2) all had between 17300 and 19100 crimes. There is a sharp decline to the next three districts (8, 9, 3), which had between 12300 and 12600 crimes. The last five districts (5, 10, 14, 13, 11) steadily drop in crimes committed, with district 11 having the lowest of them all at 5951 reported crimes.
![Picture](https://github.com/abarthell/Milwaukee-Crime-Vis/blob/master/img/cplot.png)

## What Weapons are Used?
Fortunately, two-thirds (67%) of the time, weapons were not used during these crimes over the past five years.
<p align="center">
  <img src="https://github.com/abarthell/Milwaukee-Crime-Vis/blob/master/img/dplot.png">
</p>


However, when weapons were used, the following five appeared the most frequently. **Unknown** weapons were used the most often to commit crimes 39.4% of the time. Next, **hands** were utilized 33.3% of the time, most likely during fist-to-fist brawls. **Handguns** were used 14.1% of the time, followed by **personal weapons** at 8.1%. Lastly, **guns** were used 5.1% of the time.

<p align="center">
  <img src="https://github.com/abarthell/Milwaukee-Crime-Vis/blob/master/img/eplot.png">
</p>

## Future Work
Since the latitude and longitude of the crimes are given in the dataset, it would be interesting to apply Deep Learning techniques to predict the probability of crimes being committed in certain areas during certain times (in terms of hours, day, and month).
