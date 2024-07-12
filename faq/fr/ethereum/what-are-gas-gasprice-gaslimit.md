# Comprendre le gaz, le prix du gaz et la limite de gaz sur le réseau Ethereum

Lors de la navigation sur le réseau Ethereum, les frais de transaction sont réglés en Ether (jetons ETH) mais sont calculés en unités Gas.

Bien que comprendre les frais de transaction soit suffisant pour la plupart des utilisateurs, se plonger dans le concept du gaz peut assouvir la curiosité de certains.

Le gaz agit comme le carburant des actions sur la blockchain Ethereum, servant d’unité de mesure pour déterminer les frais de transaction. Elle s’articule autour de deux paramètres essentiels :

1) La limite de gaz désigne la quantité maximale de gaz qu'un utilisateur s'engage à payer pour vérifier une transaction (minimum de 21 000). Généralement, pour les transactions impliquant des transferts d'ETH, la limite de gaz est fixée à 21 000. Les applications de portefeuille évaluent souvent cette limite en fonction de la complexité des transactions. Des limites de gaz inadéquates entraînent souvent des échecs de transaction, accompagnés d'une erreur de « panne de gaz ».

2) Le prix du gaz désigne la quantité (en ETH) qu'un utilisateur alloue par unité de gaz. Ce prix fluctue en fonction de l'activité du réseau ; pendant les périodes de pointe, les prix du gaz augmentent, alors qu’ils diminuent pendant les périodes d’accalmie. Des prix du gaz plus élevés impliquent une importance accrue de la transaction au sein du réseau Ethereum, car les mineurs reçoivent de plus grandes récompenses. Des prix du gaz inadéquats entraînent souvent des périodes d’attente prolongées pour les transactions.

Le portefeuille Deus définit automatiquement la limite de gaz et le prix du gaz pour les transactions sur le réseau Ethereum. Les frais de transaction suggérés sont calculés en multipliant la limite de gaz recommandée et le prix du gaz.

Par exemple, avec une limite de gaz de 50 000 unités et un prix du gaz de 20 Gwei (une sous-unité d'Ether), l'expéditeur s'engage à dépenser 0,001 ETH pour l'exécution de la transaction.