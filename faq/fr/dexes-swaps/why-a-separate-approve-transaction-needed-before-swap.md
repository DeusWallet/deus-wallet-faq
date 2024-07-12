# Pourquoi une transaction d'approbation distincte est-elle requise avant un échange ?

Avant de vous engager dans des opérations de swap telles que :

- Conversion d'ERC20 en ETH
- Échange d'ERC20 contre un autre ERC20
- Échange de BEP20 contre BNB
- Échange de jetons BEP20

Les utilisateurs doivent effectuer une transaction d’approbation distincte. Ces transactions d'approbation sont généralement économiques et signifient le consentement de l'utilisateur pour que le DEX déduise une quantité spécifiée de jetons ERC20/BEP20 pour l'exécution de la transaction.

Lors d'une transaction d'approbation, les utilisateurs peuvent spécifier le montant du jeton que le DEX est autorisé à déduire. Les utilisateurs ont également la possibilité d'autoriser des montants plus élevés en prévision de transactions futures, éliminant ainsi le besoin de transactions d'approbation ultérieures.

Le fait de ne pas autoriser un montant de jeton suffisant pour une transaction entraînera l'échec de la transaction.