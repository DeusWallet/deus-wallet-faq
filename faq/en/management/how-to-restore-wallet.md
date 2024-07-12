# How to Restore Your Wallet(s)

Deus makes it simple to restore any standard-compliant wallet, whether created in Deus or other non-custodial wallet apps.

To restore your wallet:

1. Go to the **Settings** and navigate to the **Manage Wallets** section.
2. Click on the **Restore** button.
3. Enter the mnemonic phrase for your wallet. If your wallet includes an additional passphrase (BIP39), provide that as well.
4. On the next screen, select the currencies you want to activate for the wallet. Choosing Ethereum or Binance Smart Chain will also automatically activate all ERC20/BEP20 tokens where your wallet has a balance. You need to manually select all blockchains where your wallet is expected to have a balance.

After selecting currencies, click the **Restore** button and wait for the wallet to synchronize with the selected blockchains and identify past transactions.

Synchronization times for Bitcoin, Bitcoin Cash, Dash, Litecoin, and Zcash can vary from several minutes to hours, depending on factors like internet connection.

Additional points to consider:

- For Bitcoin, Bitcoin Cash, and Litecoin, you must specify the address type for the selected coin. More information is available in the Bitcoin section below.
- For Zcash wallets, you can optionally specify the wallet birthday height parameter to speed up synchronization.
- By default, Deus synchronizes restored wallets via a third-party API server for faster results. While this is quicker, it is considered less private. Privacy-sensitive users can choose to restore via Blockchain, which is more private but may take a few hours.