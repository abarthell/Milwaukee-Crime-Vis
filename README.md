# Milwaukee Crime Visualization 
By: Anthony Barthell

## Motivation
Boasting a population of [nearly 600,000 residents](http://www.city-data.com/city/Milwaukee-Wisconsin.html), Milwaukee is the largest city in Wisconsin. Unfortunately, Milwaukee has been consistently ranked as [one of the most dangerous cities in America](https://www.cbsnews.com/pictures/the-most-dangerous-cities-in-america/40/). As a student at the University of Wisconsin-Madison, I analyzed [Milwaukee's criminal data](https://data.milwaukee.gov/dataset/wibr/resource/87843297-a6fa-46d4-ba5d-cb342fb2d3bb) from the past five years (2014 - Present). The dataset consists of 22 columns, displaying critical information such as **reported date and time, location, district number, and type of crime**. Rigorous data analysis of the records may translate to insightful correlations and potential remedies.

## Data Analysis of Trends
**Assault Offence** was by far the most committed crime in Milwaukee between January 1st, 2014 and July 30, 2019, with a total of 57899 incidents. The subsequent three most committed crimes were **Theft, Vehicle Theft, and Burglary**, which totaled in 35847, 32031, and 29229 incidents, respectively. There is another sharp decline to the following three most committed crimes, which were **Locked Vehicle, Criminal Damage, and Robbery**, totalling in 21555, 21330, and 16808 incidents, respectively. Lastly, the three least committed crimes were **Sex Offense, Arson, and Homicide**, which amounted in 4849, 1539, and 603 reported incidents, respectively.
![Picture](https://github.com/abarthell/Milwaukee-Crime-Vis/blob/master/img/aplot.png)

## Which Hours Are the Most Dangerous?
I initially assumed that most crimes occur during the night, but this surprisngly turned out to be false. The number of crimes steadily decreases from around 10 PM (hour 22 on the plot) with 10336 reported crimes until it levels out from 4 AM to 5 AM with around 3500 crimes. Afterwards, the number of crimes sharply increases to around 10000 by 8 AM. For the remainder of the day until 10 PM (hour 22 on the plot), the number of crimes committed interestingly stays relatively constant, hovering between 10000 to 11900 crimes. The highest number of crimes committed is at 5 PM (hour 17 on the plot), totalling 11883 crimes.
![Picture](https://github.com/abarthell/Milwaukee-Crime-Vis/blob/master/img/bplot.png)

## Which Districts Are the Worst?
Displayed below are the number of crimes committed in the 15 different Milwaukee Aldermanic Districts. 
 
![Picture](https://github.com/abarthell/Milwaukee-Crime-Vis/blob/master/img/cplot.png)

## Future Work
