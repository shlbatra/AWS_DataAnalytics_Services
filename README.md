# Retailer Data Ingestion & Recommendation System using AWS Services

### Order History App
This App gets order history data generated on EC2 Instances logs using Kinesis Data Stream. Further, the data is loaded into DyanmoDB to provide read only access 
to downstream applications with low latency. 

![OrderHistoryApp](https://github.com/shlbatra/AWS_DataAnalytics_Services/blob/main/Images/1OrderHistory.JPG)

### Product Recommendations
The order history is also used to generate product recommendations for new users based on purchasing behaviour of other similar users. 

![ProductRecommendation](https://github.com/shlbatra/AWS_DataAnalytics_Services/blob/main/Images/2ProductRecommendations.JPG)

### Transaction Rate Alarm
The orders processed are kept in check with real time window counts of the number of products sold to track any unusual server load by generating alarms using 
Kinesis Data Streams, Kinesis Data Analytics on Flink and SNS Notification service

![TransactionRateAlarm](https://github.com/shlbatra/AWS_DataAnalytics_Services/blob/main/Images/3TransactionRateAlarm.JPG)

### Data Warehousing and Visualization
Log Data on EC2 servers can be extracted using Kinesis Firehose to s3 or Opensearch index. Further, log data can be stored in Amazon Redshift for storage and further 
data analsyis. 

![DataWarehousing](https://github.com/shlbatra/AWS_DataAnalytics_Services/blob/main/Images/4DataWarehousing.JPG)

## Retailer Data Ingestion with all Order History Built

![AllTogether](https://github.com/shlbatra/AWS_DataAnalytics_Services/blob/main/Images/AllTogether.JPG)
