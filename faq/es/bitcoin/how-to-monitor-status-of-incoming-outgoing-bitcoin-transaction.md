# Cómo monitorear el estado de las transacciones entrantes/salientes de Bitcoin

La billetera Deus permite a los usuarios monitorear el estado de sus transacciones:

- Cuando un usuario envía una transacción de Bitcoin, aparece con el estado "pendiente" en la pestaña Transacciones tanto para el remitente como para el destinatario. Este estado permanece hasta que la transacción se incluye en la cadena de bloques.

- Una vez que la transacción se incluye en la cadena de bloques, su estado cambia a "enviando" para el remitente y "recibiendo" para el destinatario. Este cambio indica que la transacción ha recibido su primera confirmación.

- El estado de la transacción sigue siendo "enviando" tanto para el remitente como para el destinatario hasta que hayan pasado al menos tres bloques, lo que significa que la transacción ha recibido tres confirmaciones.

Hasta que hayan pasado tres bloques, Deus no reflejará el monto de la transacción en el saldo del destinatario ni permitirá que el destinatario gaste los fondos recibidos en otras transacciones.

Además de monitorear el estado de las transacciones dentro de Deus, los usuarios pueden usar exploradores de bloques de Bitcoin disponibles públicamente, como [btc.com](https://btc.com), para monitorear. Para rastrear el estado de las transacciones pendientes en recursos externos, los usuarios necesitan el ID de la transacción, que se puede encontrar en Deus.