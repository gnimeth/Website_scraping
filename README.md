
#  Website Scraping

- Extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup.

## Dependencies and Setup

```bash
from splinter import Browser
from bs4 import BeautifulSoup
import matplotlib.pyplot as plt
import pandas as pd
```


## Roadmap

- Extract the titles and preview text of the news articles. Store the scraping results in Python list
![App Screenshot](https://raw.githubusercontent.com/gnimeth/Website_scraping/main/Output/Screenshot_20230205_065313.png)

- Create a Beautiful Soup object and use it to scrape the data in the HTML table into a dataframe
![App Screenshot](https://raw.githubusercontent.com/gnimeth/Website_scraping/main/Output/Screenshot_20230205_065410.png)


- Analyze your dataset by using Pandas functions
![App Screenshot](https://raw.githubusercontent.com/gnimeth/Website_scraping/main/Output/Screenshot_20230205_065434.png)

![App Screenshot](https://raw.githubusercontent.com/gnimeth/Website_scraping/main/Output/Screenshot_20230205_065500.png)

## Acknowledgements
[The Mars News website](https://static.bc-edx.com/data/web/mars_news/index.html) is operated by edX Boot Camps LLC for educational purposes only. The news article titles, summaries, dates, and images were scraped from [NASA's Mars News](https://mars.nasa.gov/) website in November 2022.  Images are used according to the [JPL Image Use Policy](https://www.jpl.nasa.gov/jpl-image-use-policy) courtesy NASA/JPL-Caltech.
