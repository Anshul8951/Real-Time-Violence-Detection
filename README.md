# Cloud Based Application - Violence detection in NYC

## Project Description: 
On receiving video inputs from various locations/CCTV cameras, we detect violence on the videos on a real-time basis and alert the relevant authorities. We store this data and provide Chatbot and Query search features for specific videos too.

## Product Features:
* Uses a deep learning model consisting of CNN as a spatial feature extractor and LSTM as temporal relation learning method with a focus on the three-factor (overall generality - accuracy - fast response time).
* Message Alert on detecting violence in a real-time video.
* Detects violence timestamps in an uploaded video.
* Data consisting of the time, place and instance in video being saved in a database for analysis.
* Provides a user-friendly UI to retrieve results from the database based on the query.
* Chatbot to query about the violence trends and related questions about a particular area. The chatbot uses the data stored in the database to provide informed answers.
* Scalable to parallelly monitor and alert violence from multiple cameras and update the database accordingly.
* Technologies : Lambda functions, Amazon Sagemaker, DynamoDB/ElasticSearch, S3, EC2, Amazon Lex.


## Architecture
<p align="center"><img src = "https://github.com/AiswaryaSriram/violence-detection-cloudproj/blob/main/images/arch.png" width = 700><p>
