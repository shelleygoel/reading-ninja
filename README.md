# reading-ninja

## Objective: 
Cluster similar articles to save time and avoid reading overlapping information. 
Create an heirarchy of articles based on difficulty level to determine a natural progression of reading.

## Data:
Data for this project is scraped from blogs listed below:
dataquest.io

Data is dumped in json format.
Each data point has the following attributes:
* Code: 'int' 0 or 1 (1 if the article includes some form of code)
* title : 'str' title of the article
* link : 'str' url of the article
* content : 'str' complete plain text of the articl (excluding any links or code)
### Scraping script is available in scraping_data.ipynb

## Analysis:
Initial analysis consists of k-Means clustering and PCA to identify similar articles.
### Script is available in Clustering_analysis.ipynb

