# Web scraping Of Top Restaurants in Mumbai from Zomato


######  Web scraping tool created with BeautifulSoup and Selenium.
<br>


### Table of Contents
1) Introduction
2) About the website
3) Installations and Versions
4) Built with
5) Source
6) Conclusion
<br>


### Introduction
---
The following repo is an attempt to get **required data** from Zomato's website, to do an in depth analysis of the the restaurant industry in the financial capital of India. Here, Selenium is used to automate the browser for dynamic page of Zomato and BeautifulSoup is used for parsing.
Mumbai is also the most diverse city in the Country.  So analysis would provide a good picture of the favorable type of restaurant in the city.
<br>


### About the Website
---
In this article, we'll be scraping data from Zomato's webpage (https://www.zomato.com/mumbai/great-food-no-bull) which gives highest-rated restaurants in Mumbai. The number of restaurants will keep on changing and there are many of them to manually click on each restaurant and gets its data. Thank God we have **Web scraping**.
<br>


### Installations and Versions
---
1. Python -  [Python 3.7.6](http://https://www.python.org/downloads/release/python-376/ "[Python 3.7.6]")
2. Selenium Webdriver - [ChromeDriver 79.0.3945.36](http://https://chromedriver.storage.googleapis.com/index.html?path=79.0.3945.36/ "chromedriver")
3. BeautifulSoup - [BeautifulSoup4](http://https://pypi.org/project/beautifulsoup4/ "BeautifulSoup4")
<br>


### Built With
---
Jupyter <br>
Selenium
<br>

### Project Status
---
This project has been completed sucessfully and is effectively scraping data from the provided website, which will be used to do analysis of the restaurants types in the city of Mumbai.
<br>

### Source
---
* Medium 
* Dataquest Article - [Python WebScraping usinf BeautifulSoup](http://https://www.dataquest.io/blog/web-scraping-tutorial-python/ "Python WebScraping usinf BeautifulSoup").
* [TechBeamers](http://https://www.techbeamers.com/switch-between-windows-selenium-python/ "TechBeamers")
<br>

### Conclusion
---
Data extracted  from the site:
* **Name**: Name of Restaurant.
* **Area**: Area Residing in (for simplicity taken to be the nearest Railway Station).
* **Type**: Type of Restaurant.
* **Rating**: Rating of Restaurant on Zomato.
* **Ph_Number**: Phone Number of Restaurant.
* **Cuisine**: Cuisines available at Restaurant.
* **Avg_price**: Average price for two.
* **Beer**: Price for beer for 2
* **Time**: Operating time of Restaurant (in terms of either Breakfast/Lunch/Dinner/Brunch...)
* **Address**: Address of Restaurant.
* **Facility**: Facilities available at Restaurant.
* **Food_Rating**: Food rating given by Zomato users.
* **Service_Rating**: Service Rating given by Zomato users.
* **Ambience_Rating**: Ambience Rating given by Zomato users.


