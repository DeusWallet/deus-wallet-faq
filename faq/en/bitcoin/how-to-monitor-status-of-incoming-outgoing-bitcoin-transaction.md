# How to Monitor the Status of Incoming/Outgoing Bitcoin Transactions

Deus wallet allows users to monitor the status of their transactions:

- When a user sends a Bitcoin transaction, it appears with a 'pending' status in the Transactions tab for both the sender and the recipient. This status remains until the transaction is included in the blockchain.

- Once the transaction is included in the blockchain, its status changes to 'sending' for the sender and 'receiving' for the recipient. This change indicates that the transaction has received its first confirmation.

- The transaction status remains 'sending' for both the sender and the recipient until at least three blocks have passed, meaning the transaction has received three confirmations.

Until three blocks have passed, Deus will not reflect the transaction amount in the recipient's balance or allow the recipient to spend the received funds in other transactions.

In addition to monitoring transaction status within Deus, users can use publicly available Bitcoin block explorers, such as [btc.com](https://btc.com), for monitoring. To track the status of pending transactions on external resources, users need the transaction ID, which can be found in Deus.