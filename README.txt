Collecting, analyzing, and visualizing a rum data set!

**Fermenting the Features**

In this file we create a script to web scrape data from the 16,222 rums on the [RumX](https://www.rum-x.com/) site at the time of scraping. We extract information we think will be relevant for future analysis such as the age, rating, price, tasting notes, and much more about each rum when available. This script utilized the request, BeautifulSoup, and Pandas libraries to clean and save the data in a CSV file (rum.csv).

**Distilling the Dataset**

In this notebook we create a host of visualizations and look at a how a few key features might impact a rum's price and community rating. At the end, we create a function to generate tasting note co-occurrence heat maps to explore flavor profiles of rums from various countries. 

**Still Strength Statistics**

Finally, we take a statistical look at how some of the features we visually explored in the previous notebook explain rating and price. Using ANOVA and linear regression models we see what relationships are statistically significant and visualize if our models meet the assumptions for these types of analyses.
