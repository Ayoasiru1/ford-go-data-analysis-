# ford-go-data-analysis-
##  Dataset Overview
The dataset includes information about individual rides made in a bike-sharing system 
covering the greater San Francisco Bay area of the ford gobike for the month of February 
2018. It comprises of 183412 rows and 16 columns. 
The information in the dataset include:
	> Trip Duration (seconds)
	> Start Time and Date
	> End Time and Date
	> Start Station ID
	> Start Station Name
	> Start Station Latitude
	> Start Station Longitude
	> End Station ID
	> End Station Name
	> End Station Latitude
	> End Station Longitude
	> Bike ID
	> User Type 
	> Member Year of Birth
	> Member Gender
	> Bike Share for all Trip.

## Investigation overview

The analysis of this dataset was carried out to identify the key factors that explain the
duration of trip taken by the users of the company services. The dataset was intially 
visually and programmatically assessed to determine the extent of cleaning that is 
necessary to work with the dataset. Rows with incomplete data were dropped bringing the 
total number of rows analysed to 174592 rows of data. The distribution of the categeories 
of users and the age of users of the company's service was explored using a bar chart. The
distribution of the duration of the ride was explored using a histogram however, the 
cluster was huge for duration lesser than 10000s, therefore a log transformation was 
applied on the x-axis (duration). This revealed a uniform distribution for the duration of
the ride. The duration of rides during the various hours of the day was analysed using a 
barchat. Further exploration was done to investigate the relationship between the age of 
the user, the gender and the duration of the trip. 

## Key insights of the presentation

> For the company, the Subscribers number about 160,000 while customers are around 20,000. Subscriber to customer ratio is about 8:1

> The distribution of both customers and users follow similar trend with the largest range accounted for by the age group 23 - 32

> The distribution of the duration of the trip is unimodal and right skewed with a peak around 600s.

> Younger users between age 20 and 60 tend to take longer trip than older users

> Male user between the age 20 and 55 tend to take longer trips the other two genders

> The distribution of the number of rides by the starting hour is bimodal.

> The trend of duration of trip does not significant differ across sharing of trips or gender. However, duration of trips decreases with increasing age in all categories
