# Compreendendo o gás, o preço do gás e o limite do gás na rede Ethereum

Ao navegar na rede Ethereum, as taxas de transação são liquidadas em Ether (tokens ETH), mas são calculadas usando unidades Gas.

Embora a compreensão das taxas de transação seja suficiente para a maioria dos usuários, aprofundar-se no conceito de gás pode saciar a curiosidade de alguns.

O gás atua como o combustível que alimenta as ações na blockchain Ethereum, servindo como unidade de medida para determinar as taxas de transação. Depende de dois parâmetros essenciais:

1) Limite de Gás indica a quantidade máxima de Gás que um usuário se compromete a pagar para verificar uma transação (mínimo de 21.000). Normalmente, para transações que envolvem transferências de ETH, o limite de gás é definido em 21.000. Os aplicativos de carteira geralmente avaliam esse limite com base na complexidade da transação. Limites de gás inadequados muitas vezes resultam em falhas nas transações, acompanhadas por um erro de “falta de gás”.

2) Preço do Gás significa a quantidade (em ETH) que um usuário aloca por unidade de gás. Este preço varia de acordo com a atividade da rede; durante os picos, os preços do gás sobem, enquanto diminuem durante as calmarias. Os preços mais elevados do gás implicam uma maior importância da transação dentro da rede Ethereum, à medida que os mineiros recebem maiores recompensas. Os preços inadequados do gás frequentemente levam a períodos prolongados de pendência de transações.

A carteira Deus define automaticamente o limite e o preço do gás para transações na rede Ethereum. A taxa de transação sugerida é derivada da multiplicação do limite de gás recomendado e do preço do gás.

Por exemplo, com um limite de gás de 50.000 unidades e um preço de gás de 20 Gwei (uma subunidade do Ether), o remetente se compromete a gastar 0,001 ETH para a execução da transação.