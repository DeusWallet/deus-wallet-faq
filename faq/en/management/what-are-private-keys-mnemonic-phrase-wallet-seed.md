# Understanding Private Keys

In the world of cryptocurrency, terms such as private key, mnemonic phrase, secret phrase, and wallet seed are often used interchangeably. These terms all refer to information necessary for controlling funds in non-custodial cryptocurrency wallets, like Deus.

When setting up a non-custodial cryptocurrency wallet, users are provided with a private key. This key is generated during the setup process and, for ease of use, is presented as a series of 12 (or more) plain English words, known in Deus as the secret phrase.

The private key grants users access and ownership over all assets in the wallet. Unlike traditional services that allow password recovery, non-custodial wallets do not offer recovery options for lost private keys. Properly built wallets cannot retrieve these keys once lost.

Private keys are randomly generated on the user's device during wallet creation and never leave the device. If the wallet is deleted, the keys are also deleted, making recovery impossible without access to the device. Therefore, it's crucial for users to back up their private keys during wallet setup. Most wallets prompt users to write down a copy of the private key immediately after creation.

Each Deus multi-coin wallet comes with its own private key, referred to as the secret phrase, presented as 12 plain English words. This key allows users to:

- Restore access to the wallet even if the Deus app is deleted.
- Restore access to the wallet on a different wallet app.

In addition to the secret phrase, Deus provides several other key options:

### EVM Private Key

This key enables importing EVM-based cryptocurrencies (like Ethereum and Binance Smart Chain) from Deus to any compliant wallet app. It should not be shared publicly, as anyone with this key can control EVM-based cryptocurrencies but not Bitcoin or other non-EVM cryptocurrencies in the same wallet.

### BIP32 Root Key

This is another representation of the secret phrase, providing full control over the wallet's assets. It must be kept safe and never shared.

### Account Extended Public Key

This key allows read-only monitoring of Bitcoin and other UTXO-based cryptocurrencies (such as Litecoin and Bitcoin Cash) in the wallet. It is useful for monitoring funds without spending them. For example, you can monitor Bitcoin stored on a Ledger hardware wallet through Deus without compromising security. This key does not provide access to EVM cryptocurrencies.

### Account Extended Private Key

This key allows importing Bitcoin and other UTXO-based cryptocurrencies from Deus to another compliant wallet app. It provides the same ownership capabilities as the Account Extended Public Key but with control over the funds. It should be kept confidential and never shared, as it grants management over Bitcoin and other UTXO-based cryptocurrencies but not EVM cryptocurrencies.

By understanding these keys and their functions, users can ensure their cryptocurrency assets remain secure and accessible.