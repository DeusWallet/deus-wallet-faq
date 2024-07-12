# ¿Por qué se muestra incorrectamente el valor de una transacción en una transacción reciente?

Para mostrar con precisión la cantidad total de criptomonedas transferida en fiat (USD, EUR, etc.) para transacciones pasadas, Deus necesita conocer el tipo de cambio válido en la fecha de la transacción.

Actualmente, Deus confía en [CoinGecko](https://coingecko.com) para conocer las tasas históricas de criptomonedas. En el futuro, planeamos hacer referencia a fuentes adicionales, incluidas opciones para obtener tasas históricas de intercambios de criptomonedas descentralizados.

Si el tipo de cambio histórico en la aplicación Unstoopable es incorrecto, el monto de la transacción que se muestra en la lista de transacciones también será incorrecto. En tales casos, consulte la cantidad real transferida en criptomonedas.