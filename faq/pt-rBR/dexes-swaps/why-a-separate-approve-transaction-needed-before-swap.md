# Por que é necessária uma transação de aprovação separada antes de uma troca?

Antes de se envolver em qualquer transação de swap, como:

- Conversão de ERC20 em ETH
- Trocar ERC20 por outro ERC20
- Troca de BEP20 por BNB
- Troca de tokens BEP20

Os usuários são obrigados a realizar uma transação de aprovação separada. Essas transações de aprovação são normalmente econômicas e significam o consentimento do usuário para que o DEX deduza uma quantidade específica de tokens ERC20/BEP20 para execução de negociação.

Durante uma transação de aprovação, os usuários podem especificar o valor do token que o DEX pode deduzir. Os usuários também têm a opção de autorizar valores maiores antecipando negociações futuras, eliminando assim a necessidade de transações de aprovação subsequentes.

A não autorização de uma quantidade suficiente de tokens para uma negociação resultará no fracasso da transação.