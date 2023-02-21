# CitiBikeSharing
Module15

## Overview of the statistical analysis:
Using shared online data from CitiBike, an analysis was completed regarding usage of CitiBikes in New York City during the month of August. 

Using `jupyter notebook` to convert the trip duration to a datetime format, the resulting csv was uploaded into Tableau for analysis.

[Link for Tableau Dashboard] (https://public.tableau.com/views/Module15Challenge_16768341441350/CitiBikeAnalysis?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

## Results:
The data is broken down into three major areas of interest; the gender of the customer, the type of service puchased (one-time purchase or subscription), and when bikes are being used. 
![August Peak Hours](https://user-images.githubusercontent.com/114450503/220230579-32206043-4d64-4695-8222-498921c6ce7e.png)
![Customers by Gender](https://user-images.githubusercontent.com/114450503/220230743-90cae81c-4c0f-4a24-8d1a-48cbe3637534.png)
![Customers by Purchase type](https://user-images.githubusercontent.com/114450503/220230598-1f7c0d0c-325c-45dd-82c1-c82aca6d605b.png)

In the chart below we can see the majority of bikes appear to be used for a maximum of about 60 minutes. 
![CheckoutTimeforUsers](https://user-images.githubusercontent.com/114450503/220230889-a9b93c52-7552-4716-b5d5-e0fcb82e9e2e.png)

When comparing results by gender, we can see the majority of customers are male but the duration of bike usage is the same regardless of gender.
![CheckoutTimesbyGender](https://user-images.githubusercontent.com/114450503/220231020-a277dea0-b80c-4f94-bec4-15338b91777f.png)

As we can see in the below heat map, peak times during the week are around 8am and 5pm. Peak times during the weekend are between 10am and 6pm.

![TripsbyWeekdayperHour](https://user-images.githubusercontent.com/114450503/220231139-5844f324-a020-44a8-8068-d52e54f38653.png)

Again we break out by gender, and we can see that bikes are used around the same times regardless of gender. 
![TripsbyWeekdayperHourGender](https://user-images.githubusercontent.com/114450503/220231272-b280316f-5edc-4164-9007-2bd49190290a.png)

Finally, with the below visual we are able to determine the majority of customers are male subscribers. 
![UserTripsbyGenderbyWeekday](https://user-images.githubusercontent.com/114450503/220231366-b0cb9d72-b08c-424f-aa28-81c80e7e0477.png)

## Summary:
The intent of this analysis was to look into CitiBike success in NYC to see if the business model can be followed in other cities. With this in mind, we can view the above conclusions with the question of "Who would use our bikes?" With the above visualizations we can easily see that the most usage is from men with a subscription, likely for their daily commute to work. This is excellent news because it disproves any worry that the bikes are used by NYC tourists or other one-time customers. This means as long as there are men who work in the city of interest, this could be a viable business plan.

Other visualizations that could help with this analysis:
- A filtered chart for men based on age. This would help determine the best way to market the bikes. 
- We did two maps showing the most-used pickup and dropoff areas, but there were too many dots for the chart to be of much use. Another visualization could be built to only show the top 10 locations used, these spots could be vetted for bike stations.
