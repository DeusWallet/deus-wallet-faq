# How is the Bitcoin Transaction Fee Calculated?

Non-custodial wallets like Deus estimate the required transaction fee to ensure the Bitcoin transaction is included in the next block.

The fee recommendation setting for Bitcoin offers multiple levels based on the urgency of the transaction:

- Low: within 400 minutes
- Recommended: within 120 minutes
- High: within 30 minutes
- Custom: user-defined value

As a general rule, choose a higher fee (above the 'Recommended' setting) for urgent transactions or those involving large amounts. Conversely, setting a very low fee (e.g., $0.01) may result in the transaction being dropped (rejected) shortly after being sent.

The 'Custom' setting allows users to specify their own transaction fee rate, recommended for those familiar with Bitcoin's fee mechanism.

Note that Deus's fee recommendation service makes an educated guess based on network activity analysis. There is no guarantee that the recommended setting will always work as expected.

Additionally, the transaction fee amount does not depend on the amount of Bitcoin being transacted.