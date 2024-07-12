# Risiken im Zusammenhang mit dem Tausch von Kryptowährungen

Obwohl Deus Wallet den Prozess des Tauschens von Kryptowährungen vereinfacht, indem es Komplexitäten bewältigt und Swap-Einstellungen automatisch konfiguriert, gibt es bei Swap-Transaktionen mehrere Überlegungen zu beachten.

1. Transaktionskosten

Beim Tauschen auf dezentralen Börsen (DEXes) müssen Benutzer sowohl die Transaktionsgebühr (die an Miner auf der Ethereum-Blockchain gezahlt wird) als auch eine Swap-Gebühr (die an die DEX überwiesen wird, die die Transaktion ermöglicht) zahlen. Diese Gebühren werden innerhalb einer einzigen Swap-Transaktion an verschiedene Einheiten ausgezahlt. Die Swap-Gebühr variiert je nach Auftragsgröße, während die Transaktionsgebühr je nach Netzwerkbedingungen schwankt.

In Zeiten der Überlastung, beispielsweise wenn die Ethereum-Blockchain viel Verkehr aufweist, können die Transaktionsgebühren erheblich ansteigen. Umgekehrt verursacht die Ausführung eines Swaps auf der Binance Smart Chain im Vergleich zu Ethereum in der Regel geringere Kosten. Unabhängig von der verwendeten DEX betragen die Swap-Gebühren im Allgemeinen etwa 0,3 % des Transaktionsbetrags.

Darüber hinaus ist es wichtig zu erkennen, dass DEXes auf verschiedenen Blockchains mit unterschiedlichen Handelspaaren und Liquiditätsniveaus arbeiten.

2. Transaktionsfristen

Normalerweise bleibt eine Swap-Transaktion nach der Übermittlung an die Blockchain etwa 20 Minuten lang gültig. Wenn Sie daher einen DEX auf einer überlasteten Blockchain wie Ethereum verwenden, ist es entscheidend, sicherzustellen, dass die Swap-Transaktion eine angemessene Transaktionsgebühr enthält, um die Frist einzuhalten. Das Einreichen einer Swap-Transaktion mit einer niedrigen Gebühr kann dazu führen, dass die Transaktion über die Frist hinaus in einem ausstehenden Zustand verharrt, was zu einer fehlgeschlagenen Swap-Aktion führt.

3. Preisrutsch

Preisrutsch bezeichnet die Abweichung des Token-Preises zwischen der Platzierung einer Swap-Order und dem Abschluss der Transaktion auf der Blockchain. Diese Abweichung kann positiv oder negativ sein, abhängig von der Richtung der Preisänderung. Schwankungen der Marktbedingungen während des Zeitraums zwischen Auftragserteilung und Blockchain-Verifizierung tragen zur Preisrutsche bei.

Deus Wallet mindert dieses Risiko, indem es die geschätzten und garantierten Token-Beträge anzeigt, die Benutzer von der Swap-Transaktion erwarten können. Benutzer können beim Senden von Transaktionen auch akzeptable Slippage-Level angeben, obwohl die Wahl der geringstmöglichen Slippage die Wahrscheinlichkeit eines Transaktionsfehlers erhöhen kann.

4. Slippage-Toleranz

Slippage-Toleranz bezieht sich auf den Grad der Preisabweichung, den ein Benutzer für einen Handel zu akzeptieren bereit ist. Durch die Festlegung einer Slippage-Toleranz legen Benutzer einen Mindestschwellenwert für die Anzahl der Token fest, die sie akzeptieren, sollte der Preis schwanken. Diese Toleranz wird als Prozentsatz des gesamten Swap-Werts ausgedrückt.

5. Swap-Transaktionsgebühren

Die Kosten für Transaktionen auf der Ethereum-Blockchain können unerschwinglich hoch sein, insbesondere bei kleineren Beträgen. Während der Tausch von Kryptowährungen im Wert von 10.000 USD eine Transaktionsgebühr von 100 USD rechtfertigen kann, ist dieselbe Gebühr für kleinere Beträge, z. B. 500 USD oder weniger, möglicherweise nicht wirtschaftlich.

6. Genehmigungstransaktionen

Beim Verkauf von ERC20- oder BEP20-Token müssen Benutzer zunächst eine Genehmigungstransaktion ausführen. Diese Transaktion autorisiert die DEX, während eines Handels Token vom Guthaben des Benutzers abzuziehen. Ohne diese Genehmigungstransaktion kann die DEX die Token des Benutzers nicht für den Handel verwenden.