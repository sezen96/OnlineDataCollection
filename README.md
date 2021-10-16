# OnlineDataCollection

#RESEARCH QUESTION

"Which different categories of crypto currencies can be identified, and what are their characteristics?"

__1. Motivation__

1.1
 
Crypto currencies are getting more and more popular lately and people increasingly start investing in it. This project aims to investigate the different categories of crypto currenties that exist, and their characteristics. As crypto currencies are highly volatile, it is very interesting to investigate their characteristics and how prices of different types of crypto currencies are affected. The dataset will provide users with a clear overview of crypto currency categories, and their specific characteristics. The research question has a high practical relevance, as it provides not only traders but also policy makers with insights on the characteristics of different types of crypto currencies. 

For generating this dataset, multiple relevant websites and API's were considered. Crypto news and Newsdata.io contain articles that are linked to dates, authors and crypto currencies. The data is only refreshed after publications of articles, which makes scraping more difficult. Also, the data on these websites can still be modified after it has been published, which is not the case for Coinmarketcap.com. We therefore choose to use the API of Coinmarketcap.com, where data is refreshed every minute, and which is more user friendly. This API fits our research question best, and provides good insights in the different types of crypto currencies.

1.2

This dataset is created by by team 7 of the course Online Data Collection and Management, consisting of Robbin de Waal, Efe Kiremitci, Sezen Birkan, Bram, and Xenia Tijssen. The course is provided by instructor Hannes Data, at Tilburg University.

__2. Composition__

2.1

Each instance in the dataset represents a different cryptocurrency that we retrieve from the website. These cryptocurrencies are divided into categories. These categories are based on/linked to certain characteristics.

2.2

Cryptocurrencies: The dataset currently consists of 7114 different cryptocurrencies. However, this number is grow-ing every day. 
Categories: there are 124 categories available.

2.3 

The data we scraped does not contain all possible instances, as we did not scrape all the cryptocurrencies available on the website. 

2.4

For each observation the following data is collected: 

__CATEGORY DATA__
- Average price change
- Description
- ID
- Last Updated
- Market Cap
- Market Cap Change
- Name
- Number of Tokens
- Title
- Volume
- Volume Change

__CRYPTOCURRENCY DATA__
- CMC rank 
- Date Added
- Is active (yes/no)
- Is fiat (yes/no)
- Last Updated
- Maximum Supply
- Name
- Number of Market Pairs
- Platform
- Quote -> _(Fully diluted market cap, last updated, market cap, market cap dominance, %-change 1hour, %-change 24hours, %-change 30days, %-change 60days, %-change 7days, %-change 90days, price, volume 24hours)_
- Slug
- Symbol
- Tags
- Total Supply
- Circulating Supply

2.5

Cryptocurrencies: these are labeled by name and a short abbreviation consisting of three letters.  
Categories: Categories are labeled by name. 

2.6

There is no information missing on individual instances. 

2.7

The relationship between the individual instances is that they are all cryptocurrencies, subdivided into different categories based on certain characteristics. 

2.8

2.9

The dataset is self contained.

2.10

All data inside the dataset is available to everyone and is therefore not considered as confidential. 

2.11

No, the dataset only contains cryptocurrencies and their characteristics. The dataset does not contain any data that might be considered offensive, insulting, threatening and the data will in no way cause anxiety. 

__5. Uses__

5.1
The dataset was created for educational purposes, and has not yet been used for any tasks.

5.2
The dataset has not yet been used in any papers or systems.

5.3
What (other) tasks could the datset be used for? ...

5.4
Is there anything about the composition of the dataset or the way it was collected and preprocessed/cleaned/labeled that might impact future uses? For example, is there anything that a future user might need to know to avoid uses that could result in unfair treatment of individuals or groups (e.g., stereotyping, quality of service issues) or other undesirable harms (e.g., financial harms, legal risks) If so, please provide a description. Is there anything a future user could do to mitigate these undesirable harms?

5.5
Is there anything about the composition of the dataset or the way it was collected and preprocessed/cleaned/labeled that might impact future uses? For example, is there anything that a future user might need to know to avoid uses that could result in unfair treatment of individuals or groups (e.g., stereotyping, quality of service issues) or other undesirable harms (e.g., financial harms, legal risks) If so, please provide a description. Is there anything a future user could do to mitigate these undesirable harms?
