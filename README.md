# Sales-Prediction--Time-Series-Models
## Business Understanding
The goal here is to build a model that more accurately predicts the unit sales for thousands of items sold at different Favorita stores.
For grocery stores, more accurate forecasting can decrease food waste related to overstocking and improve customer satisfaction.

The goal of the project is to develop a time series model that accurately predicts unit sales at different locations for Favorita stores. This prediction will help them better understand the customers’ needs and avoid stocking items that would not be in demand by consumers.


## Data Understanding
Data used in this project has been sourced from Kaggle; https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data
Seven data sets will be used in this project. The data sets are as follows:

**Train.csv**
This data set includes data on:

-date: day the sale occured
-id: the sales id
-store_nbr: the store at which the sale occured
-sales: total sales for a given product family at a given store at a given date.
-onpromotion: total number of items promoted at a given store at a given date.

The **test.csv** file contains data similar to the training data. The data contains sales information collected 15 days after the train data.

**Oil.csv**

This file contains details on oil prices since Ecuador's economy heavily depends on Oil

**Stores.csv**

This file includes information on store location:

-city: the city a state is located
-state: the state a city is located
-cluster: a group of similar stores
-type: the type of store

[Store Sales Kaggle Competition](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/overview)
