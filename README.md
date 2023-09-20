# Mars Data Scraping and Analysis Project

## Introduction
This project involved the extraction and analysis of Mars-related data through two distinct deliverables. The first part focused on scraping titles and preview text from Mars news articles, while the second part involved scraping and analyzing Mars weather data.

## Deliverable 1: Mars News Scraping (part_1_mars_news.ipynb)

### Objective
In Deliverable 1, our primary goal was to scrape titles and preview text from the Mars News website. This process required automated web browsing to access the website and meticulous inspection of the page structure to identify the specific elements for extraction. To facilitate text extraction from the website, we employed the Beautiful Soup library.

### Data Handling
The scraped data was organized into Python data structures, specifically dictionaries with two keys: "title" and "preview." These dictionaries were then stored within a Python list for ease of management. As the final step, the collected data was presented within the Jupyter Notebook. An optional task was provided, allowing for the export of the scraped data to a JSON file for streamlined sharing, although this step was not obligatory for the assignment.

## Deliverable 2: Mars Weather Data Analysis (part_2_mars_weather.ipynb)

### Objective
Deliverable 2 focused on scraping and conducting a comprehensive analysis of Mars weather data obtained from the Mars Temperature Data Site. Similar to the previous task, we employed automated web browsing to access the website and identify the pertinent elements for scraping. The instructions recommended using Beautiful Soup to extract data from an HTML table.

### Data Handling
The scraped data was skillfully organized into a Pandas DataFrame, with each column aligned with the headings from the original table. These columns included crucial information such as identification numbers, terrestrial dates, Martian days (sols), solar longitudes, months, minimum temperatures, and atmospheric pressure readings. We carefully examined the data types of each column and made necessary conversions to datetime, int, or float data types where applicable.

### Data Analysis
The analysis phase of the dataset involved answering several key questions using Pandas functions. These questions included:
- Determining the number of months on Mars (12 in total).
- Calculating the quantity of Martian days' worth of data available in the dataset (a total of 1867).
- Identifying the coldest and warmest months on Mars (months 3 and 8) by calculating the average minimum daily temperature and visually representing the results as a bar chart.
- Identifying the months with the lowest and highest atmospheric pressure (months 6 and 9) by calculating the average daily atmospheric pressure and visually presenting these findings as well.
- Estimating the number of terrestrial days in a Martian year by considering the time it takes for Mars to complete its orbit around the Sun (approximately 650 Earth days) and plotting the daily minimum temperature to visualize this data.

### Conclusion
In the final step, we exported the meticulously organized DataFrame to a CSV file for future reference and analysis. This project showcases a combination of web scraping techniques and data analysis skills to extract and derive valuable insights from Mars-related data, contributing to our understanding of the Red Planet.
