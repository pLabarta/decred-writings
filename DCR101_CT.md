# Introducción a Decred: una reserva de valor segura, adaptable y sustentable

Decred es una criptomoneda enfocada en el mismo segmento que Bitcoin, la reserva de valor. Esta moneda al surgió al unir la visión del uno de los creadores de Monero, un energético forista anónimo y un equipo de desarrolladores que acababa de crear una implementación alternativa de Bitcoin, reescribiendo completamente el código de un nodo usando go-lang. Todos coincidieron en tres puntos: Bitcoin necesita financiación, debe ser independiente y deberían ser los holders quienes tomen las decisiones.

Lanzada en 2016, la red Decred fue desarrollada implementando aquellos componentes de Bitcoin que demostraron ser exitosos como el diseño de la blockchain basado en transacciones, el límite de 21 millones y el sistema de minería Proof-of-Work. Pero para solucionar los problemas detectados, se agregó un sistema de votación Proof-of-Stake y un Tesoro que acumula parte del DCR generado para financiar proyectos sin depender de empresas o inversores.

Si bien se trata de un proyecto con un fuerte origen en Bitcoin, el plan de acción y ahora también el código poco tienen en común con la primera coin que abrió el juego de las criptomonedas.

## Diferencias con Bitcoin

"Una CPU, un voto", escribió Satoshi. ¿Debería haber escrito "un BTC, un voto"? Quienes tienen BTC no tienen voz ni voto sobre la dirección del proyecto. Los mineros deciden qué implementar al minar y asegurar la cadena de su preferencia. Los desarrolladores deciden qué implementar al diseñar y escribir los cambios necesarios para hacerlo. En esta escenario y sin un mecanismo formal para tomar decisiones, llegar a un consenso se vuelve imposible y la red corre peligro de bifurcarse si la comunidad se polariza.

Bitcoin, y el grupo Satoshi Nakamoto, se encargaron de quitar a gran parte de los intermediaros financieros del camino, pero al aprovechar las virtudes del software open-source, también heredaron sus problemas. La misma apertura que permite que cualquiera colabore con el código y que cualquiera lo use sin tener que pagar ni un satoshi a una empresa desarrolladora, hace que la financiación y el mantenimiento dependan de donaciones, sean de tiempo o dinero. Así, el proyecto es abierto, pero para avanzar depende de inversores externos o desarrolladores con suficiente tiempo libre para dedicarle horas a un proyecto que no les ayuda a llevar comida a la mesa.

En estos entornos donde no hay posiciones ni sueldos, la reputación lo es todo. Si se combina este escenario con la falta de estructuras de gobierno formales, se forman pequeñas élites que se ven favorecidas y consolidan su posición de poder.

A diferencia de Bitcoin, Decred busca poder adaptarse y mejorar su tecnología constantemente. La implementación del sistema Proof-of-Stake permite que quienes tienen Decred y están dispuestos a afrontar el riesgo de holdear el activo tengan poder de decisión. Así, con mecanismos formales que incluyen discusiones y votaciones, el colectivo de stakeholders puede coordinar para invertir los fondos del Tesoro en lograr sus objetivos, sea modificar el software, construir un exchange descentralizado u organizar eventos online.

Esta variación motivó el desarrollo de distintas plataformas que más allá de las posibilidades económicas, indaga también en el potencial de las Organizaciones Autónomas Descentralizadas (DAO) y las formas de coordinación social. El resultado incluye un exchange descentralizado, un foro inmutable para discutir propuestas, un sistema de votación on-chain y un sistema de facturación y gestión de contratistas transparente y descentralizado, que detallaremos más abajo.

Todos estos desarrollos son posibles gracias a los fondos acumulados en el Tesoro, que recibe el 10% de todo el DCR generado, y fueron aprobados por la comunidad.

## PoW + PoS = "Consenso híbrido"

La inclusión de los holders en el modelo de gobernanza llevó a la implementación de un sistema de consenso híbrido que combina Proof-of-Work y Proof-of-Stake.

