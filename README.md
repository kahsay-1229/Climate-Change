Analyzing air quality of 400 densely populated cities 
Project Motivation
With the recent COVID-19 that started in China and proceeded to be the most destructive and deadly Virus in history - and which significantly affected air quality - air quality was on the forefront of our minds and we found it prudent to do analyses of the air quality of different cities around the world. , we decided to analyze which cities were most affected by these factors and which cities were less affected. Based on the data we found, we were able to assess what factors contribute to air quality and air pollution.
Challenges
Tools used for ETL, analysis, and visualizing
We used a wide range of tools with differing use cases to complete this project.
* BreezoMeter API
* Mapbox
* Jupyter Notebook
* Python (Pandas, Flask)
* MongoDB
* HTML/CSS
* JavaScript libraries:
o D3 (Data Driven Documents)
o Chart.js
o Bootstrap
o Leaflet
Brief overview of tool usage
1. We used Jupyter Notebook to insert the city latitude and longitude parameters from the CSV and feed it into the URL template.
2. After ensuring we could iterate through the rows in our CSV and we could successfully enter the coordinates contained in the CSV and the parameters we were interested in looking at into URL template, we wrote a Python script that would allow us to create a connection to our local MongoDB server on our machine.
3. We stored the features we requested for every city in our CSV file  in our MongoDB server.
4. Map Visualization: Using the Leaflet JavaScript Library 
5. Graph Visualization: We visualized the date from the 10 cities with the best rated AQIs, the 10 cities with the lowest rated AQIs, and the 10 most populous cities in bar chart form to allow us to compare how the different air quality parameters compared across the 5 best/worst/most populated cities.
6. City Dashboard Visualization: We created a dashboard to access data from any particular city the user selected within a drop-down menu that allowed the user to see the AQI score, pollutant levels, and general recommendation on what to do based on the air quality.
Conclusion
The top 5 highest cities were located in China. China is home to many manufacturing and industrial factories and is the hub for industries like automotive, biopharmaceutical, iron and steel, agricultural product processing, and mineral mining and quarrying industries. These industries are found to emit a wide range of pollutants in large quantities. The data also supports high population contributing to the air pollution problems in China.
The top 5 lowest cities were scattered all over the world. These countries were found, for the most part, to have industries that had an overall positive/less negative impact on the environment and had lower (not necessarily low) populations compared to cities with more toxic air. We concluded that many cities (like Stockholm, Sweden) made conscience efforts to cut down carbon dioxide emissions and fossils fuels by implementing wind and solar technology for their energy needs.
. Covid-19 impact
COVID 19 has been an overall negative situation as it continues to unfold causing US unemployment, countless casualties, and a state of panic and fear. However, by Americans and the world staying home our global air quality has improved overall, with US cities like NYC having a 30% drop in Nitrogen Dioxide (NO2) levels and China (most polluted country in the world) had a 40% drop in NO2 between December 20, 2019 to March 16, 2020. Though encouraging, scientists predict once lockdowns have been lifted, air quality will return to pre-COVID 19 levels.


