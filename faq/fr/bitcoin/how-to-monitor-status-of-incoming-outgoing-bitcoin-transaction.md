# Comment surveiller l'état des transactions Bitcoin entrantes/sortantes

Le portefeuille Deus permet aux utilisateurs de surveiller l'état de leurs transactions :

- Lorsqu'un utilisateur envoie une transaction Bitcoin, celle-ci apparaît avec un statut « en attente » dans l'onglet Transactions pour l'expéditeur et le destinataire. Ce statut reste jusqu'à ce que la transaction soit incluse dans la blockchain.

- Une fois la transaction incluse dans la blockchain, son statut passe à « envoi » pour l'expéditeur et « réception » pour le destinataire. Ce changement indique que la transaction a reçu sa première confirmation.

- Le statut de la transaction reste « envoi » pour l'expéditeur et le destinataire jusqu'à ce qu'au moins trois blocs se soient écoulés, ce qui signifie que la transaction a reçu trois confirmations.

Jusqu'à ce que trois blocs soient écoulés, Deus ne reflétera pas le montant de la transaction dans le solde du destinataire et ne permettra pas au destinataire de dépenser les fonds reçus dans d'autres transactions.

En plus de surveiller l'état des transactions au sein de Deus, les utilisateurs peuvent utiliser des explorateurs de blocs Bitcoin accessibles au public, tels que [btc.com](https://btc.com), pour la surveillance. Pour suivre l'état des transactions en attente sur les ressources externes, les utilisateurs ont besoin de l'ID de transaction, qui peut être trouvé dans Deus.