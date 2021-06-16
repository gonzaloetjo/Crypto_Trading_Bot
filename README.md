**CRYPTOCURRENCIES TRADING BOT**

This projects aims at developing an algorithm composed of several pieces of code, in which some cryptocurrencies prices are predicted. Based on these predictions, an investment fund of cryptocurrencies will be established on Enzyme, with its corresponding wallet address so that it can be easily accesible for people who would like to invest.

In this project, a Reddit scrapper will be used in order to get comments and submissions from Reddit in the past years. Those news will be passed through a pretrained transformer (GPT-2) in order to analyze its sentiment score. Once this id done, another scrapper will be used in order to get the historic of prices, volume... from a selected set of crypto assets on a daily basis. This information will be merged with the sentiment score for each day. After all this information is gathered, it will be passed through a deep learning regression model in order to be trained with it. For future news, Cryptopanic (news aggregator from several sources beyond Reddit) will be used. The transformer will be feeded with all this news and give as output its sentiment score, averaging by day. After this is done, this information will be merged with new daily prices, volumes... in order to keep on predicting future prices.