# web-scraping-challenge

## Scraping

#### Part One
- Open a jupyter notebook and create a file for webscraping
- Start with the NASA Mars News site and collect the latest news title and paragraph

#### Part two
- Then visit the URL for JPL Mars Space Images
- Use splinter to naigate the site and find the image URL for current mars images

#### Part three
- Use the Mars Facts webpage to use Pandas to scrape the table of facts and convert the data to a HTML string

#### Part four
- Visit the astrogeology site to obtain images for each hemisphere of Mars
- Save the URL strings and append the dictionary with the image URL string to a list

## MongoDB and Flask Application
- Create a python script that will execute all scraping code from the jupyter notebook and return one Python dictionary that contains all of the scraped data
- Create a flask route that will import your script and call your scrape function
- Create an indix route that will query your Mongo database and the the Mars data into an HTML to display data
- Create and index.html that will take the Mars data dictionary and display it.
