# Solar_Forecasting

In this project and paper, the theory behind five common machine learning models is presented, as well as their application to the problem of forecasting near-term solar irradiance. The models examined are: linear regression, ridge regression, lasso regression, decision trees, and feed-forward neural networks. The challenge of accurately forecasting solar radiation will become increasingly relevant to society as solar photovoltaics are continually added to the electrical grid, thus motivating the application of these models to this task. While none of the models presented here can match the accuracy of state-of-the-art weather models, solar forecasting provides an important test case on which to demonstrate their relative capabilities.

The weather data used in this project is downloaded from the National Renewable Energy Laboratory's (NREL) National Solar Resource Database (NSRDB) (https://maps.nrel.gov/nsrdb-viewer/). Data is collected from the following city locations:

![Map of locations from which weather data was collected](/Images/City_Data_Sources.png)

Data_Prep.ipynb extracts the raw data from the downloaded .csv files and cleans and prepares the data for further processing.

A detailed explanation of the five machine learning models as well as summaries of the application of these models to the data is presented in Final_Paper.pdf.

The code used to generate this paper is contained in Comparing_ML_Algorithms_for_Solar_Forecasting.ipynb.

Clustering.ipynb uses K-nearest neighbors to cluster the weather data and determine the transition probabilities between clusters in an attempt to determine if there are different weather dynamics that arise in different states.
