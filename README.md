# Mission-to-Mars

## Overview

The purpose of this project was to write code to utilize an automated web brower to scrape data and images from several websites then store it to a NoSQL database before using Flasks to build a web application. The data was then used to build a web page.

## Resources

* Python 3.7, Jupyter Notebook 6.4.6, VS Code 1.63.2
* MongoDB, Flask
* HTML5, Bootstrap 3

## Analysis Overview

1. A python script was written to perform specified web scraping to collect and format data (raw text strings, image urls, etc). The full code can be viewed in the Mission_to_Mars_Challenge.ipynb file.
2. The DevTools was to inspect the respective pages for the correct elements/tags to scrape.
3. A scraping.py file was used to store the scraped code for further use/referencing for the flask application. The scraped data was then coded to be stored in a Mongo database
4. Flask was then used to create a web application of all the scraped data and a website was then created/modified using an index.html file. This webpage contains all the information collected/scraped.
5. Bootstrap was used as the styling reference to create the webpage. It was ensured the page was mobile responsive and where applicable, the html sheet was modified to make the built page more visually appealing.

## Results

Collectively

The following list of files contains the relevant information as it pertains to the result from this project.  Collectively, the code/script within these files was used to create a web application that can display scraped data including images from several sites.

1. The Mission_to_Mars_Challenge.ipynb file contains the code used for scraping.
2. An updated scraping.py file containing all the scraping code
3. The app.py file used to create the flask app
4. The index.html file in the template folder and CSS stylesheets in the static folder.

A preview of the created web app is displayed in the image below.

<img width="734" alt="im1" src="https://user-images.githubusercontent.com/92636438/149673359-efda0c55-4a65-4100-9d05-65ab35656792.png">

<img width="751" alt="im2" src="https://user-images.githubusercontent.com/92636438/149673369-0fcdcb8a-bcb4-46fc-ae23-c4fb89e3fc6e.png">



