
                                                                                           Michelle Werner (6/12/2022)
# Mission to Mars: Web Scraping for NASA
---

<!--![alt](resources/___.png)-->
<img src="https://github.com/miwermi/mission-to-mars/blob/main/assets/amazing-mars.png" align="right" width="500" height="293" alt ="graphic: Amazing Mars">

## Project Overview

Junior data Scientist Robin does free lance astronomy work and hopes to work for NASA someday.  She spends a lot of time reading web articles and is currently fascinated with Mars.  For this project, I've helped Robin code a web scraper that puts together Mars data from several different sites:  

- MARS Planet Science (https://redplanetscience.com)
- California Institute of Technology's Jet Propulsion Lab (https://spaceimages-mars.com)
- Galaxy Facts on Mars (https://galaxyfacts-mars.com)
- Astropedia's Lunar and Planetary Cartographic Catalog (https://marshemispheres.com)

Figure 1: Robin and her telescope looking up at amazing Mars!


## Tech Specs
<!--![alt](resources/___.png)-->
<img src="https://github.com/miwermi/mission-to-mars/blob/main/assets/web-scraping-flask-to-mongo.png" align="right" width="500" height="293" alt ="graphic: Flask to Mongo Web Scraping">

To show Robin my work, I've created an HTML index that populates with Flask from Python code and a Mongo database.  Each time my python code is run, each of the sites we're pulling from is visited and scraped with the help of Splinter, and my python code collects and stores as new batch of info in my mongo database. Last but not least, the mongo data is called back and my web page is rebuilt!  

Figure 2: Web Scraping with Splinter, Flask, Mongo and Python


## Webpage Preview
<!--![alt](resources/___.png)-->
<img src="https://github.com/miwermi/mission-to-mars/blob/main/assets/web-scraping-flask-to-mongo.png" align="right" width="500" height="293" alt ="graphic: Flask to Mongo Web Scraping">





<img src="https://github.com/miwermi/mission-to-mars/blob/main/assets/mission-to-mars_index.html.jpg" align="right" alt ="graphic: Mission to Mars Site Index">
