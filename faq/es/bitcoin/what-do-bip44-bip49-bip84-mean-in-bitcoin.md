# ¿Qué significan BIP44 / BIP49 / BIP84 en Bitcoin?

Bitcoin utiliza tres formatos de dirección de uso común para recibir pagos. Normalmente, las carteras de criptomonedas solo admiten uno de estos formatos, aunque algunas pueden admitir varios formatos.

Sin embargo, Deus admite los tres formatos de direcciones, lo que permite a los usuarios mantener saldos y transacciones de Bitcoin separados para cada formato dentro de una única billetera multimoneda. Esto significa que una billetera creada en Deus puede tener tres billeteras Bitcoin diferentes que funcionan como criptomonedas separadas junto con otras criptomonedas.

Estos diversos formatos de direcciones surgieron a medida que aumentaron las transacciones de Bitcoin, con formatos más nuevos diseñados para reducir el tamaño de las transacciones y permitir que la red procese más transacciones por bloque.

## Direcciones heredadas (BIP44)

El formato de dirección más antiguo, conocido como BIP44, normalmente comienza con un "1". Como en el formato original, la mayoría de las billeteras pueden enviar y recibir pagos a estas direcciones. Sin embargo, las transacciones que utilizan direcciones heredadas generan tarifas más altas en comparación con otros formatos.

## Direcciones SegWit (BIP49)

Un formato más nuevo, BIP49, normalmente comienza con un "3". Muchas aplicaciones de billetera más nuevas admiten direcciones SegWit, y las transacciones desde billeteras que usan direcciones SegWit son más baratas que aquellas que usan direcciones heredadas.

## Direcciones nativas SegWit (BIP84)

El formato más reciente y rentable, BIP84, utiliza el formato de dirección bech32, que comienza con "bc1". Las transacciones que utilizan direcciones nativas SegWit tienen las tarifas más bajas.

Para identificar qué formato admite una billetera, verifique los primeros caracteres de la dirección de recepción en la aplicación de billetera. Comprender el formato de la dirección también es importante al restaurar una billetera Bitcoin en algunas aplicaciones de billetera.

La billetera Deus puede crear y restaurar billeteras que funcionen en cualquiera de estos tres formatos de dirección.