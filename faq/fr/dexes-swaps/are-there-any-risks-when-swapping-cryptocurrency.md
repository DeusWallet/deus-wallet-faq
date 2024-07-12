# Risques associés à l'échange de crypto-monnaie

Bien que le portefeuille Deus simplifie le processus d'échange de crypto-monnaies en gérant les complexités et en configurant automatiquement les paramètres d'échange, il y a plusieurs considérations à garder à l'esprit lorsque vous vous engagez dans des transactions d'échange.

1. Coûts de transaction

Lors de l'échange sur des échanges décentralisés (DEX), les utilisateurs sont tenus de couvrir à la fois les frais de transaction (payés aux mineurs sur la blockchain Ethereum) et les frais d'échange (remis au DEX facilitant la transaction). Ces frais sont versés à différentes entités au sein d’une seule transaction de swap. Les frais de swap varient en fonction de la taille de la commande, tandis que les frais de transaction fluctuent en fonction des conditions du réseau.

En période de congestion, par exemple lorsque la blockchain Ethereum connaît un trafic élevé, les frais de transaction peuvent augmenter considérablement. À l’inverse, l’exécution d’un swap sur la Binance Smart Chain entraîne généralement des coûts inférieurs à ceux d’Ethereum. Quel que soit le DEX utilisé, les frais de swap s'élèvent généralement à environ 0,3 % du montant de la transaction.

De plus, il est essentiel de reconnaître que les DEX sur différentes blockchains fonctionnent avec des ensembles distincts de paires de négociation et de niveaux de liquidité.

2. Délais de transaction

En règle générale, une transaction de swap reste valide pendant environ 20 minutes après sa soumission à la blockchain. Par conséquent, lors de l’utilisation d’un DEX sur une blockchain encombrée comme Ethereum, il est crucial de s’assurer que la transaction de swap inclut des frais de transaction adéquats pour respecter le délai. La soumission d'une transaction de swap avec des frais peu élevés peut entraîner le maintien de la transaction en attente au-delà de la date limite, entraînant l'échec de l'action de swap.

3. Dérapage des prix

Le glissement de prix désigne la variation du prix du jeton entre le placement d'un ordre de swap et la finalisation de la transaction sur la blockchain. Cet écart peut être positif ou négatif, en fonction de la direction du changement de prix. Les fluctuations des conditions du marché au cours de la période entre la soumission de l’ordre et la vérification de la blockchain contribuent au dérapage des prix.

Le portefeuille Deus atténue ce risque en affichant les montants de jetons estimés et garantis que les utilisateurs peuvent attendre de la transaction d'échange. Les utilisateurs peuvent également spécifier des niveaux de glissement acceptables lors de l'envoi de transactions, bien qu'opter pour le glissement le plus faible possible puisse augmenter la probabilité d'échec de la transaction.

4. Tolérance au glissement

La tolérance au glissement fait référence au degré de glissement de prix qu'un utilisateur est prêt à accepter pour une transaction. En définissant une tolérance de glissement, les utilisateurs établissent un seuil minimum pour le nombre de jetons qu'ils accepteront en cas de fluctuation du prix. Cette tolérance est exprimée en pourcentage de la valeur totale du swap.

5. Frais de transaction de swap

Le coût des transactions sur la blockchain Ethereum peut être prohibitif, en particulier pour les petits montants. Bien que l'échange de 10 000 $ de crypto puisse justifier des frais de transaction de 100 $, les mêmes frais pour des montants plus petits, comme 500 $ ou moins, peuvent ne pas être économiquement viables.

6. Opérations d'approbation

Lors de la vente de jetons ERC20 ou BEP20, les utilisateurs doivent d'abord exécuter une transaction d'approbation. Cette transaction autorise le DEX à déduire des jetons du solde de l'utilisateur lors d'une transaction. Sans cette transaction d'approbation, le DEX ne peut pas utiliser les jetons de l'utilisateur pour les transactions.