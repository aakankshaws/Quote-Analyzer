# Scrapy Starter Project
To clone project 
git clone https://github.com/username/scrapy-tutorial-starter
cd .\scrapy-tutorial-starter\

## Setup
Tested with Python 3.6 via virtual environment:
```shell
$ python -m venv venv
$ venv\Scripts\activate.bat
$ python -m pip install -r requirements.txt
```
## Create and Run Project
$ scrapy startproject project_name

Create new file for the spider

$ scrapy crawl quotes
$ scrapy shell url

## Save to json file 
$ scrapy crawl quotes -o quotes.json

add items in items.py
add ipeline to process item
add models.py for DB
add connect string in settings
add in pipelines.py
