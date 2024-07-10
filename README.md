# Urban-Air-Pollution

# Overview
In parts of many African cities, air quality seems to be getting worse as more people stay at home. For this challenge we’ll be digging deeper into the data, finding ways to track air quality and how it is changing, even in places without ground-based sensors. This information will be especially useful in the face of the current crisis, since poor air quality makes a respiratory disease like COVID-19 more dangerous. We’ve collected weather data and daily observations from the Sentinel 5P satellite tracking various pollutants in the atmosphere.

# Aim
Your goal is to use this information to predict PM2.5 particulate matter concentration (a common measure of air quality that normally requires ground-based sensors to measure) every day for each city. The data covers the last three months, spanning hundreds of cities across the globe.

# Importance of this Challenge
Expanding Coverage: Integrating satellite data allows us to extend air quality predictions to areas without ground sensors, offering a more comprehensive view of air quality.

Enhanced Data Fusion: Combining satellite radar data with ground-based sensor readings creates a more robust and accurate air quality prediction model, leading to better predictions and understanding of air pollution dynamics.

Public Health Impact: Accurate air quality predictions are crucial for public health, enabling timely interventions and raising awareness in regions prone to poor air quality.

# Technologies Used

Python: Python was used for its powerful capabilities in data preprocessing, feature engineering, and building machine learning models. Its extensive libraries and tools make it an ideal choice for handling and analyzing large datasets.

Satellite Data Processing: Specialized tools and libraries were utilized to process and extract relevant information from Sentinel 5P satellite radar data, transforming raw satellite data into meaningful inputs for our models.

Data Analysis: Utilizing tools like NumPy and Pandas for data manipulation and analysis(Visualization).

Machine Learning Models: Advanced regression models, specifically the LightGBM regressor, were implemented to predict air quality readings using both satellite and ground-based sensor data, providing more accurate and reliable predictions.
