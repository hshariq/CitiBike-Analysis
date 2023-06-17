# CitiBike-Analysis Tableu

### Problem Statement
"Optimizing Urban Mobility: Unleashing Actionable Insights from Citi Bike Usage Data"

The task at hand is to create a dynamic, visually appealing Tableau dashboard to deliver a meticulous analysis of the Citi Bike dataset. 

### EDA and Cleaning Perfomed:
Visit the Jupyter Notebook to get an overview of data cleaning and EDA applied throughout the project

## Dashboards:

### User Profile:
![UP](https://github.com/hshariq/CitiBike-Analysis/blob/main/img/Screenshot%202023-06-10%20225528.png)

This dashboard provides a comprehensive overview of trip durations, age distribution, gender, and user types, allowing for an in-depth analysis of user behavior and preferences.

### Trip Profile:
![TP](https://github.com/hshariq/CitiBike-Analysis/blob/main/img/Screenshot%202023-06-10%20225701.png)

This dashboard offers valuable insights into the most popular start and end stations, peak start times, and popular routes, enabling a thorough understanding of usage patterns and facilitating strategic decision-making for the Citibike network.

As a CitiBike business, there are two most important elements of my business: 

Customer Segmentation:
What type of users most use the bikes. One of the main things for us is to make sure we attain high user satisfaction, engagement, and loyalty. We operate in a region of high competition, hence this element for our business is severely important. By gathering information such as user demographics, user types, and age groups, our project incorporated user profiling into the analysis of the Citibike dataset. Moreover, based on this User Profiling we would like to target specific customers to further increase the use of bikes, and achieve a higher stream of customers.

Optimizing Bike Station Placement
In a city like New York CitiBike would like to ensure that all the bikes are optimally placed in areas that encourage a high demand from bikers.  To tackle this problem, the BI project utilized historical data from CitiBike. By analyzing this dataset, our team identified popular areas and routes, peak demand times, and underutilized stations.

We will be solving our Customer Segmentation using our User Profiling Dashboard

### Gender:
![G](https://github.com/hshariq/CitiBike-Analysis/blob/main/img/Screenshot%202023-05-31%20143006.png)

We can see a clear Majority of Male, however Female also participate in high trip durations. Unknown gender is a problem for us, we need to refine our collection methods such that percentages of Unknown decreases.

### Age:
![age](https://github.com/hshariq/CitiBike-Analysis/blob/main/img/Screenshot%202023-05-31%20143101.png)

We can see that trip duration is very evenly divided between 20–50-Year-olds. These are Customers that are independent, and are financially held, hence CitiBike is a viable option. <20 and 60+ is in minority, showing that our labourous product is not suitable for these ages.  

### User Type, total trip duration:
![UTTTD](https://github.com/hshariq/CitiBike-Analysis/blob/main/img/Screenshot%202023-05-31%20143118.png)

Who are these types? Subscriber are users that have bought a subscription over a certain period of time. These are constants, that will be charged a fixed amount irrespective of their trips. Customers are those that on their way for one time use buy our services. 

### User Type, average trip duration:
![avg](https://github.com/hshariq/CitiBike-Analysis/blob/main/img/Screenshot%202023-05-31%20144915.png)

Interesting find, when we look at the average trip duration, we see that Customer type has a much higher average TD. These are one time users, hence we should devise a package, that sets the price by trip duration. Higher TD, higher price leading to maximizing revenue.

Further analysis of User types led us to this chart:

![scat](https://github.com/hshariq/CitiBike-Analysis/blob/main/img/Screenshot%202023-05-31%20145346.png)

We can clearly see that our customers are less spread compared to Subscriber. An interesting find shows that for some ages, like 45-50, and 30-35, our customers peak at trip durations. This suggests that our customers that generate higher TD’s, are in this age bracket.  On the other hand, customers of ages, 70+ are very scarce. This suggests that most of our customers are tourists, and high age people do not travel much, and due to obvious health reasons avoid biking.

![s1](https://github.com/hshariq/CitiBike-Analysis/blob/main/img/Screenshot%202023-05-31%20145505.png)

On the other hand, with Subscribers we generate a steady stream of usage. The chart is well spread and says that for all ages it is generating high TD’s. The frequency of 70+ users is much higher, showing that old people that have a structured schedule, along which they operate use our bikes. This could be for recreational purposes. Since old people are not bounded by any schedules, a subscription helps them to keep their activity levels high. 

![s2](https://github.com/hshariq/CitiBike-Analysis/blob/main/img/Screenshot%202023-05-31%20150008.png)

Next we look at how our genders are spread by User types.

![hyt](https://github.com/hshariq/CitiBike-Analysis/blob/main/img/Screenshot%202023-05-31%20150544.png)

For subscribers we see that male are in majority, however female produce over 800k records, which clearly means that despite the relative small percentage, we should not ignore them as a valuable customer.

![hytt](https://github.com/hshariq/CitiBike-Analysis/blob/main/img/Screenshot%202023-05-31%20150602.png)

Next for customers, we have a vert interesting find. All of Gender Unknown, lie in the Customer type of our dataset. Zero instances of Unknown exist in subscriber. Which shows, that for the registration process of our customers, we should generate a form that ensures a reply. We can do this by compulsory fields or adding options to cater for all. This would enrich our data, and allow to grow with better quality of data.

![h](https://github.com/hshariq/CitiBike-Analysis/blob/main/img/Screenshot%202023-05-31%20150930.png)

### Peak Hours:
![peak](https://github.com/hshariq/CitiBike-Analysis/blob/main/img/Screenshot%202023-05-31%20151710.png)

Our top 3 peak hours are: 
8 am
5 pm
6 pm
These are very well distributed by age, and we can see majority lies in the age bracket of 25-50, showing most of our users are working people and use our product as a mean of commute.

We will be solving our Optimizing Bike Station Placement using our Trip Profiling Dashboard:

We have frist started by looking at the total distance travelled each month. For this we have used the visualization below.
![dm](https://github.com/hshariq/CitiBike-Analysis/assets/114312270/1c34e0e3-7cd3-4b57-9d30-1f2b5541baa1)

We can clearly see that there is an overall increase in total distance travelled which indicates that stakeholders should be able to accommodate new customers.


### Peak Hours by Weekdays
![pewd](https://github.com/hshariq/CitiBike-Analysis/assets/114312270/7d2e493f-2ae8-49dd-ab13-506ae30cb548)

The heatmap provides a visual representation of the busiest times for bike usage throughout the week. This information could be used to predict peak usage times and ensure there are enough bikes available during these periods. For example there should be ample amount of bikes on tuesday 8 o’clock in the morning.

### Most Popular Starting Stations:
![pss](https://github.com/hshariq/CitiBike-Analysis/blob/main/img/Screenshot%202023-05-31%20032507.png)

Top 10 Start and End Stations: The two bar graphs represent the most popular stations for users to start and end their trips. This data might indicate areas with the highest demand for bikes. For instance, if "8 Ave & West st 31" frequently appear as top start and end stations, it suggests these areas are bustling hubs of activity. Similarly, if there are stations that consistently appear in the top 10 for both start and end points, it could indicate a popular commuting route or a high traffic area.

![topall](https://github.com/hshariq/CitiBike-Analysis/assets/114312270/7a880fd7-d695-45f6-a2c5-2ac34160443b)

This tree map provides another perspective on the most popular stations, potentially highlighting any differences in station popularity based on the number of trips versus unique users. For example, a station might rank high on the bar graph (suggesting many trips begin or end there), but lower on the tree map if the same users are making multiple trips.

### Top 10 Routes
![t10](https://github.com/hshariq/CitiBike-Analysis/blob/main/img/Screenshot%202023-05-31%20022601.png)
![t10map](https://github.com/hshariq/CitiBike-Analysis/assets/114312270/6763d7b3-943c-44df-a240-ea0f346f1468)


The table and accompanying map together show the most frequently used routes by Citi Bike users. The color coding helps users understand which start and end stations are connected, providing a visual narrative of how people move around the city. For instance, if a route between "Central Park South & 6th Avenue" and "West St & Chambers St" is particularly popular, it might suggest a common commute path or a scenic route favored by tourists.

### Insights and Findings:
•	There is a majority of male bikers however there are also female bikers.
•	Trip duration is evenly distributed among age from 20 to 60 indicating our main customers
•	Overall trip duration is heavly dominated by subscribers with a majority of 81% approximately however average trip duration is dominated by customers.
•	Customers are less spread as compared to subscribers with respect to age. The age groups 45-50 and 30-35 are the main contributors of peak trip duration among customers indicating mostly tourist.
•	Among subscribers there is an even spread in TD however, people with age 70 and above have a high increase as compared to customers.
•	Among our subscribers, male are in majority, however the number of female subcribers are over 800k, which clearly means that despite the relative small percentage, we should not ignore them as a valuable customer.
•	All our unknown genders lie among the customers indicating that the data collection of customers needs improvments.
•	Our top 3 peak hours are 8pm, 5pm and 6pm
•	There is an overall increase in the total distance travelled and total number of bikers across months.
•	The most popular starting and ending station is 8 Avenue West St 31.
•	The most busiest days are Tuesday, Wednesday and Thursday at 8.00 to 9.00 and 17.00 to 18.00.
•	The most used route is E 7 st & Avenue A.


### Recommendations:
•	Provide more faciclity for female drivers.
•	Since average trip time of customers is high so rates should be changed from customers to maximize profit.
•	Since there are 70+ customers as well, facilities should be provided.
•	Resource balancing could be done to incorporate increasing customers at peak stations.
•	More stations should be made in order to incorporate increasing number of users every year.
•	Analyze the 'user type' and 'birth year' data to gain insights into which demographic groups are most likely to become subscribers. Targeted marketing campaigns could be developed based on these insights.
•	With the help of 'start time', 'start station', and 'end station', you can create a trip planner feature. This feature could suggest the fastest route, predict the availability of bikes at the start station, and the likelihood of a free slot at the end station at a particular time.
•	Analyze the 'start' and 'end' station data to understand where users are commonly starting and ending their journeys. If these locations correlate with public transport hubs, there might be opportunities to integrate with public transport services to provide a more comprehensive transport solution.



 
