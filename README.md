**BlackSwan AI v1.0.0 - Proof of Concept Release**

A ChatGPT powered news trading tool. Prepare for potential bullish and bearish events occuring in  crypto markets by executing a leveraged futures trading instanteously upon the release of anticipated news, the OpenAI API reads the latest stories and determines if the condition has been met. Enter your crtieria into the conditions.json file and run the main blackswan.py script to continuously scan news stories from a number of stories.

A test instance can be found in the folder 'test_instance' to simulate a given news story being matched against criteria and ensure you are configuring the bot correctly.

Full instructions can be found on our website: blackswan.biz within our white paper.

This is a long term project with plans to require native **$BLACKSWAN** token holdings for usage and train historical market data against news reports to allow trades to be made based on breaking news articles without any prior conditions being specified.


**REQUIREMENTS:**

python 3.8

OpenAI account with API key

ByBit account with API key 


**Install with PIP:**

feedparser 6.0.10

beautifulsoup4 4.8.2 

openai 0.27.0

Bybit 0.2.12

**Configuration steps:**

Input API keys into config.py

Input desired conditions, trading pairs and amounts into conditions.json

Fund ByBit futures account with funds for an inverse trading pair (BTC, ETH, etc) - support for linear pairs with USD collateral coming in future updates. See roadmap/white paper for details.

