# Optimización de las tarifas de transacción en Ethereum con Deus

Deus ofrece un enfoque simplificado para recomendar tarifas de transacción para Ethereum, atendiendo tanto a las transacciones urgentes como a las preferencias del usuario. Así es como funciona:

## Opciones de tarifas

1. **Recomendado:** Ideal para transacciones que requieren un procesamiento rápido (0-20 minutos).
2. **Personalizado:** Permite a los usuarios establecer manualmente el monto de su tarifa preferida.

## Elegir la tarifa adecuada

A la hora de seleccionar una tarifa, es recomendable optar por un importe mayor en escenarios de urgencia o cuando se trata de sumas de transacciones importantes. Aquí hay un desglose:

- **Comercio con criptomonedas:** Las transacciones que involucran contratos inteligentes, especialmente aquellas con operaciones urgentes, se benefician de una confirmación rápida para evitar fallas comerciales.

## Pautas de ajuste de tarifas

Deus obtiene su tarifa "recomendada" de la cadena de bloques de Ethereum, teniendo en cuenta la congestión de la red. Para mejorar la confiabilidad de las transacciones, Deus sugiere aumentar la tarifa según el valor de la transacción:

- Para transacciones ≤ $500: agregue un 5% por encima de la tarifa recomendada por la red.
- Para transacciones ≤ $1,000: Agregar 10%.
- Para transacciones > $1,000 y ≤ $5,000: Agregar 15%.
- Para transacciones > $5,000 y ≤ $10,000: Agregar 20%.
- Para transacciones > $10,000: Agregar 25%.

## Mejores prácticas

Para mitigar el riesgo de fallas o demoras en las transacciones, especialmente para transacciones de alto valor, es prudente considerar al menos el valor de la tarifa recomendado por Deus. Hacerlo no sólo acelera la confirmación de la transacción sino que también minimiza posibles problemas durante la congestión de la red.

Al seguir estas pautas, los usuarios pueden optimizar sus transacciones de Ethereum para lograr eficiencia y confiabilidad, garantizando una ejecución perfecta incluso en escenarios exigentes.