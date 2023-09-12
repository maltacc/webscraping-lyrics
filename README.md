# Taylor Swift Lyric Scraper
The goal of this project was to use absolutelyrics.com to retrieve, clean, and visualize data about Taylor Swift's songs. We then selected VADER and BERT models to perform sentiment analysis, where the BERT model achieved a 96% accuracy score.

# Data 
* We web-scraped 11 Taylor Swift albums from absolutelyrics.com. Although absolutelyrics.com has not been updated, it allowed web scraping. Alternate lyric websites blocked access even with a 20-second sleep time between requests.
* Data was evaluated based on accuracy score and F1 score. 

# Visualizations
* Stacked bar chart 
* Word cloud

# Models 
* Our Lyric Scraper employed a VADER and ALBERT Model to perform sentiment analysis on all lyrics. Because VADER was pre-trained using Twitter and Facebook texts, it was more suited to short, less complex strings. As we were classifying the lyrics of each song, we also trained an ALBERT Model. 
