# Bike-Share-PowerBI-project-Dashboard

### Dashboard Link : 

## Problem Statement:
To uncover valuable and unexpected hidden insights from the data, answering business questions and providing strategic recommendations.

### Process/steps followed:
Step 1 ; Firstly, I got this dataset from Kaggle and downloaded it.
Step 2 : Secondly, I extracted the file and named it Bike share data analysis on my computer and since it had a number of same files, I decided to then save everything I extracted into one folder so I can just combine the whole CSV file in power bi.
Step 3 : Thirdly, after saving the whole file in one folder, about 12 csv files I extracted, into one folder, I named it again as Bike share data set.
Step 4 : I then opened power Bi to start work. So I exported the whole folder containing the files from my desktop to power bi and then chose the combine and transform data option.
Step 5 : After choosing to combine all the files in the folder as one, I needed to do a little transforming before anything else in order to make my visualization work easy. So I first looked through my dataset and realized not all the information was going to be relevant so deleted these columns.(start station name, start station id, end station name, end station id, start_lat, start_lng, end_lat, end_lng)
Step 6 : I then proceeded to changing a few title names for my work. So I changed rideable_type to Ride/Bike type, and changed member_casual to rider.
Step 7 : I then checked for null values or blanks.
Step 8 : I again decided to split the started_at and ended_at column which contained the date and time of the activities. So I extracted the time values from the date values and ended up with some new columns. Mainly, start Date, End Date, Start Time and End Time.
Step 9 : From here, I needed to work out the duration per bike id so I just created a new column and worked out the durations there.
Step 10 : The next and final step was to create a new table as my calender date where I can work out the months and weekdays from that calender table. So I did that, and then since it’s a new table I had to create a relationship with the main data table which is bike share data. So yhh.

### Some Business Questions or KPIs to answer from this project :
 What is the number of rides per month and rider type?
 what is the total rides per rider type?
 what is the total number of rides by bike type?
 what is the total bike rides by weekday and rider type?
 what is the total number of rides by bike type and rider type?
 find the total rides?
 what is the total ride duration?
 what is the average ride duration?
 What is the maximum ride duration?
 What is the busiest ride day?

 ### Key insights 
 ## What is the number of rides per month and rider type?
 1. The chart shows that, the total rides for members overall was higher than for casual type riders at member types (3127293) and casual type riders (2540693).
 2. Also, from the chart, it shows that a lot of riders participated more in July than any other month by 7.80% of the total.
 3. Total Rides for member and casual diverged the most when the Month was November, when member were 146120 higher than casual.

## what is the total rides per rider type?
1. Total Rides for member type riders which is (3127293) was higher than casual type riders which is (2540693).
2. Also, Member type riders accounted for 55.17% of Total Rides.

##  what is the total number of rides by bike type?
1. Total rides by classic bike type far exceeded the remaining two at 3268797 total rides followed by electric bikes at 2087901 total rides and finally docked bikes at 311288 total rides.

## what is the total bike rides by weekday and rider type?
1. Saturday in Rider casual made up 9.83% of Total Rides.
2. Average Total Rides was higher for member (446,756.14) than casual (362,956.14).
3. Total Rides for member and casual diverged the most when the Weekday was Wednesday, when member were 206020 higher than casual.

## what is the total number of rides by bike type and rider type?
1. classic bike in Rider_member made up 35.30% of Total Rides.
2. Average Total Rides was higher for member TYPE RIDERS (1,563,646.50) than casual TYPE RIDERS (846,897.67).
3. Total Rides for member and casual diverged the most when the Ride/Bike Type was classic bike, when member were 733229 higher than casual.

##  find the total rides?
 Total rides equals 6 million

## what is the total ride duration?
 Total Duration across amounted to 83 million

## what is the average ride duration?
 Average Ride duration amounted to 14.60

## What is the maximum ride duration?
 Maximum ride duration for this data set amounts to 59

## What is the busiest ride day?
 The busiest day for the entirety of the project was on saturday.




