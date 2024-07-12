# Why was I billed a transaction fee for an unsuccessful swap?

Even if a transaction on the Ethereum blockchain doesn't successfully complete all its intended steps, the user is still charged the transaction fee by the network. This is because users are responsible for covering the computational costs of both successful and unsuccessful transactions.

Several factors can contribute to the failure of a swap transaction:

- **Timing between submission and confirmation:** If the time taken for confirmation exceeds the user-defined validity period for the swap, the transaction will fail. This often occurs during network congestion or when the transaction fee set by the user is insufficient for timely processing.

- **Low price slippage setting:** A user opting for a minimal acceptable price slippage increases the likelihood of a decentralized exchange (DEX) being unable to execute the swap within specified price parameters.

- **Low transaction fee setting:** Choosing a lower transaction fee can lead to prolonged pending status beyond the validity period set for a trade.