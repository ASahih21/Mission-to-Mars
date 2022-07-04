# Mission-to-Mars

## Goal
To learn how to retrieve meaningful data from the web. Using **Flask, HTML, Python, MongoDB, Splinter, Pandas and BeautifulSoup**, we set out to retrieve data regarding NASA's activities on Mars.
The information was then display on a web side where it could be refreshed at will.

## Process
We created an entry point to the application: **app.py**. This module held routes that did the scraping work. It connected to the various URLS and extracted the initial data set that is displayed on the screen. This module also performed additional data extraction and returned a dataset whose content gets parsed on the web page. The content of this dataset is then inserted onto MongoDB. In this case we had created a data and collection: **mars_app**.  The formatting of the information of the web page resided in and **index.html**, located in the **templates** folder.
