# My Data Science Projects
This is where I share my progress in data science techniques and present the projects I am working on.

# May 17th, 2025 - Kaggle Titanic Challenge
The introductory challenge on kaggle.com - I used a logistic regression model to predict the survival rate among Titanic passengers.
I did some basic feature engineering to try and create better insights from the data provided.
In the test data, one passenger had no fare value specified, so I went back to the training data and trained a linear regression model on the fare using my features. The resulting predicted fare was -2 dollars, so I went with a fare of 0 for that passenger.
The final score on kaggle with the predictions from this notebook was 0.76315.

# May 30th, 2025 - EU State GDP Per Capita Visualization
I obtained GDP per capita data from [Eurostat](https://ec.europa.eu/eurostat/databrowser/view/nama_10r_3gdp/default/table?lang=en). Data is available in high resolution in individual NUTS 3 regions, but to provide a simplified overview, I went for the country level for this one. Using Plotly, I created an interactive map that displays the evolution over the years 2014-2023. 
