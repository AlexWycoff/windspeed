# windspeed: Wind Speed Prediction with Synthetic Data
This repository hosts the code used and data generated throughout the research process for my publication "Evaluating the effectiveness of synthetic training data for day-ahead wind speed prediction in the Great Lakes."

## Requirements
Python 3.11 and the following libraries:

- Pandas
- Numpy
- Matplotlib
- Seaborn
- Geopandas
- Requests
- Scikit Learn
- TensorFlow
- Keras

## Notebooks

The code used throughout this project is divided into three notebooks:

1. Data Retrieval: Functions to retrieve data from the  National Renewable Energy Laboratory (NREL) Wind Resource Database (WRDB).
2. Data Analysis: This notebooks hosts exploratory analysis of the retrieved data, including distributions and correlation of variables and geographic analysis.
3. Model Comparison: The primary notebook for the project. This notebook hosts code that cleans synthetic data retrieved from the NREL and observational data from the Lake Michigan Wind Assessment, then trains LSTM models on data from each dataset. We evaluate what effect training parameters such as length of training data, batch size, and epochs of training have on both models, allowing us to create a neutral testing ground for the two models.

## Data

In this project, we use data from the NREL's National Offshore Wind (NOW-23) Great Lakes dataset and the Lake Michigan Wind Assessment. Both sources are attributed in the research paper outline included in this repository.
