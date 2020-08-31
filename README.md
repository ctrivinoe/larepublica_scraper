# larepublica_scraper

## Xpath - Python 

_Project developed for the [Platzi's](https://platzi.com/clases/web-scraping/) Web Scraping Basics with Python and Xpath._

This project is a news scraper for the newspaper [La Republica](https://www.larepublica.co/). We will extract titles, summaries and body from the news to store them for further analysis. The storage will be a folder with the daily date that will contain a .txt for each news extracted.


## Preview 👁

![](https://media.giphy.com/media/JTW0Qa33DeAiV3YNX5/giphy.gif)


## Warning ⚠️

This project is functional today (31-08-2020). If the HTML structure of the [website](https://www.larepublica.co/) changes, the project'll not work well.
Also advise that scraping is totally legal today (31-08-2020) on the [website](https://www.larepublica.co/).

## Pre-requisites 📋
_You need Python 3 for run this project: [Python 3](https://www.python.org/downloads/release/python-370/)_

## Deployment 🚀🌐

We need to create a virtual environment to run the project. To do this, from the project folder: 
* Windows:
```
py -m venv venv
```
* Linux
```
python -m venv venv
```
To activate it:

* Windows:
```
venv\Scripts\activate
```
* Linux:
```
source venv/bin/activate
```
Once activated, we need to install the dependencies:
```
pip install request lxml
```
* Request: for http
* LXML: for Xpath

## Run 🏃
To run the program (with the virtual environment activated):

```
py scraper.py
```

## Tools 🛠️

* [Visual Studio CODE](https://code.visualstudio.com/) - Code Editor


## Author ✒️

* **Cristian Triviño Estévez** - [Personal Site](https://ctrivinoe.com)


---
❤️ [ctrivinoe](https://github.com/ctrivinoe) 🍻
