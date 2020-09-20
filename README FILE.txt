Exploratory Phase
## Introduction
The dataset under investigation is the flight data which contain key details for domestic flights in USA for 2019. The data was obtained from the Bureau of Transportation Statistics (https://www.transtats.bts.gov/Fields.asp?Table_ID=236) which contains large volume of information on various transportation methods. The dataset consist of about 7.4 million flights and  48 columns which include tail number, carrier code, destination and origin airport, arrival and departure delay, causes of delay, date, cancellation reasons, airtime, distance e.t.c


## Data Exploration
The first step was to download the dataset month by month for 2019. After downloading the monthly data was merged through the following steps; glob package was used to iterate through the monthly data, pandas read function used to read the monthly data and the pandas concat fnction was used to merger into a large data set (air_time.csv).
Note: Due to the data size and internet connectivity only the dataset for 2019 could be downloaded.
I assessed data the using pandas functions and methods for data assessment checking data characteristics and areas that require cleaning. 
Minor cleaning was donne which include convert of date to datetime format, dropping of unwanted columns, changing data type for some columns.
The data exploration and visualization started with looking at some general numbers   ATL (William B Hartsfield-Atlanta Intl) showed the highest number of departure and arrivals while the least numbers were seen in AKN (King Salmon Airport). 
Friday and Monday accounted for most travel. This is closely followed by Tues, wed and Sun which show activity level close to Friday and Monday. The high activity on friday and Monday would mostly be from those heading for or coming back from weekend holiday trips in other cities, states or countries.
Of all the scheduled flights only a small fraction 1.82% were cancelled which is a fairly good record. Cancellation were mostl due to severe weather issues which is actually justifiable but the high amount coming from Carrier reason are worth investigating if there is a drive to improve efficiency in the aviation industry.  Can technology help us in anyway?
Aside from flight cancellation which seems like an area for further investigation delays are also very critical. Out of the over 7.2 million successful flights in 2019, 2.23 million flights were delayed.  Mostly as a result of National Aviation system delays. This resulting from non-extreme weather conditions, airport operations, heavy traffic volume, and air traffic control. Second most common reasom is late aircraft arrival  and Carrier delays. Late Aircraft is never independent and it result from other source of delays. If we can keep carrier delays low maybe NAS and Late Aircraft will reduce drastically. It all about keeping to schedules and timelines.
Of all the airline South West Airline seems to be notorious both for delays and cancellation. Though has made the most flight across USA in 2019, it still need to improve in terms of efficiency. Looking at the main causes of the delay in terms of the 17 airlines available in the data. SouthWest Airline has the highest counts in terms of Late Aircraft and Carrier delays. The truth is once there is a delay by the airline it most likely results in aircraft delays somewhere else
The area of delays and cancellation are worth investigating majorly among the top five airline has they seem to be the most affected. Not just delay count but also delay time because the one main reason why aviation is so much cherished is because of TIME. 


### Key insight from the Explanatory phase

South West Airline has the worst performance in terms of cancellation with over 33000 flight cancelled this is followed by American Airlines.
 
Delta Airline has the least number of cancellation just over 1800 flights though it is the second most active airline in USA. Based on this we can see better organizations in fkight scheduling compared to other airlines
Although Weather account for the highest reason for delays we can see over 30% carrier delays resulting from inefficient in airline operation
Southwest Airline has more cancellations resulting from carrier delays than weather.

Also in terms of delays SouthWest Airline has the most delays resulting mainly from carrier delays.

Delta and United Airlines have the least number of Carrier delays, which is quite a good record whe compared to the other three airlines

Aside from looking at the delays counts, delay time is key and as expected carrier delays and late aircraft delays. When airline fail to keep strictly to there schedule we not only have carrier delays but also Late aircraft as the most trips are round trips. Late departure means late arrival at the destimation. And those who have been scheduled to travel with the flights will also be delayed and the cycle goes on and on. Now you see airline operations need to be more efficient!!!!

Southwest Airline has the longest delay time, not really surprised based on what we have seen earlier. Of all the top five airline, United Airline surprisingly seem to have the best record in term of length of Carrier delays.

-Could SouthWest Airline be doing more than its capacity. When scheduling and planning airline need to stay within there capacities to avoid unforseen delays.

The final ranking developed based on carrier cancellation and carrier delays United  Airline came top closely followed by Delta. Delta seems to stand out for me because been the second most active it is been able to keep a fairly good record in terms of delays and cancellations.

The truth is delays and cancellation resulting from weather, security and NAS are almost unavoidable. Safety is key for the aviation industry. Late Aircraft and Carrier delays need to be really looked into in airline operation. More specificially carrier delays and cancellation if reduced to the bearest minimum will surely affect other forms of delays most especially NAS and Late aircraft delays and cancellations.

Keeping to schedule, not going beyond its capacity and putting up the best in terms of technology will go a long way to imporve their performance.
