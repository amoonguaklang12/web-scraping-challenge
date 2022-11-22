# web-scraping-challenge

This challenge tests my ability to web scrape data from given websites using HTML tags. It then tasked me to perform various operations on the data such as cleaning it, updating it, and loading it into various formats such as a cluster hosted by MongoDB or exported as a CSV file.

This repo contains the following items:

- mars_data_challenge_part_1.ipynb
	- Web scraped article titles and summaries from the Mars News website (https://redplanetscience.com/).
	- Placed scraped data into dictionary format
	- Uploaded the collection into a cluster hosted on MongoDB
- mars_data_challenge_part_2.ipynb
	- Web Scraped data from a table containing Mars temperature data (https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html)
	- Transformed scraped data into a Pandas dataframe
	- Performed graphical analysis and created visualizations
	- Exported the dataframe to a csv file in the Resources directory
- Resources directory: Contains the exported csv file from mars_data_challenge_part_2.ipynb

All relevant analysis and visualizations can be found in the jupyter notebooks.