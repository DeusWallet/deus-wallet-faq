# How to Resend a Failed Bitcoin Transaction

When users send Bitcoin transactions with a very low fee, such transactions are likely to stay pending for a short time and then get rejected by the network as if they never happened.

If users encounter a transaction with a failed (rejected) status in Deus, it is recommended to double-check its status using a public block explorer like [btc.com](https://btc.com) by searching for the transaction ID.

If Deus shows a transaction as failed but a public block explorer shows it as pending or confirmed, the issue likely lies within Deus. In this case, users should not attempt to resend the transaction to avoid double spending. Instead, they should report the issue to Deus wallet support for troubleshooting.

A transaction should be considered failed only if both Deus and the public block explorer show it as failed or rejected.