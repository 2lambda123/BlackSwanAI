
**BlackSwan AI v2.0.b - Phase 2 Release**

We are proud to officially announce our Phase 2 release with the following major updates.

- added Windows compatible version
- added support for linear and inverse trading pairs
- added support for 3 additional exchanges (Kucoin, Binance and Bitmex)
- added support for Take Profit/Stop Loss (TP/SL)
- added Twitter monitoring, search for Tweets by username or search term
- fixed bugs related to script exiting when API requests fail or OpenAI returned JSON is invalid.


**BlackSwan AI v1.0.0 - Proof of Concept Release**

A ChatGPT powered news trading tool. Prepare for potential bullish and bearish events occuring in  crypto markets by executing a leveraged futures trading instanteously upon the release of anticipated news, the OpenAI API reads the latest stories and determines if the condition has been met. Enter your crtieria into the conditions.json file and run the main blackswan.py script to continuously scan news stories from a number of stories.

A test instance can be found in the folder 'test_instance' to simulate a given news story being matched against criteria and ensure you are configuring the bot correctly.

Full instructions can be found on our website: blackswan.biz within our white paper.

This is a long term project with plans to require native **$BLACKSWAN** token holdings for usage and train historical market data against news reports to allow trades to be made based on breaking news articles without any prior conditions being specified.


**REQUIREMENTS:**

python 3.1.0

pip

Git

OpenAI account with API key

ByBit/Binance/Bitmex/Kucoin account with API key 


**Install with PIP:**

feedparser 6.0.10

beautifulsoup4 4.8.2 

openai 0.27.0

Bybit 0.2.12

(use command 'pip install -r requirements.txt' in both the main folder and blackswan-master folder to install dependencies)
**Configuration steps:**

Input API keys and searched search terms/user accounts into config.py

Input desired conditions, trading pairs and amounts into conditions.json

Fund ByBit futures account with funds for an inverse trading pair (BTC, ETH, etc) - support for linear pairs with USD collateral coming in future updates. See roadmap/white paper for details.

