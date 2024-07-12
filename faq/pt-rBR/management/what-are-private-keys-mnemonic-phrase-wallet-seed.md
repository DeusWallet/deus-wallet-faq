# Compreendendo as chaves privadas

No mundo da criptomoeda, termos como chave privada, frase mnemônica, frase secreta e semente de carteira são frequentemente usados ​​de forma intercambiável. Todos esses termos referem-se a informações necessárias para controlar fundos em carteiras de criptomoedas sem custódia, como Deus.

Ao configurar uma carteira de criptomoeda sem custódia, os usuários recebem uma chave privada. Esta chave é gerada durante o processo de configuração e, para facilidade de uso, é apresentada como uma série de 12 (ou mais) palavras simples em inglês, conhecidas em Deus como frase secreta.

A chave privada concede aos usuários acesso e propriedade sobre todos os ativos da carteira. Ao contrário dos serviços tradicionais que permitem a recuperação de senhas, as carteiras sem custódia não oferecem opções de recuperação de chaves privadas perdidas. Carteiras construídas corretamente não podem recuperar essas chaves depois de perdidas.

As chaves privadas são geradas aleatoriamente no dispositivo do usuário durante a criação da carteira e nunca saem do dispositivo. Se a carteira for excluída, as chaves também serão excluídas, impossibilitando a recuperação sem acesso ao dispositivo. Portanto, é crucial que os usuários façam backup de suas chaves privadas durante a configuração da carteira. A maioria das carteiras solicita aos usuários que anote uma cópia da chave privada imediatamente após a criação.

Cada carteira multi-moedas Deus vem com sua própria chave privada, conhecida como frase secreta, apresentada como 12 palavras simples em inglês. Esta chave permite aos usuários:

- Restaurar o acesso à carteira mesmo que o aplicativo Deus seja excluído.
- Restaure o acesso à carteira em um aplicativo de carteira diferente.

Além da frase secreta, Deus oferece diversas outras opções importantes:

### Chave Privada EVM

Esta chave permite importar criptomoedas baseadas em EVM (como Ethereum e Binance Smart Chain) de Deus para qualquer aplicativo de carteira compatível. Ela não deve ser compartilhada publicamente, pois qualquer pessoa com esta chave pode controlar criptomoedas baseadas em EVM, mas não Bitcoin ou outras criptomoedas não EVM na mesma carteira.

### Chave raiz BIP32

Esta é outra representação da frase secreta, proporcionando controle total sobre os ativos da carteira. Deve ser mantido seguro e nunca compartilhado.

### Chave pública estendida da conta

Esta chave permite o monitoramento somente leitura de Bitcoin e outras criptomoedas baseadas em UTXO (como Litecoin e Bitcoin Cash) na carteira. É útil para monitorar fundos sem gastá-los. Por exemplo, você pode monitorar Bitcoins armazenados em uma carteira de hardware Ledger através do Deus sem comprometer a segurança. Esta chave não fornece acesso a criptomoedas EVM.

### Chave privada estendida da conta

Esta chave permite importar Bitcoin e outras criptomoedas baseadas em UTXO de Deus para outro aplicativo de carteira compatível. Ela fornece os mesmos recursos de propriedade que a chave pública estendida da conta, mas com controle sobre os fundos. Deve ser mantido confidencial e nunca compartilhado, pois concede gerenciamento sobre Bitcoin e outras criptomoedas baseadas em UTXO, mas não sobre criptomoedas EVM.

Ao compreender essas chaves e suas funções, os usuários podem garantir que seus ativos de criptomoeda permaneçam seguros e acessíveis.