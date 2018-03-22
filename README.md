# CHRC Race Paces
An analysis of NYRR race data for the Crown Heights Running Club.  

## Getting Started
This project uses a Jupyter Notebook to read and analyze NYRR data.\
In addition you will need:
- Pandas
- MatPlotLib
- New York Road Runners race data saved as a csv
  - csvs for each race should be saved with the following name convention: race_name_distance.csv
  - ex: staten_island_haf for the Staten Island Half Marathon

## How It Works
The program reads through all the csv files in and complies them into one dataframe. The dataframe can then be grouped by runner, race distance, race, or other factors.\
At present, the data can be used to show:\
![image](https://user-images.githubusercontent.com/26753690/37789887-6c185c40-2ddb-11e8-9cc0-c433adec4326.png)\
the spread of paces in the club, \
![image](https://user-images.githubusercontent.com/26753690/37789751-18d88938-2ddb-11e8-9b0b-882a35dd567d.png)\
changes in pace ranges by race, \
![image](https://user-images.githubusercontent.com/26753690/37791046-917e6198-2dde-11e8-80bc-20d569209344.png)\
and changes in a runner’s pace over the season.

In addition to the fields provided by NYRR, I added fields for race distance and predicted 10K pace. Why did I do this? I wanted a way to compare paces across race distances, and predicted 10K pace is the standard NYRR uses when corraling runners. 

_Data source: New York Road Runners_
