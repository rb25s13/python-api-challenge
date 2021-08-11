# What's the Weather Like?
 __________________
< where ya headed? >
 ------------------
                        ^__^
                        (oo)\_______
                        (__)\       )\/\
                            ||----w |
                            ||     ||
							
#### Use Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"


### Conclusions:

		The plots of temperature vs latitude clearly show that the temperatures are increasing as you get 
		closer to the equator. The increase in temperature is due to this area getting more direct sunlight.
		
		The linear regression of humidity vs latitude indicate that there is not a clear relationship
		between the two variables. There is a cluster of plots on the higher end of the humidity spectrum
		near the equator, but our linear regression is nearly flat.
		
		Based on the google maps and heatmap, we can see that the cities that are closer to water, typically
		have a higher humidity percentage. The scatter plot of latitude vs humidity has a small cluster near
		the equator, but the rest of the data does not have a clear correlation. 
		
							
							
### Contents:

        /output_data - contains csv files with city data set and images of graphs
        /VacationPy - ipynb for generating a heat map for humidity and pull in hotels for certain parameters
        /WeatherPy - ipynb for getting the weather data for a random list and plotting the data