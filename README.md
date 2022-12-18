# Module12

## Deliverable 1: Scrape Titles and Preview Text from Mars News

Open the Jupyter Notebook in the starter code folder named part_1_mars_news.ipynb. You will work in this code as you follow the steps below to scrape the Mars News website.

1. Use automated browsing to visit the Mars NASA news site. Inspect the page to identify which elements to scrape.

2. Create a Beautiful Soup object and use it to extract text elements from the website.

3. Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures

4. Optionally, store the scraped data in a file or database (to ease sharing the data with others). To do so, export the scraped data to either a JSON file or a MongoDB database.

## Deliverable 2: Scrape and Analyze Mars Weather Data

1. Use automated browsing to visit the Mars Temperature Data Site Links to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html.

2. Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.

3. Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website.

4. Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.

5. Analyze your dataset by using Pandas functions to answer the following questions:
  * How many months exist on Mars?
  * How many Martian (and not Earth) days worth of data exist in the scraped dataset?
  * What are the coldest and the warmest months on Mars (at the location of Curiosity)? 
  * Which months have the lowest and the highest atmospheric pressure on Mars?
  * About how many terrestrial (Earth) days exist in a Martian year?
  
6. Export the DataFrame to a CSV file.
