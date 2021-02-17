# Week-1-Homework-
## Compound Case Study (Blockchain and Cryptocurrencies)

### Overview 

Compound was founded in 2017 and is headquartered in San Francisco, California. Geoffrey Hayes and Robert Leshner are the founders of the company. Compound is an open-source decentralised protocol that unlocks new financial applications for developers. In simple terms, Compound is a lending platform in the cryptocurrency market where people can use their crypto assets as collateral to take loan or lend assets to another people and gain a decent annal interest on their assets.  

Compound has raised two rounds of funding. The first round raised $8.2M from seed funding on 16 May 2018. Their latest funding  raised $25M on Nov 14, 2019 from series A funding (early-Stage Venture). Therefore, Compound has raised $33.2M fund in total. Moreover, Compound is funded by 11 investors among which Andreessen Horowitz and Bain Capital Ventures are the most recent investors. According to PriveCo, Compound has a post-money valuation in the range of $100M to $500M as of Nov 14, 2019. 


### Business Activities 

Basically, Compound’s protocol is a series of open-source smart contracts that algorithmically adjust the interest rates for each asset in real-time, as borrowing demand for the asset changes. Compound supports the borrowing and lending of specific set of crypotocurrencies, including: Dai (DAI), Ether (ETH), USD Coin (USDC), Ox (ZRX), Tether (USDT), Wrapped BTC (WBTC), Token (BAT), Augur (REP), and Sai (SAI). However, Compound has created their own token (COMP) which is a cToken (**technology - cToken**). COMP (CTokens) are created from Ethereum as ERC-20 tokens and are one of the great benefits and innovations of a blockchain-based crypto money market; They can be transferred, traded, or programmed into other Dapps in the DeFi ecosystem similar to other Ethereum tokens, all while earning (or paying) interest. people can transfer cTokens by using theri public and private keys. Each asset supported by the Compound Protocol is integrated through a cToken contract, which is an EIP-20 compliant representation of balances supplied to the protocol. However, people also can purchase COMP coin from crypto market (e.g. Binance) and the exchange rate of COMP coin are link with USDT, BUSD AND BTC. As we know, USDT, BUSD AND BTC are the most popular coin (token) in the market. Therefore, it is easy for people to purchase COMP token. 



#### Clients, Competitor and Future

The people who want to borrow cryptocurrency or stake their cryptocurrency to earn APY (annual percentage yield) can be potential clients of Compound. So far, Compound Finance has more than 8 billion dollars of total supply and 3 billion of total borrow. Compound is one of the biggest DeFi Dapps. Competitors of Compound include Aave, dYdX, MakerDao and Creamfinance. As a lending plattform, credit ranking and high interest rate are the key factors for people choosing them. Moreover, Compound has 83.9k followers and 100 percentage engage on twitter. It is good for the people know what happend in the company. I think one of the weekness of Compound is that they only can stake or borrow 13 types of crypto, and Compound only provieds landing and depositing sevice to customers, it would be limitation the option to clients. Compound's compertior Aave offers 23 types of crypto for borrwoing and depositing.  

For both lenders and borrowers, the main risk with Compound is the potential for hackers to exploit or hack the smart contracts that make Compound work. By doing so, they could steal crypto locked up in Compound's smart contracts. Moreover, Compound offers bug bounties for anyone who discovers vulnerabilities. 



#### Flash Loans in DeFi

In 2020, many losses occured in the DeFi space from flash loan attacks. Lenders on the Compound platform have fallen victim to flash loans exploit, and loss of over **$100 million**. 

Flash Loan is borrowing cryptocurrency without collateral, and the loan needs to be paid back in seconds. The borrower can call (create) a smart contract where multiple transactions can happen in a few seconds. If they can make more money through their loan, then they can return the debt and pocket the keep the profit. However, flash loan attack is the attacker borrowing the cryptocurrency from the loan provider and pushing up the price of the stable coin temporarily to increase its value, at the end they pay back the loan with it.  

The story of Compound flash loan attack is as follows. The attacker borrowed 46 million DAI flash loan from Compound and switched it to cDAI. At that time, 46 million DAI was worth 2.4 billion cDAI. However, because of an oracle (oracle is what reads provides off-chain data for a blockchain) price feed mistake, attacker converted 2.4 billion cDAI and yielded 46.2 million DAI. Then, the attacker payed back 46 million DAI flash loan and was left with 170.9 million cDAI which was worth 3.5 million dollars in profit. Here the oracle was from a well-known central exchange called Coinbase. A mistake in the price feed of this oracle was capitalised by the attacker, and this unreasonable profit.

For this kind of problems, Compound should not only relying on centralised oracles, but also, decentralised ones such as Chainlink.






