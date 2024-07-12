# How Can You Send Bitcoin Transactions That Can't Be Spent Until a Certain Date?

Deus Wallet offers the capability to send Bitcoin transactions that are locked until a specific future date. While this functionality is inherent to the Bitcoin blockchain, it is rarely implemented by wallet applications.

As an experimental feature, it is not enabled by default. Users must manually activate it by navigating to Settings >> Experimental Features.

Once the transaction is confirmed on the blockchain, the recipient becomes the owner of the funds. However, they cannot spend the funds until the specified time has passed. In the Deus Wallet application, a lock icon is displayed next to the balance amount originating from such transactions.

To receive these transactions, the recipient must be using Deus Wallet version 0.10 or higher and utilize the BIP44 address format for Bitcoin. Other wallets may not recognize these transactions on the network and may not display them at all.