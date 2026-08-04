# **🚕 Ola Ride Data Analytics – End-to-End Project**



###### An end-to-end Data Analytics project on Ola ride booking data using SQL, Power BI and Excel to extract business insights on ride trends, revenue, cancellations and ratings.



### **Project Objective:**



###### To analyze Ola ride data and answer real-world business questions such as:

###### 

* ###### What is the daily ride volume trend?
* ###### Which vehicle types generate maximum booking value?
* ###### Why are rides getting cancelled?
* ###### Which customers contribute the highest revenue?
* ###### How do customer and driver ratings vary across vehicle types?



### **Tools \& Technologies:**



* ###### **SQL (MySQL) –** Data querying \& view creation
* ###### **Power BI –** Interactive dashboard \& KPIs
* ###### **MS Excel –** Initial data cleaning \& validation



### **Dataset Description:**



###### **Column Name → Description**

* ###### Date, Time → Ride date \& time
* ###### Booking\_ID → Unique booking ID
* ###### Booking\_Status → Success / Cancelled / Driver Not Found
* ###### Customer\_ID → Unique customer ID
* ###### Vehicle\_Type → Prime Sedan, Mini, Bike, Auto, etc.
* ###### Pickup\_Location, Drop\_Location → Ride locations
* ###### V\_TAT, C\_TAT → Turn-around times
* ###### cancelled\_Rides\_by\_Customer → Customer cancellation reason
* ###### cancelled\_Rides\_by\_Driver → Driver cancellation reason
* ###### Incomplete\_Rides, Incomplete\_Rides\_Reason → Incomplete ride details
* ###### Booking\_Value → Revenue of ride
* ###### Payment\_Method → Cash, UPI, Card
* ###### Ride\_Distance → Distance travelled
* ###### Driver\_Ratings, Customer\_Rating → Ride ratings



### **SQL Analysis Performed:**



* ###### Retrieve all successful bookings
* ###### Average ride distance by vehicle type
* ###### Total cancelled rides by customers \& drivers
* ###### Top 5 customers by total bookings
* ###### Driver cancellation due to personal \& car related issues
* ###### Max \& Min driver ratings for Prime Sedan
* ###### Rides paid using UPI
* ###### Average customer rating per vehicle type
* ###### Total booking value of successful rides
* ###### All incomplete rides with reasons



###### All SQL queries and views are available inside the **[sql](sql/)** folder.



### **Power BI Dashboard Pages:**



###### **Pages → Insights**

* ###### Overall → Ride Volume Trend, Booking Status Breakdown
* ###### Vehicle Type → Total \& Successful Booking Value, Avg Distance
* ###### Revenue → Revenue by Payment Method, Top Customers
* ###### Cancellation → Customer \& Driver Cancellation Reasons
* ###### Ratings → Driver Ratings vs Customer Ratings



### **Key Business Insights:**



* ###### Cash \& UPI contribute more than 85% of total revenue.
* ###### Prime Sedan \& Prime Plus are the highest revenue generating vehicle types.
* ###### Overall cancellation rate ≈ 28%, majorly due to driver-side issues.
* ###### Average customer \& driver ratings stay close to 4.0, indicating stable service quality.
