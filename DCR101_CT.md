# Introducción a Decred: una reserva de valor segura, adaptable y sustentable

*Por Pablo Labarta*

**Decred** es una criptomoneda enfocada en el mismo segmento que **Bitcoin**, la reserva de valor. Esta es el resultado de un artículo escrito por uno de los creadores de **Monero**, un miembro anónimo del foro Bitcointalk y un equipo de programadores que acababa de escribir una **implementación alternativa de Bitcoin** en el lenguaje de programación Go en vez de C++. Todos coincidían en tres puntos: Bitcoin necesita financiación, debe mantenerse independiente y debería existir un proceso para actualizar moneda y tomar decisiones.

Lanzada en 2016, la red Decred fue desarrollada implementando aquellos componentes de Bitcoin que demostraron ser exitosos como el diseño de la blockchain basado en **transacciones**, el límite de **21 millones** y el sistema de **minería** **Proof-of-Work**. Pero para solucionar los problemas detectados, se agregaron nuevos componentes: el sistema Proof-of-Stake le da poder a los holders y aumenta el costo de los ataques a la red por parte de los mineros y un Tesoro descentralizado, con su respectivo sistema de gobernanza, permiten que el proyecto sea completamente sustentable, sin depender de empresas o inversores.

Si bien se trata de un proyecto con un fuerte origen en Bitcoin, el plan de acción y ahora también el código poco tienen en común con la primera coin que abrió el juego de las criptomonedas. Decred es una interación sobre Bitcoin con especial atención en la [gobernanza](https://es.cointelegraph.com/news/bitcoin-could-revolutionize-governance-says-cypherpunk-jameson-lopp).

## Diferencias con Bitcoin

**"Una CPU, un voto"**, escribió Satoshi Nakamoto. ¿Debería haber escrito "un BTC, un voto"? Quienes tienen BTC no tienen voz ni voto sobre la dirección del proyecto Bitcoin.

Los **mineros** son quienes deciden qué implementar al trabajar y asegurar la cadena de su preferencia. Los **programadores** deciden qué implementar al diseñar y escribir los cambios necesarios para hacerlo. Pero **no existen mecanismos formales** para tomar decisiones como grupo.

Bitcoin, y el grupo Nakamoto, se encargaron de quitar a gran parte de los **intermediaros financieros** del camino, pero al aprovechar las virtudes del software open-source, también heredaron sus problemas. La misma apertura que permite que cualquiera colabore con el código y que cualquiera lo use sin tener que pagar ni un satoshi a una empresa desarrolladora, hace que **la financiación y el mantenimiento** dependan de donaciones, sean de tiempo o dinero. Se trata de un problema tan famoso que hasta tiene nombre: [la tragedia de los comunes](https://es.wikipedia.org/wiki/Tragedia_de_los_bienes_comunales). Así, el proyecto es abierto, pero para avanzar depende de inversores externos o desarrolladores con suficiente tiempo libre para dedicarle horas a un proyecto que no les ayuda a llevar comida a la mesa. Así, **las empresas** que minan o le pagan a los desarrolladores son quienes definen la agenda y el camino a seguir.

A su vez, en estos entornos donde no hay posiciones ni sueldos, la reputación lo es todo. Si se combina este escenario con la falta de estructuras de gobierno formales, se forman **pequeñas élites de mineros y programadores** que se ven favorecidas y consolidan su posición de poder. En la práctica, estos grupos pueden impedir que se implementen nuevas ideas que no los benefician como sucedió con **SegWit**, la discusión por el tamaño de los bloques o [el cambio a ProgPow](https://es.cointelegraph.com/news/progpow-is-dead-long-live-progpow-ethereum-developer-call-summary) en **Ethereum**.

A diferencia de Bitcoin, Decred busca poder adaptarse, incorporar nuevas ideas y mejorar su tecnología constantemente. El sistema **Proof-of-Stake** permite que quienes tienen Decred y están dispuestos congelarlo por un tiempo tengan poder de decisión. Así, con mecanismos formales que incluyen discusiones y votaciones, el colectivo de stakeholders puede coordinar para invertir los fondos del Tesoro para lograr sus objetivos, sea modificar el software, construir un exchange descentralizado u organizar eventos online.

Esta variación motivó el desarrollo de distintas plataformas que, más allá de las posibilidades económicas, indagan también en el potencial de las [**Organizaciones Autónomas Descentralizadas (DAO)**](https://es.cointelegraph.com/ethereum-for-beginners/what-is-dao) y las formas de coordinación social. El resultado incluye, entre otros, un exchange descentralizado, un servicio de mezcla/privacidad, un foro inmutable para discutir propuestas, un sistema de votación on-chain y un sistema de facturación y gestión de contratistas transparente y descentralizado.

## Los principios de la comunidad

Las bases de Decred pueden resumirse en los seis principios definidos por su comunidad:

1. **Software libre y de código abierto:** Todo el software desarrollado por Decred será libre y de código abierto.
2. **Libertad de expresión y consideración:** Todos tienen derecho a comunicar sus opiniones e ideas si miedo a la censura. Se considerarán todas las voces constructivas basadas en los hechos y la razón.
3. **Inclusión de todos los stakeholders:** La inclusión representa a un sistema con múltiples partes interesadas y se debe trabajar para mantener la diversidad de perspectivas y usuarios.
4. **Privacidad y seguridad progresiva:** Tecnología de privacidad y seguridad será implementada de forma continua y progresiva, tanto de manera proactiva como en respuesta a ataques.
5. **Emisión fija y finita:** La emisión es finita y la emisión total nunca deberá superar los 20.999.999,99800912 DCR.
6. **Fungibilidad universal:** La fungibilidad universal es fundamental para que Decred funcione como una reserva de valor y los ataques contra esta deberán ser monitoreados de forma activa y, si es necesario, se deberá tomar contramedidas.

## PoW + PoS = "Consenso híbrido"

La inclusión de los tenedores de DCR al modelo de gobernanza llevó a la implementación de un sistema de consenso híbrido que **combina Proof-of-Work y Proof-of-Stake**. Este le permite cambiar las reglas de consenso de una manera ordenada, balanceando las necesidades de los usuarios y de los mineros.

La creación de bloques mediante la minería **Proof-of-Work** es un mecanismo exitoso probado en Bitcoin. Es por esto que Decred toma el componente PoW. Pero se trata de un sistema que también tiene sus problemas: las particularidades de la industria del hardware tienden a **concentrar a los fabricantes** y centralizar el acceso a la tecnología. La creación de hardware eficiente como los ASIC, computadoras especializadas en solo un uso (en este caso minar criptomonedas), se vuelve un privilegio de unos pocos capaces de montar grandes fábricas y operaciones.

La incorporación del componente **Proof-of-Stake** es el agregado que le da a los poseedores de DCR, los holders, voz y voto para cambiar las reglas de consenso, financiar nuevos desarrollos y auditar el trabajo de los mineros. En la práctica funciona como un sistema de doble autenticación, los bloques deben pasar por **dos controles**: PoW y PoS.

Decred incentiva la participación en la seguridad y la toma de decisiones, quienes compran tickets del sistema Proof-of-Stake reciben el 30% de la recompensa de los bloques. Los mineros reciben el 60% debido a los mayores costos de sus operaciones y el 10% restante va al Tesoro.

Los holders de Decred pueden participar en el sistema PoS al congelar su DCR a cambio de tickets. Estos brindan poder de voto y se usan para determinar los cambios a las reglas de consenso, la validez de los bloques encontrados por los mineros, el uso que se le da a los fondos del Tesoro y otras políticas dentro de Decred.

Para participar de la votación Proof-of-Stake, quienes tienen DCR pueden usarlo para comprar tickets. Esto implica congelar una cantidad de DCR determinada por la dificultad de la red, también conocida como el precio del ticket. Al hacerlo, recibe un ticket que será llamado a votar en un bloque mediante una lotería aleatoria. En promedio, los tickets tardan 28 días en ser llamados a votar y el precio actual puede ser consultado usando dcrdata, el explorador de bloques de Decred.

Quienes deseen participar del sistema Proof-of-Stake de Decred pueden **comprar tickets** usando [Decrediton](https://decred.org/wallets/), la billetera de escritorio.

## El Tesoro

El Tesoro de Decred es una **dirección** que recibe el **10% de todo el DCR** generado en cada bloque. Este es la pieza fundamental que sostienene la autonomía de Decred y le permite operar sin [depender de inversores o empresas](https://es.cointelegraph.com/news/bitmex-research-unveils-who-funds-bitcoin-network-development) que buscan ampliar sus negocios.

Hasta el momento las claves están en manos de Decred Holding Group, pero el [trabajo necesarios](https://proposals.decred.org/proposals/c96290a2478d0a1916284438ea2c59a1215fe768a87648d04d45f6b7ecb82c3f) para descentralizar su administración está [avanzado](https://github.com/decred/dcrd/pull/2170).

En el futuro se busca quitar a todos los humanos del medio. El tesoro pasará a ser una cuenta especial dentro de Decred, con sus propias reglas. De esta forma los stakeholders podrán validar las transacciones que salen del Tesoro y verificar que se este pagando lo indicado. La actualización del Tesoro requiere pruebas que garanticen la prevención de cualquier ataque al Tesoro de Decred.

Las personas que realizan trabajo para Decred se llaman contratistas y cobran por su trabajo en DCR a través del Tesoro. Si bien el Tesoro acumula DCR, **las propuestas se financian en dólares** (USD), sin excepción. Los pagos a los contratistas se hacen en DCR al tipo de cambio promedio del periodo trabajado. Así, estos también están expuestos a la volatilidad de la moneda, algunos meses cobran más en USD y otros meses, menos.

El uso de los fondos del Tesoro se define a través de **[Politeia](https://proposals.decred.org)**, una **plataforma de gobernanza** pensada para recibir propuestas, discutir y votar para ejecutarlas o no. Los stakeholders de Decred son quienes definen los proyectos que serán financiados y el dinero solo sale del Tesoro cuando cuando el contratista presenta sus resultados. Este es un pequeño detalle muy importante: el Tesoro siempre paga luego de que el trabajo sea presentado, nunca antes. De esta forma se evita que se acerquen personas, prometan algo, cobren y no lo cumplan.

Politeia es una plataforma similar a **Reddit**, pero con dos importantes mejoras: el contenido se sella en la blockchain de Decred usando [DCRTime](https://docs.decred.org/advanced/dcrtime/) y los usuarios deben pagar un pequeño monto **para evitar el spam**. Crear una cuenta en Politeia cuesta **0,1 DCR** y presentar una propuesta, otros 0,1 DCR.

Las propuestas son planes de acción que incluyen:

- Problemas

- Soluciones
- Costos
- Equipo de trabajo
- Plan de pago

La infraestructura de Politeia no está descentralizada y depende de administradores. Para evitar la censura, al publicar o comentar, los usuarios generan un token anti-censura, que prueba que publicaron el mensaje. 

Para ser aprobada, una propuesta debe atravesar tres etapas: la **discusión** con la comunidad a través de los distintos canales de chat, la **publicación de la propuesta** en Politeia y la **votación** de la misma. La votación dura una semana y debe alcanzar dos metas: el 20% de los tickets activos debe participar y el 60% de los votos deben ser positivos. Una vez aprobada, los contratistas involucrados pueden presentar el trabajo realizado y recibir su **compensación en DCR** a través del Sistema de Gestión de Contratistas, el anexo contable de Politeia.

## Inversión en el usuario

El Tesoro está disponible para financiar todos los desarrollos que la comunidad de stakeholders crea necesarios para el éxito del proyecto. Estos no se limitan únicamente a mejoras en el software, la estructura de Decred permitió incursionar también en otras áreas.

Actualmente Decred desarrolla y mantiene:

- Un [exchange descentralizado](https://proposals.decred.org/proposals/417607aaedff2942ff3701cdb4eff76637eca4ed7f7ba816e5c0bd2e971602e1)
- La [implementación](https://github.com/decred/dcrlnd) de Lightning Network
- Un [servicio de privacidad](https://github.com/decred/cspp) para mezclar DCR
- [Politeia](https://proposals.decred.org/), una plataforma de gobernanza para discutir, votar y financiar propuestas
- [dcrdata](https://explorer.dcrdata.org/), un explorador de bloques diseñado para analizar Decred
- Tres proyectos de investigación sobre la actividad on-chain de Decred y su gobernanza
- [Billeteras](https://decred.org/wallets/) de escritorio, Android y iOS
- Una [revista mensual](https://medium.com/decred/journals/home) que detalla todos los avances
- [Podcasts y videos](https://www.youtube.com/channel/UCJ2bYDaPYHpSmJPh_M5dNSg) que cubren el proyecto

El tesoro y los procesos formales permite que los stakeholders de todo el mundo coordinen para empujar las iniciativas más urgentes, sea mejorar la seguridad, filmar videos educativos o crear un exchange sin fines de lucro. Esta capacidad permite que Decred invierta en aquellas áreas que mayor impacto tendrán para sus usuarios y no en productos que buscan generar ingresos.

## Equipo e historia

En **2013**, el equipo fundador de Decred, trabajó en una [implementación alternativa](https://github.com/btcsuite/btcd) a [Bitcoin Core](https://es.cointelegraph.com/explained/what-is-bitcoin-core), el software más usado para correr nodos de Bitcoin, escrito en Go en vez de C++. Si bien la tecnología funcionaba y había sido probada, este software llamado [btcsuite](https://github.com/btcsuite) fue rechazado por la comunidad de **Bitcoin Core** y no parecía haber un camino claro para colaborar.

Al mismo tiempo, un miembro de Bitcointalk llamado [Tacotime](https://bitcointalk.org/index.php?action=profile;u=19270), había comenzado a trabajar en "[memcoin2](https://decred.org/research/mackenzie2013.pdf)", una criptomoneda que [proponía](https://bitcointalk.org/index.php?topic=169204.0) un sistema de consenso híbrido que pudiese "eventualmente, brindar un control democrático de la política monetaria a sus usuarios mediante el voto participativo".

En **2014,** **Tacotime** e [_Ingsoc](https://bitcointalk.org/index.php?action=profile;u=93639), otro miembro anónimo de Bitcointalk, [se conectaron](https://bitcointalk.org/index.php?topic=1290358.msg13256312#msg13256312) con **Jake Yocom-Piatt**, CEO de **Company Zero** (C0), para acercarle el concepto en el cual habían estado trabajando. En ese momento C0 se llamaba **Conformal Systems** y trabajaban en el campo de la privacidad y la seguridad. Entre sus productos estaban Cyphertite, un sistema de almacenamiento en la nube que usa zero-knowledge proofs, Coinvoice, un procesador de pagos en Bitcoin, y btcd una implementación alternativa del nodo de Bitcoin escrita en Go, que fue migrada a **btcsuite** en 2015. A pesar de que Bitcoin Core sigue siendo el software más usado en la red Bitcoin, btcsuite es usado por grandes proyectos del espacio como Ethereum, OpenBazaar y incluso el equipo de Lightning Labs que hizo la primera implementación de Lightning Network. A su vez, varios miembros de C0 colaboraron con el desarrollo de OpenBSD, un sistema operativo libre enfocado en la seguridad.

Hacia fines de **2015**, C0 publicó una serie de artículos en su blog donde Jake detalla [los problemas que enfrenta Bitcoin](https://blog.companyzero.com/2015/11/bitcoins-biggest-challenges/) y algunas [ideas para mejorarlo](https://blog.companyzero.com/2015/12/iterating-bitcoin/) y crear un sistema de dinero digital descentralizado más robusto e inclusivo. El 12 de diciembre, anunciaron el lanzamiento de Decred y el **8 de febrero de 2016** la red comenzó a funcionar con la creación del bloque génesis.

En 2016, tacotime hizo su [última publicación en Bitcointalk](https://bitcointalk.org/index.php?topic=169204.msg13256478#msg13256478), mencionando el desarrollo de Decred en su posteo sobre Memcoin2 y se dedicó a colaborar con Monero para luego desaparecer.

Hoy el equipo de Decred esta integrado por **más de 90 personas** de todo el mundo y algunos personajes anónimos. Cualquier puede colaborar con el proyecto a través de los repositorios de Github. Si su trabajo es valioso, serán invitados a convertirse en contratistas y cobrar por sus esfuerzos.

## {conclusion sin terminar} El poder de la inteligencia colectiva

Las plataformas desarrolladas por Decred permiten coordinar a toda la comunidad para desarrollar esta criptomoneda. Esta iteración sobre Bitcoin apuesta principalmente a el potencial de la colaboración humana por sobre la idea de congelar reglas usando criptografía.

Parte de la tesis de Decred es que en el futuro vendrán nuevos desafíos y la única forma de anticiparse es contar con estructuras flexibles que permiten adaptarse a estos problemas desconocidos. Así, la comunidad de Decred constantemente busca incorporar a nuevos desarrolladores, investigadores y comunicadores para expandirse.











