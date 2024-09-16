# web_scraping

Analysis

      The data indicates that the third month(March) has the coldest average minimum temperature at -83.3 degrees Celsius.  It also indicates that the eighth month(August) has the warmest average minimum temperature at -68.4 degrees Celsius. 

      The data indicates that the sixth month(June) has the lowest average pressure at 745.  It also indicates that the ninth month(September) has the highest average pressure at 913. 

      Based off the trends of the Minimum Temperature over Time graph I would estimate there are 650 days in a Martian year.  This is the distance between the two consistent low points.  This would than indicate that there are approximately 24 months in a year.
  This new assignment consists of two technical products. You will submit the following deliverables:

    Deliverable 1: Scrape titles and preview text from Mars news articles.

    Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

  Open the Jupyter Notebook in the starter code folder named part_1_mars_news.ipynb. You will work in this code as you follow the steps below to scrape the Mars News website.

      Use automated browsing to visit the Mars news siteLinks to an external site.. Inspect the page to identify which elements to scrape.

      Create a Beautiful Soup object and use it to extract text elements from the website.

      Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures

      Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.

      Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website.

      Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.

      Analyze your dataset by using Pandas functions to answer the following questions:

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
          Visually estimate the result by plotting the daily minimum temperature of each observation
      Export the DataFrame to a CSV file.

References

The Mars News websiteLinks to an external site. is operated by edX Boot Camps LLC for educational purposes only. The news article titles, summaries, dates, and images were scraped from NASA's Mars NewsLinks to an external site. website in November 2022. Images are used according to the JPL Image Use PolicyLinks to an external site., courtesy NASA/JPL-Caltech.
