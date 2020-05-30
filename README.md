# twitter-sentiment-analysis

Twitter is a form of social media with widespread use, a platform that millions of users visit to get informed on news, and also share their views. As of 2019, Twitter reported more than 330 million monthly active users, of which 145 million do use the service daily.

For this project, I executed sentiment analysis on tweets about the two latest US Presidents: Donald Trump and Barack Obama. 

In terms of data, I collected ~4,500 tweets on them via the Twitter API, focusing specifically on American-based tweets for this analysis.

This project essentially implement an **end-to-end Data Pipeline**, from extraction to storage, and from storage to manipulation and visualiazation. The project is organized in 3 notebooks:
1. Project Intro and Data Extraction
2. Data Load and NLP analysis - Barack Obama tweets
3. Data Load and NLP analysis - Donald Trump tweets 

In terms of tools, I have used, among others:
- **tweepy** for data sourcing
- **mysql** and **sqlalchemy** libraries for interaction between my Python dataframes and the MySQL database
- **pandas** for dataframe manipulation
- **re** library for tweet cleaning with the help of Regular Expressions
- **geopy** for geo-mapping of tweet locations
- **textblob** for the NLP analysis
- **seaborn, wordcloud, plotly** for exploratory analysis
