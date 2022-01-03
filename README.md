# What's the weather like as we approach the equator?


<details>
<summary> Tools, Languages, & Libraries Utilized</summary>
<li>Python</li>
<li>Pandas</li>
<li>NumPy</li>
<li>Google Maps API</li>
<li>Open Weather Map API</li>
<li>Requests</li>
<li>Matplotlib</li>
<li>SciPy - Lingress</li>
<li>VS Code</li>
<li>Jupyter Notebook</li>
</details>


#### Use Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"

							
### Contents:

        /output_data - contains csv files with city data set and images of graphs
        /VacationPy - ipynb for generating a heat map for humidity and pull in hotels for certain parameters
        /WeatherPy - ipynb for getting the weather data for a random list and plotting the data

### Conclusions:

The plots of temperature vs latitude clearly show that the temperatures are increasing as you get 
closer to the equator. The increase in temperature is due to this area getting more direct sunlight.
<br />
<img style="margin:0 auto;display:block" src="./output_data/Southern Hemisphere - Max Temperature vs. Latitude Linear Regression.png">
<br />
<br />
<img style="margin:0 auto;display:block" src="./output_data/Northern Hemisphere - Max Temp vs. Latitude Linear Regression.png">
<br />
The linear regression of humidity vs latitude indicate that there is not a clear relationship
between the two variables. There is a cluster of plots on the higher end of the humidity spectrum
near the equator, but our linear regression is nearly flat.
<br />
<img style="margin:0 auto;display:block" src="./output_data/Southern Hemisphere - Humidity (%) vs. Latitude Linear Regression.png">
<br />
<br />
<img style="margin:0 auto;display:block" src="./output_data/Northern Hemisphere - Humidity (%) vs. Latitude Linear Regression.png">
<br />
Based on the google maps and heatmap, we can see that the cities that are closer to water, typically
have a higher humidity percentage. The scatter plot of latitude vs humidity has a small cluster near
the equator, but the rest of the data does not have a clear correlation. 

<br />
<img style="margin:0 auto;display:block" src="./output_data/heatmap.png">
<br />		
							
