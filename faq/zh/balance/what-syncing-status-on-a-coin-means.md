### 硬币上的“同步”状态是什么意思？

硬币上的“同步”状态表示 Deus 应用程序正在尝试与相应的区块链同步。

虽然“同步”通常会短暂出现，但在几种情况下可能需要更长的时间：

- **初始同步**：当使用比特币、比特币现金、达世币、莱特币或 Zcash 恢复钱包时，如果钱包是从区块链而不是第三方 API 服务恢复的，则每个硬币的同步可能需要几个小时。恢复的硬币越多，该过程所需的时间越长。

- **首次激活**：在设置钱包后首次激活比特币、比特币现金、达世币、莱特币或 Zcash 也会导致同步时间延长。

- **不频繁使用应用程序**：在几天或几周不活动后打开钱包应用程序可能会触发更长的同步过程。

- **网络条件差**：网速慢或网络连接不稳定会延长同步时间。

- **RPC 响应时间慢**：以太坊和币安智能链 RPC 提供商的延迟或响应缓慢会导致同步时间延长。在这种情况下，建议等待几分钟或重新启动钱包应用程序。

请记住，Deus 应用程序仅在打开时同步。如果应用程序关闭，同步将暂停并在重新打开应用程序时恢复。