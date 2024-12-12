Bike Rental Prediction

Objectives:

Perform exploratory data analysis (EDA) and visualize the data to understand the environmental and seasonal settings.
Predict bike rental counts based on environmental and seasonal settings using a machine learning algorithm.

Skills Involved:

Exploratory data analysis
Data manipulation
Data visualization
R programming
Machine learning

Problem Statement:

Bike-sharing systems automate the process of renting bikes from one location and returning them to another. The company wants to predict the number of bikes rented daily based on environmental and seasonal factors.

Dataset Description:

Variables and Descriptions:

instant: Record index
dteday: Date
season: Season (1: Spring, 2: Summer, 3: Fall, 4: Winter)
yr: Year (0: 2011, 1: 2012)
mnth: Month (1–12)
holiday: Weather day is a holiday or not
weekday: Day of the week
workingday: 1: Working day (not a weekend/holiday), 0: Otherwise
weathersit: Weather situation
1: Clear/few clouds
2: Mist/cloudy
3: Light snow/light rain
4: Heavy rain/ice pellets
temp: Normalized temperature (Celsius)
atemp: Normalized feeling temperature (Celsius)
hum: Normalized humidity
windspeed: Normalized wind speed
casual: Count of casual users
registered: Count of registered users
cnt: Total count of rented bikes (casual + registered)

Tasks to Perform (in R):

1]Exploratory Data Analysis:

Load the dataset and relevant libraries
Perform data type conversions
Handle missing value analysis
Attribute Distribution and Trends

2]Plot monthly distribution of total bikes rented:

Plot yearly distribution of total bikes rented
Use boxplots for outlier analysis

3]Dataset Preparation:

Split data into train and test sets

4]Model Creation:

Use the Random Forest algorithm to create a model

5]Performance Prediction:

Predict and evaluate the model on the test dataset
