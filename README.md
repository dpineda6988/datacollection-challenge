# datacollection-challenge
# MarsSoup

An jupyter notebook analysis of data scraped from two websites using Splinter and Beautiful Soup.

## Description

Research and the potential exploration of Mars continues to be a topic of interest in the world of science and exploration.  Much of the data and latest finds exist in the form articles and data sets/tables now available widely on the internet.  This analysis is meant to extract some of the available data from different online websites for further research and inquiry and is separated into two parts

#### Part 1: Mars News
file name: 'part_1_mars_news.ipynb'

Splinter is used to automatically browse the [Mars News Site](https://static.bc-edx.com/data/web/mars_news/index.html) after which Beautiful Soup is used to extract the text selements from the webpage.  The titles and preview text of the news articles that were scraped are then extracted and saved to a dictionary.


#### Part 2: Mars Weather
file name: 'part_2_mars_weather.ipynb'

The [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html) contains Mars weather data collected by the Curiousity Rover. Splint is used to automatically browse the site and Beautiful Soup is again used to scrape the table displayed on the website.  Once collected, the data is then saved into a pandas DataFrame for further data manipulation and analysis.  Overall, the data is explored to answer the following questions:
1. How many months exist on Mars?
2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
3. What are the coldest and the warmest months on Mars (at the location of Curiosity)?
4. Which months have the lowest and the highest atmospheric pressure on Mars?
5. About how many terrestrial (Earth) days exist in a Martian year?

The data contained with in the DataFrame is also extracted into a .csv file for potential further use in the future.

### Dependencies
* Python with the following libraries: Splinter, Beautiful Soup, pandas
* jupyter notebook - file names: 'part_1_mars_news.ipynb' and 'part_2_mars_weather.ipynb'
* Google Chrome web browser with an internet connection

### Installing & Execution
Once the necessary programs and libraries are installed, the MarsSoup directory can be downloaded to execute the main files ('part_1_mars_news.ipynb' and 'part_2_mars_weather.ipynb').

## Authors

Daniel Pineda

## Acknowledgments
MarsSoup was created as an assignment for the University of California, Irvine Data Analytics Bootcamp - June 2024 Cohort under the instruction and guidance of Melissa Engle (Instructor) and Mitchell Stone (TA).
The practical exercises and coding examples demonstrated through the bootcamp helped inform and inspire the code for this project.