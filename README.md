# NYC-Taxi-Trip-Time-Prediction

New York City’s 12,779 yellow medallion taxicabs comprise a $1.8 billion industry serving about 240 million passengers a year. Information on New York’s cabs attracts a broad audience due to their central transportation role and their prominence in Manhattan traffic. Exploiting an understanding of taxi trip durations and the ability to predict taxi durations could present valuable insights to city planners and the people of New York. Hence, this problem statement is of great significance.



![d1af8b50b2d19f24ec34a055048e25ff](https://user-images.githubusercontent.com/98027899/159118681-06d2fcd4-0adb-4e81-85e3-97a637105f4b.jpg)



The dataset consists of the 2016 NYC Yellow Cab trip record data, which was originally published by the NYC Taxi and Limousine Commission (TLC). We have to build a model that predicts the total ride duration of taxi trips in New York City. Thus, the problem statement is defined as follows: determine best predictors of NYC taxi trip durations, and build a multivariate taxi trip duration predictor.

The data has 11 columns and 1,458,644 rows. There are 10 features, and the details of the features are:

vendor_id - a code indicating the provider associated with the trip record

pickup_datetime - date and time when the meter was engaged

dropoff_datetime - date and time when the meter was disengaged

passenger_count - the number of passengers in the vehicle (driver entered value)

pickup_longitude - the longitude where the meter was engaged

pickup_latitude - the latitude where the meter was engaged

dropoff_longitude - the longitude where the meter was disengaged

dropoff_latitude - the latitude where the meter was disengaged

store_and_fwd_flag - This flag indicates whether the trip record was held in vehicle memory before sending to the
vendor because the vehicle did not have a connection to the server - Y=store and forward; N=not a store and forward trip

The last column in data is trip_duration in seconds, which is target variable.


### Model Performance
Final Model: XGBoost Regressor with GridSearch Cross Validation

### Result  
Adjusted R2 score - 82% on training data and 80% on test data.
