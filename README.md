# hotel-data-analysis
## Data analysis project - SQL and Power BI

The aim of the analysis is to answer the questions posed by stakeholders:

- Is our hotel revenue growing by year?
- Should we increase our parking lot size?
- What trends can we see in data


Let's take a preliminary look at the data (from the database):

![image](https://user-images.githubusercontent.com/33282870/222798075-c883012e-6815-49f4-a243-10d3ac844a85.png)

We will now combine the tables and create a data source for further analysis in Power BI:

![image](https://user-images.githubusercontent.com/33282870/222798334-8804444f-afc1-4ab0-a146-bbd86682e8d0.png)

As the accommodation in the database is divided into weekdays and weekends, we create a new column in which we will sum both values:

![image](https://user-images.githubusercontent.com/33282870/222798706-ed11d7ca-e58c-4c86-b699-8de9e0597bf8.png)

It is worth mentioning that the split between weekdays and weekend days will be very useful in further analyses.

What proportion of parking spaces were required by hotel customers (broken down by year and hotel)? It should be noted that the data needs to be more granular, as this allows us to better understand trends and adjust future investments:

![image](https://user-images.githubusercontent.com/33282870/222800047-f1897d31-6530-44e4-af47-17eb2a5bf849.png)


### Final dashboard:

![image](https://user-images.githubusercontent.com/33282870/222797442-62d50868-21a0-41a8-aff6-793711b902b8.png)

Link to repo: https://github.com/marcin-pawlowski/hotel-data-analysis 

The idea and data for this analysis came from the https://absentdata.com/ website and YT tutorial.
