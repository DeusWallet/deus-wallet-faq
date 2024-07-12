## So verwalten Sie Ethereum-Transaktionen

Sobald eine Ethereum-Transaktion bestätigt und in einen Block auf der Blockchain aufgenommen wurde, wird sie unveränderlich und kann nicht storniert oder geändert werden. Wenn eine Transaktion jedoch noch aussteht und auf eine Bestätigung wartet, gibt es Methoden, sie zu verwalten.

Normalerweise werden Ethereum-Transaktionen schnell bestätigt, normalerweise innerhalb von Sekunden oder Minuten, sodass wenig Spielraum für eine Stornierung bleibt. In Zeiten hoher Netzwerkaktivität können Transaktionen jedoch stunden- oder sogar tagelang in einem ausstehenden Zustand verharren. In solchen Fällen ist es möglich, die ausstehende Transaktion durch eine neue zu ersetzen, bevor sie bestätigt wird.

Um eine ausstehende Transaktion zu stornieren, besteht ein Ansatz darin, eine neue Transaktion mit einer höheren Transaktionsgebühr und derselben Nonce wie die ursprüngliche Transaktion an Ihre eigene Adresse zu senden. Diese Methode kann zwar die ursprüngliche Transaktion stornieren, der Erfolg ist jedoch nicht garantiert und funktioniert möglicherweise nicht konsistent.

Es ist wichtig zu beachten, dass einige Wallet-Apps wie Deus ab Juni 2021 keine Kontrolle über die „Nonce“-Einstellung für Transaktionen bieten und daher die Stornierung ausstehender Transaktionen nicht ermöglichen können. Diese Funktionalität wird jedoch voraussichtlich in zukünftigen Updates integriert.