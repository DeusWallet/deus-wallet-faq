# Como monitorar o status das transações de entrada/saída de Bitcoin

A carteira Deus permite aos usuários monitorar o status de suas transações:

- Quando um usuário envia uma transação Bitcoin, ela aparece com status 'pendente' na guia Transações tanto para o remetente quanto para o destinatário. Este status permanece até que a transação seja incluída na blockchain.

- Uma vez incluída a transação na blockchain, seu status muda para ‘enviando’ para o remetente e ‘recebendo’ para o destinatário. Esta alteração indica que a transação recebeu sua primeira confirmação.

- O status da transação permanece 'enviando' tanto para o remetente quanto para o destinatário até que pelo menos três blocos tenham passado, o que significa que a transação recebeu três confirmações.

Até que três blocos tenham passado, Deus não refletirá o valor da transação no saldo do destinatário nem permitirá que o destinatário gaste os fundos recebidos em outras transações.

Além de monitorar o status das transações no Deus, os usuários podem usar exploradores de blocos Bitcoin disponíveis publicamente, como [btc.com](https://btc.com), para monitoramento. Para acompanhar o status das transações pendentes em recursos externos, os usuários precisam do ID da transação, que pode ser encontrado no Deus.