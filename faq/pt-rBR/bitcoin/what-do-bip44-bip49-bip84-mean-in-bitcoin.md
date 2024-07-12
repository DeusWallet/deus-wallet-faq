# O que significa BIP44 / BIP49 / BIP84 em Bitcoin?

Bitcoin utiliza três formatos de endereço comumente usados ​​para receber pagamentos. Normalmente, as carteiras de criptomoedas suportam apenas um desses formatos, embora algumas possam lidar com vários formatos.

Deus, no entanto, suporta todos os três formatos de endereço, permitindo aos usuários manter saldos e transações Bitcoin separados para cada formato dentro de uma única carteira multimoedas. Isso significa que uma carteira criada em Deus pode ter três carteiras Bitcoin diferentes funcionando como criptomoedas separadas junto com outras criptomoedas.

Esses vários formatos de endereço surgiram à medida que as transações Bitcoin aumentaram, com formatos mais recentes projetados para reduzir o tamanho das transações e permitir que a rede processasse mais transações por bloco.

## Endereços legados (BIP44)

O formato de endereço mais antigo, conhecido como BIP44, normalmente começa com “1”. Como formato original, a maioria das carteiras pode enviar e receber pagamentos para esses endereços. No entanto, as transações que utilizam Endereços Legados incorrem em taxas mais elevadas em comparação com outros formatos.

## Endereços SegWit (BIP49)

Um formato mais recente, BIP49, normalmente começa com “3”. Muitos aplicativos de carteira mais recentes suportam endereços SegWit, e as transações de carteiras que usam endereços SegWit são mais baratas do que aquelas que usam endereços legados.

## Endereços SegWit nativos (BIP84)

O formato mais recente e econômico, BIP84, utiliza o formato de endereço bech32, que começa com “bc1”. As transações usando endereços SegWit nativos têm as taxas mais baixas.

Para identificar qual formato uma carteira suporta, verifique os primeiros caracteres do endereço de recebimento no aplicativo de carteira. Compreender o formato do endereço também é importante ao restaurar uma carteira Bitcoin em alguns aplicativos de carteira.

A carteira Deus pode criar e restaurar carteiras operando em qualquer um desses três formatos de endereço.