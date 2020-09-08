# DataPreparation-ExploratoryAnalysis
Data Preparation (Pre-processing) &amp; Exploratory Analysis_Temperature_Readings

This data analysis demonstration is based on a dataset comprising 'In-Out' temperature measurements from IOT devices (location: India). This work has been initially focused on data preparation/manipulation of the imported dataset features to apply all necessary data preprocessing/cleaning methods by use of numpy and pandas (i.e. dropping/adding columns to the dataframe,column rename,'Date' feature conversion to datetime object and use as index, feature engineering to extract datetime categories, detection & dropping of duplicate records, applying the map function and use of interpolation(linear,polynomial to fill missing temperature entries).

In addition, an exploratory data analysis is presented so as to extract useful information from the 'temperature' feature with the help of data visualization techniques (i.e. pie & bar charts, count/distribution/box/scatter plots). The scope of the EDA is to uncover meaningful insights related to key 'temperature' dataset column characteristics such as a) the amount of 'temperature' observations per class ('In-Out' temp entries--> balanced/unbalanced dataset), b) the 'temperature' density estimation, c) 'temperature' time series distribution and d) 'In/Out temperature' min/max/mean/median values when grouped at different time periods (hours,days,months).

The Dataset (.csv file format) for this project has been obtained from Kaggle:

"Temperature Readings : IOT Devices" -- File: "IOT-temp.csv" -- Source:https://www.kaggle.com/atulanandjha/temperature-readings-iot-devices
