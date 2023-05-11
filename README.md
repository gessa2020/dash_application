# Dash application
## A dash application to monitor and report US domestic airline flights performance
![](IMAGES/front.jpeg)
## Introduction
This is a dash application project to monitor and report US domestic flights performance for the year range between
2005 to 2020 inclusive. It's one of the projects that i did in the IBM Data Analyst Professional Certificate program.
The goal is to analyze the performance of the reporting airline to improve flight reliability thereby improving customer reliability.

The Report has two key items as shown below:
- Yearly airline performance report 
- Yearly average flight delay statistics
![](IMAGES/Report_Design.jpg)

The yearly airline performance component consists of the following for each chosen year:
- A bar chat showing number of flights under different cancellation categories 
- A line chat showing average flight time by reporting airline 
- A pie chart showing percentage of diverted airport landings per reporting airline 
- A choropleth map showing number of flights flying from each state 
- A treemap showing number of flights flying to each state from each reporting airline

The yearly average flight delay statistics component consists of the following for each chosen year:
- Monthly average carrier delay by reporting airline
- Monthly average weather delay by reporting airline 
- Monthly average late aircraft delay by reporting airline for the given year.
- Monthly average security delay by reporting airline for the given year.
- Monthly average late aircraft delay by reporting airline for the given year.

##  Problem statement 
- Which airlines have the highest number of flights to destination states?
- Which  states have the highest number of flights  originating from there?
- what is the average monthly flight time in minutes by most airlines?
- what is the average carrier delay time in minutes for various airlines?
- what are the common causes of carrier delays?
- What is the average late aircraft delay time in minutes by airlines?


## Skills demonstrated.
- Python was used for coding the project together with some appropriate python libraries
- I used Visual Studio code to develop the application and launch it in the web browser.

## Data sourcing
The dataset used in this project was provided by the skills network labs. To access it click  <a href="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/Data%20Files/airline_data.csv">HERE</a>  
The sample Dataset contains information about US domestic airlines.It includes information about the airlines and the 
states where these airlines conduct business together with other relevant information used in this project.
The airlines include:
| AIRLINE           | AIRLINE_CODE |  AIRLINE          | AIRLINE_CODE                   |
| ----------------- | -------      | ----------------- | -------------------------------|
| Alaska Airlines   | (AS)         | Frontier Airlines  | (F9)                          |
| Allegiant Air     | (G4)         | Hawaiian Airlines  | (HA)                          |
| American Airlines | (AA)         | JetBlue Airways    | (B6)                          |
| Delta Air Lines   | (DL)         | Southwest Airlines | (WN)                          |
| Sun Country Airlines| (SY)       | United Airlines    | (UA)                         |
| ViaAir            | (VC)         | Virgin America     | (VX)                          |
| Endeavor Air      | (9E)         | Envoy Air          | (MQ)                         |
| ExpressJet        | (EV)         | GoJet Airlines     | (G7)                          |
| Mesa Airlines     | (YV)         | Piedmont Airlines  | (PT)                         |
| PSA Airlines      | (OH)         | Republic Airways   | (YX)                         |
| SkyWest Airlines  | (OO)         | Southwest Airlines | (WN)                          |

The US states together with thier abbreviations used in the project are listed in the table below.
| STATE             | ABBREVIATION |  STATE             | ABBREVIATION               |
| ----------------- | -------      | -----------------  | ---------------------------|
| Alabama           | (AL)         | Alaska             | (AK)                        |
| Arizona           | (AZ)         | Arkansas           | (AR)                         |
| California        | (CA)         | Colorado            | (CO)                         |
| Connecticut       | (CT)         | Delaware           | (DE)                          |
| Florida           | (FL)         | Georgia            | (GA)                         |
| Hawaii            | (HI)         | Idaho              | (ID)                         |
| Illinois          | (IL)         | Indiana            | (IN)                         |
| Iowa              | (IA)          | Kansas            | (KS)                         |
| Kentucky          | (KY)         | Louisiana          | (LA)                         |
| Maine             | (ME)          | Massachusetts     | (MA)                          |
| Maryland          | (MD)         | Michigan           | (MI)                          |
| Minnesota         | (MN)         | Wyoming            | (WY)                          |
| Wisconsin         | (WI)         | West Virginia      | (WV)                         |
| Washington        | (WA)         | Virginia           | (VA)                           |
| Vermont           | (VT)         | Utah                | (UT)                          |
| Texas             | (TX)        | Tennessee            | (TN)                          |
| South Dakota      | (SD)        | South CarolinaX      | South Carolina(SC)            |
| Rhode Island      | (RI)         | Pennsylvania        | (PA)                          |
| Oregon            | (OR)         | Oklahoma            | (OK)                          |
| Ohio              | (OH)         | North Dakota        | (ND)                         |
| North Carolina    | (NC)        | New York             | (NY)                          |
| New Mexico        | (NM)         | New Jersey          | (NJ)                          |
| New Hampshire     | (NH)         | New Hampshire       | (NH)                          |
| Nevada            | (NV)          | Nebraska           | (NE)                          |
| Montana           | (MT)          | Missouri           | (MO)                          |
| Mississippi       | (MS)          |  Oklahoma          | (OK)                          |

