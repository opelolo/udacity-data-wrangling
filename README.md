## Project Description
This is a Data wrangling project done to meet the Udacity Data Analyst Nanodegree requirements.

### Steps
The project involves:
1. Gathering data from Twitter's API
2. Assessing the data to find data quality issues
3. Cleaning the data

### Data Quality issues found
#### tweet_json
* the date format in created_at contains different features that should be separated.

* Tweet_json has retweets. Remove them

#### Prediction
* Dog and conf have three different columns. Consolidate them into one

* jpg_url column has 66 duplicate entries. Remove duplicates

#### Archive
* Archive has numerous null values

* The source column has a complex url. Remove the a href//https part

#### General
* Prediction and archive columns have complex names.

* tweet_id should not be an integer. Convert to string