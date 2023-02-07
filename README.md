# Feb2023_TurkeyEarthquake
Manipulated rescue requests data from Twitter for 06 Feb 2023 Earthquake in Turkey.


This data is retrieved via Twitter API for my personal academic use. I used my API credentials with TwitteR library in R by specifying the word "yardım" (which means rescue in Turkish). In order to serve this data as public to help crisis management of this catastrophic disaster, I manipulated data by the following sequence; 

- remove (URL, whitespaces, rt, @, #, emoticons, mentions etc.), 
- group by text and cityName, 
- summarise min date and max date (to show starting/ last time of repetitive tweets), 
- tweet count (repetitive tweet count).

I will be sharing links to the updated files below:
- [v1](rescueRequests_v1.csv) #this is derived from 110th tweets.
- [v2](rescueRequests_v2.csv) #this includes v1. #this is derived from 210th tweets.
- [v3](rescueRequests_v3.csv) #this includes v1 and v2. #this is derived from 310th tweets.
- [v4](rescueRequests_v4.csv) #this includes v1, v2 and v3. #this is derived from 410th tweets.
- [v5](rescueRequests_v5.csv) #this includes v1, v2, v3 and v4. #this is derived from 510th tweets.

