# WeRateDogs_Twitter
This project was completed as part of Udacity's Data Analyst Nanodegree Program certification in January 2021.

# Summary
Using Python libraries, I gathered data from a variety of sources and in a variety of formats, performed data wrangling on these datasets by assessing their quality and tidiness, then cleaned them. Finally, I performed Exploratory Data Analysis (EDA) on the clean and tidy dataset and presented my insights.

The dataset are the tweet archive of Twitter user @dog_rates, also known as WeRateDogs.  WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10 and a numerator of greater than 10. Why? Because "they're good dogs Brent." WeRateDogs has over 8.9 million followers and has received international media coverage.

# Data Wrangling Process 
- Gathered data from different sources (Udacity WeRateDogs Twitter archive, retweet count and favorite count from Tweepy and tweet image predictions) and  documented unclean issues first
- Assessed the data files for quality and addressed completeness, validity, accuracy and consistency of the available data
- Assessed the data for tidiness to make sure that structural or organizational issues are addressed
- Cleaned the data by fixing the quality and tidiness issues that were identified in the previous step, using Python and Pandas
- The assessment process started with visual assessment and was followed by programmatic assessment

# Technologies Used
- Python, Numpy, Pandas, Matplotlib, Seaborn, JSON, Tweepy
- Jupyter Notebook, Regex

# Insights from EDA
- The number of retweets has a strong positive correlation with the number of favorites a tweet receives. Both of these variables are also positively correlated with the rating that the dogs have received (although not as strong of a correlation)
- Based on the data available, pupper is the most popular dog stage, followed by doggo, puppo and floofer
- The highest rated dog breeds are Rottweiler, French_bulldog, Old_english_sheepdog, Golden_retriever, Bloodhound, Samoyed, Chihuahua, Irish_setter, Pembroke, Standard_poodle, tan_coonhound, Labrador_retriever, Pomeranian, Pomeranian, Lakeland_terrier, Eskimo_dog, Bedlington_terrier and Gordon_setter

# Resources

### [Tweepy API Reference](http://docs.tweepy.org/en/v3.2.0/api.html#API)

### [RegexOne](https://regexone.com/)

### [Python Requests Library](https://pypi.org/project/requests/)

### [Python DataFrame Constructor](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html)

### [Reading and Writing JSON to a File in Python](https://stackabuse.com/reading-and-writing-json-to-a-file-in-python/)

### [Using a code timer](https://stackoverflow.com/questions/7370801/how-to-measure-elapsed-time-in-python)

### [Handling Exceptions](https://wiki.python.org/moin/HandlingExceptions)

### [Try and Except in Python](https://www.pythonforbeginners.com/error-handling/python-try-and-except)

### [How to Scrape More Information From Tweets on Twitter](https://towardsdatascience.com/how-to-scrape-more-information-from-tweets-on-twitter-44fd540b8a1f)

### [Using conditional to generate new column in pandas dataframe](https://code.i-harness.com/en/q/19c9fbc)
