# Mars_News_Web_Scraping

![Mars-website](images/Image-from-Mars-website.png?raw=true)

## 1) Mars_News: Scrape the Mars Planet Science Exploration Program website for titles and previews, then save the results into a JSON and connect the data to MongoDB.
url: https://redplanetscience.com/
    a) Using splinter and browser visit the Mars NASA news site (url above)
    b) Using BeautifulSoup, scrape the website and store the html code in response, then visualize the code using .prettify
    c) Using ChromeDevTools, identify html sections where the titles and previews are shown
    d) Store the titles and previews under the results variable using .find_all(specific-html-sections) 
    e) Run a for loop to store the title and preview pairs in a dictionary using an empty list
    f) Close the browser connection
    g) Save the data in a JSON file
    h) Load data into MongoDB
    
2) 
    
    
    
    
   
# Install:
- Splinter (Browser)
- BeautifulSoup (bs4)
- Webdriver_manager.chrome
- Requests
- Json
- PyMongo
- Pandas
