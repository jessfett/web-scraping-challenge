# Mission To Mars

## Task
The Mission To Mars activity required scraping 4 different webpages for a variety of information from article titles, to tables, to images. 

### Dependencies
You need to utilize the following libraries:
-Pandas
-BeautifulSoup
-Splinter
-Flask
-PyMongo
-ChromeDriverExtension

### Procedure

In order to scrape the webpages, you will utilize Beatiful Soup to access the html code for the web pages.  You will parse through the coding to find the information neccessary and access the class to retrieve the information.  Additionally, utilizing read_html, you will be able to pull complete tables from the web page, which allows you to create dataframes with Pandas. 

Ultimately you will take this information and load it to a MongoDB, where you can then load it to an html to create an output of information. Coding the html output using Bootstrap allows to customize the webpage to create an aesthetically pleasing output. 
