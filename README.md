# US-election-2020-sentiment-analysis Using Twitter Sentiment Analysis with Python

## Dataset creation

- Using twitter API to scrape tweets
  - Copy “API Key”, “API Secret”, “Access Token”, and “Access Token Secret” to use as Oauth keys.
  - Setup Authentication with Twitter using tweepy package.
  - Extracting tweets for both Donald Trump and Joe Biden.

  - converting the files into dataframe and to csv
  
  - generated data is avaliabe in 'trump_data.csv' and 'biden_data.csv'.
  - both the dataset contains to 2 columns and 10000 rows
  

## Data Analysis

- Importing the datasets
- Sentiment analysis using TextBlob
  - Polarity ranges from -1 to +1 and tells whether the text has negative sentiments or positive sentiments
  - polarity function returns the polarity of each tweet
  - adding the tag of 'Positive', 'Negative' or 'Netural' according to the polarity
  - Visualizing to find Positive, Negative and Neutral
  - Droping all neutral data since they do not add value to the analysis
  - After droping the neutral data the I have an uneven dataset to balance out both datasets I make use of 'balanced_data' function.
  - After balancing the data we have 4000 rows in each dataset.
 
## Data Visualization

- for Donald Trump
  - From the below figure, one can easily interpret that polarity ranges from -1 to +1 and a larger number of people have positive reviews because it is mostly concentrated between 0 and 0.5.
  - From below figure of boxplot, one can easily identify most of the polarity is concentrated between -0.25 to 0.50. So, it is basically showing only the concentration of polarity.
  - Analyzing Most Positive and Most Negative replies
   - Word clouds can be useful to find your customer's pain points in business purposes, I am using it to get insights of public opinion about the presidential candidate and most frequently used keywords by the citizens.
   
- for Joe Biden
  - From the below figure, one can easily interpret that polarity ranges from -1 to +1 and a larger number of people have positive reviews because it is mostly concentrated between 0 and 0.5.
  - From below figure of boxplot, one can easily identify most of the polarity is concentrated between -0.25 to 0.50. So, it is basically showing only the concentration of polarity.
  - Analyzing Most Positive and Most Negative replies 
   - Word clouds can be useful to find your customer's pain points in business purposes, I am using it to get insights of public opinion about the presidential candidate and most frequently used keywords by the citizens. 

- for People Sentiment

  -  From the below figures, it is very evident that Joe Biden is getting more positive replies as compare to negative reviews.
  - The overall people sentiment is more favouralbe to Joe Biden over Donald Trump.

## Sentiment Analysis on Twitter data ahead of 2020 US Elections on the basis of Location
 -A sentiment analysis project performed on data collected from Twitter mentioning the two primary contestants in the 2020 US Elections. 
 -The data for this project was collected using Twitter's publicly available tweepy api.
 -The project uses VADER Sentiment Analysis algorithm to judge the sentiment of the tweets made on either primary contestants. 
 -Based on the intensity of the different sentiments involved in the tweet, we judge the overall sentiment of the tweet. We group such sentiments together to find out the overall sentiment of a particular state towards a particular candidate in order to figure out whether the state is going to be a red one or a blue one.

##The overall success of this analysis will be found out only after the election results are declared.

  
  



  

 



