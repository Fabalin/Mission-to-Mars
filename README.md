# Mission-to-Mars
Web-Scraping to procure data from NASA and JPL regarding Mars. 

## Overview 
Using Splinter in conjunction with Selenium, data was scraped from the HTML source file of the websites below: 

- [Mars NASA News Site](https://redplanetscience.com/)
  - News article data regarding Mars 
- [Mars Images](https://spaceimages-mars.com)
  - Latest Featured Image of Mars Surface
- [Mars Facts](https://galaxyfacts-mars.com)
  - Facts regarding Mars relative to Earth 
  - Scraped using Pandas.  
- [Mars Hemisphere Images](https://marshemispheres.com/)
  - Full size Image Links of Mars Hemispheres

This information was stored in the local MongoDB prior to injecting the links into the webpages' HTML file using flask app. A button was created in the webpage using Bootstrap3 CSS module to allow for fresh data to be scraped upon interaction. Finally, additonal formatting ws done to the HTML file using Bootstrap/ CSS components to procure background images and change the font color. Due to Bootstrap3's built in capability of having containers that are responsive to the size of the webpage, the final product was also mobile responsive. 

## Software
- Anaconda - 4.11.0
- Jupyter Notebook - 6.4.8
- Python - 3.7.11
- MongoDB - 5.0 
- HTML5
- CSS - 2.1
- Bootstrap - 3.0

### Key Dependencies in Python 
- Pandas (1.4.2)
- Splinter (0.17.0)
- Selenium (4.0)
- webdriver_manager (2.0.4)
- bs4 (7.3.1)
- PyMongo (4.1.1)
- flask (1.1.1)
- flask PyMongo (2.3.0)

## Results Showcase:
![Webpage1](https://github.com/Fabalin/Mission-to-Mars/blob/main/Resources/web_page1.PNG)
![Webpage2](https://github.com/Fabalin/Mission-to-Mars/blob/main/Resources/web_page2.PNG)
