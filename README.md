# ETH-USD-price-feed-using-Chainlink-oracle-Web3-Brownie-Python-and-Solidity
1. Chainlink Price Feeds are the quickest way to connect smart contracts to the real-world market prices of assets.
2. The latest price of Ethereum (ETH) inside smart contracts is fetched using the ETH/USD Price Feed on the Kovan testnet.
3.  To consume price data, your smart contract should reference AggregatorV3Interface, which deϐines the external functions implemented by Price Feeds.

1. Fetches Current Data Price From Any Oracle [Code Snippet]
![image](https://user-images.githubusercontent.com/88326377/128458517-5e97c6e1-e1a8-4a99-9c2d-62997f3ecc48.png)

2. Records that data in a struct [Code Snippet]
![image](https://user-images.githubusercontent.com/88326377/128459710-7a0b11da-5c4c-44b2-9487-404a99389515.png)

3. A function to calculate mean of the prices stored [Code Snippet]
![image](https://user-images.githubusercontent.com/88326377/128458595-7602aca8-cac8-4a98-8ab1-b27911b31201.png)

4. Write CRUD operations for that struct [Code Snippet]
![image](https://user-images.githubusercontent.com/88326377/128458617-f89c9aa6-2e6f-4659-a41f-760020702902.png)

5. Also write tests for these 
![image](https://user-images.githubusercontent.com/88326377/128458695-81f8c69d-6a61-4849-81a0-b9cf69beb06b.png)

