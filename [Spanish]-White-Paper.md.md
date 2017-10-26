### Un contrato inteligente de próxima generación y una plataforma de aplicación descentralizada

El desarrollo de Bitcoin de Satoshi Nakamoto en el año 2008[<sup>[1a]</sup>](http://nakamotoinstitute.org/bitcoin/)[<sup>[1b]</sup>](http://www.newyorker.com/magazine/2011/10/10/the-crypto-currency)–2009[<sup>[1c]</sup>](https://en.bitcoin.it/wiki/Category:History)[<sup>[1d]</sup>](https://blockexplorer.com/block/000000000019d6689c085ae165831e934ff763ae46a2a6c172b3f1b60a8ce26f) ha sido aclamado como una evolución radical en el dinero y la moneda, siendo el primer ejemplo de un activo digital que simultáneamente no tiene respaldo o valor intrínseco[<sup>[2]</sup>](https://bitcoinmagazine.com/articles/you-say-bitcoin-has-no-intrinsic-value-twenty-two-reasons-to-think-again-1399454061/) ni un emisor o controlador centralizado. Sin embargo, otra parte del experimento Bitcoin, discutiblemente más importante, es la subyacente tecnología blockchain como una herramienta de consenso distribuido. La atención está rápidamente comenzando a trasladarse a este otro aspecto de Bitcoin. Las aplicaciones alternativas comúnmente citadas de la tecnología blockchain incluyen el uso de activos digitales en blockchain para representar monedas personalizadas e instrumentos financieros(colored coins),[<sup>[3]</sup>](https://docs.google.com/a/buterin.com/document/d/1AnkP_cVZTCMLIzw4DvsW6M8Q2JC0lIzrTLuoWu2z1BE/edit) la posesión de un dispositivo físico subyacente (propiedad inteligente),[<sup>[4]</sup>](https://en.bitcoin.it/wiki/Smart_Property) activos no fungibles tales como nombres de dominio (Namecoin)[<sup>[5]</sup>](http://namecoin.org) , así como aplicaciones más complejas que implican tener activos digitales controlados directamente por un código que implementa reglas arbitrarias conocidas como contratos inteligentes[<sup>[6]</sup>](https://en.bitcoin.it/wiki/Contracts) o incluso organizaciones autónomas descentralizadas basadas en blockchain (DAOs por sus siglas en inglés)[<sup>[7]</sup>](http://bitcoinmagazine.com/7050/bootstrapping-a-decentralized-autonomous-corporation-part-i/)

Lo que Ethereum intenta es proveer un blockchain con un lenguaje de programación integrado Turing completo, completamente desarrollado que puede ser utilizado para crear "contratos" que pueden ser utilizados para codificar funciones de transición de estado arbitrarias, permitiendo a los usuarios crear cualquiera de los sistemas arriba descritos, así como muchos otros que aún no hemos imaginados, simplemente escribiendo la lógica en pocas líneas de código.

### Tabla de contenidos

* [Introducción a Bitcoin y Conceptos existentes](#introduccion-a-bitcoin-y-conceptos-existentes)
    * [Historia](#historia)
    * [Bitcoin como un sistema de transición de estado](#bitcoin-como-un-sistema-de-transicion-de-estado)
    * [Minería](#minería)
    * [Merkle Trees](#merkle-trees)
    * [Árboles Merkle](#arboles-merkle)
    * [Aplicaciones Alternativas de Blockchain](#aplicaciones-alternativas-de-blockchain)
    * [Scripting](#scripting)

* [Ethereum](#ethereum)
    * [Cuentas Ethereum](#cuentas-ethereum)
    * [Mensajes y transacciones](#mensajes-y-transacciones)
    * [Función de transición del estado de Ethereum](#funcion-de-transicion-de-estado-de-ethereum)
    * [Ejecución de código](#code-execution)
    * [Cadena de bloques y minería](#cadena-de-bloques-y-mineria)

* [Aplicaciones](#aplicaciones)
    * [Sistemas de Moneda](#sistemas-de-monedas)
    * [Derivados financieros](#derivados-financieros)
    * [Sistemas de identidad y reputación](#sistemas-de-identidad-y-reputacion)
    * [Almacenamiento de archivos descentralizado](#almacenamiento-de-archivos-descentralizado)
    * [Organizaciones autónomas descentralizadas](#organizaciones-autonomas-descentralizadas)
    * [Aplicaciones adicionales](#aplicaciones-adicionales)

* [Miscelánea e inquietudes](#miscelanea-e-inquietudes)
    * [Implementación modificada de GHOST](#implementacion-modificada-de-ghost)
    * [Tarifas](#tarifas)
    * [Computación y Completitúd Turning](#computación y completitud-turning)
    * [Moneda y emisión](#moneda-y-emision)
    * [Centralización de minería](#centralizacion-de-mineria)
    * [Escalabilidad](#escalabilidad)

+ [Conclusión](#conclusion)
* [Notas, referencias y lecturas adicionales](#notas-referencias-y-lecturas-adicionales)