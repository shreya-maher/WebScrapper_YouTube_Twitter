# WebScrapper_YouTube_Twitter
Web Scrappers for YouTube and Twitter to extract information of user profiles

Designed a database for influencers on YouTube and Twitter. Primary sources of data were their respective websites

1.) For YouTube Data: https://www.youtube.com/

2.) For Twitter Data: https://twitter.com/

Scrapped data for profiles of Influencers from both platforms across categories as: News, Programming, Gaming, Fashion, Makeup, Fitness, Movie Reviews, and Technology  

-------------------------------

The Twitter Scrapper: (twitterscrapper_dmdd.py) 

1. Fetch top users under a particular category with their complete profile information and tweets made in past 24 hours.

2. Can be used to perform analysis of reach and engagement of a particular users profile and to check fit of a particular influencer for certain marketing needs 

3. Input: Keyword

4. Output: 2 CSV files with users information and information of related tweets from profiles 
(Parameters in 2 files: User ID, Tweet Created At, Tweet Likes,Retweets,Tweet Description, Name, Followers, Location, Created At, Verified,URL, Total Tweets, Total tweets in last 24hrs, Latest Status updated by User, Witheld In Countries, Following, Total Likes By Profile) 

-----------------------------------------

The YouTube Scrapper: (youtubescrapper_dmdd.py) 

1. Fetch top users under a particular category with their complete profile information and latest videos uploaded 

2. Can be used to perform analysis of reach and engagement of a particular users profile and to check fit of a particular influencer for certain marketing needs 

3. Input: Keyword

4. Output: 2 CSV files with users information and information of related videos from profiles 
(Parameters in 2 files: User ID, Profile Views, Profile Subscribers, Name, Location, Created At,URL)  
