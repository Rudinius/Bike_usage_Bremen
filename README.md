# Bike_usage_Bremen
Data analytics and forecasting of bike usage in Bremen, Germany

In this project the values of different bicylce counting stations in the city of Bremen, Germany are analyzed. The goals are:

* Visualize datasets and get a deeper understanding of the presented data
* Answer general questions about the data like:
  * Is the bike traffic increasing/decreasing or approximately constant over time?
  * Did the COVID pandemic have an influence on the bike usage?
  * What are the most used bike ways and why?
* Train a machine learning model, to accurately forecast the bike traffic for a given day. For this different ML models should be used and compared to a baseline model.

The data ranges from 01.01.2013 to 31.12.2022. In addtition to the data of the bicycle counting stations, further data (weather data, geo-locations, national holidays, school vacations) are added.

This project contains 3 notebooks:
 * 1_Data_Prep
 * 2_EDA
 * 3_Model_Training

In the first notebook 1_Data_Pred the datasets are loaded, described and prepared and column names are formatted as well as different datasets are joined together and lastly exported for the next step.
In the second notebook 2_EDA the data is analyzed indepth, about e.g., missing data, data distribution and correlations. The missing data and outliers are handled and the dataset is exported for the last step.
In the last notebook 3_Model_Training the dataset is finally prepared for learning algorithms and different algorithms are being tested.

**Note:**
This project is optimized to be used with Google Colaboratory because of higher computational power and GPU resources compared to my local dev enviromnet. Some code blocks (e.g., the export of .csv files) will only work in Google Colaboratory environment. 
