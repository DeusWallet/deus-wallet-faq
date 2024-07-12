# Why is a separate Approval transaction required prior to a swap?

Before engaging in any swap transactions such as:

- Converting ERC20 to ETH
- Exchanging ERC20 for another ERC20
- Swapping BEP20 for BNB
- Interchanging BEP20 tokens

Users are required to conduct a separate Approval transaction. These Approval transactions are typically economical and signify the user's consent for the DEX to deduct a specified quantity of ERC20/BEP20 tokens for trade execution.

During an Approval transaction, users can specify the token amount the DEX is permitted to deduct. Users also have the option to authorize higher amounts in anticipation of future trades, thus eliminating the need for subsequent Approval transactions.

Failure to authorize a sufficient token amount for a trade will result in transaction failure.