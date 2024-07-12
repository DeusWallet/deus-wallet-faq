# Comment sont calculés les frais de transaction Bitcoin ?

Les portefeuilles non dépositaires comme Deus estiment les frais de transaction requis pour garantir que la transaction Bitcoin est incluse dans le bloc suivant.

Le paramètre de recommandation de frais pour Bitcoin propose plusieurs niveaux en fonction de l’urgence de la transaction :

- Faible : dans les 400 minutes
- Recommandé : dans les 120 minutes
- Élevé : dans les 30 minutes
- Personnalisé : valeur définie par l'utilisateur

En règle générale, choisissez des frais plus élevés (supérieurs au paramètre « Recommandé ») pour les transactions urgentes ou celles impliquant des montants importants. À l’inverse, la définition de frais très bas (par exemple 0,01 $) peut entraîner l’abandon (le rejet) de la transaction peu de temps après son envoi.

Le paramètre « Personnalisé » permet aux utilisateurs de spécifier leur propre taux de frais de transaction, recommandé pour ceux qui connaissent le mécanisme de frais de Bitcoin.

Notez que le service de recommandation de frais de Deus fait une estimation éclairée basée sur l'analyse de l'activité du réseau. Il n'y a aucune garantie que le paramètre recommandé fonctionnera toujours comme prévu.

De plus, le montant des frais de transaction ne dépend pas du montant de Bitcoin traité.