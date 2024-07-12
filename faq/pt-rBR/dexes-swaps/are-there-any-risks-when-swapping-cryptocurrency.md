# Riscos associados à troca de criptomoedas

Embora a carteira Deus simplifique o processo de troca de criptomoedas, lidando com complexidades e definindo configurações de troca automaticamente, há várias considerações a serem lembradas ao se envolver em transações de troca.

1. Custos de transação

Ao trocar em exchanges descentralizadas (DEXes), os usuários são obrigados a cobrir tanto a taxa de transação (paga aos mineradores na blockchain Ethereum) quanto uma taxa de swap (remetida ao DEX que facilita a transação). Essas taxas são desembolsadas para diferentes entidades em uma única transação de swap. A taxa de swap varia dependendo do tamanho do pedido, enquanto a taxa de transação varia de acordo com as condições da rede.

Durante períodos de congestionamento, como quando o blockchain Ethereum passa por alto tráfego, as taxas de transação podem aumentar significativamente. Por outro lado, a execução de um swap na Binance Smart Chain normalmente incorre em custos mais baixos em comparação com o Ethereum. Independentemente do DEX utilizado, as taxas de swap geralmente giram em torno de 0,3% do valor da transação.

Além disso, é essencial reconhecer que DEXes em diferentes blockchains operam com conjuntos distintos de pares de negociação e níveis de liquidez.

2. Prazos de transação

Normalmente, uma transação de swap permanece válida por aproximadamente 20 minutos após o envio ao blockchain. Portanto, ao utilizar um DEX em um blockchain congestionado como o Ethereum, é crucial garantir que a transação de swap inclua uma taxa de transação adequada para cumprir o prazo. O envio de uma transação de swap com uma taxa baixa pode fazer com que a transação permaneça em estado pendente além do prazo, levando a uma falha na ação de swap.

3. Derrapagem de preços

A derrapagem de preço denota a variação no preço do token entre a colocação de uma ordem de swap e a conclusão da transação no blockchain. Esta variação pode ser positiva ou negativa, dependendo da direção da mudança de preço. As flutuações nas condições de mercado durante o período entre o envio do pedido e a verificação do blockchain contribuem para a derrapagem dos preços.

A carteira Deus mitiga esse risco exibindo os valores estimados e garantidos de tokens que os usuários podem esperar da transação de swap. Os usuários também podem especificar níveis de derrapagem aceitáveis ​​ao enviar transações, embora optar pelo menor derrapagem possível possa aumentar a probabilidade de falha da transação.

4. Tolerância ao deslizamento

A tolerância à derrapagem refere-se ao grau de derrapagem de preço que um usuário está disposto a aceitar para uma negociação. Ao definir uma tolerância à derrapagem, os usuários estabelecem um limite mínimo para o número de tokens que aceitarão, caso o preço flutue. Esta tolerância é expressa como uma percentagem do valor total do swap.

5. Taxas de transação de swap

O custo de transação na blockchain Ethereum pode ser proibitivamente alto, especialmente para quantias menores. Embora a troca de criptomoedas no valor de US$ 10.000 possa justificar uma taxa de transação de US$ 100, a mesma taxa para valores menores, como US$ 500 ou menos, pode não ser economicamente viável.

6. Transações de aprovação

Ao vender tokens ERC20 ou BEP20, os usuários devem primeiro executar uma Transação de Aprovação. Esta transação autoriza o DEX a deduzir tokens do saldo do usuário durante uma negociação. Sem esta transação de aprovação, o DEX não poderá utilizar os tokens do usuário para negociações.