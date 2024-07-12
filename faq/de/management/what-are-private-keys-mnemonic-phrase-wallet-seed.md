# Private Schlüssel verstehen

In der Welt der Kryptowährungen werden Begriffe wie privater Schlüssel, mnemonische Phrase, geheime Phrase und Wallet Seed oft synonym verwendet. Diese Begriffe beziehen sich alle auf Informationen, die für die Kontrolle von Geldern in nicht verwahrten Kryptowährungs-Wallets wie Deus erforderlich sind.

Beim Einrichten eines nicht verwahrten Kryptowährungs-Wallets erhalten Benutzer einen privaten Schlüssel. Dieser Schlüssel wird während des Einrichtungsvorgangs generiert und besteht zur Vereinfachung aus einer Reihe von 12 (oder mehr) einfachen englischen Wörtern, die in Deus als geheime Phrase bezeichnet werden.

Der private Schlüssel gewährt Benutzern Zugriff und Eigentum an allen Vermögenswerten im Wallet. Im Gegensatz zu herkömmlichen Diensten, die eine Kennwortwiederherstellung ermöglichen, bieten nicht verwahrte Wallets keine Wiederherstellungsoptionen für verlorene private Schlüssel. Richtig erstellte Wallets können diese Schlüssel nach dem Verlust nicht wiederherstellen.

Private Schlüssel werden während der Wallet-Erstellung zufällig auf dem Gerät des Benutzers generiert und verlassen das Gerät nie. Wenn das Wallet gelöscht wird, werden auch die Schlüssel gelöscht, wodurch eine Wiederherstellung ohne Zugriff auf das Gerät unmöglich wird. Daher ist es für Benutzer von entscheidender Bedeutung, ihre privaten Schlüssel während der Wallet-Einrichtung zu sichern. Die meisten Wallets fordern die Benutzer auf, unmittelbar nach der Erstellung eine Kopie des privaten Schlüssels aufzuschreiben.

Jedes Deus-Multi-Coin-Wallet verfügt über einen eigenen privaten Schlüssel, die sogenannte Geheimphrase, die aus 12 einfachen englischen Wörtern besteht. Mit diesem Schlüssel können Benutzer:

- Den Zugriff auf das Wallet wiederherstellen, auch wenn die Deus-App gelöscht wird.

- Den Zugriff auf das Wallet über eine andere Wallet-App wiederherstellen.

Neben der Geheimphrase bietet Deus mehrere andere Schlüsseloptionen:

### EVM-Privatschlüssel

Dieser Schlüssel ermöglicht das Importieren von EVM-basierten Kryptowährungen (wie Ethereum und Binance Smart Chain) von Deus in jede kompatible Wallet-App. Er sollte nicht öffentlich geteilt werden, da jeder mit diesem Schlüssel EVM-basierte Kryptowährungen, aber nicht Bitcoin oder andere nicht-EVM-Kryptowährungen im selben Wallet kontrollieren kann.

### BIP32-Root-Schlüssel

Dies ist eine weitere Darstellung der Geheimphrase, die volle Kontrolle über die Vermögenswerte des Wallets bietet. Er muss sicher aufbewahrt und darf niemals geteilt werden.

### Erweiterter öffentlicher Kontoschlüssel

Dieser Schlüssel ermöglicht die schreibgeschützte Überwachung von Bitcoin und anderen UTXO-basierten Kryptowährungen (wie Litecoin und Bitcoin Cash) in der Wallet. Er ist nützlich, um Gelder zu überwachen, ohne sie auszugeben. Sie können beispielsweise Bitcoin, das in einer Ledger-Hardware-Wallet gespeichert ist, über Deus überwachen, ohne die Sicherheit zu gefährden. Dieser Schlüssel bietet keinen Zugriff auf EVM-Kryptowährungen.

### Erweiterter privater Kontoschlüssel

Dieser Schlüssel ermöglicht den Import von Bitcoin und anderen UTXO-basierten Kryptowährungen von Deus in eine andere kompatible Wallet-App. Er bietet dieselben Eigentumsrechte wie der erweiterte öffentliche Kontoschlüssel, jedoch mit Kontrolle über die Gelder. Er sollte vertraulich behandelt und niemals weitergegeben werden, da er die Verwaltung von Bitcoin und anderen UTXO-basierten Kryptowährungen, jedoch nicht von EVM-Kryptowährungen ermöglicht.

Indem Benutzer diese Schlüssel und ihre Funktionen verstehen, können sie sicherstellen, dass ihre Kryptowährungsanlagen sicher und zugänglich bleiben.