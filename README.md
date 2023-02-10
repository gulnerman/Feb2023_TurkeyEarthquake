# Feb2023_TurkeyEarthquake
Manipulated rescue requests data from Twitter for 06 Feb 2023 Earthquake in Turkey.


This data is retrieved via Twitter API for my personal academic use. I used my API credentials with TwitteR library in R by specifying the word "yardım" (which means rescue in Turkish). In order to serve this data as public to help crisis management of this catastrophic disaster, I manipulated data by the following sequence; 

- remove (URL, whitespaces, rt, @, #, emoticons, mentions etc.), 
- group by text and cityName, 
- summarise min date and max date (to show starting/ last time of repetitive tweets), 
- tweet count (repetitive tweet count).

I will be sharing links to the updated files below:

the 6th of Feb
- [6thFebruary_v1](rescueRequests_v1.csv) #this is derived from 110th tweets.
- [6thFebruary_v2](rescueRequests_v2.csv) #this includes v1. #this is derived from 210th tweets.
- [6thFebruary_v3](rescueRequests_v3.csv) #this includes v1 and v2. #this is derived from 310th tweets.
- [6thFebruary_v4](rescueRequests_v4.csv) #this includes v1, v2 and v3. #this is derived from 410th tweets.
- [6thFebruary_v5](rescueRequests_v5.csv) #this includes v1, v2, v3 and v4. #this is derived from 510th tweets.

the 7th of Feb
- [7thFebruary_v1](rescueRequests_7thFebruary_v1.csv) #this is derived from 100th tweets pulled in the 7th of February 2023. 

the 8thFeb of 2023 ##there was a slowing down issue on Twitter therefore the pulling attempts failed several times for larger amounts.
- [8thFebruary_v1](rescueRequests_8thFebruary_v1.csv) #this is derived from 10th tweets pulled in 8th of February 2023. 
- [8thFebruary_v2](rescueRequests_8thFebruary_v2.csv) #this includes v1. #this is derived from 20th tweets pulled in 8th of February 2023. 
- [8thFebruary_v3](rescueRequests_8thFebruary_v3.csv) #this includes v1 and v2. #this is derived from 50th tweets pulled in 8th of February 2023. 

the 9th of Feb
- [9thFebruary_v1](rescueRequests_9thFebruary_v1.csv) #this is derived from 30th tweets pulled in 9th of February 2023. 
- [9thFebruary_v2](rescueRequests_9thFebruary_v2.csv) #this includes v1. #this is derived from 40th tweets pulled in 9th of February 2023. 
- [9thFebruary_v3](rescueRequests_9thFebruary_v3.csv) #this includes v1 and v2. #this is derived from 60th tweets pulled in 9th of February 2023. 
- [9thFebruary_v4](rescueRequests_9thFebruary_v4.csv) #this includes v1, v2, and v3. #this is derived from 80th tweets pulled in 9th of February 2023. 
- [9thFebruary_v5](rescueRequests_9thFebruary_v5.csv) #this includes v1, v2, v3 and v4. #this is derived from 100th tweets pulled in 9th of February 2023. 
- [9thFebruary_v6](rescueRequests_9thFebruary_v6.csv) #this includes v1, v2, v3, v4 and v5. #this is derived from 120th tweets pulled in 9th of February 2023. 

the 10th of Feb
- [10thFebruary_v1](rescueRequests_10thFebruary_v1.csv) #this is derived from 20th tweets pulled in 10th of February 2023. 
- [10thFebruary_v2](rescueRequests_10thFebruary_v2.csv) #this includes v1. #this is derived from 40th tweets pulled in 10th of February 2023. 
- [10thFebruary_v3](rescueRequests_10thFebruary_v3.csv) #this includes v1 and v2. #this is derived from 80th tweets pulled in 10th of February 2023. 
- [10thFebruary_v4](rescueRequests_10thFebruary_v4.csv) #this includes v1, v2 and v3. #this is derived from 120th tweets pulled in 10th of February 2023. 
