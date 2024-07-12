# Que signifient BIP44 / BIP49 / BIP84 dans Bitcoin ?

Bitcoin utilise trois formats d'adresse couramment utilisés pour recevoir des paiements. En règle générale, les portefeuilles de crypto-monnaie ne prennent en charge qu’un seul de ces formats, bien que certains puissent gérer plusieurs formats.

Deus, cependant, prend en charge les trois formats d'adresse, permettant aux utilisateurs de conserver des soldes et des transactions Bitcoin distincts pour chaque format au sein d'un seul portefeuille multi-pièces. Cela signifie qu'un portefeuille créé dans Deus peut avoir trois portefeuilles Bitcoin différents fonctionnant comme des crypto-monnaies distinctes aux côtés d'autres crypto-monnaies.

Ces différents formats d'adresse sont apparus à mesure que les transactions Bitcoin augmentaient, avec de nouveaux formats conçus pour réduire la taille des transactions et permettre au réseau de traiter davantage de transactions par bloc.

## Adresses héritées (BIP44)

Le format d'adresse le plus ancien, appelé BIP44, commence généralement par un « 1 ». Comme dans le format d'origine, la plupart des portefeuilles peuvent à la fois envoyer et recevoir des paiements à ces adresses. Cependant, les transactions utilisant des adresses héritées entraînent des frais plus élevés que les autres formats.

## Adresses SegWit (BIP49)

Un format plus récent, BIP49, commence généralement par un « 3 ». De nombreuses applications de portefeuille plus récentes prennent en charge les adresses SegWit, et les transactions provenant de portefeuilles utilisant des adresses SegWit sont moins chères que celles utilisant des adresses héritées.

## Adresses SegWit natives (BIP84)

Le format le plus récent et le plus économique, BIP84, utilise le format d'adresse bech32, qui commence par « bc1 ». Les transactions utilisant des adresses SegWit natives entraînent les frais les plus bas.

Pour identifier le format pris en charge par un portefeuille, vérifiez les premiers caractères de l'adresse de réception dans l'application de portefeuille. Comprendre le format de l'adresse est également important lors de la restauration d'un portefeuille Bitcoin dans certaines applications de portefeuille.

Le portefeuille Deus peut créer et restaurer des portefeuilles fonctionnant dans l'un de ces trois formats d'adresse.