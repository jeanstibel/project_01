## Project_01

## Introduction

### What is Cryptocurrency?
Cryptocurrency, often referred to as crypto, is a type of digital or virtual currency that uses cryptography for security. Unlike traditional currencies, cryptocurrencies operate without a central issuing or regulatory authority, relying instead on a decentralized system to record transactions and issue new units. Cryptocurrencies enable peer-to-peer transactions, allowing individuals to send and receive payments anywhere in the world without the need for banks to verify transactions.

Instead of existing as physical money, cryptocurrency transactions are recorded as digital entries in an online ledger. These transactions are stored in digital wallets and verified using encryption techniques to ensure security and integrity. The first and most well-known cryptocurrency, Bitcoin, was created in 2009. Today, many individuals are drawn to cryptocurrencies for trading and investment, often speculating on price movements.

### How Does Cryptocurrency Work?
Cryptocurrencies operate on a distributed public ledger known as blockchain. The blockchain maintains a secure and transparent record of all transactions, which is continuously updated by the network’s participants.

Cryptocurrency units are generated through mining, a process involving the use of computational power to solve complex mathematical problems. Alternatively, users can purchase cryptocurrencies from brokers and store them in cryptographic wallets. Ownership of cryptocurrency does not equate to holding a tangible asset but rather a key that enables the transfer of a recorded unit of measure on the blockchain.

### Cryptocurrency Examples

Thousands of cryptocurrencies exist today, but some of the most notable include:

- **Bitcoin (BTC):** The first cryptocurrency, created in 2009 by an entity known as Satoshi Nakamoto. It remains the most widely traded cryptocurrency.
- **Ethereum (ETH):** Launched in 2015, Ethereum is a blockchain platform that supports its own cryptocurrency, Ether. It is the second most popular cryptocurrency.
- **Litecoin (LTC):** A cryptocurrency similar to Bitcoin, Litecoin offers faster transaction times and innovative features.
- **Ripple (XRP):** Ripple’s distributed ledger system, launched in 2012, supports various types of transactions beyond cryptocurrency. Ripple has collaborated with several financial institutions.

### Dataset in Cryptocurrency

The dataset used in this project includes daily historical price data for various cryptocurrencies, starting from April 28, 2013. Key attributes of the dataset include:
- **Date:** Date of observation.
- **Open:** Opening price for the day.
- **High:** Highest price of the day.
- **Low:** Lowest price of the day.
- **Close:** Closing price for the day.
- **Time:** The hour of the day
- **Volume:** Total number of transactions for the day.
- **Market Cap:** Total market capitalization in USD.
- **Circulating Supply:** Total number of coins or tokens available for trading.

### Key Metrics:
- **Market Cap:** Measures the total value of a cryptocurrency, calculated as the current price multiplied by the circulating supply. Market cap helps rank cryptocurrencies, assess growth potential, and evaluate market sentiment.
- **Volume:** Indicates the total number of coins traded within a specific timeframe, reflecting market activity and liquidity.
- **Circulating Supply:** Represents the total number of coins currently available in the market for trading.

### Data Acquisition

The project uses two primary data sources:
1. **Coin Stats API:** Provides current data for the top 19 cryptocurrencies ranked by performance on a given day. Data includes opening prices, daily price changes, and 24-hour and 7-day changes.
2. **Kaggle:** Offers historical data for cryptocurrencies from 2017 to 2024, enabling comparative analysis of price trends and market behavior.

### Data Integration:

Initially, data from Coin Stats API was acquired for cryptocurrencies ranked from 1 to 19. Subsequently, historical data from Kaggle was cross-referenced to identify 13 cryptocurrencies with complete historical records. These included Bitcoin, Ethereum, Ripple, Binance Coin, Solana, Dogecoin, Cardano, Tron, Avalanche, Chainlink, Shiba Inu, Stellar, and Polkadot.

## Analysis and Insights

### Historical Performance:

The analysis focused on price trends from 2017 to 2024, including:
- Percentage change in price over time.
- Number of trades per year for each cryptocurrency.

### Performance Metrics:

To assess performance, the difference between yearly open(lowest) and close(highest) prices was calculated for each cryptocurrency from 2020 to 2024. Rankings were then adjusted based on this analysis. The top five performers were Bitcoin, Ethereum, Binance Coin, Solana, and Avalanche.
Key Observations:
- Bitcoin consistently dominated trade volume and market share across the years.
- Other cryptocurrencies, such as Ethereum and Binance Coin, also demonstrated strong growth.
- Avalanche’s rank improved significantly in the performance-based analysis compared to its initial ranking.

### Visualization:

- Graphs illustrating yearly high and low prices.
- Pie charts showing trade volume distribution for the top five cryptocurrencies.
- Bar charts comparing the number of transactions for each cryptocurrency annually.

### Conclusion

The analysis revealed that while Bitcoin and Ethereum maintained their dominance, other cryptocurrencies showed varying levels of growth and market activity. Performance-based rankings highlighted differences in cryptocurrency behavior over time, emphasizing the importance of diverse analytical approaches. Future research could explore additional factors such as regulatory impacts, adoption rates, and technological advancements.

### References
- Coin Stats Documentation: https://docs.api.coinstats.app/reference/market-data
- Coin Stats Website: https://coinstats.app/
- Kaggle Data: https://www.kaggle.com/datasets/kaanxtr/btc-price-1m
- https://en.wikipedia.org/wiki/Cryptocurrency
- https://www.coinbase.com/learn/crypto-basics/plp-what-is-cryptocurrency?utm_source=google_search_nb&utm_medium=cpc&utm_campaign=11552175024&utm_content=112936290695&utm_term=what+is+cryptocurrency&utm_creative=665616836048&utm_device=c&utm_placement=&utm_network=g&utm_location=9003437&gad_source=1&gclid=Cj0KCQiAvvO7BhC-ARIsAGFyToVdJuWYEpt90358re161PwgyNItg2m57Qv8DWAHECuJONOg0w06vFcaAjprEALw_wcB


