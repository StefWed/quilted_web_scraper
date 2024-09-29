# Web Scraping For Your Hobby Or: Tracking Favourite Products

#### -- Project Status: [Closed]

## Project Intro/Objective
The purpose of this project is to build a web scraper tracking a particular search term. In this case at hand the idea is to support one's hobby and keep track of a certain product range/ a certain product of interest from a particular webshop. Be aware that this project serves as an example - a walkthrough on how one builds a web scraper and what to pay attention to. The website and data are not shared completely.

#### In my particular case
Anna Maria Horner is a designer for patchwork fabric. Her designs are vibrant and colorful - often times with folkloric motives. The fabrics are perfect for flower power homes and friends of maximalism.

Let's build a scraper that checks on Anna Maria Horner products from an online webshop. 


### Methods Used
* Web Scraping using requests
* Utilizing BeautifulSoup to parse HTML code, retrieving information
* Processing data and storing result in DataFrame, and as csv file

### Technologies
* Python
* Pandas, jupyter
* requests, BeautifulSoup (bs4)

## Project Description
#### Important Note
Respect Scraping Ethics! 

The scraped content belongs to the website owner. Check robots.txt and the Terms of Use! If in doubt, scrape websites which have an API. Making requests to a website can cause a toll on a website's performance, please do not cause any disruption to the regular functioning of the website!

#### Notebook WebScraping_SearchResult_FirstPage.ipynb

This is the introductory notebook, it serves as a prototype. Data is 
It starts with the first step - checking robots.txt and walks step by step through the process of:
- initiating a request with a search term using requests, printing the status code
- storing the result with usage of BeautifulSoup
- explaining how to access each single product and store them in a list
- gathering all kind of information like product name, product type, price, product page
- storing everything in a DataFrame and csv file

 #### Notebook WebScraping_SearchResult_FirstPage_MoreAdvanced.ipynb

 This notebook builds up on the first one. The code is build up in proper functions with docstrings.
 
 The input() function from Python was added to aks for the specific search term/ search phrase. Other than that a few messages/ functionalities werde added - for instance in the case when no product was found.

