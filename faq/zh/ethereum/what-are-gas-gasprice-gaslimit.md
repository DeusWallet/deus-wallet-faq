# 了解以太坊网络上的 Gas、Gas 价格和 Gas 限制

在浏览以太坊网络时，交易费用以 Ether（ETH 代币）结算，但使用 Gas 单位计算。

虽然理解交易费用对大多数用户来说已经足够了，但深入研究 gas 的概念可以满足一些人的好奇心。

Gas 充当以太坊区块链上操作的燃料，是确定交易费用的计量单位。它取决于两个关键参数：

1) Gas 限制表示用户承诺为验证交易支付的最大 Gas 量（最低 21,000）。通常，对于涉及 ETH 转账的交易，gas 限制设置为 21,000。钱包应用程序通常根据交易复杂性来衡量此限制。不足的 gas 限制通常会导致交易失败，并伴有“gas 不足”错误。

2) Gas 价格表示用户每 gas 单位分配的数量（以 ETH 为单位）。此价格随网络活动而波动；在高峰期，gas 价格会飙升，而在低谷期则会下降。更高的 gas 价格意味着交易在以太坊网络中的重要性增加，因为矿工会获得更大的回报。gas 价格不足通常会导致交易待处理期延长。

Deus 钱包会自动为以太坊网络交易设置 gas 限制和 gas 价格。建议的交易费用是通过将建议的 gas 限制和 gas 价格相乘得出的。

例如，如果 gas 限制为 50,000 个单位，gas 价格为 20 Gwei（以太币的一个子单位），则发送者承诺花费 0.001 ETH 来执行交易。