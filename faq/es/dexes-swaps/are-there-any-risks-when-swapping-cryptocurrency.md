# Riesgos asociados con el intercambio de criptomonedas

Si bien la billetera Deus simplifica el proceso de intercambio de criptomonedas al manejar las complejidades y configurar los ajustes de intercambio automáticamente, hay varias consideraciones a tener en cuenta al realizar transacciones de intercambio.

1. Costos de transacción

Al realizar intercambios en intercambios descentralizados (DEX), los usuarios están obligados a cubrir tanto la tarifa de transacción (pagada a los mineros en la cadena de bloques Ethereum) como una tarifa de intercambio (remitida al DEX que facilita la transacción). Estas tarifas se desembolsan a diferentes entidades dentro de una única transacción de swap. La tarifa de intercambio varía según el tamaño del pedido, mientras que la tarifa de transacción fluctúa según las condiciones de la red.

En momentos de congestión, como cuando la cadena de bloques Ethereum experimenta un alto tráfico, las tarifas de transacción pueden aumentar significativamente. Por el contrario, ejecutar un swap en Binance Smart Chain normalmente genera costos más bajos en comparación con Ethereum. Independientemente del DEX utilizado, las tarifas de swap generalmente rondan el 0,3% del monto de la transacción.

Además, es esencial reconocer que los DEX en diferentes blockchains operan con distintos conjuntos de pares comerciales y niveles de liquidez.

2. Plazos de transacción

Normalmente, una transacción de intercambio sigue siendo válida durante aproximadamente 20 minutos después de su envío a la cadena de bloques. Por lo tanto, cuando se utiliza un DEX en una cadena de bloques congestionada como Ethereum, es crucial asegurarse de que la transacción de intercambio incluya una tarifa de transacción adecuada para cumplir con la fecha límite. Enviar una transacción de swap con una tarifa baja puede hacer que la transacción permanezca en un estado pendiente más allá de la fecha límite, lo que lleva a una acción de swap fallida.

3. Deslizamiento de precios

El deslizamiento de precios denota la variación en el precio del token entre la colocación de una orden de intercambio y la finalización de la transacción en la cadena de bloques. Esta variación puede ser positiva o negativa, dependiendo de la dirección del cambio de precio. Las fluctuaciones en las condiciones del mercado durante el período entre el envío de la orden y la verificación de la cadena de bloques contribuyen al deslizamiento de precios.

La billetera Deus mitiga este riesgo al mostrar las cantidades de tokens estimadas y garantizadas que los usuarios pueden esperar de la transacción de intercambio. Los usuarios también pueden especificar niveles de deslizamiento aceptables al enviar transacciones, aunque optar por el deslizamiento más bajo posible puede aumentar la probabilidad de que la transacción falle.

4. Tolerancia al deslizamiento

La tolerancia al deslizamiento se refiere al grado de deslizamiento del precio que un usuario está dispuesto a aceptar para una operación. Al establecer una tolerancia de deslizamiento, los usuarios establecen un umbral mínimo para la cantidad de tokens que aceptarán, en caso de que el precio fluctúe. Esta tolerancia se expresa como un porcentaje del valor total del swap.

5. Tarifas de transacción de swap

El costo de realizar transacciones en la cadena de bloques Ethereum puede ser prohibitivamente alto, particularmente para cantidades más pequeñas. Si bien intercambiar $10,000 en criptomonedas puede justificar una tarifa de transacción de $100, la misma tarifa para cantidades más pequeñas, como $500 o menos, puede no ser económicamente viable.

6. Transacciones de aprobación

Al vender tokens ERC20 o BEP20, los usuarios primero deben ejecutar una transacción de aprobación. Esta transacción autoriza al DEX a deducir tokens del saldo del usuario durante una transacción. Sin esta transacción de aprobación, el DEX no puede utilizar los tokens del usuario para realizar transacciones.