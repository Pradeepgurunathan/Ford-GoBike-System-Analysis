# Ford GoBike System Analysis 
### by Pradeep Gurunathan

[Click to preview the Slide report](http://htmlpreview.github.io/?https://github.com/Pradeepgurunathan/Ford-GoBike-System-Analysis/blob/master/Data_Explanatory_Slide_report.slides.html)


[Click to preview the data exploration report](http://htmlpreview.github.io/?https://github.com/Pradeepgurunathan/Ford-GoBike-System-Analysis/blob/master/Data_Explanatory_Slide_report.html)

[Click to preview the data explanatory report](http://htmlpreview.github.io/?https://github.com/Pradeepgurunathan/Ford-GoBike-System-Analysis/blob/master/Data_Exploration_report.html)

## Dataset : Ford GoBike

> The data consists of approximately FordGoBike's 18,50,000 bike rides for public from Jan 2018 to Dec 2018. The features include the trip start/end time, start/end station, duration in seconds as well as additional information such as user type, gender, and birth date. Approximately, 114,000 data points were removed from the analysis due to inconsistencies, such as inaccurate birth date, and a few columns having NaN values. The data can be found [here](https://s3.amazonaws.com/fordgobike-data/index.html), with feature documentation available [here](https://www.lyft.com/bikes/bay-wheels/system-data).


## Summary of Findings

> In the exploration, I found that there are two types of clients using the system: Subscribers who use it for their daily commute, having short trips to and from work, who rent a bike on weekdays at 8-9am and 5-6pm, and Customers, usually tourists or occasional riders who use the system mainly on weekends to explore the Bay Area. The bike share system was used more often around summertime (May-October) with a clear drop from January to March, most probably due to the harsh weather conditions. Moreover, I have checked if there are some differences in trends for genders. In most cases the trend for males/females was the same, except of the fact that females tend to have slightly longer trips and suprisingly, for casual users there are quite a lot of females using the system between January and March in comparison to males (the ratio is much smaller than for the rest of the year).

    

## Key Insights for Presentation

> For the presentation, I  mainly focus on customer renting habits for the year 2018. 
  I start by introducing the split between those who use the system occasionally and those who have a membership. Afterwards, I move to daily and weekly habits of customers. I use the heatmap to show demand of the bikes throughout the week. To finish, I introduce the barplot of age distribution of users of FordGoBike bikes as per user type.
