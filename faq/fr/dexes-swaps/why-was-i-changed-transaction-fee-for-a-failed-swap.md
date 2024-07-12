# Pourquoi des frais de transaction m'ont-ils été facturés pour un swap infructueux ?

Même si une transaction sur la blockchain Ethereum ne termine pas avec succès toutes les étapes prévues, les frais de transaction sont toujours facturés à l'utilisateur par le réseau. En effet, les utilisateurs sont responsables de couvrir les coûts de calcul des transactions réussies et infructueuses.

Plusieurs facteurs peuvent contribuer à l’échec d’une opération de swap :

- **Délai entre la soumission et la confirmation :** Si le temps nécessaire à la confirmation dépasse la période de validité définie par l'utilisateur pour le swap, la transaction échouera. Cela se produit souvent lors d'une congestion du réseau ou lorsque les frais de transaction fixés par l'utilisateur sont insuffisants pour un traitement rapide.

- **Paramètre de glissement de prix faible :** Un utilisateur optant pour un glissement de prix minimal acceptable augmente la probabilité qu'un échange décentralisé (DEX) ne soit pas en mesure d'exécuter le swap dans les paramètres de prix spécifiés.

- **Paramètre de frais de transaction faibles :** Le choix de frais de transaction inférieurs peut entraîner un statut d'attente prolongé au-delà de la période de validité définie pour une transaction.