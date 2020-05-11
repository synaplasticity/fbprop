# fbprop
fbprophet examples using covaid-19 dataset

### fb Prophet
Install prophet - https://facebook.github.io/prophet/docs/installation.html

### Start with ...
- covaid-19-notebook-global-confirmed-cases.ipynb - Global confirmed cases and has the best accuracy and completely automated. Do note the uncertanity increases beyond a 1 month forecast

### Data set
* https://github.com/CSSEGISandData/COVID-19

#### Dataset setup
(Except for covaid-19-notebook-global-confirmed-cases.ipynb. This notebook does that for you)

For older notebooks, do the following ...
* Get https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv and copy to "ds" folder
Need to get the original and create a timeseries data set with ...
* Column a: Label: 'ds' Data: Date
* Column b: Label: 'y' Data: Count

*The notebooks already have datasets defined this way and they are available in ds folder*

