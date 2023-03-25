# Internship-Project-NYC-Bicycle-Riders-Data-Prediction
Context:-

The New York City Department of Transportation collects daily data about the number of bicycles going over bridges in New York City. This data is used to measure bike utilization as a part of transportation planning. This dataset is a daily record of the number of bicycles crossing into or out of Manhattan via one of the East River bridges (that is, excluding Bronx thruways and the non-bikeable Hudson River tunnels) for a stretch of 9 months.

Content:-

A count of the number of bicycles on each of the bridges in question is provided on a day-by-day basis, along with information on maximum and minimum temperature and precipitation.

Acknowledgements:-

New York City - East River Bicycle Crossings is a open source dataset on Kaggle. It was published by The New York City Department of Transportation on a sample size of 9months. Which consist of 210 days of data and consist of 3 parameters. Mainly High Temperature, Low Temperature & precipitation.

Inspiration:-

1. Which day in the whole nine months has maximum ridership attained?
2. Which day in the whole nine months has minimum ridership attained?
3. To find the Average bicycle riders crossing all four bridges everyday.
4. To understand the relationship between temperature and ridership volume and how this relationship affects our dataset.
5. To design a prediction model based on the linear regression to predict the future volume.

Methodology:-

* We have four bridges in our dataset, Brooklyn Bridge	Manhattan Bridge	Williamsburg Bridge	Queensboro Bridge.
* As a part of Exploratory Data Analysis we will comapare all four Bridges individually with the all three parameters. Which will create a broad understanding about our dataframe.
* For the Prediction model:-
We have use the dataframe in such a way by which we will achieve a linear relation. For attaining it we take High Temperature and Total riders all day as our data.

Observations:-

* For a successful EDA there must be zero null value. In our dataset every coloumn has non null value.
* For 25% days the Higher Temperature was 55°F.
* For 50% days the Higher Temperature was 62.10°F.
* For 75% days the Higher Temperature was 68°F.
* The Maximum Temperature which was observed was 81°F. Which was on 18th April.
* For 25% days the Low Temperature was 44.10°F.
* For 50% days the Low Temperature was 46.90°F.
* For 75% days the Low Temperature was 50°F.
* The minimum Temperature which was observed was 26.10°F.
* Standard Deviation:- a quantity expressing by how much the members of a group differ from the mean value for the group
Standard Deviation for High Temperature was observed 11.18°F.
Standard Deviation for Low Temperature was observed 9.5°F
 
1. Exploratory Data Analysis
* Brooklyn Bridge:-

A). Maximum Daily Bicycle Ridership is turned out to be 3871  on 18/04/2016.

B). ie. 162riders/Hr

C). With Higher Temperature of 81°F and Lower Temperature of 51°F.

D). The Average no of riders crossing Brooklyn Bridge is 2270riders/Day.

E) The Average Temperature fell by an rider is 60.5°F.

F). Every third rider crosses the bridge every minute.

G). The Length of Brooklyn Bridge is 1834m.

H). That means the average distance between the three bicycle riders per minute is 611.3m.

* Manhattan Bridge:-

A).Maximum Daily Bicycle Ridership is turned out to be 6951 on 21/04/2016.

B).ie. 290riders/Hr

C). With Higher Temperature of 71.1°F and Lower Temperature of 50.0°F.

D).The Average no of riders crossing Manhattan Bridge everyday is found out to be 4050riders/Day

E). The Average Temperature fell by an rider is 60.58°F.

F). Every fifth rider crosses the Manhattan Bridge per minute.

* Williamsburg Bridge:-

A). Maximum Daily Bicycle Ridership is turned out to be 7426 on 21/04/2016.

B). ie. 310riders/Hr

C). With Higher Temperature of 71.1°F and Low Temperature of 50°F.

D). The Average no of riders crossing Williamsburg Bridge everyday is found out to be 4863riders/Day.

E).ie. 203riders/Hr

F). The Average Temperature fell by an rider is 60.58°F.

G). Every Fourth rider crosses the Williamsburg Bridge every minute.

* Queensboro Bridge:-

A). Maximum Daily Bicycle Ridership is turned out to be 4813 on 21/04/2016.

B). ie. 200riders/Hr

C). With Higher Temperature of 71.1°F.

D). The Average no of riders crossing Queensboro Bridge everyday is found out to be 3353riders/Day.

E). ie. 140riders/Hr

F). The Average Temperature fell by an rider on Queensboro Bridge is found out to be 60.58°F.

G). Every third person is crossing Queensboro Bridge.


![image](https://user-images.githubusercontent.com/111125394/227701153-12fa3c72-df03-4c4c-b748-e4e15caeee38.png)

  


