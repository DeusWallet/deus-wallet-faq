# Comprensión del gas, el precio del gas y el límite del gas en la red Ethereum

Al navegar por la red Ethereum, las tarifas de transacción se liquidan en Ether (tokens ETH), pero se calculan utilizando unidades de Gas.

Si bien para la mayoría de los usuarios es suficiente comprender las tarifas de transacción, profundizar en el concepto de gas puede saciar la curiosidad de algunos.

El gas actúa como combustible que impulsa las acciones en la cadena de bloques Ethereum y sirve como unidad de medida para determinar las tarifas de transacción. Depende de dos parámetros fundamentales:

1) El límite de gas indica la cantidad máxima de gas que un usuario se compromete a pagar para verificar una transacción (mínimo de 21 000). Normalmente, para las transacciones que implican transferencias de ETH, el límite de gas se establece en 21.000. Las aplicaciones de billetera a menudo miden este límite en función de la complejidad de las transacciones. Los límites de gas inadecuados a menudo resultan en fallas en las transacciones, acompañadas de un error de "falta de gas".

2) El precio del gas significa la cantidad (en ETH) que un usuario asigna por unidad de gas. Este precio fluctúa con la actividad de la red; Durante los picos, los precios del gas aumentan, mientras que disminuyen durante las calmas. Los precios más altos del gas implican una mayor importancia de la transacción dentro de la red Ethereum, ya que los mineros reciben mayores recompensas. Los precios inadecuados del gas frecuentemente dan lugar a períodos prolongados de espera de transacciones.

La billetera Deus establece automáticamente tanto el límite como el precio del gas para las transacciones de la red Ethereum. La tarifa de transacción sugerida se obtiene multiplicando el límite de gas recomendado y el precio del gas.

Por ejemplo, con un límite de gas de 50.000 unidades y un precio del gas de 20 Gwei (una subunidad de Ether), el remitente se compromete a gastar 0,001 ETH para la ejecución de la transacción.