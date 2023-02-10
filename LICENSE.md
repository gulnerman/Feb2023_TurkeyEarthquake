MIT License

Copyright (c) 2023 Ayse Giz Gulnerman

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


This manipulated rescue requests data from Twitter for 06 Feb 2023 Earthquake in Turkey.
This data is retrieved via Twitter API for my personal academic use. 
I used my API credentials with TwitteR library in R by specifying the word "yardım" (which means rescue in Turkish). 
In order to serve this data as public to help crisis management of this catastrophic disaster, I manipulated data by the following sequence;

remove (URL, whitespaces, rt, @, #, emoticons, mentions etc.),
group by text and cityName,
summarise min date and max date (to show starting/ last time of repetitive tweets),
tweet count (repetitive tweet count).

This data can be use of any humanitarian and academic efforts. Please be considerate while using, give reference to this repo and contact for further information. 
