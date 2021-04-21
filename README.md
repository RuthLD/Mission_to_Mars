# Mission_to_Mars
Project 10 of Bootcamp Using Web Scraping to collect infromation about Mars.
## Overview
Using BeautifulSoup to visit and collect the most recent information about the plant Mars from four different websites.
1. The first website was the [NASA Mars News Site](https://redplanetscience.com) to get the featured news article title and description. 
1. The second website was to find the [Featured Image](https://spaceimages-mars.com) from Mars.
1. The third website was to get a table of weather [facts from Mars](https://galaxyfacts-mars.com) compared to Earth.
1. The fourth website was to get images of the [four hemispheres of Mars](https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars).
	
## Results
The follow are examples returned from the [scraping.py](https://github.com/RuthLD/Mission_to_Mars/blob/main/scraping.py) file.
1. Example of Article Title and Description:
	* ![Img_1.png](https://github.com/RuthLD/Mission_to_Mars/blob/main/Resources/Img_1.png)
2. Example of Featured Image:
	* ![Img_2.png](https://github.com/RuthLD/Mission_to_Mars/blob/main/Resources/Img_2.png)
3. Example of Facts:
	* ![Img_3.png](https://github.com/RuthLD/Mission_to_Mars/blob/main/Resources/Img_3.png)
4. Example of Hemisphere Images:
	* ![Img_4.png](https://github.com/RuthLD/Mission_to_Mars/blob/main/Resources/Img_4.png)


The images are returned as URLs to be used in the [app.py](https://github.com/RuthLD/Mission_to_Mars/blob/main/app.py) file to create a simple webpage to scrape for the most recent news about Mars.

## Webpage
The simple web page was created using MongoDB and Flask to scrape the web for the most recent news articles. The page html is [here](https://github.com/RuthLD/Mission_to_Mars/blob/main/templates/index.html). 
