# COVID19 Data on the USA

Data analysis on the Coronavirus epidemic that is happening in the USA - Comments and suggestions are more than welcome!

## What does it do?

Using the code you will 
- Download the COVID19 data on the US, availabe in another GitHub repository
- Put the data into a DataFrame and filter them
- Run a least-square fit using the Logistic growth model
- Save the data into a folder called Fit_Data
- Plot the data and the fitted model 



## The ource of the the data is the COVID Tracking project and

Page describing the project
https://covidtracking.com

CSV File available on GitHub
https://github.com/COVID19Tracking/covid-tracking-data/blob/master/data/states_daily_4pm_et.csv

## How to use the code?

- Open COVID19_USA_DataAnalysis.ipynb and run it. It has no outputs. Close it.
- Open COVID19_USA_Plots.ipynb and plot what data you are interested in

There are two Jupyter Notebook files:

- COVID19_USA_DataAnalysis.ipynb

This file contains the code to perform a least-square fit on the available data on the US. It fits the data to a Logistic model. It performs the fit and stores the outcome in the folder Fit_Data. It contains no output. You can simply run it and then close it.

- COVID19_USA_Plots.ipynb

This file contains the code to visualize, data, the corresponding fit and save your plot. Two functions will be used to look at the data: **plot_fit_by_indicator** and **plot_fit_by_state**. The notebook contains the explanation about how to use these functions. Here we simply report, at readers' convenience, the indicators you will be able to look at are.

### Data available in the USA and the state-wise database

- **date** = date of observation
- **states** number of states with covid-19 cases
- **positive** number of tests with positive result
- **negative** number of tests with negative result
- **posNeg** sum of positive and negative
- **pending** number of tests with pending result
- **death** number of death cases
- **total** total number of cases

## What else is in it?

- The folder **Fit_Data**, where the output of COVID19_USA_DataAnalysis.ipynb will be stored in the form of .CSV files. These files are organized in two sub-folders: Indicators, States, where the respective data are stored.

- A folder **Plots**, where the output of COVID19_USA_Plots.ipynb will be saved, in the form of a .PNG file. These plots are organized in subfolders. The names of the subfolders are consistent with the way the data is analized: ByState and ByIndicator


