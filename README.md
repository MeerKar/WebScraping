# WebScraping

In this project, by using HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup and scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.  Through this project some core skills like collecting data, organizing and storing data, analyzing data, and then visually communicating insights are strengthened .

This project is consists of two technical products and have submitted the following deliverables:

### Deliverable 1 

Scrape titles and preview text from Mars news articles, and it has beeen updated in a jupyter notebook using Python Pandas and the link follows,


#### Deliverable 2 

Scrape and analyze Mars weather data, which exists in a table, and this too has been updated in a jupyter notebook using Python Pandas and the link follows.


### Part 1 : 

### Scrape Titles and Preview Text from Mars News


Inorder to scrape the Mars News website automated browsingis used  to visit the Mars news siteLinks to an external site. Then innspected the page to identify which elements to scrape.,for this  a Beautiful Soup object is created and used it to extract text elements from the website.


Then  the titles and preview text of the news articles  scraped has been extracted. Then stored the scraping results in Python data structures as follows:


.  Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview. An example is the following:

<img width="994" alt="image" src="https://user-images.githubusercontent.com/116701851/222311430-103d99c5-857c-414e-8ab7-f67332eccab0.png">

.  Store all the dictionaries in a Python list.

.  And printed the list in the Python list

