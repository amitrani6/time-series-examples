# Time Series Examples
This repository contains examples of time series analysis.

This repository contains twelve files and one folder:

  1) `data_files` - A folder containing subfolders of `.csv` files for this repository. The subfolders are titled by subject, i.e. `financial_data` contains fundamental data, `price_data` contains stock prices, and `supporting_data` contains general time series data for analysis

  2) **gitignore** - Contains the files excluded from this repository
  
  3) **Obtain_and_Append_Data.ipynb** - A notebook which contains code that appends time series data from an API, to avoid request limitations

  4) **README.md** - This document

  5) **Time Series Stock Sample Data.ipynb** - A Jupyter Notebook containing examples of preparing time series data for analysis
  
  6) **Time_Series_Models_Examples.ipynb** - A Jupyter Notebook containing multiple time series models
  
  7) **Weather_data.ipynb** - A Jupyter Notebook containing a visualization of weather data
  
  8) **fundamental_trend_analysis.ipynb** - A Jupyter Notebook containing analysis of fundamental financial data
  
  9) **requirements.txt** - The requirements file for running the files of this repository
  
  10) **stationarity_check_funtion.py** - Contains a funtion that neatly displays the results of a Dickey-Fuller test
  
  11) **time_series.yml** - A file for replicating the environment required to run the files within this repository
  
  12) **time_series_removing_trends_and_decomposition.ipynb** - A Jupyter Notebook containing the removal of trends for time series analysis
  
  13) **trend_analysis.ipynb** - A Jupyter Notebook containing examples of stationarity
  
  
 # Relevant Articles Written About This Repository:
 
 1) ["Working With Time Series Data"](https://towardsdatascience.com/working-with-time-series-data-a8872ebcac3) (Towards Data Science) - An article about time series data visualizations with matplotlib and Plotly, based on **Time Series Stock Sample Data.ipynb**
 
 2) ["Time Series and Trend Analysis"](https://medium.com/datadriveninvestor/time-series-and-trend-analysis-6a4f255f3d6e) (Data Driven Investor) - An article about time series trend analysis using matplotlib, its mpl component, and statsmodels based on **trend_analysis.ipynb**
 
 3) ["Achieving Stationarity With Time Series Data"](https://towardsdatascience.com/achieving-stationarity-with-time-series-data-abd59fd8d5a0) (Towards Data Science) - An article about stationarity in time series data based on **time_series_removing_trends_and_decomposition.ipynb**
 
4) ["Time Series Decomposition and Statsmodels Parameters"](https://medium.com/@amitrani/time-series-decomposition-and-statsmodels-parameters-69e54d035453) (Towards Data Science) - An article about time series decomposition models using the statsmodels module based on **time_series_removing_trends_and_decomposition.ipynb**
