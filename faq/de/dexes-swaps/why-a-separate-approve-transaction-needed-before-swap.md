# Warum ist vor einem Tausch eine separate Genehmigungstransaktion erforderlich?

Vor der Durchführung von Tauschtransaktionen wie:

- Umwandlung von ERC20 in ETH
- Austausch von ERC20 gegen ein anderes ERC20
- Austausch von BEP20 gegen BNB
- Austausch von BEP20-Token

Benutzer müssen eine separate Genehmigungstransaktion durchführen. Diese Genehmigungstransaktionen sind in der Regel wirtschaftlich und bedeuten die Zustimmung des Benutzers, dass die DEX eine bestimmte Menge an ERC20/BEP20-Token für die Handelsausführung abzieht.

Während einer Genehmigungstransaktion können Benutzer den Tokenbetrag angeben, den die DEX abziehen darf. Benutzer haben auch die Möglichkeit, im Hinblick auf zukünftige Handelsgeschäfte höhere Beträge zu autorisieren, wodurch die Notwendigkeit nachfolgender Genehmigungstransaktionen entfällt.

Wenn für einen Handel kein ausreichender Tokenbetrag autorisiert wird, schlägt die Transaktion fehl.