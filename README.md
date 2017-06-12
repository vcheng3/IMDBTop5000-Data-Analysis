# IMDBTop5000-Data-Analysis


Make Sure you have Tableau Desktop installed to view. 

Also view on Tableau online:

https://us-east-1.online.tableau.com/#/site/imdbtop5000visualization/user/external/vcheng3@buffalo.edu/workbooks
and
https://us-east-1.online.tableau.com/#/site/imdbtop5000visualization/workbooks/52032/views

Cleaned in R, dataset retrieved from 

https://www.kaggle.com/deepmatrix/imdb-5000-movie-dataset

# Note on the original dataset.

The dataset from kaggle actually has many problems that originated from the web crawling and data scraping. As a result, you'll have complications such as numbers not being accurate for a large number of movies. For example, most of the numeric data is in USD. The european films for the most part have been converted. The problem lies with the asian films. Many of the international asian films don't have their numeric data in USD for parts like grossing, budget, etc.. This is a problem. There is also no easy way to automate this. Therefore I had to manually convert many of those numeric values.
