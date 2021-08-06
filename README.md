# ETH-USD-price-feed-using-Chainlink-oracle-Web3-Brownie-Python-and-Solidity
● Chainlink Price Feeds are the quickest way to connect smart contracts to the real-world market prices of assets. 
● The latest price of Ethereum (ETH) inside smart contracts is fetched using the ETH/USD Price Feed on the Kovan testnet. 
● To consume price data, your smart contract should reference AggregatorV3Interface, which deϐines the external functions implemented by Price Feeds.
1. Fetches Current Data Price From Any Oracle [Code Snippet]
![image](https://user-images.githubusercontent.com/88326377/128458517-5e97c6e1-e1a8-4a99-9c2d-62997f3ecc48.png)

2. Records that data in a struct [Code Snippet]
![image](https://user-images.githubusercontent.com/88326377/128458555-24269f3b-98be-480f-a86b-15024e99c256.png)
![image](https://user-images.githubusercontent.com/88326377/128458575-a1c4152f-3e1a-4768-ba05-86be67a41506.png)

3. A function to calculate mean of the prices stored [Code Snippet]
![image](https://user-images.githubusercontent.com/88326377/128458595-7602aca8-cac8-4a98-8ab1-b27911b31201.png)

4. Write CRUD operations for that struct [Code Snippet]
![image](https://user-images.githubusercontent.com/88326377/128458617-f89c9aa6-2e6f-4659-a41f-760020702902.png)

5. Also write tests for these 
a. Deployed contracts 
![image](https://user-images.githubusercontent.com/88326377/128458680-bc033745-3d59-41f6-9cf8-64c1844b1808.png)

b. Unit testing
![image](https://user-images.githubusercontent.com/88326377/128458695-81f8c69d-6a61-4849-81a0-b9cf69beb06b.png)

