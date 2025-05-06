# ¿Cómo funciona la tecnología Blockchain en Bitcoin?

**Blockchain** es el sistema que mantiene segura y transparente la red de Bitcoin.

## ¿Qué es un bloque?

Cada bloque contiene información esencial sobre las transacciones y está vinculado al anterior, formando una cadena.

| Elemento del Bloque      | Descripción                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| Transacciones            | Lista de transferencias hechas en la red                                   |
| Hash del bloque anterior | Conecta el bloque actual con el anterior, creando la cadena                 |
| Marca de tiempo          | Fecha y hora en la que se añadió el bloque                                 |
| Nonce                    | Número aleatorio usado para resolver el problema criptográfico              |
| Hash propio del bloque   | Resultado único que identifica el bloque (depende de su contenido + nonce) |

!!! note
    Todos los bloques están conectados. Si cambias uno, se rompe toda la cadena posterior.

## ¿Quién valida los bloques?

Los llamados **mineros**, usando potencia computacional, resuelven problemas matemáticos para añadir nuevos bloques. Este proceso se llama *prueba de trabajo*.
