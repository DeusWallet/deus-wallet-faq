# Risks Associated with Cryptocurrency Swapping

While Deus wallet simplifies the process of swapping cryptocurrencies by handling complexities and configuring swap settings automatically, there are several considerations to bear in mind when engaging in swap transactions.

1. Transaction Costs

When swapping on decentralized exchanges (DEXes), users are obliged to cover both the transaction fee (paid to miners on the Ethereum blockchain) and a swap fee (remitted to the DEX facilitating the transaction). These fees are disbursed to different entities within a single swap transaction. The swap fee varies depending on the order size, while the transaction fee fluctuates according to network conditions.

During times of congestion, such as when the Ethereum blockchain experiences high traffic, transaction fees can escalate significantly. Conversely, executing a swap on the Binance Smart Chain typically incurs lower costs compared to Ethereum. Regardless of the DEX used, swap fees are generally around 0.3% of the transaction amount.

Additionally, it's essential to recognize that DEXes on different blockchains operate with distinct sets of trading pairs and liquidity levels.

2. Transaction Deadlines

Typically, a swap transaction remains valid for approximately 20 minutes post-submission to the blockchain. Therefore, when utilizing a DEX on a congested blockchain like Ethereum, ensuring that the swap transaction includes an adequate transaction fee to meet the deadline is crucial. Submitting a swap transaction with a low fee may result in the transaction lingering in a pending state beyond the deadline, leading to a failed swap action.

3. Price Slippage

Price slippage denotes the variance in token price between the placement of a swap order and the completion of the transaction on the blockchain. This variance can be positive or negative, contingent upon the direction of the price change. Fluctuations in market conditions during the period between order submission and blockchain verification contribute to price slippage.

Deus wallet mitigates this risk by displaying the estimated and guaranteed token amounts users can expect from the swap transaction. Users can also specify acceptable slippage levels when sending transactions, although opting for the lowest possible slippage may increase the likelihood of transaction failure.

4. Slippage Tolerance

Slippage tolerance refers to the degree of price slippage a user is willing to accept for a trade. By setting a slippage tolerance, users establish a minimum threshold for the number of tokens they will accept, should the price fluctuate. This tolerance is expressed as a percentage of the total swap value.

5. Swap Transaction Fees

The cost of transacting on the Ethereum blockchain can be prohibitively high, particularly for smaller amounts. While swapping $10,000 worth of crypto may justify a $100 transaction fee, the same fee for smaller amounts, such as $500 or less, may not be economically viable.

6. Approval Transactions

When selling ERC20 or BEP20 tokens, users must first execute an Approval Transaction. This transaction authorizes the DEX to deduct tokens from the user's balance during a trade. Without this approval transaction, the DEX cannot utilize the user's tokens for trades.