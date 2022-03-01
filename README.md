GCT - [GeoCompetitorTracker 🗺 ](http://geocompetitortracker.herokuapp.com/)

The scope of the project is to give an insight to food delivery companies that are looking forward to expand their business on a given city, Berlin for this instance.
We learned how to scrape web pages using Selenium, sourcing data from HERE Api, structure, package and deliver the program through a front end using a basic webframe (streamlit).
This project is a display of the gathered knowledge through the months spent at campus learning Data Science related disciplines.

Features:

- Data visualization regarding quantities and qualities about the restaurants present in the examined area.
- This project is entirely written in Python 🐍, we used different libraries to display data such as Pandas , Numpy, Matplotlib, Folium etc, Selenium and BeautifoulSoup for scraping and Heroku for deployment.
- Two of the main challenges were to work with the limited number of results per request made on the HERE API, and to work with CSS selectors on Lieferando & Wolt pages; in the first case we came up with a mathematical function to split the total area of the city (delimited with a geojson file) into smaller areas where there were at most 100 restaurants (width of the area found by trial and error). The second case was tackled by switching from BeautifulSoup to Selenium thanks to its drivers who are able to detect and interact with CSS selectors, lots of reading through its documentation went through.

How to Use the Project

- Search page: input an address (no need to be to specific, uses similarity recognition) or an area of the city and the radius of the company's service area, then check the "search" box.
- Recommend page: input the same radius of operation and add the type of kitchens you would like to serve (or leave "All" for no preferences)

Credits
aside from the contributors [Ayelen Klas](https://github.com/ayelenklas), [Malte Bernaud](https://github.com/mberneaud), [Nicole Dressler](https://github.com/ndressler) and myself, a special thanks goes to [Dominik Wagner](https://github.com/domzae) who's been our mentor throughout the project and, of course, to [Le Wagon!](https://github.com/lewagon)

How to Contribute to the Project:
if you like what you see we're currently looking for a mentor in order to create a roadmap. Ideally we would like to see GCT scale on a global level beign able to produce on demand analysis for each main metropoli in the world, and then to apply to different industries too.
