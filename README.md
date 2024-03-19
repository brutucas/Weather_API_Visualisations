# Weather_API_Visualisations

## Project Reflection: Weather Analysis as We Approach the Equator

## Background

Exploring the true power of data, whether it's financial, political, or social, has always fascinated me. It's the definitive answers that data provides to questions that intrigue me the most. This curiosity led me to utilize my knowledge of Python requests, APIs, and JSON traversals to delve into a fundamental question: "What's the weather like as we approach the equator?"

At first glance, the answer seems obvious - it gets hotter. But how would I prove it scientifically? This project provided the perfect opportunity to explore this question in depth.

## Setting Up

I kicked off the project by creating a new GitHub repository as a creative outlet for this investigation. After cloning the repository to my local machine, I added two main scripts: `WeatherAPI.ipynb` and `VacationAPI.ipynb`, which would be the backbone of my analysis. I then pushed these initial changes to GitHub to track my progress.

## Part I - WeatherPy

The main challenge was to analyze the weather of over 500 cities worldwide, varying in distance from the equator, using the OpenWeatherMap API. This task required not just technical skills but also a bit of common sense to create a representative model of weather across world cities.

### Creating Scatter Plots

I began by generating a series of scatter plots to explore various relationships between weather conditions and latitude, including temperature, humidity, cloudiness, and wind speed. After each plot, I took the time to explain the findings, offering insights into what the data was revealing about weather patterns relative to the equator.

### Conducting Linear Regression

The next step involved running linear regression analyses on the same relationships, this time separating the data into Northern and Southern Hemispheres. This division allowed for a more nuanced understanding of how weather variables change with latitude in different parts of the world. After generating each pair of plots, I provided explanations on what the linear regression was modeling, discussing any noticeable relationships and additional analyses.

### Data Collection and Visualization

A crucial aspect of this project was the methodical collection of weather data for at least 500 unique cities, using a series of successive API calls. I meticulously logged each city as it was being processed, including the city number and name. Finally, I saved all the retrieved data into a CSV file and generated data visualisations for each scatter plot to visually document my findings.

## Conclusion

This project was not only a testament to the power of data in answering fundamental questions but also an incredible opportunity to enhance my skills in data analysis and visualization. As I delved into the relationship between weather patterns and latitude, I gained valuable insights into the practical applications of Python programming, API interactions, and statistical modeling in the realm of environmental science.
