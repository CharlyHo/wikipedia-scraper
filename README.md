# Wikipedia scraper
 
BeCode learning project aiming at scraping wikipedia and using API.

# Mission Objectives

In this project, we will guide you step by step through the process of:

1. Creating a self-contained development environment (virtual environment)
2. Retrieving some information from an API
3. Leveraging your knowledge to scrape a website that does not provide an API
4. Saving the output for later processing

More specifically, in this project we will query an API to obtain a list of countries and their past political leaders. We then extract and sanitize their short bio from Wikipedia. Finally, we save the data.

Scraping data is often the first coding step of a data science project (meaning, the data collection) and you will likely come back to it in the future.

#  Installation  

Clone the repository:
"""
git clone https://github.com/CharlyHo/wikipedia-scraper.git
cd wikipedia-scraper
"""

Make sure you have Python installed. Then, install all required libraries by running:  
"""
pip install -r requirements.txt
"""


# Must-have features (MVP)

- You should have a working `wikipedia_scraper.ipynb` notebook that calls the API and creates a JSON file
- Create your own exception to include proper exception handling
- Have a nice README that explains your project.