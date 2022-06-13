# NYC-Taxi-Trip-Time-Prediction
### **Objective** : 
### New York City’s 12,779 yellow medallion taxicabs comprise a $1.8 billion industry serving about 240 million passengers a year. Information on New York’s cabs attracts a broad audience due to their central transportation role and their prominence in Manhattan traffic. Exploiting an understanding of taxi trip durations and the ability to predict taxi durations could present valuable insights to city planners and the people of New York. Hence, this problem statement is of great significance.
### New York City taxi rides form the core of the traffic in the city of New York. The many rides taken every day by New Yorkers in the busy city can give us a great idea of traffic times, road blockages, and so on. Predicting the duration of a taxi trip is very important since a user would always like to know precisely how much time it would require him to travel from one place to another. Our task is to build a model that predicts the total ride duration of taxi trips in New York City. The dataset is based on the 2016 NYC Yellow Cab trip record data made available in Big Query on Google Cloud Platform.
![image](https://user-images.githubusercontent.com/98027899/173228627-6c6eaebc-032c-4e68-a5a9-c2b6a3223745.png)


### **Data Summary** : 
### NYC Taxi Data.csv -  The data has 11 columns and 1,458,644 records.
* ### Independent features : id , vendor_id , pickup_datetime , dropoff_datetime , passenger_count , pickup_longitude , pickup_latitude , dropoff_longitude , dropoff_latitude , store_and_fwd_flag 
* ### Target Variable : trip_duration
![image](https://user-images.githubusercontent.com/98027899/173228822-c7d05dad-fc6d-40d7-9a56-bbcfc2b1a004.png)


### **Project Details** :

### The distribution of all the featutes
![Screenshot 2022-06-12 151524fgf](https://user-images.githubusercontent.com/98027899/173227559-dd76f72a-c642-4d78-bbf0-84888c5fba28.png)

### Weekly and monthly analysis of cab trips across NYC.
![Screenshot 2022-06-12 151639](https://user-images.githubusercontent.com/98027899/173227564-9fde1105-8f26-40fb-b4c3-4eb298471efe.png)

### Hourly analysis of cab trips across NYC.
![Screenshot 2022-06-12 151653](https://user-images.githubusercontent.com/98027899/173227568-31dfb2ba-2d95-4587-b33d-40e60a455aaa.png)

### Bivariate analysis of Trip Duration with hour and weekday
![Screenshot 2022-06-12 151731](https://user-images.githubusercontent.com/98027899/173227574-f57a036f-956f-4119-ac66-50e19f4d0b6f.png)

### Used folium graph to represent all the latitude and longitude geospatial dropoff and pickup trip locations across the city.
![Screenshot 2022-06-12 151709](https://user-images.githubusercontent.com/98027899/173227570-e2bd993b-d089-4da4-96f6-eb7729febc1f.png)

### Correlation heatmap for analysing if features have high correlation.
![Screenshot 2022-06-12 151907](https://user-images.githubusercontent.com/98027899/173227582-bfa1de26-56bd-413b-af5f-b05c33d66b55.png)

### Model performances on training and test data
![Screenshot 2022-06-12 152212](https://user-images.githubusercontent.com/98027899/173227640-851e090e-2ac7-433b-9005-27e76de86c54.png)

### Most influential features according to best model.
![Screenshot 2022-06-12 151816](https://user-images.githubusercontent.com/98027899/173227590-85801b2d-ad65-4cf9-b134-5580eba4e428.png)


![image](https://user-images.githubusercontent.com/98027899/173228827-a32b9e35-7555-4531-99c5-5f71ae363d40.png)

### **Conclusion** :
### In this project we developed an optimal regressor model using cross validation and tried to predict the trip time taken by a cab ride in NYC.
### Our best model was XGBoost through which we achieved adjusted R score of 80% on test data.

![image](https://user-images.githubusercontent.com/98027899/173228948-dbb73f86-11bd-489d-9ede-2195bf2630da.png)

### **Scope** :
### Providing an accurate time required for the trip we can help both the host and customers make data driven informed decision regarding the bookings.It will help in inducing competitive rides fare as well as prove to be efficient in traffic management.

![image](https://user-images.githubusercontent.com/98027899/173228828-b47f7a35-c2d0-4b1d-8eff-70b6ce2d77e1.png)

### **References** :
https://xgboost.readthedocs.io/en/latest/python/python_api.html

https://www.kaggle.com/c/nyc-taxi-trip-duration/code
