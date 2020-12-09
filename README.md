<img src="https://raw.githubusercontent.com/codecaviar/digital_asset_management/master/assets/bingyune-and-company-logo-6400x3600.png" align="left" width="200" height="auto">

<br/><br/><br/><br/>

----------

# Beautiful Soup: How to Extract Data With Web Scraping

**Code Caviar Story**: https://www.bingyune.com/blog/beautiful-soup-webscraping    

## Project Overview

Web scraping is a technique used to extract and save large amounts of data from websites. Data, in general terms, is any set of information that is collected, shared, or stored for some purpose such as texts or numbers written on a piece of paper, bytes or bits inside the memory of a smartphone, and even facts or beliefs that are stored inside a person's mind. Unfortunately, data displayed by most websites can only be viewed using a web browser - be it text, media, or data in any other format. When you try to get the data you want manually, you might spend a lot of time clicking, scrolling, and searching. Web scraping essentially automates this process of collecting the data, performing the same manual task within a fraction of the time. The concerns with time and repetition is especially true if you need large amounts of data from websites that are regularly updated with new content. Because every website is different and many websites constantly change, each website will need its own personal treatment to extract the data relevant to you. Enter web scraping.

**The goal of this project is to provide a practical introduction to web scraping in Python.** The project makes use of webpages from [Red Light Novel](https://www.readlightnovel.org/terms-of-service). The website gives users access to read light novels, web novels, Korean novels, and Chinese novels online for free. The project will turn a web novel into an audio book. *Solo Leveling* or *I Alone Level Up* is a South Korean web novel written by Chugong. The web novel was serialized in [Kakao](https://en.wikipedia.org/wiki/Kakao)'s digital comic and fiction platform KakaoPage since July 25, 2016, and later published by D&C Media under their Papyrus label since November 4, 2016. The novel has been licensed in English by Webnovel under the title *Only I Level Up*.

## Summary:

Writing automated web scraping programs is fun, and the use cases of web scraping for business and personal needs are endless. For example, a business might use web scraping to gather contact details of businesses from websites like linkedin.com. Similarly, an individual might use web scraping to gather product details (price, images, rating, review, etc.) from a website like amazon.com to test and train machine learning models. Just remember, not everyone wants you pulling data from their web servers. If you’re scraping a page respectfully for educational purposes, then you’re unlikely to have any problems. Still, it’s a good idea to do some research on your own and make sure that you’re not violating any Terms of Service before you start a large-scale project. To learn more about the legal aspects of web scraping, check out [Legal Perspectives on Scraping Data From The Modern Web](https://www.lawinsociety.org/legal-perspectives-on-scraping-data-from-the-modern-web).

## Getting Started

Cloning the git repository and installing the provided packages will help you get a copy of the project up and running on your local machine. The analysis for this project was performed using Jupyter Notebook (.ipynb) and the packages were managed using the Anaconda platform.

```
git clone https://github.com/codecaviar/beautiful_soup_webscraping.git
conda env create -f environment.yml
```

File Description:
* environment.yml - packages used to perform this analysis
* notebook_beautiful_soup_webscraping.ipynb - Jupyter Notebook for this project including data wrangling and exploratory data analysis     

## Authors

- **BingYune Chen** - [LinkedIn](https://www.linkedin.com/in/bingyune-chen/)
- **BingYune & Co** - [GitHub](https://github.com/codecaviar)

## License

The project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

The project referenced the following resources:
* https://realpython.com/beautiful-soup-web-scraper-python/
* https://realpython.com/python-web-scraping-practical-introduction/

----------
The Code Caviar is a digital magazine about data science and analytics that dives deep into key topics, so you can experience the thrill of solving at scale.
