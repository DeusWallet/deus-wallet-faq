# Понимание закрытых ключей

В мире криптовалют такие термины, как закрытый ключ, мнемоническая фраза, секретная фраза и начальное значение кошелька, часто используются как синонимы. Все эти термины относятся к информации, необходимой для контроля средств в некастодиальных криптовалютных кошельках, таких как Deus.

При настройке некастоционального криптовалютного кошелька пользователям предоставляется закрытый ключ. Этот ключ генерируется в процессе установки и для простоты использования представлен в виде серии из 12 (или более) простых английских слов, известных в Deus как секретная фраза.

Закрытый ключ предоставляет пользователям доступ и владение всеми активами в кошельке. В отличие от традиционных сервисов, которые позволяют восстанавливать пароли, кошельки, не связанные с хранением, не предлагают вариантов восстановления утерянных закрытых ключей. Правильно построенные кошельки не смогут восстановить эти ключи после утери.

Приватные ключи генерируются случайным образом на устройстве пользователя во время создания кошелька и никогда не покидают устройство. При удалении кошелька удаляются и ключи, что делает восстановление невозможным без доступа к устройству. Поэтому пользователям крайне важно создавать резервные копии своих личных ключей во время настройки кошелька. Большинство кошельков предлагают пользователям записать копию закрытого ключа сразу после создания.

Каждый мультимонетный кошелек Deus поставляется с собственным секретным ключом, называемым секретной фразой, представленным в виде 12 простых английских слов. Этот ключ позволяет пользователям:

- Восстанавливать доступ к кошельку, даже если приложение Deus будет удалено.
- Восстанавливать доступ к кошельку в другом приложении кошелька.

Помимо секретной фразы, Деус предоставляет еще несколько ключевых опций:

### Закрытый ключ EVM

Этот ключ позволяет импортировать криптовалюты на основе EVM (например, Ethereum и Binance Smart Chain) из Deus в любое совместимое приложение-кошелек. Его не следует публиковать публично, поскольку любой, у кого есть этот ключ, может управлять криптовалютами на основе EVM, но не биткойнами или другими криптовалютами, не относящимися к EVM, в одном кошельке.

### Корневой ключ BIP32

Это еще одно представление секретной фразы, обеспечивающее полный контроль над активами кошелька. Его необходимо хранить в безопасности и никогда не разглашать.

### Расширенный открытый ключ учетной записи

Этот ключ позволяет отслеживать биткойны и другие криптовалюты на основе UTXO (такие как Litecoin и Bitcoin Cash) в кошельке только для чтения. Это полезно для мониторинга средств, не тратя их. Например, вы можете отслеживать биткойны, хранящиеся в аппаратном кошельке Ledger, через Deus, не ставя под угрозу безопасность. Этот ключ не обеспечивает доступ к криптовалютам EVM.

### Расширенный закрытый ключ учетной записи

Этот ключ позволяет импортировать биткойны и другие криптовалюты на основе UTXO из Deus в другое совместимое приложение-кошелек. Он предоставляет те же возможности владения, что и расширенный открытый ключ учетной записи, но с контролем над средствами. Его следует сохранять конфиденциальным и никогда не разглашать, поскольку он обеспечивает управление биткойнами и другими криптовалютами на основе UTXO, но не криптовалютами EVM.

Понимая эти ключи и их функции, пользователи могут обеспечить безопасность и доступность своих криптовалютных активов.