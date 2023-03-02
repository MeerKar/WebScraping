# WebScraping

This project,  the id and class attributesis identified  by using HTML elements , , and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup and scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.  Through this project some core skills like collecting data, organizing and storing data, analyzing data, and then visually communicating insights are strengthened .

This project is consists of two technical products and have submitted the following deliverables:

### Deliverable 1 

Scrape titles and preview text from Mars news articles, and it has beeen updated in a jupyter notebook using Python Pandas and the link follows,
https://github.com/MeerKar/WebScraping/blob/main/part_1_mars_news.ipynb

#### Deliverable 2 

Scrape and analyze Mars weather data, which exists in a table, and this too has been updated in a jupyter notebook using Python Pandas and the link follows.
https://github.com/MeerKar/WebScraping/blob/main/part_2_mars_weather.ipynb


### Part 1 : 

### Scrape Titles and Preview Text from Mars News


Inorder to scrape the 'Mars News' website automated browsing is used  to visit the 'Mars news site' links to an external site. Then innspected the page to identify which elements to scrape.,for this  a Beautiful Soup object is created and used it to extract text elements from the website.


Then  the titles and preview text of the news articles  scraped has been extracted. Then stored the scraping results in Python data structures as follows:


### Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview. An example is the following:

<img width="994" alt="image" src="https://user-images.githubusercontent.com/116701851/222311430-103d99c5-857c-414e-8ab7-f67332eccab0.png">

### Store all the dictionaries in a Python list.

#### And printed the list in the Python list



### Part 2 : 

### Scrape and Analyze Mars Weather Data

Following  steps below is used to scrape and analyze Mars weather data.

### 1. Used automated browsing to visit the 'Mars Temperature Data' Site Links to an external site to inspect the page to identify which elements to scrape.
 
  The  URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.

### 2. Created a Beautiful Soup object and used it to scrape the data in the HTML table.   


### 3. Assembled the scraped data into a Pandas DataFrame. The columns have headings as the table on the website. Here’s an explanation of the column headings:

and the output follows:

id: the identification number of a single transmission from the Curiosity rover

terrestrial_date: the date on Earth

sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars

ls: the solar longitude

month: the Martian month

min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)

pressure: The atmospheric pressure at Curiosity's location



<img width="652" alt="image" src="https://user-images.githubusercontent.com/116701851/222313218-f681600d-6ea1-43d3-801d-a0e9175849ff.png">



<img width="483" alt="image" src="https://user-images.githubusercontent.com/116701851/222313372-70198835-6866-4331-9c11-4bbb0e2bafec.png">



### 4. Examined the data types that are currently associated with each column.converted the data to the appropriate datetime, int, or float data types.


<img width="313" alt="image" src="https://user-images.githubusercontent.com/116701851/222313471-d95d1b9f-6c9c-4b2d-8d55-d315eee535e3.png">


### 5. Analyzed the dataset by using Pandas functions to answered the following questions:

#### How many months exist on Mars?


<img width="358" alt="image" src="https://user-images.githubusercontent.com/116701851/222313811-56b98f7a-2036-45ec-8697-4637d932ef2d.png">


### How many Martian (and not Earth) days worth of data exist in the scraped dataset?

<img width="192" alt="image" src="https://user-images.githubusercontent.com/116701851/222313950-0d4f4096-164c-4d5c-b5a6-25c51c2c9de6.png">


### What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:

<img width="406" alt="image" src="https://user-images.githubusercontent.com/116701851/222314079-49997788-4b94-43f1-9482-723b77c70784.png">


### Find the average minimum daily temperature for all of the months.

<img width="413" alt="image" src="https://user-images.githubusercontent.com/116701851/222314203-bda0771d-13d4-4682-adbd-8446a5b0d6a6.png">

### Plot the results as a bar chart.

<img width="814" alt="image" src="https://user-images.githubusercontent.com/116701851/222314285-e3a5e443-9ea3-4b60-b720-ee73656efcb3.png">




#### Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:

### Find the average daily atmospheric pressure of all the months.


<img width="463" alt="image" src="https://user-images.githubusercontent.com/116701851/222314384-dd615a0c-e5e4-47a8-9cff-0885789deb03.png">


### Plot the results as a bar chart.

<img width="705" alt="image" src="https://user-images.githubusercontent.com/116701851/222314917-7539660e-081d-44c5-9212-746503da8824.png">


### About how many terrestrial (Earth) days exist in a Martian year? To answer this question:

Consider how many days elapse on Earth in the time that Mars circles the Sun once.

Visually estimate the result by plotting the daily minimum temperature.

<img width="409" alt="image" src="https://user-images.githubusercontent.com/116701851/222315148-a7580697-f864-41d3-b2eb-dae6e0f4dc8e.png">

### To conclude the project dataframe is exported as CSV file.

<img width="358" alt="image" src="https://user-images.githubusercontent.com/116701851/222315367-11e98301-c218-4fae-9675-d29feef1bfed.png">









