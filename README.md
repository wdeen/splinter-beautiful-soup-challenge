# splinter-beautiful-soup-challenge
Module 11 Challenge (Splinter / Beautiful Soup) - Wassim Deen

# Summary of Challenge
- Part 1: Scrape Titles and Preview Text from Mars News (`part_1_mars_news.ipynb`)
    1. Use automated browsing to visit the Mars news site. Inspect the page to identify which elements to scrape.
        - Website: https://static.bc-edx.com/data/web/mars_news/index.html

    2. Create a Beautiful Soup object and use it to extract text elements from the website.

    3. Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures
        - Store each title-and-preview pair in a Python dictionary and give each dictionary two keys: `title` and `preview`.
        - Store all the dictionaries in a Python list.
        - Print the list in your notebook.

    4. Export the scraped data to a JSON file.

- Part 2: Scrape and Analyse Mars Weather Data (`part_2_mars_weather.ipynb`)
    1. Use automated browsing to visit the Mars news site. Inspect the page to identify which elements to scrape.
        - Website: https://static.bc-edx.com/data/web/mars_facts/temperature.html

    2. Create a Beautiful Soup object and scrape the data in the HTML table.

    3. Assemble the scraped data into a Pandas DataFrame (`weather_df`). The columns should have the same headings as the table
        - `id`: The identification number of a single transmission from the Curiosity rover
        
        - `terrestrial_date`: The date on Earth

        - `sol`: The number of elapsed sols since Curiosity landed on Mars

        - `ls`: The solar longitude

        - `month`: The month

        - `min_temp`: The minimum temperature, in Celsius, of a single Martian day

        - `pressure`: The atmospheric pressure at Curiosity's location

    4. Examine the data types in the Pandas DataFrame and convert if necessary

    5. Analyse your dataset (`weather_df`) using functions from Pandas to answer the following questions:
        - Q1: How Many Months Exist on Mars?
        - Q2: How Many Martian Days in the Scraped Dataset Exist?
        - Q3: What are the Coldest and the Warmest Months on Mars (at the Location of Curiosity)?
        - Q4: Which Months Have the Lowest and the Highest Atmospheric Pressure on Mars?
        - Q5: About How Many Terrestrial (Earth) Days Exist in a Martian Year?

    6. Export Mars Weather DataFrame (`weather_df`) to CSV


# Notes
1. Exported data is stored in 'Data' Folder


# Final Repository Structure
```
├── README.md
├── part_1_mars_news.ipynb
├── part_2_mars_weather.ipynb
└── Data
    ├── mars_news.json
    ├── mars_weather.csv

```
