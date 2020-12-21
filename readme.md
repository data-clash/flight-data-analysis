# Flights Data Exploration
## by Anuja Jadhav


## Dataset 

> This project is divided into two major parts. In the first part, I conducted an exploratory data analysis on a Flight delay dataset (Source: https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp?pn=1 - From Jan 2009 to Jan 2019) from United States. I used Python data science and data visualization libraries(Pandas, Matplotlib,Seaborn) to explore the dataset’s variables and understand the data’s structure, oddities, patterns and relationships. The analysis in this part is structured, going from simple univariate relationships up through multivariate relationships. I considered carrier delay in minutes, number of carrier delays , number of carrier diversions and number of carrier cancellations to answer the question: Which carrier(s) has shown consistently good performance with respect to carrier delay,arrival diversions, arrival cancellations for 10 years (2009 to 2019)?
There is no one single answer out of a given dataset and this part of the project is to ask questions of the data and make discoveries. 

For the fairness of analysis, only the airlines which flew more than 8 years between 2009 and 2019 are chosen. Each performance KPI is normalized into a ratio (KPI / total flight arrivals for an airline ) to generate 4 new KPIs:

1. Cancellation Ratio = Total Cancellation of the carrier in the year / Total Flight arrivals in the year
2. Diversion Ratio = Total Diversion of the carrier in the year / Total Flight arrivals in the year
3. Carrier Delay Ratio = Total Number of Carrier Delay of the carrier in the year / Total Flight arrivals in the year
4. Average Carrier Delay (Minutes) Ratio = Total Carrier Delay minutes of the carrier in the year / Total Carrier Delays in the year

In the second part, I took the main findings from the exploration and conveyed them to others through an explanatory analysis. To this end, I created a slide deck that leverages polished, explanatory visualizations to communicate the results. I chose relevant visualizations along that path, and polish them to construct a story for your readers. 

## Summary of Findings

> In the multivariate plots, it was clear that carrier delays and carrier delay minutes show no co-relation.
> The numerical variables were initially normalized with a ratio transformation. As it was observed not all airlines flew all 10 years. 
> Carrier arrival delays seemed to be the most affected problem followed by flight cancellations and finally flight diversions. > Carrier delays (in minutes) was roughly unimodal with most of the airlines having an average delay of 59min.


## Key Insights for Presentation

>Overall we can say that 2012, there were least airline problems than other years.
>All time Lowest Average Carrier Delay Minutes: Hawaiian Airlines
>All time Lowest Number of Carrier Delays: Alaska Airlines
>All time Lowest Cancellation Ratio: Hawaiian Airlines
>All time Lowest Diversion Ratio: Hawaiian Airlines

## Feedback (From a friend) 
> What do you notice about each visualization?
Lot of information in line charts. Heatmaps are easy to understand. 
> How would it be easy to understand line charts?
Increase font. Remove borders of charts. Put legend out of chart. Explain the Ratios earlier. 
> What questions do you have about the data?
Successful flight arrival information is missing. 
> What do you think is the main takeaway from the slide deck?
Hawaiin Airline was the best performing airline.


