
### Web Crawler Application  
[![Build Status](https://travis-ci.org/SuperCh-SE-NCSU/ProjectScraping.svg?branch=master)](https://travis-ci.org/SuperCh-SE-NCSU/ProjectScraping)

Using Scrapy to crawl craigslist and kbb to get sale information about used cars users specified and their kbb price.

### Goals
Our goal is to offer a mailing service to people who are looking at craigslist for used car, providing a craigslist link to the car that they have expressed their interests in from our subscribing website and the kbb price for the specific car.

### Background
*A lot of people look at craigslist for an ideal used car that they are planing to buy or are just interested in. Normally when people look at the car price that listed on a craigslist page, they want to know if the car is worth the price listed. For people who are not car experters, they usually go to kbb to check the average price with the same specified conditions that are listed on craigslist. 
It's usually true that people will look through lots of cars on craigslist and check their kbb price time and time again. It could takes several days, or several weeks before they find their ideal car.
Sometimes, a good car is just posted to craigslist, which is exactly the car you want. But you are busy with your work or being tangled with some personal thins and forget to check craigslist, you may miss the car.
If there is some service that can email 
### Methods

### Result

### Disscussion

### Conclusion

### Future Work

### Reference

Users can subscribe to our email service.We will send them the lastest car information they need once per day. 
### Demo

http://152.46.17.210:8080/<br/>
<img align=left src="https://github.com/SuperCh-SE-NCSU/ProjectScraping/blob/master/pythontemp_model/img/subscribe.png" style="float:left;with:100px;height:300px">
### Install 3rd part library (needed for subscription)

```
sudo pip install lpthw.web
```   

### Develop Phase

  (1).  Crawl craigslist to get sale price and other information about used cars users specified and send the information to subscribed users's emails (completed)

  (2).  Set parameters to get the price from kbb (demo, to be implemented in a function)

  (3).  Integrate part 1 and part 2 to form the information which will be sended to users (partly completed)

  (4).  Rewrite 1,2,3 in scrapy (to do)
  
  (5).  Build a website for users to subscribe to our email service (completed)
  
  (6).  Get data from a dynamic website (done)

  (7).  Complete the whole system and compare the two different strategies (to do)

