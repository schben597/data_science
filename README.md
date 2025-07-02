# My Data Science Projects
This is where I share my progress in data science techniques and present the projects I am working on.

# July 2nd, 2025
Data analysis and workup performed for my Master's thesis at [UPF](https://www.upf.edu/en/web/masterbiomedupf).
Raw data consists of two heating cycles, with absorbance readings at 350 nm taken every minute for each sample condition. I added buffer blanks to adjust for condensation forming on the plate during the first minutes of the measurement. The data, after subtracting the buffer curves, appears jumpy, so I applied a curve-smoothing protocol to fit a logistic function. With the logistic in place, I can calculate the plateau and draw further insights.


# June 2nd, 2025
Building on previous visualizations, incorporating air quality data. European annual air pollution data by country taken from [Eurostat](https://ec.europa.eu/eurostat/databrowser/view/env_air_emis__custom_16946228/default/table?lang=en)
Experimenting with different map types and looking at the relationship between GDP per capita and emissions per capita. 


# May 30th, 2025 - EU State GDP Per Capita Visualization
I obtained GDP per capita data from [Eurostat](https://ec.europa.eu/eurostat/databrowser/view/nama_10r_3gdp/default/table?lang=en). Data is available in high resolution in individual NUTS 3 regions, but to provide a simplified overview, I went for the country level for this one. Using Plotly, I created an interactive map that displays the evolution over the years 2014-2023. 

By rendering the map as a png within the workbook, you can view it on here. For the interactive maps, the code needs to be executed locally.

# May 17th, 2025 - Kaggle Titanic Challenge
The introductory challenge on kaggle.com - I used a logistic regression model to predict the survival rate among Titanic passengers.
I did some basic feature engineering to try and create better insights from the data provided.
In the test data, one passenger had no fare value specified, so I went back to the training data and trained a linear regression model on the fare using my features. The resulting predicted fare was -2 dollars, so I went with a fare of 0 for that passenger.
The final score on kaggle with the predictions from this notebook was 0.76315.
