# WebScraping
Before you start your own webscraping project, make sure that you respect effective copyright restrictions. Different countries have different perspectives on the legal side of web scraping and web crawling. Read the "Note of caution" below for more details.

This repository contains a set of Jupyter notebooks written in python for scraping data from websites and creating a csv file from it.

This script is partly based on the PH tutorial *Intro to Beautiful Soup* by Jeri Wieringa (for getting data from one page) and the BetterProgramming Tutorial *How to Scrape Multiple Pages of a Website Using a Python Web Scraper* by Angelica Dietzel (for getting data from multiple pages).

Another useful guide to scraping with python can be found here: https://www.learndatasci.com/tutorials/ultimate-guide-web-scraping-w-python-requests-and-beautifulsoup/

Documentations for *Beautiful Soup* can be found here: https://www.crummy.com/software/BeautifulSoup/bs4/doc/#find-all

## Responsible scraping

- Make sure to read the terms of use of the site you want to scrape. Some sites explicitely prohibit all forms of automated downloading.
- Check the robots.txt on the root of the site's domain. (More info on how to interpret what you find there here: https://en.wikipedia.org/wiki/Robots.txt)
- Control or limit your crawl rate (for example by inserting a sleep function) to avoid disrupting the activity of the website.

# Notebooks

### JapaneseStudents (multiple pages)
This notebook contains code to scrape data from the database: Lexikon Japans Studierende provided by the Staatsbibliothek Berlin (https://themen.crossasia.org/japans-studierende/index/show).
It is a database that lists the names of Japanese students who studied abroad at German universities and other higher education institutions from 1868–1914.

### PeaceTreaties (one page)
This notebook is based on a database focused on European peace treaties from 1450 to 1789 (https://www.ieg-friedensvertraege.de/vertraege).

The database was created as part of a project that was funded by the DFG (German Research Foundation) and contains a selection of some 1800 treaties.