La creación de bloques mediante la minería Proof-of-Work es un mecanismo probado y funciona. Es por esto que Decred toma el componente PoW de Bitcoin. Pero se trata de un sistema que también tiene sus problemas: las particularidades de la industria del hardware tiende a concentrar a los fabricantes y centralizar el acceso a la tecnología. Así, la creación de hardware eficiente, como los ASICs, computadoras especializadas en solo un uso (en este caso minar criptomonedas), se vuelve un privilegio de unos pocos capaces de montar grandes fábricas y operaciones. A su vez, compartir el algoritmo con otras monedas, puede llegar a ser un vector de ataque si no se domina el segmento.

La incorporación del componente Proof-of-Stake es el agregado que le da a los poseedores de DCR, los holders, voz y voto para cambiar las reglas de consenso, financiar nuevos desarrollos y auditar el trabajo de los mineros. En la practica funciona como un sistema de doble autenticación, los bloques deben pasar por dos controles: PoW y PoS.

Decred incentiva la participación en la seguridad y la toma de decisiones, quienes compran tickets del sistema Proof-of-Stake reciben el 30% de la recompensa de los bloques. Los mineros reciben el 60% debido a los mayores costos de sus operaciones y el 10% restante va al Tesoro.

Los holders de Decred pueden participar en el sistema PoS al congelar su DCR a cambio de tickets. Los tickets brindan poder de voto y se usan para determinar los cambios a las reglas de consenso, la validez de los bloques encontrados por los mineros, el uso que se le da a los fondos del Tesoro y otras políticas dentro de Decred.

Para participar de la votación Proof-of-Stake, quienes tienen DCR pueden usarlo para comprar tickets. Esto implica congelar una cantidad de DCR determinada por la dificultad de la red, también conocida como el precio del ticket. Al hacerlo, recibe un ticket que será llamado a votar en un bloque mediante una lotería aleatoria. En promedio, los tickets tardan 28 días en ser llamados a votar y el precio actual puede ser consultado usando dcrdata, el explorador de bloques de Decred.

## El Tesoro

El Tesoro de Decred es una dirección especial que recibe el 10% de todo el DCR generado en cada bloque. Hasta el momento las claves están en manos de Decred Holding Group, pero los trabajos necesarios para descentralizar su administración están casi terminados. La actualización del Tesoro requiere pruebas que garaticen la mitigación de cualquier impacto o ataque al fondo de desarrollo de Decred. Luego del ataque a la DAO en Ethereum y situaciones como los fondos congelados debido a un bug en Parity, queda claro que nunca está de más probar.

Si bien el Tesoro acumula DCR, las propuestas se financian en dólares (USD), sin excepción. Los pagos a los contratistas se hacen en DCR al tipo de cambio promedio del periodo trabajado. Así, los contratistas también están expuestos a la volatilidad de la moneda. Algunos meses cobrán más en USD y otros meses, menos.

El uso de los fondos del Tesoro se define a través de Politeia, una plataforma de gobernanza pensada para recibir propuestas, discutir y votar para ejecutarlas o no. Los stakeholders de Decred son quienes definen los proyectos que serán financiados y el dinero solo se libera una vez que el trabajo fue realizado. Este es un pequeño detalle muy importante: el Tesoro siempre paga luego de que el trabajo sea presentado, nunca antes. De esta forma se evita que se acerquen personas, prometan algo, cobren y no lo cumplan.

Politeia es una plataforma similar a Reddit, pero con dos importantes mejoras: el contenido queda sellado en la blockchain de Decred y los usuarios deben pagar un pequeño fee para evitar el spam. Crear una cuenta en Politeia cuesta 0,1 DCR y presentar una propuesta, otros 0,1 DCR. Al publicar o comentar, los usuarios generan un token anti-censura, que prueba que publicaron el mensaje. Así, a pesar de tener administradores, los usuarios pueden estar seguros de que no podrán ser censurados con facilidad.

RESUMEN PROPUESTA VOTO ETC

## Lightning Network

Desarrollo de Lightning en Decred

BTCSuite, btcd,lightninglabs, dcrd,dcrlightning

## Desarrollo independiente

Financiacion privacidad, DEX, wallet, atención a la experiencia de usuario, dcrdata.

