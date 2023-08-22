# Mars Data Scraping and Analysis

## Introduction
In this multi-part activity, you'll be working with Jupyter Notebooks to scrape data from Mars-related websites and analyze the collected information. Here's what you'll do in each part:

## Part 1: Scrape Titles and Preview Text from Mars News
In the part_1_mars_news.ipynb notebook, you will:

1. Utilize automated browsing to visit the Mars News website and inspect the page for scraping targets.
2. Create a Beautiful Soup object to extract text elements from the website.
3. Scrape titles and preview text of news articles from the site.

## Part 2: Scrape and Analyze Mars Weather Data
In the part_2_mars_weather.ipynb notebook, your tasks include:

1. Automate browsing to access the Mars Temperature Data Site and examine the page for scraping possibilities.
2. Utilize Beautiful Soup to scrape data from an HTML table or use Pandas' read_html function for the same purpose.
3. Construct a Pandas DataFrame to organize the scraped data, focusing on columns like id, terrestrial_date, sol, ls, month, min_temp, and pressure.
4. Analyse the dataset using Pandas functions to answer various questions:
   * Determine the number of months on Mars.
   * Calculate Martian days of data in the dataset.
   * Identify the coldest and warmest months on Mars by finding average minimum daily temperatures and plotting them.
   * Determine the months with the lowest and highest atmospheric pressures on Mars by finding average daily atmospheric pressures and plotting them.
   * Estimate the number of terrestrial (Earth) days in a Martian year by considering the time Mars takes to orbit the Sun and visualizing the daily minimum temperature trend.
5. Export the DataFrame containing your analyzed data to a CSV file.

This project will enhance your web scraping skills and allow you to uncover insights from Mars-related data sources. Dive into the notebooks and embark on your journey of exploring the Martian climate and news!'
