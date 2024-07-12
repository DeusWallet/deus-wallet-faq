# What do BIP44 / BIP49 / BIP84 Mean in Bitcoin?

Bitcoin utilizes three commonly-used address formats for receiving payments. Typically, cryptocurrency wallets support only one of these formats, though some can handle multiple formats.

Deus, however, supports all three address formats, allowing users to maintain separate Bitcoin balances and transactions for each format within a single multi-coin wallet. This means a wallet created in Deus can have three different Bitcoin wallets functioning as separate cryptocurrencies alongside other cryptocurrencies.

These various address formats emerged as Bitcoin transactions increased, with newer formats designed to reduce transaction sizes and enable the network to process more transactions per block.

## Legacy Addresses (BIP44)

The oldest address format, known as BIP44, typically starts with a "1". As the original format, most wallets can both send and receive payments to these addresses. However, transactions using Legacy Addresses incur higher fees compared to other formats.

## SegWit Addresses (BIP49)

A newer format, BIP49, typically starts with a "3". Many newer wallet apps support SegWit addresses, and transactions from wallets using SegWit addresses are cheaper than those using Legacy Addresses.

## Native SegWit Addresses (BIP84)

The most recent and cost-effective format, BIP84, uses the bech32 address format, which starts with "bc1". Transactions using Native SegWit Addresses have the lowest fees.

To identify which format a wallet supports, check the first few characters of the receiving address in the wallet app. Understanding the address format is also important when restoring a Bitcoin wallet in some wallet apps.

The Deus wallet can create and restore wallets operating in any of these three address formats.