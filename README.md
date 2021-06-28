# surfs_up

***Overview of the analysis:***

The purpose of this analysis is to provide W. Avy with more information about temperature trends before opening up his surf and ice cream shop. W. Avy wants temperature data for the months of June and December in Oahu. This data will allow him to determine if the surf and ice cream shop will be sustainable year-round.

***Results:*** 

Using Python, Pandas functions and methods, and SQLAlchemy, we filtered the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June. We then converted those temperatures to a list, created a DataFrame from the list, and generated the summary statistics.

1. Deliverable 1:
- we wrote a query that filtered the date column from the Measurement table to retrieve all the temperature for the month of June.
- we then converted the June temperatire to a list.
- we then created a DataFrame from the list of temperatures for the month of June.
- we generated the summary statistics for the June temperature DataFrame.

Gatheirng this information allowed us to come up with the following table:

<img width="171" alt="June_temps" src="https://user-images.githubusercontent.com/83566868/123574781-20c85c00-d796-11eb-9026-805dbe720116.png">

2. Deliverable 2:
- we wrote a query that filtered the date column from the Measurement table to retrieve all the the temperature for the month of December.
- we converted the December temperature to a list.
- we created a DataFrame from the list of temperatures for the month of December.
- We generated the summary statistics for the December temperature DataFrame.

Gathering this information allowed us to come with the following table:

<img width="157" alt="Dec_temps" src="https://user-images.githubusercontent.com/83566868/123574745-0f7f4f80-d796-11eb-83b4-f96fc5061b9a.png">

***Summary:***

The conslusion to the analysis is that both June and December are very similar in temperature. The analysis for both June and December shows that there is a high chance that W. Avy can have a high chance of making profit during those two months. Since the data shows that the temperature are not as hot, it still shows a very comfortable time for people wanting to eat ice cream. There could be that possiblity of surfing to not be as popular due to the weather, but maybe having a survey in town to find out if people still like to surf when it is not as hot can also help W. Avy gather feedback to see if it will be worth it or not. Although when running additional queries to gather more weather Data for both months, such a precipiation. We gathered that December does have a little bit more precipiation, but not a huge difference where it can effect the opening up of the surf shop. 

<img width="334" alt="June_prcp" src="https://user-images.githubusercontent.com/83566868/123576902-6d149b80-d798-11eb-8b6b-13ad25ec3830.png">

<img width="329" alt="Dec_prcp" src="https://user-images.githubusercontent.com/83566868/123576956-89183d00-d798-11eb-9a80-cba43b23de26.png">




