# CarScrape
My ex-girlfriend (now wife :D) was looking to buy a new car a few years ago.

So I made a craigslist scraper that records 'good' deals and emailed
them to her. 

Good deals are found when the ratio between the Craigslist post asking
price divided by the low end of the Kelly Blue Book recommeneded listing price is less than 1. 

Example panda dataframe before being emailed: (Note: KBB's high price range is used
below because at the time of running, no asking prices fell under the KBB low range).

![Example Output](https://github.com/JosephAlanLane/CarScrape/blob/40173d92a43fcfc86a8fb159dd133d072597bfcf/CarScrape%20Output.png)
