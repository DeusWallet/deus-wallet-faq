# Was bedeuten BIP44 / BIP49 / BIP84 in Bitcoin?

Bitcoin verwendet drei häufig verwendete Adressformate zum Empfangen von Zahlungen. Normalerweise unterstützen Kryptowährungs-Wallets nur eines dieser Formate, obwohl einige mehrere Formate verarbeiten können.

Deus unterstützt jedoch alle drei Adressformate, sodass Benutzer separate Bitcoin-Guthaben und -Transaktionen für jedes Format in einem einzigen Multi-Coin-Wallet verwalten können. Dies bedeutet, dass ein in Deus erstelltes Wallet drei verschiedene Bitcoin-Wallets haben kann, die als separate Kryptowährungen neben anderen Kryptowährungen fungieren.

Diese verschiedenen Adressformate entstanden mit der Zunahme der Bitcoin-Transaktionen, wobei neuere Formate darauf ausgelegt sind, die Transaktionsgrößen zu reduzieren und es dem Netzwerk zu ermöglichen, mehr Transaktionen pro Block zu verarbeiten.

## Legacy-Adressen (BIP44)

Das älteste Adressformat, bekannt als BIP44, beginnt normalerweise mit einer „1“. Wie im ursprünglichen Format können die meisten Wallets Zahlungen an diese Adressen senden und empfangen. Transaktionen mit Legacy-Adressen verursachen jedoch im Vergleich zu anderen Formaten höhere Gebühren.

## SegWit-Adressen (BIP49)

Ein neueres Format, BIP49, beginnt normalerweise mit einer „3“. Viele neuere Wallet-Apps unterstützen SegWit-Adressen und Transaktionen von Wallets mit SegWit-Adressen sind günstiger als solche mit Legacy-Adressen.

## Native SegWit-Adressen (BIP84)

Das neueste und kostengünstigste Format, BIP84, verwendet das bech32-Adressformat, das mit „bc1“ beginnt. Transaktionen mit nativen SegWit-Adressen haben die niedrigsten Gebühren.

Um herauszufinden, welches Format eine Wallet unterstützt, überprüfen Sie die ersten paar Zeichen der Empfangsadresse in der Wallet-App. Das Verständnis des Adressformats ist auch wichtig, wenn Sie in einigen Wallet-Apps eine Bitcoin-Wallet wiederherstellen.

Die Deus-Wallet kann Wallets erstellen und wiederherstellen, die in einem dieser drei Adressformate funktionieren.