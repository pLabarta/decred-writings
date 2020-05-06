# Introducción a Decred: una reserva de valor segura, adaptable y sustentable

Decred es una criptomoneda enfocada en el mismo segmento que Bitcoin, la reserva de valor. Esta moneda es el resultado de unir la visión del uno de los creadores de Monero, un energético forista anónimo y un equipo de programadores que acababa de crear una implementación alternativa de Bitcoin, reescribiendo completamente el código de un nodo usando go-lang. Todos coincidieron en tres puntos: Bitcoin necesita financiación, debe mantenerse independiente y deberían ser los poseedores de las monedas quienes tomen las decisiones.

Lanzada en 2016, la red Decred fue desarrollada implementando aquellos componentes de Bitcoin que demostraron ser exitosos como el diseño de la blockchain basado en transacciones, el límite de 21 millones y el sistema de minería Proof-of-Work. Pero para solucionar los problemas detectados, se agregó un sistema de votación Proof-of-Stake y un Tesoro que acumula parte del DCR generado para financiar proyectos sin depender de empresas o inversores.

Si bien se trata de un proyecto con un fuerte origen en Bitcoin, el plan de acción y ahora también el código poco tienen en común con la primera coin que abrió el juego de las criptomonedas. Suele decirse que Decred es Bitcoin con [gobernanza](https://es.cointelegraph.com/news/bitcoin-could-revolutionize-governance-says-cypherpunk-jameson-lopp).

## Diferencias con Bitcoin

"Una CPU, un voto", escribió Satoshi Nakamoto. ¿Debería haber escrito "un BTC, un voto"? Quienes tienen BTC no tienen voz ni voto sobre la dirección del proyecto Bitcoin.

Los mineros son quienes deciden qué implementar al trabajar y asegurar la cadena de su preferencia. Los programadores deciden qué implementar al diseñar y escribir los cambios necesarios para hacerlo. Pero no existen mecanismos formales para tomar decisiones como grupo.

Bitcoin, y el grupo Nakamoto, se encargaron de quitar a gran parte de los intermediaros financieros del camino, pero al aprovechar las virtudes del software open-source, también heredaron sus problemas. La misma apertura que permite que cualquiera colabore con el código y que cualquiera lo use sin tener que pagar ni un satoshi a una empresa desarrolladora, hace que la financiación y el mantenimiento dependan de donaciones, sean de tiempo o dinero. Así, el proyecto es abierto, pero para avanzar depende de inversores externos o desarrolladores con suficiente tiempo libre para dedicarle horas a un proyecto que no les ayuda a llevar comida a la mesa.

En estos entornos donde no hay posiciones ni sueldos, la reputación lo es todo. Si se combina este escenario con la falta de estructuras de gobierno formales, se forman pequeñas élites de mineros y programadores que se ven favorecidas y consolidan su posición de poder.

A diferencia de Bitcoin, Decred busca poder adaptarse y mejorar su tecnología constantemente. La implementación del sistema Proof-of-Stake permite que quienes tienen Decred y están dispuestos a afrontar el riesgo de holdear el activo tengan poder de decisión. Así, con mecanismos formales que incluyen discusiones y votaciones, el colectivo de stakeholders puede coordinar para invertir los fondos del Tesoro para lograr sus objetivos, sea modificar el software, construir un exchange descentralizado u organizar eventos online.

Esta variación motivó el desarrollo de distintas plataformas que más allá de las posibilidades económicas, indaga también en el potencial de las Organizaciones Autónomas Descentralizadas (DAO) y las formas de coordinación social. El resultado incluye un exchange descentralizado, un foro inmutable para discutir propuestas, un sistema de votación on-chain y un sistema de facturación y gestión de contratistas transparente y descentralizado, que detallaremos más abajo.

Todos estos desarrollos son posibles gracias a los fondos acumulados en el Tesoro, que recibe una parte de todo el DCR generado, y fueron aprobados por la comunidad.

## PoW + PoS = "Consenso híbrido"

La inclusión de los holders en el modelo de gobernanza llevó a la implementación de un sistema de consenso híbrido que combina Proof-of-Work y Proof-of-Stake.

La creación de bloques mediante la minería Proof-of-Work es un mecanismo probado y funciona. Es por esto que Decred toma el componente PoW de Bitcoin. Pero se trata de un sistema que también tiene sus problemas: las particularidades de la industria del hardware tiende a concentrar a los fabricantes y centralizar el acceso a la tecnología. Así, la creación de hardware eficiente, como los ASICs, computadoras especializadas en solo un uso (en este caso minar criptomonedas), se vuelve un privilegio de unos pocos capaces de montar grandes fábricas y operaciones. A su vez, compartir el algoritmo con otras monedas, puede llegar a ser un vector de ataque si no se domina el segmento.

La incorporación del componente Proof-of-Stake es el agregado que le da a los poseedores de DCR, los holders, voz y voto para cambiar las reglas de consenso, financiar nuevos desarrollos y auditar el trabajo de los mineros. En la práctica funciona como un sistema de doble autenticación, los bloques deben pasar por dos controles: PoW y PoS.

Decred incentiva la participación en la seguridad y la toma de decisiones, quienes compran tickets del sistema Proof-of-Stake reciben el 30% de la recompensa de los bloques. Los mineros reciben el 60% debido a los mayores costos de sus operaciones y el 10% restante va al Tesoro.

Los holders de Decred pueden participar en el sistema PoS al congelar su DCR a cambio de tickets. Los tickets brindan poder de voto y se usan para determinar los cambios a las reglas de consenso, la validez de los bloques encontrados por los mineros, el uso que se le da a los fondos del Tesoro y otras políticas dentro de Decred.

Para participar de la votación Proof-of-Stake, quienes tienen DCR pueden usarlo para comprar tickets. Esto implica congelar una cantidad de DCR determinada por la dificultad de la red, también conocida como el precio del ticket. Al hacerlo, recibe un ticket que será llamado a votar en un bloque mediante una lotería aleatoria. En promedio, los tickets tardan 28 días en ser llamados a votar y el precio actual puede ser consultado usando dcrdata, el explorador de bloques de Decred.

## El Tesoro

El Tesoro de Decred es una dirección especial que recibe el 10% de todo el DCR generado en cada bloque. Hasta el momento las claves están en manos de Decred Holding Group, pero los trabajos necesarios para descentralizar su administración están casi terminados. La actualización del Tesoro requiere pruebas que garanticen la mitigación de cualquier impacto o ataque al fondo de desarrollo de Decred. Luego del ataque a la DAO en Ethereum y situaciones como los fondos congelados debido a un bug en Parity, queda claro que nunca está de más probar.

Si bien el Tesoro acumula DCR, las propuestas se financian en dólares (USD), sin excepción. Los pagos a los contratistas se hacen en DCR al tipo de cambio promedio del periodo trabajado. Así, los contratistas también están expuestos a la volatilidad de la moneda. Algunos meses cobran más en USD y otros meses, menos.

El uso de los fondos del Tesoro se define a través de Politeia, una plataforma de gobernanza pensada para recibir propuestas, discutir y votar para ejecutarlas o no. Los stakeholders de Decred son quienes definen los proyectos que serán financiados y el dinero solo se libera una vez que el trabajo fue realizado. Este es un pequeño detalle muy importante: el Tesoro siempre paga luego de que el trabajo sea presentado, nunca antes. De esta forma se evita que se acerquen personas, prometan algo, cobren y no lo cumplan.

Politeia es una plataforma similar a Reddit, pero con dos importantes mejoras: el contenido queda sellado en la blockchain de Decred y los usuarios deben pagar un pequeño fee para evitar el spam. Crear una cuenta en Politeia cuesta 0,1 DCR y presentar una propuesta, otros 0,1 DCR. Al publicar o comentar, los usuarios generan un token anti-censura, que prueba que publicaron el mensaje. Así, a pesar de tener administradores, los usuarios pueden estar seguros de que no podrán ser censurados con facilidad.

Cualquiera puede publicar una propuesta en Politeia. El proceso por el cual se aprueban las propuestas consta de tres etapas: la discusión con la comunidad a través de los distintos canales de chat, la publicación de la propuesta en Politeia y la votación de la misma. La votación dura una semana y debe alcanzar dos metas: el 20% de los tickets activos debe participar y el 60% de los votos deben ser positivos. Una vez aprobada, los contratistas involucrados pueden presentar el trabajo realizado y recibir su compensación en DCR a través de la plataforma del Sistema de Gestión de Contratistas.

## Dinero adaptable

El Tesoro está disponible para financiar todos los desarrollos apoyados por la comunidad de stakeholders de Decred. Esto permite no solo sustentar el desarrollo del código base de los nodos y las plataformas de minería, sino también incursionar en otras áreas.

Actualmente Decred desarrolla y mantiene, entre otros proyectos:

- Un exchange descentralizado
- La implementación de Lightning Network
- Un servicio de privacidad para mezclar DCR
- Politeia, una plataforma de gobernanza para discutir, votar y financiar propuestas
- dcrdata, un explorador de bloques diseñado para analizar Decred
- Tres proyectos de investigación sobre la actividad on-chain de Decred y su gobernanza
- Billeteras de escritorio, Android y iOS
- Una revista mensual que detalla todos los avances
- Pi UI, una colección de componentes de interfaz gráfica
- Podcasts y videos que cubren el proyecto

El tesoro y los procesos formales permite que los stakeholders de todo el mundo coordinen para empujar las iniciativas más urgentes, sea mejorar la seguridad o crear un exchange sin fines de lucro. Esta capacidad   permite que Decred invierta en aquellas áreas que mayor impacto tendrán para sus usuarios: la seguridad, las interfaces gráficas, la privacidad y quitar a los intermediarios del camino.

## Equipo e historia

En 2013, el equipo fundador de Decred, trabajó en una implementación alternativa a Bitcoin Core, el software más usado para correr nodos de Bitcoin, escrito en Go en vez de C++. Si bien la tecnología funcionaba y había sido probada, este software llamado Btcsuite fue rechazado por la comunidad de Bitcoin Core y no parecía haber un camino claro para colaborar.

Al mismo tiempo, un miembro de Bitcointalk conocido llamado Tacotime, había comenzado a trabajar en "[memcoin2](https://decred.org/research/mackenzie2013.pdf)", una criptomoneda que proponía un sistema de consenso híbrido que pudiese "eventualmente, brindar un control democrático de la política monetaria a sus usuarios mediante el voto participativo".

En 2014, Tacotime e Ingsoc_, otro miembro anónimo de Bitcointalk, se conectaron con Jake Yocom-Piatt, CEO de Company Zero (C0) para acercarle el concepto en el cual habían estado trabajando. En ese momento C0 se llamaba Conformal Systems y trabajaban en el campo de la privacidad y la seguridad. Entre sus productos estaban Cyphertite, un sistema de almacenamiento en la nube que usa zero-knowledge proofs, Coinvoice, un procesador de pagos en Bitcoin, y btcd una implementación alternativa del nodo de Bitcoin escrita en Go, que fue migrada a btcsuite en 2015. A pesar de que Bitcoin Core sigue siendo el software más usado en la red Bitcoin, btcsuite es usado por grandes proyectos del espacio como Ethereum, OpenBazaar y incluso el equipo de Lightning Labs que hizo la primera implementación de Lightning Network.

Hacia fines de 2015, C0 publicó una serie de artículos en su blog donde Jake detalla los problemas que enfrenta Bitcoin y algunas ideas para crear un sistema de dinero digital descentralizado más robusto e inclusivo. El 12 de diciembre, anunciaron el lanzamiento de Decred y el 8 de febrero de 2016 la red comenzó a funcionar.

Hoy el equipo de Decred esta integrado por más de 90 personas de todo el mundo y algunos personajes anónimos. Cualquier puede colaborar con el proyecto a través de los repositorios de Github. Si su trabajo es valioso, serán invitados a convertirse en contratistas y cobrar por sus esfuerzos.

## El valor de la inteligencia colectiva











