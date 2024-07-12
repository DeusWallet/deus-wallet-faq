# Understanding Gas, Gas Price, and Gas Limit on the Ethereum Network

When navigating the Ethereum network, transaction fees are settled in Ether (ETH tokens) but are computed using Gas units.

While comprehending transaction fees suffices for most users, delving into the concept of gas can satiate the curiosity of some.

Gas acts as the fuel powering actions on the Ethereum blockchain, serving as the unit of measurement for determining transaction fees. It hinges on two pivotal parameters:

1) Gas Limit denotes the utmost amount of Gas a user commits to pay for verifying a transaction (minimum of 21,000). Typically, for transactions involving ETH transfers, the gas limit is set at 21,000. Wallet applications often gauge this limit based on transaction complexity. Inadequate gas limits often result in transaction failures, accompanied by an 'out of gas' error.

2) Gas Price signifies the quantity (in ETH) a user allocates per gas unit. This price fluctuates with network activity; during peaks, gas prices surge, whereas they dwindle during lulls. Higher gas prices imply increased importance of the transaction within the Ethereum network, as miners receive greater rewards. Inadequate gas prices frequently lead to prolonged transaction pending periods.

Deus wallet automatically sets both gas limit and gas price for Ethereum network transactions. The suggested transaction fee is derived by multiplying the recommended gas limit and gas price.

For instance, with a gas limit of 50,000 units and a gas price of 20 Gwei (a subunit of Ether), the sender commits to spending 0.001 ETH for transaction execution.