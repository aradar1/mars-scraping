Background
You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

As you work on this Challenge, remember that you’re strengthening the same core skills that you’ve been developing until now: collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.

What You're Creating
This new assignment consists of two technical products. You will submit the following deliverables:

Deliverable 1: Scrape titles and preview text from Mars news articles.

Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

Requirements
Part 1: Scrape Titles and Preview Text from Mars News (40 points)
Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup). (10 points)

The titles and preview text of the news articles were scraped and extracted. (20 points)

The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries. (10 points)

Part 2: Scrape and Analyze Mars Weather Data (60 points)
The HTML table was extracted into a Pandas DataFrame. Either Pandas or Splinter and Beautiful Soup were used to scrape the data. The columns have the correct headings and data types. (15 points)

The data was analyzed to answer the following questions: (10 points)

How many months exist on Mars? (5 points)
How many Martian days' worth of data are there? (5 points)
The data was analyzed to answer the following questions, and a data visualization was created to support each answer: (30 points)

Which month, on average, has the lowest temperature? The highest? (10 points)
Which month, on average, has the lowest atmospheric pressure? The highest? (10 points)
How many terrestrial days exist in a Martian year? A visual estimate within 25% was made. (10 points)
The DataFrame was exported into a CSV file. (5 points)

