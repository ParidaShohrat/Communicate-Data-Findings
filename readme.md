# USA Flights Data Exploratory and Explanatory Analysis
## by Parida

## Dataset
>
> This dataset reports flights in the United States for January 2008, it consists of various columns related to delay and cancellation of flights. Data source link: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7

## Summary of Findings
>
> **Univiriate Exploration:**
>
> - **Flights cancellation reason**: carrier and weather are the two most reasons for cancellation, and then is the National Aviation System(NAS). Surprise, there is no cancellation because of security.
>
> - **Day of Week**: Interestingly, the middle of the week (Tuesday, Wednesday, Thursday) have more proportion of flights delay compared to the Weekend (Saturday, Sunday).
>
> - **Distance**: distance distribution is right-skewed. When plotted on a log-scale, the distance distribution looks roughly normal distribution. The flights become limited when the distance increases(more than 3000).
> 
> **Biviriate Exploration:**
>
> - **Arrival Delays and Departure Delays**: it shows a strong positive correlation between arrival delays and departure delays.
>
> - **Carrier and Departure Delays**: Almost all carriers have many outliers, which means carriers sometimes have a severe delay problem that over 1000 minutes. However, it doesn't mean carriers delays all the time. Most of the airlines can depart on time or control the delay less than 20 minutes.
>
> - **Carrier and Arrival Delays**: Arrival delays are right_skewed, we can see that some airlines such as Hawaiian Airlines(HA) and 9 Air Co (AQ) are the two flights with little arrival delays compared to other carriers.
>
> **Multivarite Exploration:**
>
> - **Distance with Arrival and Departure Delays**: with the distance increase, arrival delays and departure delays increase simultaneously.
>
> - **Day of the week with Weather Delay and Arrival Delay**: Wednesday has the most arrival and departure delays. 
>
> - **Relations of different delays**: Carrier delays have the most significant effect on departure delays. 

## Key Insights for Presentation
>
> - **Flights Delay By Day of Week:**
>
> Interestingly, the weekend days have the least number of flights delay over the workdays. The middle of the week has the most flight delays.
> 
> - **Flights Delay By Distance:**
>
> With the distance increase, the arrival delays are decreased overall.
>
> - **Flights Delay by Cancellation Reason:**
>
> There is no flights delayed because of security. SkyWest Airlines(OO) has the most extended NAS delays(C), and Carrier delays(A), and Envoy Airline(MQ) has the most extended Weather delays.
