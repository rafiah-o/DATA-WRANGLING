# DATA WRANGLING
## by Opeyemi Rafiat Fasasi


## Dataset

This project aimed at identifying, assessing and cleaning data quality and data tidiness issues. Three datasets were used and can be found below;

Tweets Archive: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/59a4e958_twitter-archive-enhanced/twitter-archive-enhanced.csv

Image Prediction: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv

Tweets - https://video.udacity-data.com/topher/2018/November/5be5fb7d_tweet-json/tweet-json.txt


## Summary
I adopted the Define-Code-Test approach to Identify, assess and clean eight data quality issues and three data tidiness issues.

QUALITY:
Change the data type of some columns
Deal with missing values either by removing or imputing values
Extract date from the timestamp column
Replace None with NaN
Fill incorrect and empty animal names with 'Unknown'
Remove rows that contains retweet
Remove duplicates
Rename some columns headers to be more descriptive

TIDINESS:
Combine doggo,floofer,pupper,puppo into a column called stages
Dropping columns not necessary for the analysis
Merge the three datasets into one



## Insights:
- Majority of the tweet has one image
- The average retweet_count has the highest value in June
- November has the least average  retweet_count
