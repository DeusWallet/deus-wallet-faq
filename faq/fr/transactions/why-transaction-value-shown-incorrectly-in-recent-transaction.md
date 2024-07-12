# Pourquoi la valeur d'une transaction est-elle affichée de manière incorrecte dans une transaction récente ?

Pour afficher avec précision le montant total de crypto-monnaie transféré en monnaie fiduciaire (USD, EUR, etc.) pour les transactions passées, Deus a besoin de connaître le taux de change en vigueur à la date de la transaction.

Actuellement, Deus s'appuie sur [CoinGecko](https://coingecko.com) pour les taux historiques de crypto-monnaie. À l’avenir, nous prévoyons de référencer des sources supplémentaires, notamment des options permettant d’obtenir des taux historiques à partir d’échanges décentralisés de crypto-monnaie.

Si le taux de change historique dans l'application Unstoopable est incorrect, le montant de la transaction affiché dans la liste des transactions sera également incorrect. Dans de tels cas, référez-vous au montant réel transféré en cryptomonnaie.