## Data analysis and visualization
Graph showing 2005 flight performance![](IMAGES/Perf_2005.jpg)
### key points from the graph above
- The top three Airlines that had highest number of flights to destination states were; Southwest Airlines (WN) which had 34 flights heading to california, followed by  American Airlines (AA) with 33 flights heading to Texas and then Delta Air Lines (DL) with 26 flights whose destination was Georgia (GA).
- Southwest Airlines (WN) had the highest percentage of flights reported of about 16.1%, followed by American Airlines (AA) with 9.64% of reported flights and then Envoy Air (MQ) with 9.05% of reported flights.
- We realise that the top five states which had the highest number of flights originating from there were California with 117 flights,Texas with 108 flights, Florida with 77 flights, Illinois (IL) with 73 flights and Georgia (GA) with 60 states
- Month 1 had the hightest number of monthly flights with cancellation codes, A and B whereas month 4 and 5 did not have any flights with any cancellation code reported
- The top three airlines that had flights with the highest average monthly flight time are; JetBlue Airways (B6) with about 350 minutes of flight time followed by Hawaiian Airlines (HA) with a flight time of about 300 minutes and then Continental Airlines(CO) with flight time of about 250 minutes.

Graph showing 2005 airline carrier delay![](IMAGES/Delay_2005.jpg)
### key points from the graph above
- SkyWest Airlines (OO) had the most average carrier delay of about 250 minutes in the seventh month
ExpressJet (EV), American Airlines (AA) and Northwest Airlines (NW) are the major airlines that experienced weather delays in minutes in certain months of the year.
- Alaska Airlines (AS) is the major airline that experienced a security delay in minutes reported of about close 50 minutes in month 6.
- United Airlines (UA) experienced the most average late aircraft delay time of about 350 minutes in the third month 
- Airtran Airways(FL) experienced the second most average late aircraft delay time of about 200 minutes in month 3
- Average late aircraft delay by most airlines is about 50 minutes

Graph showing 2010 flight performance![](IMAGES/Perf_2010.jpg)
### key points from the graph above
- The top four airlines which had the highest number of flights to destination states were American Airlines (AA) with about 35 flights to Texas, followed by SkyWest Airlines (OO) with about 26 flights to california(CA),
then Southwest Airlines (WN) which had 25 flights to california and tied with Delta Air Lines (DL) which
also had 25 flights to Georgia (GA).
- We can see that top 5 states that had the highest number of flights originating from there inclluded Texas with 124 flights, followed by california with 96 flights followed by Georgia with 78 flights and Florida with 78 flights as well, followed by Illinois (IL) with 56 flights
- It can also be noted that month 2 and 12 experienced the most number of flights with various cancellation codes

Graph showing 2010 airline carrier delay![](IMAGES/Delay_2010.jpg)
### key points from the graph above
- Most average carrier delay time experienced by airlines were not more than 50 minutes on average.
- Envoy Air (MQ),SkyWest Airlines (OO) and Delta Air Lines (DL) were the main airlines that experienced varying weather delays in minutes at different months
- Envoy Air (MQ) and Continental Airlines(CO) are the airlines that majorly also experienced NAS delay time in minutes.
- There were no flights that experienced dalays related to security matters that were reported.
- Airlines such as Endeavor Air(9E),Southwest Airlines (WN) and American Airlines (AA) are the airlines whose flights experienced the most average aircraft delays, with Endeavor Air(9E) experiencing the highest delays of upto 120 minutes followed by Southwest Airlines (WN) and then American Airlines (AA) with least delays.

### Cluster building
To perform clustering, we had to preprocess the data using principle component analysis algorithm to produce two principle componets as our dimensions to be used in the clustering process.These were used to generate the clusters as seen in the image above. Further anlysis was performed to find the ideal number of clusters to be used in our data.We considered the ideal number of clusters to be used as 3 that can be seen in the graph above.

Graph showing cluster analysis with data![](IMAGES/clusterstat.jpg)
Having performed some statistics on the generated clusters, we can draw the following conclusions
1. Cluster 1 has the highest average income of about 13k and average age of 46 years.This can be considerd as a high value target cluster for banking products such as loans and savings.
2. Cluster 2 has the least average income of about 9.4k and has the least average age of 29 years. This can be a target cluster for bank products such as mortgage and credit card
3. Cluster 0 has a moderate average income of about 9.7k and has the higest average age of 84 years. This can be a target cluster for bank products such as pension


## Final model buiding and evaluation
Model performance graph![](IMAGES/modal_image1.png)

A range of models were trained on the data and their performance assessed as seen in the bar graph above.
The gradient boosting classifier and the Random forest model were the best performing classifers.
Further analysis was performed to know which of them was the better model.The Random forest emerged as the slightly better model by comparing the performance of thier classification reports and confusion matrices. 
The best performing model was saved for use in the streamlit application.

## Model deployment
Streamlit Application user interface![](IMAGES/streamlitapp.jpg)

## Conclussion

1. The clusters generated give us some useful information about our customer base such as their average income,
   age,debt to income ratio, education and years employed. 
2. We can use the statistics about these clusters to know where each customer belongs to.
3. With this information, we can then be able to tailor our bank products such as savings, loans, mortgage
   credit card to specific customers depending on the cluster they belong to for better performance of marketing     campaigns.













