# fbprop
fbprophet examples using covaid-19 dataset

### fb Prophet
Install prophet - https://facebook.github.io/prophet/docs/installation.html

### Start with ...
- covaid-19-notebook-Apr23.ipynb - Global confirmed cases and has the best accuracy. Do note the uncertanity increases beyond a 1 month forecast

### Data set
* https://github.com/CSSEGISandData/COVID-19

#### Dataset setup
Need to get the original and create a timeseries data set with ...
* Column a: Label: 'ds' Data: Date
* Column b: Label: 'y' Data: Count

*The notebooks already have datasets defined this way and they are available in ds folder*

##### TODO : Automate the above steps
