# data-collection-challenge

Part 1: Web Scraping for News Titles and Previews

I used automated browsing to visit the Mars news site (https://static.bc-edx.com/data/web/mars_news/index.html). I then inspected the page to identify which elements to scrape.

I created a Beautiful Soup object and used it to extract text elements from the website.

I extracted the titles and preview text of the news articles that I scraped. I stored each title-and-preview pair in a Python dictionary and all the dictionaries in a Python list. I also printed the list to my Jupyter Notebook.

Part 2: Web Scraping for Mars Temperature Data

I used automated browsing to visit the Mars temperature site (https://static.bc-edx.com/data/web/mars_facts/temperature.html). I then inspected the page to identify which elements to scrape.

I create a Beautiful Soup object and used it to scrape the data in the HTML table. 

I assembled the scraped data into a Pandas DataFrame.

I analyzed the dataset using Pandas functions to answer the following questions:

    How many months exist on Mars?
    How many Martian (and not Earth) days worth of data exist in the scraped dataset?
    What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
        Find the average minimum daily temperature for all of the months.
        Plot the results as a bar chart.
    Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
        Find the average daily atmospheric pressure of all the months.
        Plot the results as a bar chart.
    About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
        Consider how many days elapse on Earth in the time that Mars circles the Sun once.
        Visually estimate the result by plotting the daily minimum temperature.

Finally, I exported the DataFrame to a CSV file.
