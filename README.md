# Analysis of Speeches by Government Heads of India and USA

In this project our contribution has been the following:

* Scrape the presidential speeches by the presidents of the United States (1789-latest).
* Scrape the Speeches by our ex-PM Dr. Manmohan Singh (2008-2014). 
* Scrape the speeches by our current PM Narendra Modi (2020-latest) and harmonise the data with already existing data source (2014-2020).
* We make all the data sources scraped above publically available for further potential research.
* We perform various analysis on this data starting from a preliminary statistical analysis. Then we perform topic modelling experiments on the data by the United States Presidents as well as the Prime Ministers of India. We contrast the topics between the two Indian PMs. This is a new contribution to literature to the best of our knowledge. We further perform sentiment analysis experiments on the data for both settings.


Link to data (csv) files: https://drive.google.com/drive/folders/1_-Rm9goWmW7h-y1kG8VEAnYZ2-dE-lH7?usp=share_link

The file structure of this repository is as follows:

```go
+--- india_dump // contains the results for India
+--- usa_dump // contains the results for USA
+--- analyse_india_extra.ipynb // Code for India Analysis (2)
+--- analyse_india.ipynb // Code for India Analysis (1)
+--- analyse_us_dataset.ipynb // Code for Scraping US dataset
+--- analyse_us.ipynb // Code for performing analysis on US dataset
+--- combine_india_modi.ipynb // Code for harmonising the datasets for Modi Speeches
+--- scrape_india_manmohan.ipynb // Code for scraping Manmohan Singh Speeches
```