# COVID-19-Spread-Rates-to-Large-Cities-Popular-Venues-Correlation-Study
IBM Capstone Study on the possible impact top venues in a city have on COVID-19



COVID-19 Spread Rates to Large Cities Popular Venues Correlation Study

Summary

Much has been documented about preventative measures to help individuals from catching the COVID-19 Virus, those range from hand washing, staying 6 feet apart, avoiding crowded places, isolating yourself, and wearing a mask. 

January 21st, 2020 was the day the first case of COVID-19 was confirmed in the United States. The entire World has been affected by the virus, no place on earth is now free of it. Some communities have been affected more than others and researchers try to make sense of what affects certain cities more than others.

It is easy to assume the higher the population, the higher the rate of COVID-19 cases, but it does not end there. There are several studies, research papers, and articles studying population characteristics that contribute to the faster spread of COVID-19. Many agree that one of the reasons for some cities’ infection rate larger than others cannot not be merely reduced to population size, or the density. The size of the family household has to be taken into consideration as well. 

This study aims to not only analyze the relationship that population and average household size have on Coronavirus cases, but also checks if other population characteristics have an influential relationship. A different approach will be taken in this study. Not only demographics will be used in the comparison of cities, but also Foursquare API to explore the cities’ most popular venues, and how that relates to the infection rate.

As you will see throughout the study, the type of the business can lead to a larger impact on the number of cases reported.


Interest:

This study is not trying to establish health recommendations; rather to provide a different perspective to individuals in our local and federal government involved in policy writing with respect to COVID-19. Additionally, it provides a different way of thinking about the problem to average citizens and researchers.


The Data:

Acquisition:

For this analysis, the data was acquired as follows:
COVID-19 cases: Data was selected based on top 10 states affected by Coronavirus. With the CDC Covid Data Tracker, I was able to find links to each state’s Coronavirus website. The data was at county level.
County and City information: To find information about each county, I used Census Gazetteer Files. From there I was able to retrieve counties gazetter national files which had cities and counties as well as unique identifiers as FIPS and GEOID. I was able to also get places gazetteer files which provided me with cities latitude and longitude for geographic mapping.
County and City Demographics: Demographics information, such as Population, Persons per Household, Density, and Median Income were collected from the census quickfacts page.
Foursquare API was used to obtain the top 5 most common venues per city. 

