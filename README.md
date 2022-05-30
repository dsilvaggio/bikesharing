# bikesharing
## Overview
  Analysis was performed on citibike data from August in New York City to help investors determine if a similar bike share program would be viable in Des Moines, IA. The analysis will be used to complete a proposal for how a similar bike share program will function in a new city. Citibike data for the month of August was downlaoded in CSV format from their webiste. Pandas was then used to transform the "tripduration" column into a datetime datatype. A new CSV with the converted column was exported to create visualizations needed for the proposal.
## Link to the Tableau Story
[Link to Tableau](https://public.tableau.com/shared/QDRMX5QBD?:display_count=n&:origin=viz_share_link)
## Results
  For NYC Citibike data, there are definite trends on the types of users as well as when and where bikes are being used. 
  ### 1) Types of users
 A majority (65%) of citibike users are male. Most users (81%) are subscribers, or people who have purchased an annual pass instead of a day pass. 

![This is an image](https://github.com/dsilvaggio/bikesharing/blob/main/images/Screen%20Shot%202022-05-28%20at%205.10.56%20PM.png)

### 2) Checkout Times
The most common checkout time is only 5 minutes. The gender of the user has no influence on how long they checkout a bike for, since all genders showed 5 minutes as their most common checkout tme. 

![This is an image](https://github.com/dsilvaggio/bikesharing/blob/main/images/Screen%20Shot%202022-05-28%20at%205.14.19%20PM.png)

![This is an image](https://github.com/dsilvaggio/bikesharing/blob/main/images/Screen%20Shot%202022-05-28%20at%205.14.28%20PM.png)

### 3) Trips by Weekday
During the week, peak riding hours are in the mornings (6am - 9am) and evenings (5pm - 8pm). On the weekends, peak hours are during the entire afternoon (8am - 8pm).

![This is an image](https://github.com/dsilvaggio/bikesharing/blob/main/images/Screen%20Shot%202022-05-28%20at%205.19.23%20PM.png)

During the week, both males and females are have similar peak hours. A majority of rides from unknown users are being taken on the weekends. 

![This is an image](https://github.com/dsilvaggio/bikesharing/blob/main/images/Screen%20Shot%202022-05-28%20at%205.22.10%20PM.png)

### 4) August Peak Hours
Peak hours for bike usage are 5pm, 6pm, and 8am. Non-peak hours are between 1am and 5am. 

![This is an image](https://github.com/dsilvaggio/bikesharing/blob/main/images/Screen%20Shot%202022-05-29%20at%205.33.40%20PM.png)

### 5) Trips by Gender by Weekday
Bikes are used primarily by male subscribers, followed by female subscribers. 

![This is an image](https://github.com/dsilvaggio/bikesharing/blob/main/images/Screen%20Shot%202022-05-29%20at%205.36.01%20PM.png)
## Summary
Key findings after this analysis include:
1) Male subscribers make up the largest percent of users. They are using bikes primarily during work commute hours.
2) An ideal time to do bike repairs would between the hours of 1am and 5am.  
3) A subscription service for users to pre pay for the entire year should be offered.
4) The target market are male subscribers using bikes for work transportation and other weekend events. 

Two additional visualizations that I would suggest for future analysis are:
1) Starting and Ending locations by user type as well as gender to determine if where bikes are being targeted makes a difference by gender and user type.
2) Number of trips taken by age to determine your target age demographic.  
