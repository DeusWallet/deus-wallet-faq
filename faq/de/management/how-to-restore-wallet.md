# So stellen Sie Ihre Wallet(s) wieder her

Mit Deus können Sie ganz einfach jede standardkonforme Wallet wiederherstellen, egal ob sie in Deus oder anderen nicht verwalteten Wallet-Apps erstellt wurde.

So stellen Sie Ihre Wallet wieder her:

1. Gehen Sie zu **Einstellungen** und navigieren Sie zum Abschnitt **Wallets verwalten**.

2. Klicken Sie auf die Schaltfläche **Wiederherstellen**.

3. Geben Sie die mnemonische Phrase für Ihre Wallet ein. Wenn Ihre Wallet eine zusätzliche Passphrase (BIP39) enthält, geben Sie diese ebenfalls ein.

4. Wählen Sie auf dem nächsten Bildschirm die Währungen aus, die Sie für die Wallet aktivieren möchten. Wenn Sie Ethereum oder Binance Smart Chain auswählen, werden auch automatisch alle ERC20/BEP20-Token aktiviert, bei denen Ihre Wallet ein Guthaben hat. Sie müssen alle Blockchains, bei denen Ihre Wallet voraussichtlich ein Guthaben hat, manuell auswählen.

Klicken Sie nach der Auswahl der Währungen auf die Schaltfläche **Wiederherstellen** und warten Sie, bis die Wallet mit den ausgewählten Blockchains synchronisiert ist und vergangene Transaktionen identifiziert.

Die Synchronisierungszeiten für Bitcoin, Bitcoin Cash, Dash, Litecoin und Zcash können je nach Faktoren wie der Internetverbindung zwischen mehreren Minuten und Stunden variieren.

Zusätzliche zu berücksichtigende Punkte:

- Für Bitcoin, Bitcoin Cash und Litecoin müssen Sie den Adresstyp für die ausgewählte Münze angeben. Weitere Informationen finden Sie im Abschnitt Bitcoin weiter unten.
- Für Zcash-Wallets können Sie optional den Parameter „Wallet Birthday Height“ angeben, um die Synchronisierung zu beschleunigen.
- Standardmäßig synchronisiert Deus wiederhergestellte Wallets über einen API-Server eines Drittanbieters, um schnellere Ergebnisse zu erzielen. Dies ist zwar schneller, gilt jedoch als weniger privat. Datenschutzbewusste Benutzer können die Wiederherstellung über Blockchain wählen, was privater ist, aber einige Stunden dauern kann.