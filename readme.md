# Flights Data Exploratory and Explanatory Analysis
## by Parida

## Dataset
>
> This dataset reports flights in the United States for 2008, it consists of various columns related to delay and cancellation of flights. Data source link: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7

## Summary of Findings
>
> Distance has a right skewed distribution, with a lot of flights on the short distance end, and a few on the long distance end. When plotted on a log-scale, the distance distribution looks roughly normal distribution. The flights become limited when the distance increases(more than 3000).
>
> The distribution of Arrdelay is right skewed and mode is around 0. There are few flights which arrived before their time.
>
> The distribution of the delay of departure time is right skewed and the mode is around 0 minutes.
>
> We can see that most of the delays are because of late aircraft, then carrier delays and then NAS delays (minute difference between them). Then we have weather delays and few security delays
>
> We see that as the distance increases the air time increases which is the expected behaviour.
>
> We see that both arrival and departure delays are lesser when the distance increases to a large extent.
>
> There is a positive relationship between arrival and departure delays and distance and air time. there is no significant relationship between departure delays/arrival delays and distance.
>
> We see that arriaval delay is least in April and same goes with departure delay. Both arrival and departure delays are highest in February.

## Key Insights for Presentation
> 
> Flights Delayed By Month:
> We see from the chart that most of the flight delays occur in February.
> 
> Flights Delayed By Day of Week:
> We see from the chart that most of the flight delays occur on Friday.
> 
> Occurence of Delay Types:
> We see that the NAS Delays occur the most and Security Delays occur the least.
