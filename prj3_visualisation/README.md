# Ford GoBike System Data Exploration
## by Lambiv Gills Dzenyuy


## Dataset

The data consists of information regarding 5183412 individaual bike trips with 
15 columns covering the data for Chicago bike share for Febuary 2019.

## Summary of Findings

In the exploring the data, I found that a strong relationship between 
trip durations and user_type. I found a surprising result trends in 
gender, user type and bike share for all trip indicated that most 
cutomers of all gender categories  were associated with
high duraitin. This user type effect on duration was first noticed when 
duration was ploted against user_tyep. When I filtered out trips for each gender category 
and exploited duration trends with other variables user type sitll had a  higher effect on 
trip duration with cutomers who don't use bike share for all trip havaing high duration
than those who don't. Subscriber for each gender for all two categories of bike share for
all trip had less duration than customers. How ever the difference in duration for subscribers 
who use bike share for all trip and those who don't is that much.

Apart from the main variables of interest i investigated trip start day and user birth year with duration and
other  variables of interest and they didn't have that much of effect as the variables of interest.


## Key Insights for Presentation

For the presentation, I focus on just the influence of user type, member gender 
and bike share for all trip on trip duration and leave out most of the intermediate derivations. I start with
a duration distribution on a transformed scale, then followed by the duration against user type to get a general 
overview of how durarion change with respect to user type on a violin plot.

 I then investigate the cateforical values of interest to show each of the relate
 to one anothe t influence trip duration. I use the violin plots of 
 duration  and gender  across user type on bike share for all trip. I then now isolate trips based on gender
 and for each I  investigate duration across user type  on bike share for all trips 
