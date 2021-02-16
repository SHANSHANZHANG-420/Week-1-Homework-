# Week-1-Homework-
## Compound (Company) Case Study (Blockchain and Cryptocurrencies)

### Overview 

Compound was founded in 2017 and is headquartered in San Francisco, California. Geoffrey Hayes and Robert Leshner are the founders of the company. Compound is an open-source decentralised protocol that unlocks new financial applications for developers. In simple terms, Compound is a lending platform in the cryptocurrency market where people can use their crypto assets as collateral to take loan or lend assets to another people and gain a decent annal interest on their assets.  

Compound has raised two rounds of funding. The first round raised $8.2M from seed funding on 16 May 2018. Their latest funding  raised $25M on Nov 14, 2019 from series A funding (early-Stage Venture). Therefore, Compound has raised $33.2M fund in total. Moreover, Compound is funded by 11 investors among which Andreessen Horowitz and Bain Capital Ventures are the most recent investors. According to PriveCo, Compound has a post-money valuation in the range of $100M to $500M as of Nov 14, 2019. 


### Business Activities 

Basically, Compound’s protocol is a series of open-source smart contracts that algorithmically adjust the interest rates for each asset in real-time, as borrowing demand for the asset changes. Compound supports the borrowing and lending of specific set of crypotocurrencies, including: Dai (DAI), Ether (ETH), USD Coin (USDC), Ox (ZRX), Tether (USDT), Wrapped BTC (WBTC), Token (BAT), Augur (REP), and Sai (SAI). However, Compound has created their own token (COMP) which is a cToken (**technology - cToken**). CTokens are created from Ethereum as ERC-20 tokens and are one of the great benefits and innovations of a blockchain-based crypto money market; They can be transferred, traded, or programmed into other Dapps in the DeFi ecosystem similar to other Ethereum tokens, all while earning (or paying) interest. people can transfer cTokens by using theri public and private keys. Each asset supported by the Compound Protocol is integrated through a cToken contract, which is an EIP-20 compliant representation of balances supplied to the protocol. 



#### Clients and Competitor

The people who want to borrow cryptocurrency or stake their cryptocurrency to earn APY (annual percentage yield) can be potential clients of Compound. So far, Compound Finance has more than 8 billion dollars of total supply and 3 billion of total borrow. Competitors of Compound include Aave, dYdX, MakerDao and Creamfinance. As a lending plattform, credit ranking and high interest rate are the key factors for people choosing them. Also, Compound has 83.9k followers and 100 percentage engage on twitter. It is good for the people know what happend in the company. I think one of the weekness of Compound is that they only can stake or borrow 13 types of crypto, it would be limitation the option of clients. 


#### Flash Loans in DeFi

In 2020, many losses occured in the DeFi space from flash loan attacks. Lenders on DeFi protocol Compound (company) has fallen victim to flash loans exploit, and the tune of over **$100 million**. 

Flash Loan is borrowing cryptocurrency to borrower without collateral, and the loan needs to be paid back in seconds. The borrower can call (create) smart contracts in that same transaction. If they can make more money through their loan, then they can return the money and pocket the profits in few seconds. However, flash loan attack is the attacker borrowing the cryptocurrency from the loan provider and pushing up the price of the stable coin temporarily to double its value, at the end they pay back the loan with it. Therefore, flash loan attack usually is the attacker stole money from a flash loan provider. 

The story of Compound flash loan attack is another suitation. the attacker borrows 46 million DAI flash loan from Compound and switch it to cDAI. At that time, 46 million DAI is equal 2.4 billion cDAI. However, because of Oracle price fill mistake, attacker converted 2.4 billion cDAI  yielded 46.2 million DAI. Moreover, the attacker payed back 46 million DAI flash loan and left with 170.9 million cDAI which worth 3.5 million dollars profits. In here we can see Compound did not actually lose money from this flash loan trade. But, that flash loan trade leads to price of cDAI price increase, and some of the collateal become their assets ..... 

For this kind of problems, Compound should not only relying on on-chain centralized price oracles, they should look at the price off-chain likes the price in decentralized platform e.g. Chainlink. 






