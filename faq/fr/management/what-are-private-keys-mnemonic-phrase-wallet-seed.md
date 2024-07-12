# Comprendre les clés privées

Dans le monde de la crypto-monnaie, des termes tels que clé privée, phrase mnémonique, phrase secrète et graine de portefeuille sont souvent utilisés de manière interchangeable. Ces termes font tous référence aux informations nécessaires au contrôle des fonds dans des portefeuilles de crypto-monnaie non dépositaires, comme Deus.

Lors de la configuration d’un portefeuille de crypto-monnaie non dépositaire, les utilisateurs reçoivent une clé privée. Cette clé est générée pendant le processus de configuration et, pour faciliter son utilisation, est présentée sous la forme d'une série de 12 (ou plus) mots anglais simples, connus dans Deus sous le nom de phrase secrète.

La clé privée accorde aux utilisateurs l'accès et la propriété de tous les actifs du portefeuille. Contrairement aux services traditionnels qui permettent la récupération de mots de passe, les portefeuilles non dépositaires n'offrent pas d'options de récupération des clés privées perdues. Les portefeuilles correctement construits ne peuvent pas récupérer ces clés une fois perdues.

Les clés privées sont générées aléatoirement sur l'appareil de l'utilisateur lors de la création du portefeuille et ne quittent jamais l'appareil. Si le portefeuille est supprimé, les clés sont également supprimées, rendant la récupération impossible sans accès à l'appareil. Par conséquent, il est crucial que les utilisateurs sauvegardent leurs clés privées lors de la configuration du portefeuille. La plupart des portefeuilles invitent les utilisateurs à noter une copie de la clé privée immédiatement après sa création.

Chaque portefeuille multi-pièces Deus est livré avec sa propre clé privée, appelée phrase secrète, présentée sous forme de 12 mots anglais simples. Cette clé permet aux utilisateurs de :

- Restaurez l'accès au portefeuille même si l'application Deus est supprimée.
- Restaurez l'accès au portefeuille sur une autre application de portefeuille.

En plus de la phrase secrète, Deus propose plusieurs autres options clés :

### Clé privée EVM

Cette clé permet d'importer des crypto-monnaies basées sur EVM (comme Ethereum et Binance Smart Chain) depuis Deus vers n'importe quelle application de portefeuille conforme. Elle ne doit pas être partagée publiquement, car toute personne possédant cette clé peut contrôler les crypto-monnaies basées sur EVM, mais pas Bitcoin ou d'autres crypto-monnaies non EVM dans le même portefeuille.

### Clé racine BIP32

Il s'agit d'une autre représentation de la phrase secrète, offrant un contrôle total sur les actifs du portefeuille. Il doit être conservé en sécurité et jamais partagé.

### Clé publique étendue du compte

Cette clé permet la surveillance en lecture seule du Bitcoin et d'autres crypto-monnaies basées sur UTXO (telles que Litecoin et Bitcoin Cash) dans le portefeuille. C’est utile pour surveiller les fonds sans les dépenser. Par exemple, vous pouvez surveiller les Bitcoins stockés sur un portefeuille matériel Ledger via Deus sans compromettre la sécurité. Cette clé ne donne pas accès aux cryptomonnaies EVM.

### Clé privée étendue du compte

Cette clé permet d'importer du Bitcoin et d'autres crypto-monnaies basées sur UTXO depuis Deus vers une autre application de portefeuille conforme. Il offre les mêmes capacités de propriété que la clé publique étendue du compte, mais avec un contrôle sur les fonds. Il doit rester confidentiel et ne jamais être partagé, car il permet de gérer Bitcoin et d'autres crypto-monnaies basées sur UTXO, mais pas les crypto-monnaies EVM.

En comprenant ces clés et leurs fonctions, les utilisateurs peuvent garantir que leurs actifs de crypto-monnaie restent sécurisés et accessibles.