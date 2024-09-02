# Web Scraping For Your Hobby Or: Tracking Favourite Products

#### -- Project Status: [Active]

## Project Intro/Objective
The purpose of this project is to build a web scraper. In this particular case the idea is to support one's hobby and keep track of a certain product range/ a certain product of interest from a particular webshop.

#### In my particular case
Anna Maria Horner is a designer for patchwork fabric. Her designs are vibrant and colorful - often times with folkloric motives. The fabrics are perfect for flower power homes and friends of maximalism.

Let's build a crawler that checks on Anna Maria Horner products from a known webshop in the UK. 


### Methods Used
* Web Scraping using requests, BeautifulSoup
* Processing and Storing result in DataFRame, as csv file

### Technologies
* Python
* Pandas, jupyter
* requests, BeautifulSoup (bs4)

## Project Description
#### Important Note
Always check on the website robots.txt and see if and what the owners allow in regard to gathering information.

#### Notebook WebScraping_SearchResult_FirstPage.ipynb

This is the introductory notebook. It starts with the first step - checking robots.txt and walks step by step through the process of:
- initiating a request with a search term using requests, printing the status code
- storing the result with usage of BeautifulSoup
- explaining how to access each single product and store them in a list
- gathering all kind of information like product name, product type, price, product page
- storing everything in a DataFrame and csv file

 
