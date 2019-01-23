## Flight-Statistics-Dashboard

### TEAM MEMBERS:
* Ananya Yetigadda
* Gabriela Cantu
* Shruthi Elkal
* Shubha Prashanth
* Tinku Supakar

### Project Description:
The project demonstrates visualizations with multiple views on the same data, each of which is able to drill down into the data based further in each view. Our visualizations show different views on flight delay data across major, airports, airlines, routes and months of the year. The visualization story follows average arrival and departure delays and attempts to analyze the hidden causes of these delays. Using publicly available data from Bureau of Transportation Statistics (BTS), the overall goal of this project is to investigate the general basis of flight delays and identify airlines, airports and routes with the highest delay rates.

### Dataset
The original dataset pertaining to flight delays (2013-2018) was downloaded from the Bureau of Transportation Statistics (BTS) website which stores, analyzes and maintains the transportation data.  The data set analyzed contains information for 14 carriers and 316 airports. The data was downloaded as .csv file which made it easy to read into python using the csv module. During the exploratory data analysis, more than 100 variables, were examined for insights in this project. The variables we mainly considered were:
* Numerical continuous variables: Year, Month, number of flights, Arrival delay, Departure Delay
* Categorical variables: Airports, Carriers
* Categorical variables with continuous values: Delay causes
* Calculated continuous variables: Flight Delay (%), Avg Arrival delay, Avg Departure Delay
https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp 

In addition, for the exact geo locations for each airport, we used the dataset from the following website.
https://opendata.socrata.com/dataset/Airport-Codes-mapped-to-Latitude-Longitude-in-the-/rxrh-4cxm


