# ¿Cómo se pueden enviar transacciones de Bitcoin que no se pueden gastar hasta una fecha determinada?

Deus Wallet ofrece la capacidad de enviar transacciones de Bitcoin que están bloqueadas hasta una fecha futura específica. Si bien esta funcionalidad es inherente a la cadena de bloques de Bitcoin, rara vez se implementa mediante aplicaciones de billetera.

Como característica experimental, no está habilitada de forma predeterminada. Los usuarios deben activarlo manualmente navegando a Configuración >> Funciones experimentales.

Una vez que se confirma la transacción en la cadena de bloques, el destinatario se convierte en propietario de los fondos. Sin embargo, no pueden gastar los fondos hasta que haya pasado el tiempo especificado. En la aplicación Deus Wallet, se muestra un icono de candado junto al monto del saldo que se origina en dichas transacciones.

Para recibir estas transacciones, el destinatario debe utilizar Deus Wallet versión 0.10 o superior y utilizar el formato de dirección BIP44 para Bitcoin. Es posible que otras billeteras no reconozcan estas transacciones en la red y que no las muestren en absoluto.