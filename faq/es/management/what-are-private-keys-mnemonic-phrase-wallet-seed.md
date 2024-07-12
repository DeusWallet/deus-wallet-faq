# Comprensión de las claves privadas

En el mundo de las criptomonedas, términos como clave privada, frase mnemotécnica, frase secreta y semilla de billetera a menudo se usan indistintamente. Todos estos términos se refieren a la información necesaria para controlar fondos en carteras de criptomonedas sin custodia, como Deus.

Al configurar una billetera de criptomonedas sin custodia, los usuarios reciben una clave privada. Esta clave se genera durante el proceso de configuración y, para facilitar su uso, se presenta como una serie de 12 (o más) palabras en inglés sencillo, conocidas en Deus como la frase secreta.

La clave privada otorga a los usuarios acceso y propiedad sobre todos los activos de la billetera. A diferencia de los servicios tradicionales que permiten la recuperación de contraseñas, las billeteras sin custodia no ofrecen opciones de recuperación de claves privadas perdidas. Las billeteras correctamente construidas no pueden recuperar estas claves una vez perdidas.

Las claves privadas se generan aleatoriamente en el dispositivo del usuario durante la creación de la billetera y nunca abandonan el dispositivo. Si se elimina la billetera, las claves también se eliminan, lo que hace imposible la recuperación sin acceso al dispositivo. Por lo tanto, es fundamental que los usuarios hagan una copia de seguridad de sus claves privadas durante la configuración de la billetera. La mayoría de las billeteras solicitan a los usuarios que escriban una copia de la clave privada inmediatamente después de su creación.

Cada billetera multimoneda Deus viene con su propia clave privada, conocida como frase secreta, presentada como 12 palabras en inglés sencillo. Esta clave permite a los usuarios:

- Restaurar el acceso a la billetera incluso si se elimina la aplicación Deus.
- Restaurar el acceso a la billetera en una aplicación de billetera diferente.

Además de la frase secreta, Deus ofrece otras opciones clave:

### Clave privada de EVM

Esta clave permite importar criptomonedas basadas en EVM (como Ethereum y Binance Smart Chain) desde Deus a cualquier aplicación de billetera compatible. No debe compartirse públicamente, ya que cualquier persona con esta clave puede controlar las criptomonedas basadas en EVM, pero no Bitcoin u otras criptomonedas que no sean EVM en la misma billetera.

### Clave raíz BIP32

Esta es otra representación de la frase secreta, que proporciona control total sobre los activos de la billetera. Debe mantenerse seguro y nunca compartirse.

### Clave pública extendida de cuenta

Esta clave permite el monitoreo de solo lectura de Bitcoin y otras criptomonedas basadas en UTXO (como Litecoin y Bitcoin Cash) en la billetera. Es útil para monitorear fondos sin gastarlos. Por ejemplo, puedes monitorear Bitcoin almacenado en una billetera de hardware Ledger a través de Deus sin comprometer la seguridad. Esta clave no proporciona acceso a las criptomonedas EVM.

### Clave privada extendida de la cuenta

Esta clave permite importar Bitcoin y otras criptomonedas basadas en UTXO desde Deus a otra aplicación de billetera compatible. Proporciona las mismas capacidades de propiedad que la clave pública extendida de la cuenta pero con control sobre los fondos. Debe mantenerse confidencial y nunca compartirse, ya que otorga administración sobre Bitcoin y otras criptomonedas basadas en UTXO, pero no sobre criptomonedas EVM.

Al comprender estas claves y sus funciones, los usuarios pueden garantizar que sus activos de criptomonedas permanezcan seguros y accesibles.