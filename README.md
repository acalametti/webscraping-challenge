# webscraping-challenge

## Contributors: Alex Calametti

# Overview:  

The purpose of this project is to utilize skills in web scraping, data extraction, and data analysis to gather information about Mars and gain insight from the collected data. The project is divided into two main deliverables, each with its own set of tasks:

### 1: Scrape Mars News Articles

- Use automated browsing with Splinter to visit the Mars News website.
- Identify HTML elements and use Beautiful Soup to extract titles and preview text from news articles.
- Store the scraping results in Python data structures (dictionaries and lists).

### 2: Scrape and Analyze Mars Weather Data

- Use automated browsing to visit the Mars Temperature Data Site.
- Create a Beautiful Soup object to scrape data from an HTML table.
- Assemble the scraped data into a Pandas DataFrame with specified column headings.
- Analyze the dataset using Pandas functions to answer specific questions.

## Dependencies and files 

- Splinter
- Beautiful Soup
- Pandas
- Matplotlib
- Datetime
- Selenium
- Mars news site: Mars data site"https://static.bc-edx.com/data/web/mars_news/index.html
- Mars temperature data site: https://static.bc-edx.com/data/web/mars_facts/temperature.html

# Steps 

## Part 1: Mars News Articles (part_1_mars_news.ipynb)

1. Utilize Splinter to visit the Mars News website by creating a browser session.

2. Identify and parse relevant HTML elements using Beautiful Soup and extract titles and preview text from Mars news articles.

3. Store the extracted information in Python dictionaries, each containing a title and preview pair. Group these dictionaries into a list.

  ![Screen Shot 2023-12-13 at 4 20 43 PM](https://github.com/acalametti/webscraping-challenge/assets/136642574/d7eb3514-b3a0-472f-bd3d-a089b9f1919f)


5. Print the list in your Jupyter Notebook for verification and quite browser session.

## Part 2: Mars Weather Data Analysis (part_2_mars_weather.ipynb)

1. Use Splinter to creat a browsing session and visit the Mars Temperature Data Site.

2. Create a Beautiful Soup object to extract and parse data in the tables' rows.

3. Add the scraped data into a Pandas DataFrame with appropriate column headings and data types.

4. Utilize Pandas functions to answer specific questions related to average temperature and pressure, number of months on mars,  and the number of terrestrial days from the Mars weather dataset.

5. Plot the results as bar charts to enhance data interpretation.

   ![Screen Shot 2023-12-13 at 10 13 30 AM](https://github.com/acalametti/webscraping-challenge/assets/136642574/f17c5f1f-830c-46dc-abe8-2681ecdda84b)

    ![Screen Shot 2023-12-13 at 10 13 37 AM](https://github.com/acalametti/webscraping-challenge/assets/136642574/1a27b38a-f3bf-45fd-905d-2984f145f347)

    ![Screen Shot 2023-12-13 at 10 13 43 AM](https://github.com/acalametti/webscraping-challenge/assets/136642574/81ae0adc-d728-41b0-8f39-d842df0849d5)


7. Save the final DataFrame to a CSV file for future reference (mars_weather.csv).


#Acknowledments

Thank you to my tutor Geronimo Perez and for helping me troubleshoot on this project! 
