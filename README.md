# Web Scraping

Scraping data from `phoneranking.com` website and saving it to csv file.

Phoneranking is website which ranks the phone yearly. It also contains details about all the mobile phones which are launched every year from all different brands. We fetch the data about different phones and can utilize this data to understand the popularity of any specific phone brand or specific phone model.

Fetched details are stored in csv file and the csv file contains below columns:

Column | Description
--------|-----------
**brand**| Brand/Company of phone
**name**| Model number of the phone
**rating**| Overall rating of the phone
**released**| Year in which the phone was released
**os**| Operating system the mobile phone is using

This csv file can be further used to do customer analysis on mobile devices based on their ratings and operating system.

Script is written using `Python` and `BeautifulSoup`.
