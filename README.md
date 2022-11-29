# Discogs_NUFinTechFinalProject
 
## *Package Requirements and Versions*
pip install x ; where 'x' is the package listed below:

`python == 3.7.13+`

`scikitlearn`

`pandas == 1.3.5+`

`fbprophet`

## *Files Navigation*

*Resources:* 
Directory containing all images of plots created in Jupyter Notebook, and original csv data files can be located at - https://github.com/cyndercone2/Discogs_NUFinTechFinalProject

*Discogs_NUFinTechFinalProject.ipynb:* 
Data exploration investigating csv files and API connections, cleanup of dataframes, and final dataframes and all graphs.

## *Project Overview*
In this project I set out to see if I could predict the value of a given record over time. This can help inform future investments on records. Specifically, I used data from Discogs.com, one of the largest databases for audio in the world. 

Discogs has API, but the API does not contain any sales data. I was able to pull my wantlist from the API, that helped me identify the specific releases sales data I wanted to work with. After identifying the specfic release ID from my wantlist, I was able to add that to the Ultimately, I copied and pasted the data and coverted it into a csv. 

I used fb prophet to forecat the future values of the record based on the historic sales data. I also used the plot components feature to identify what days of the week were the most likely to experience and increase or decrease in value of the record. 


## *Conclusion*
The project could be expanded to automatically pull record data if a way to get around the recaptcha mechanism existed on the sales history page. 

## *References*
- https://towardsdatascience.com/how-to-interpolate-time-series-data-in-apache-spark-and-python-pandas-part-1-pandas-cff54d76a2ea
- https://sailajakarra.medium.com/facebook-prophet-for-time-series-cf26be1be274
- https://towardsdatascience.com/what-does-rmse-really-mean-806b65f2e48e


