# Gas, Gaspreis und Gaslimit im Ethereum-Netzwerk verstehen

Beim Navigieren im Ethereum-Netzwerk werden Transaktionsgebühren in Ether (ETH-Token) abgerechnet, aber mit Gaseinheiten berechnet.

Während es für die meisten Benutzer ausreicht, Transaktionsgebühren zu verstehen, kann die Vertiefung in das Konzept von Gas die Neugier mancher Benutzer stillen.

Gas fungiert als Treibstoff für Aktionen in der Ethereum-Blockchain und dient als Maßeinheit zur Bestimmung von Transaktionsgebühren. Es hängt von zwei zentralen Parametern ab:

1) Das Gaslimit bezeichnet die maximale Menge an Gas, die ein Benutzer für die Verifizierung einer Transaktion zu zahlen bereit ist (mindestens 21.000). Normalerweise wird das Gaslimit für Transaktionen mit ETH-Überweisungen auf 21.000 festgelegt. Wallet-Anwendungen messen dieses Limit oft anhand der Transaktionskomplexität. Unzureichende Gaslimits führen oft zu Transaktionsfehlern, begleitet von einem „Gas-fehlgeschlagen“-Fehler.

2) Der Gaspreis bezeichnet die Menge (in ETH), die ein Benutzer pro Gaseinheit zuweist. Dieser Preis schwankt mit der Netzwerkaktivität; Während Spitzenzeiten steigen die Gaspreise, während sie während Flauten sinken. Höhere Gaspreise bedeuten eine erhöhte Bedeutung der Transaktion innerhalb des Ethereum-Netzwerks, da die Miner höhere Belohnungen erhalten. Unzureichende Gaspreise führen häufig zu längeren Wartezeiten für Transaktionen.

Die Deus-Wallet legt automatisch sowohl das Gaslimit als auch den Gaspreis für Ethereum-Netzwerktransaktionen fest. Die empfohlene Transaktionsgebühr ergibt sich aus der Multiplikation des empfohlenen Gaslimits und des Gaspreises.

Bei einem Gaslimit von 50.000 Einheiten und einem Gaspreis von 20 Gwei (einer Untereinheit von Ether) verpflichtet sich der Absender beispielsweise, 0,001 ETH für die Transaktionsausführung auszugeben.