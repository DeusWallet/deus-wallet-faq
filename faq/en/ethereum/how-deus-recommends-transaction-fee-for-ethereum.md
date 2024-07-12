# Optimizing Transaction Fees on Ethereum with Deus

Deus offers a streamlined approach to recommending transaction fees for Ethereum, catering to both time-sensitive transactions and user preferences. Here's how it works:

## Fee Options

1. **Recommended:** Ideal for transactions requiring swift processing (0-20 minutes).
2. **Custom:** Allows users to manually set their preferred fee amount.

## Choosing the Right Fee

When selecting a fee, it's advisable to opt for a higher amount in scenarios of urgency or when dealing with significant transaction sums. Here's a breakdown:

- **Trading Cryptocurrencies:** Transactions involving smart contracts, especially those with time-sensitive trades, benefit from prompt confirmation to avoid trade failures.
  
## Fee Adjustment Guidelines

Deus derives its 'recommended' fee from Ethereum's blockchain, factoring in network congestion. To enhance transaction reliability, Deus suggests increasing the fee based on the transaction value:

- For transactions ≤ $500: Add 5% above the network's recommended fee.
- For transactions ≤ $1,000: Add 10%.
- For transactions > $1,000 and ≤ $5,000: Add 15%.
- For transactions > $5,000 and ≤ $10,000: Add 20%.
- For transactions > $10,000: Add 25%.

## Best Practices

To mitigate the risk of transaction failure or delays, especially for high-value transactions, it's prudent to consider at least the fee value recommended by Deus. Doing so not only expedites transaction confirmation but also minimizes potential issues during network congestion.

By adhering to these guidelines, users can optimize their Ethereum transactions for efficiency and reliability, ensuring seamless execution even in demanding scenarios.