# 比特币中的 BIP44 / BIP49 / BIP84 是什么意思？

比特币使用三种常用的地址格式来接收付款。通常，加密货币钱包仅支持其中一种格式，但有些可以处理多种格式。

但是，Deus 支持所有三种地址格式，允许用户在单个多币钱包中为每种格式维护单独的比特币余额和交易。这意味着在 Deus 中创建的钱包可以有三个不同的比特币钱包，与其他加密货币一起作为单独的加密货币运行。

随着比特币交易的增加，这些不同的地址格式应运而生，新格式旨在减少交易规模并使网络能够处理每个区块的更多交易。

## 旧地址 (BIP44)

最古老的地址格式称为 BIP44，通常以“1”开头。作为原始格式，大多数钱包都可以向这些地址发送和接收付款。但是，与其他格式相比，使用旧地址的交易会产生更高的费用。

## SegWit 地址 (BIP49)

BIP49 是一种较新的格式，通常以“3”开头。许多较新的钱包应用程序都支持 SegWit 地址，使用 SegWit 地址的钱包交易比使用传统地址的交易更便宜。

## 原生 SegWit 地址 (BIP84)

最新且最具成本效益的格式 BIP84 使用 bech32 地址格式，以“bc1”开头。使用原生 SegWit 地址的交易费用最低。

要确定钱包支持哪种格式，请检查钱包应用程序中接收地址的前几个字符。在某些钱包应用程序中恢复比特币钱包时，了解地址格式也很重要。

Deus 钱包可以创建和恢复以这三种地址格式中的任何一种运行的钱包。