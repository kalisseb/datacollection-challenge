# datacollection-challenge

Using web-scraping, I collected both news and weather data for Mars. The information was scraped from the URL's provided below, organized into lists/dataframes and charted. 

Python Modules and Libraries that were used: splinter, BeautifulSoup, matplotlib, and pandas

Part 1 URL: 'https://static.bc-edx.com/data/web/mars_news/index.html'

Part 2 URL: 'https://static.bc-edx.com/data/web/mars_facts/temperature.html'

## Review

### Part 1: Mars News

In this first file, I used BeautifulSoup to extract the text elements from the html to group each article and list its title and a preview of its contents. This information was organized into a dictionary and added to a list.

### Part 2: Mars weather

In this file I utilized the same tools to scrape weather data from the html. This information was stored in a pandas dataframe. After adjusting the datatypes appropriately, the information was analyzed and charted. Charts include the average minimum temperature by month (sorted by month as well as temperature), average pressure by month, and number of days by minimum temperature. The information from the dataframe was then saved to a csv titled "mars_data_df.csv".
