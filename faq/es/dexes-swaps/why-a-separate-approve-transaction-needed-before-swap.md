# ¿Por qué se requiere una transacción de aprobación por separado antes de un intercambio?

Antes de realizar cualquier transacción de swap como:

- Conversión de ERC20 a ETH
- Intercambiar ERC20 por otro ERC20
- Cambiando BEP20 por BNB
- Intercambio de tokens BEP20

Los usuarios deben realizar una transacción de aprobación por separado. Estas transacciones de aprobación suelen ser económicas y significan el consentimiento del usuario para que DEX deduzca una cantidad específica de tokens ERC20/BEP20 para la ejecución comercial.

Durante una transacción de aprobación, los usuarios pueden especificar la cantidad de token que el DEX puede deducir. Los usuarios también tienen la opción de autorizar montos más altos en anticipación de operaciones futuras, eliminando así la necesidad de transacciones de aprobación posteriores.

No autorizar una cantidad simbólica suficiente para una operación resultará en el fracaso de la transacción.