# web-scraping-github

### - By Neil Mankodi



## What is Web Scraping?
Web scraping is the process of collecting and parsing raw data from the Web. The Internet hosts perhaps the greatest source of information on the planet and being able to parse this information and extract only the relevant information is a very valuable skill. Many disciplines, such as data science, business intelligence, and investigative reporting, can benefit enormously from collecting and analyzing data from websites. 

## Project Outline:
* Identify site to scrape
  * In this project we will be scraping "https://github.com/topics"
* Goal of this project
  * Scrape the github web pages to extract information about the topics listed on the above mentioned url and then for each topic, scrape the topic specific url to extract information about the top repositories of that topic
  * Save all this information in csv files which can then be used for future analysis
* Install required libraries. Libraries used in this project are as follows:
  * Requests
  * BeautifulSoup
  * Pandas
  * OS
* Use requests library to download web page "https://github.com/topics"
* Use the BeautifulSoup library to parse and extract the following information regarding the topics listed on the web page:
  * Title of the topic
  * Description of the topic
  * URL to the topic's web page
* For each topic listed on the above web page:
  * use the requests library to download the specific web page eg. "https://github.com/topics/3D"
  * use the BeautifulSoup library to parse and extract information from the web page
  * scrape the web page of that topic to extract the following information for all the repositories listed
    * Username of owner
    * Name of the repository
    * Number of stars achieved by that repository
    * URL for the repository
* Save all extracted information as seperate csv files
