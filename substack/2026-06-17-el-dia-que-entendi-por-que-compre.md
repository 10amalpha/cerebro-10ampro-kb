---
title: "Velocidad de Ontología"
date: 2026-06-17
url: https://www.10am.pro/p/el-dia-que-entendi-por-que-compre
source: substack
paywalled: true
---
> Post exclusivo para suscriptores de 10ampro — suscríbete en https://www.10am.pro/subscribe
> Post original: https://www.10am.pro/p/el-dia-que-entendi-por-que-compre

# Velocidad de Ontología

[![](https://substack-post-media.s3.amazonaws.com/public/images/0f293225-cbee-40e5-ba93-a38a6a944975_1642x958.png)](https://substackcdn.com/image/fetch/$s_!IBf0!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F0f293225-cbee-40e5-ba93-a38a6a944975_1642x958.png)

## I. La Palabra que No Entendía

El día que compré Palantir no entendía la palabra más importante de mi propia tesis.

La había escrito. La había dicho en el podcast. Había publicado un artículo de treinta páginas — *[Palantir: la Compañía más Importante de Occidente](https://www.10am.pro/p/palantir-la-compania-mas-importante?utm_source=publication-search)* — donde la ponía en el centro de todo, como si fuera obvia. “El verdadero moat de Palantir no es su software. Es su dominio de la ontología.” Sonaba bien. Sonaba inteligente. Y durante semanas la usé como se usa una palabra prestada: con la confianza de quien repite algo que escuchó en una buena conferencia, sin haber pagado el precio de entenderla por dentro.

La ontología, escribí entonces, es en filosofía el estudio de lo que existe. Parménides, Aristóteles, Heidegger se pasaron la vida en eso. Y en ciencia de datos, agregué, es el framework que define cómo distintas piezas de información se relacionan entre sí. Correcto. Académicamente impecable. Y completamente hueco, porque una definición no es comprensión. Saber que la ontología “es lo que existe” tiene la misma utilidad práctica que saber que la economía “es el estudio de la escasez”. No te dice nada sobre qué hacer un lunes a las nueve de la mañana cuando tienes que decidir dónde poner tu dinero.

El click — el de verdad, el que te reorganiza el cerebro — no me llegó leyendo a Heidegger. Me llegó mucho después, leyendo a Antonio Linares, y voy a llegar ahí. Pero arrancó con Palantir, porque Palantir es el único lugar donde la palabra dejó de ser filosofía y se convirtió en una máquina que cobra millones de dólares por existir. Así que déjenme empezar por donde de verdad empezó: por un aeropuerto.

---

## II. El Aeropuerto

Imaginen el aeropuerto JFK. No la terminal, no la fila de migración. El concepto “aeropuerto” dentro de un computador.

[![](https://substack-post-media.s3.amazonaws.com/public/images/fcde7a3e-3653-4c98-aa64-d4f7505189bd_1642x958.png)](https://substackcdn.com/image/fetch/$s_!pJkZ!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Ffcde7a3e-3653-4c98-aa64-d4f7505189bd_1642x958.png)

Para casi cualquier sistema de software del mundo, JFK es una fila en una tabla. Una celda que dice “país: Estados Unidos”, otra que dice “ciudad: Nueva York”, otra con la latitud, otra con la longitud. Datos. Una hoja de cálculo glorificada. Si quieres saber qué aviones despegaron de ahí, abres otra tabla, en otro sistema, que probablemente llama a JFK por otro nombre — un código, un número interno, una sigla que solo el departamento de operaciones entiende. Y si quieres cruzar eso con los retrasos, abres una tercera tabla, en un tercer sistema, donde “retraso” significa algo ligeramente distinto a lo que significaba en el segundo. Ese es el estado natural de los datos en cualquier organización grande: islas que no se hablan, cada una con su propio idioma, cada una jurando que su versión de la realidad es la verdadera.

Una ontología hace algo distinto. En la ontología, JFK no es una fila. Es un *objeto* — un Aeropuerto, con mayúscula — y ese objeto sabe quién es. Sabe su país, su ciudad, sus coordenadas (eso son sus *propiedades*). Pero, más importante, sabe con quién está conectado: sabe qué Aviones son operados desde él, qué Vuelos partieron de su pista, qué Aerolíneas lo usan como hub, qué Retrasos se originaron en sus puertas (eso son sus *relaciones*, o links). Y sabe qué se le puede *hacer* — qué decisiones, qué cambios, qué órdenes puede recibir y ejecutar contra el mundo real (eso son las *acciones*). Objetos, propiedades, relaciones, acciones. Cuatro piezas. Eso es una ontología, despojada de toda la filosofía alemana: un modelo donde las cosas que existen en tu negocio están conectadas entre sí de la misma manera en que están conectadas en la vida real, y donde sobre esas conexiones se puede actuar.

El problema que resuelve es el problema más viejo y más caro de la era de los datos: que cada sistema le pone un nombre distinto a la misma cosa. Lo escribí en el artículo de Palantir y lo repito porque es el corazón de todo: un “cliente” en el área de ventas es un “usuario” en el área de producto y una “cuenta” en el área de finanzas. La misma persona, tres nombres, tres tablas, cero conexión. Multipliquen eso por miles de entidades a través de docenas de sistemas y tienen el caos que paraliza a casi todas las empresas del planeta. La ontología impone un idioma común. Un solo modelo de la realidad donde “cliente” significa una cosa, siempre, en todas partes, y donde ese cliente está atado a sus pedidos, sus pagos, sus quejas y sus devoluciones sin que nadie tenga que hacer un Excel a medianoche para cruzarlos.

Y aquí está la parte contraintuitiva, la que comparto porque es la que separa esto de cualquier base de datos común. Cuando le agregas más datos a un sistema tradicional, obtienes más complejidad. Más tablas, más cruces, más gente confundida. Cuando le agregas más datos a una ontología bien diseñada, obtienes más *claridad*. Porque cada dato nuevo no es una fila más: es una conexión más, un nodo más en una red que se vuelve más inteligente con cada cosa que aprende. Yo lo escribí entonces como una fórmula medio provocadora:

**Valor(Datos) = Información × Contexto²**

El contexto va al cuadrado porque las relaciones entre datos crecen exponencialmente, no en línea recta. Dos datos tienen una conexión posible. Diez datos tienen cuarenta y cinco. Cien datos tienen casi cinco mil. Una ontología es la única estructura que captura ese valor exponencial mientras todos los demás siguen sumando filas y viendo crecimiento lineal. Por eso Palantir puede integrar una fuente nueva de datos en días mientras sus competidores tardan meses: no están copiando una tabla, están enchufando un nodo a una red que ya entiende el mundo.

Ese fue el primer click. Entender que la ontología no era una palabra elegante para “base de datos”, sino el sistema operativo sobre el cual una organización entiende su propia realidad. Pero faltaba el segundo click, el que convirtió esto de un concepto bonito sobre una sola empresa en la lente con la que ahora miro absolutamente todas mis inversiones. Y ese me lo dio otro inversionista, leyendo sobre una fábrica de medicamentos que se diseña a sí misma.

---

## III. Velocidad de Ontología

Antonio Linares escribe los deep dives más rigurosos que leo en inglés. No los lee mucha gente todavía, lo cual para mí es una ventaja informacional, no un defecto. Y en su análisis de Recursion Pharmaceuticals — una empresa que usa inteligencia artificial para diseñar medicamentos, prediciendo en silicio qué moléculas vale la pena fabricar antes de tocar un solo tubo de ensayo — Antonio nombró el concepto que a mí me faltaba. Lo llamó *Ontology Velocity*. Velocidad de ontología.

[![](https://substack-post-media.s3.amazonaws.com/public/images/dd3b2cea-919a-4a1c-a632-b2cc1d4fd9f9_1641x958.png)](https://substackcdn.com/image/fetch/$s_!2unM!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fdd3b2cea-919a-4a1c-a632-b2cc1d4fd9f9_1641x958.png)

La idea es esta, y se las traduzco tal como me reorganizó la cabeza a mí. Toda empresa tiene una ontología. No solo Palantir. Toda. Es el modelo de trabajo que la empresa tiene del mundo en el que opera, construido a partir de los datos que recoge. Una panadería tiene una ontología pobre y casi inmóvil. Un banco tiene una más rica. Google tiene una monstruosa. Pero el punto de Antonio no es *cuán grande* es la ontología de una empresa. Es **cuán rápido mejora**. Porque mientras más rápido mejora el modelo que una empresa tiene del mundo, más rápido entrega más valor por cada dólar que gasta. Y en un mundo donde la inteligencia artificial compone sobre los datos, la empresa con la ontología que mejora más rápido no solamente gana. Abre una brecha que se compone sobre sí misma hasta volverse imposible de cruzar.

Léanlo otra vez, porque es la frase que lo cambió todo para mí:

> ***la empresa con la ontología que mejora más rápido abre una brecha que se compone hasta volverse imposible de cruzar.***

No es la que tiene más datos hoy. Es la que aprende más rápido de los datos que tiene. La ontología de Recursion es la biología misma, y su negocio entero es una máquina para mejorar ese modelo de la biología más rápido de lo que cualquier otro puede. El loop es el activo: el laboratorio húmedo genera datos, los modelos predicen, el laboratorio prueba la predicción, el resultado — acierto o error — reentrena el modelo, y vuelve a empezar, cada vuelta más apretada que la anterior. El motor paga su propia mejora. Antonio llama a las empresas con esa forma ***Singularity Scalers*****: negocios cuyo output se desacopla del input y que se vuelven exponencialmente más poderosos a costo marginal casi cero a medida que la IA compone.**

Ahí fue donde junté los cables. Palantir me había enseñado *qué* es una ontología. Antonio me enseñó que la ontología no es una foto, es una *velocidad* — una derivada, para los que les gusta el cálculo. Y que esa velocidad es medible, comparable, y probablemente el mejor predictor que existe de qué empresa va a componer durante una década y cuál se va a quedar coleccionando filas en una tabla.

Desde ese día no he vuelto a mirar una posible inversión de la misma forma. Antes preguntaba lo que pregunta todo el mundo: ¿qué tan grande es el mercado, qué tan barata está la acción, qué tan bueno es el equipo. Ahora, antes que nada, pregunto una sola cosa: ¿qué tan rápido mejora el modelo que esta empresa tiene de su propio mundo? Y cuando empecé a hacerme esa pregunta sobre las empresas que ya tenía en cartera, descubrí que sin saberlo había estado comprando velocidad de ontología todo el tiempo. Solo que no tenía la palabra.

Este es exactamente el tipo de lente que [vamos a afilar en vivo en el Día D — 14 de octubre, Auditorio Fundadores de EAFIT, Medellín.](https://eldiad.10am.pro/) Una vez al año la comunidad se sienta en la misma sala a desarmar los modelos mentales con los que vemos el mundo antes de poner el dinero, y este año la velocidad de ontología va a ser uno de ellos. Los detalles y el link de registro están más abajo, al final del artículo; y para los 10am alphas dejé ahí mismo el cupón del 40%.

Pero antes de la sala, los tres ejemplos. Déjenme mostrarles tres.

---

## IV. Duolingo: La Ontología que Sabe Cómo Aprendes

Empecemos con la más fácil de querer y la más fácil de subestimar: Duolingo.

La mayoría de la gente ve a Duolingo como una app de idiomas con un búho que te manda notificaciones agresivas. Eso es la interfaz. Lo que pasa por debajo es una de las ontologías educativas más densas que existen. Cada vez que tú — o cualquiera de sus cientos de millones de usuarios — respondes una pregunta, Duolingo no está registrando solo “correcto” o “incorrecto”. Está registrando *qué* error cometiste, en qué punto exacto de la frase, después de cuántos segundos de duda, a qué hora del día, en qué racha, después de cuánto tiempo sin practicar ese concepto en particular. Está modelando, persona por persona, cómo aprende un cerebro humano un idioma. No el cerebro promedio: el tuyo.

[![](https://substack-post-media.s3.amazonaws.com/public/images/4a3235f0-ded2-48af-a6a0-59162d940d6f_1642x958.png)](https://substackcdn.com/image/fetch/$s_!cLgW!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F4a3235f0-ded2-48af-a6a0-59162d940d6f_1642x958.png)

Esa es una ontología educativa, y su velocidad es brutal. Cada respuesta de cada usuario mejora el modelo que Duolingo tiene de cómo se olvida y cómo se retiene. El concepto técnico que persiguen — cuándo exactamente estás a punto de olvidar una palabra para repasártela justo en ese instante — solo es posible si tu modelo del olvido mejora con cada interacción. Una academia de idiomas tradicional tiene un profesor con intuición y veinte años de experiencia. Duolingo tiene un modelo que reentrena con miles de millones de respuestas al día. La intuición del profesor es valiosa pero está congelada. El modelo de Duolingo corre training cada noche. Esa es la diferencia entre tener datos y tener velocidad de ontología.

Y fíjense en algo que voy a repetir hasta el cansancio en este artículo, porque es el patrón que más me obsesiona: Duolingo no podría capturar nada de esa data sin su interfaz. El búho, la gamificación, las rachas, las notificaciones culposas — todo eso que parece marketing infantil — es en realidad el aparato de captura. Es lo que hace que vuelvas todos los días y le entregues, sin darte cuenta, una muestra más de cómo aprende tu cerebro. La UI/UX no es el producto. La UI/UX es la jeringa con la que extraen la sangre que alimenta la ontología.

---

## V. Hims & Hers: La Ontología de tu Cuerpo

La segunda la conocen los que leyeron mi [artículo sobre péptidos: Hims & Hers.](https://www.10am.pro/p/el-negocio-mas-grande-del-que-nadie?utm_source=publication-search)

Escribí entonces que Hims era el negocio más grande del que nadie estaba hablando, y la tesis sigue intacta, pero ahora la puedo decir con la palabra correcta. Hims está construyendo una ontología de salud directa al consumidor. Cada consulta, cada síntoma reportado, cada tratamiento recetado, cada renovación, cada abandono, cada efecto secundario que un paciente menciona en un mensaje de seguimiento — todo eso es un nodo. Y a diferencia de tu médico de cabecera, que te ve veinte minutos cada seis meses y olvida la mitad, Hims no olvida nada y lo conecta todo. Sabe qué tratamiento funciona para qué perfil, qué combinación retiene a un paciente, en qué momento del tratamiento la gente se cae, qué molécula nueva pedir antes de que el mercado la pida.

[![](https://substack-post-media.s3.amazonaws.com/public/images/409a0fcd-1e50-42e7-a21e-ebe3f5b9fffc_1643x957.png)](https://substackcdn.com/image/fetch/$s_!X50B!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F409a0fcd-1e50-42e7-a21e-ebe3f5b9fffc_1643x957.png)

Antonio, que también es bull de Hims, lo ve igual: el valor real no está en vender la pastilla. Está en el modelo de la salud del consumidor que se construye vendiendo millones de pastillas y observando qué pasa después. Cuando la FDA suelte los péptidos — y escribí un artículo entero sobre por qué eso va a pasar — quien tenga el canal y, sobre todo, quien tenga el *modelo* de qué ofrecerle a quién, captura la década. Hims no está acumulando pacientes. Está acumulando velocidad de ontología sobre el cuerpo humano a escala de consumo masivo.

Y otra vez, miren la puerta de entrada: la interfaz. La razón por la que Hims pudo construir ese modelo y la medicina tradicional no, es que Hims diseñó una experiencia tan simple, tan sin fricción, tan poco vergonzosa, que la gente le cuenta cosas a una app que no le contaría a un doctor de bata blanca en un consultorio frío. La UI/UX bajó la barrera de la confesión. Y cada confesión es un dato. Cada dato, un nodo. Cada nodo, más velocidad.

---

## VI. Robinhood: La Ontología que Sabe Quién Gana

La tercera es la que más me impresiona, y la que más conecta con todo lo que he escrito sobre la [transferencia de riqueza más grande de la historia: Robinhood.](https://www.10am.pro/p/el-puente-de-los-124-trillones-como?utm_source=publication-search)

En mi artículo sobre cómo Robinhood se convierte en el Wall Street de los millennials, hice las cuentas de los $124 trillones que se van a transferir entre generaciones en las próximas décadas, y de lo que significa que Robinhood capture incluso una fracción de eso. Esa tesis sigue en pie. Pero la velocidad de ontología le agrega una capa que entonces no supe nombrar.

[![](https://substack-post-media.s3.amazonaws.com/public/images/11d9b68f-0c8c-48f8-84e1-24f4d4c8e7be_1643x957.png)](https://substackcdn.com/image/fetch/$s_!sVQa!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F11d9b68f-0c8c-48f8-84e1-24f4d4c8e7be_1643x957.png)

Robinhood está construyendo una ontología financiera del comportamiento de inversión de toda una generación. Y aquí va la frase que de verdad me quita el sueño:

> **Robinhood sabe más sobre cuáles son los trades ganadores que casi cualquier herramienta de análisis que ustedes o yo podamos comprar.**

No porque tenga mejores analistas. Porque tiene el dato que nadie más tiene: qué hace, en tiempo real, cada uno de sus millones de usuarios, y cómo le va después. Sabe quién compró qué, a qué hora, después de leer qué, con cuánto miedo, y si ganó o perdió. Sabe qué patrones de comportamiento preceden a un buen trade y cuáles preceden a una catástrofe. Bloomberg te vende datos del mercado. Robinhood *es* el dato del comportamiento que mueve el mercado por abajo.

Los usuarios de Robinhood Gold, los más comprometidos, mantienen muchísimo más capital en la plataforma y tradean muchísimo más — escribí sobre ese multiplicador. Cada uno de esos trades, cada uno de esos movimientos, alimenta el modelo. Robinhood no está acumulando cuentas de corretaje. Está acumulando una velocidad de ontología sobre cómo invierte el ser humano, y esa es probablemente la ontología financiera más valiosa que se está construyendo fuera de un hedge fund — con la diferencia de que el hedge fund modela unos pocos cientos de posiciones y Robinhood modela los reflejos de una generación entera.

¿Y la puerta de entrada? La misma historia, por tercera vez. Robinhood ganó porque hizo que comprar una acción se sintiera tan fácil como pedir un domicilio. El confeti, los cero comisiones, la interfaz limpia que enfureció a Wall Street — todo eso que los puristas llamaron “gamificación irresponsable” — era el aparato de captura. Bajaron la fricción de invertir a cero, y a cambio se quedaron con el dato de cómo invierte todo el mundo. La UI/UX fue el anzuelo. La ontología fue la pesca.

---

## VII. Por Qué Todas Empiezan con un Buen Botón

Aquí está el patrón que no puedo dejar de ver, y que es la verdadera tesis de este artículo.

Las empresas con la mejor ontología casi siempre arrancan desde una UI/UX excepcional. Y durante mucho tiempo pensé que eso era una coincidencia bonita — que las empresas buenas simplemente eran buenas en todo. No es coincidencia. Es causal, y la flecha de la causalidad va en una dirección que cambia cómo evalúo una empresa entera.

[![](https://substack-post-media.s3.amazonaws.com/public/images/a2b9f2e8-b3f6-4771-b6cf-3222dc954bdc_1643x957.png)](https://substackcdn.com/image/fetch/$s_!WBxi!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fa2b9f2e8-b3f6-4771-b6cf-3222dc954bdc_1643x957.png)

La ontología necesita datos para existir y velocidad para componer. Pero los datos no caen del cielo. Hay que capturarlos. Y la única forma de capturar datos ricos, honestos, de alta frecuencia y sobre el comportamiento real de la gente, es construir una interfaz tan buena que la gente quiera usarla todos los días y, al usarla, te entregue su comportamiento sin sentir que está siendo extraída. La UI/UX no es la capa cosmética por encima del producto serio. Es el órgano de captura del que depende toda la ontología que viene después. Duolingo, Hims, Robinhood: las tres ganaron primero la batalla de la interfaz, y precisamente *por eso* pudieron ganar después la batalla — mucho más importante y mucho más invisible — del modelo del mundo.

Esto invierte algo que el value investing tradicional desprecia. El inversionista clásico ve una app bonita y piensa “eso es superficial, ¿dónde está el moat?”. Yo ahora veo una app bonita con altísima frecuencia de uso y pienso: ahí hay una manguera de datos abierta a presión, y al final de esa manguera se está construyendo una ontología que en cinco años va a ser imposible de copiar. La interfaz es la evidencia de superficie de un foso que se está cavando por debajo. Es la misma lógica de Palantir, que arrancó por el lado más difícil — la CIA, el FBI, el Departamento de Defensa — porque sabía que si lograbas que el analista de contraterrorismo usara tu herramienta para conectar puntos entre vidas humanas, tenías el dato más rico del planeta. La diferencia es que Palantir lo hizo con clientes premium y estas empresas lo hacen con cientos de millones de consumidores. El principio es idéntico: gana la interfaz, captura el comportamiento, construye la ontología, abre la brecha.

Cuando ahora estudio una posible inversión, ese es el primer filtro que corro. No “¿es bonita la app?”. Sino: ¿esta interfaz está capturando un comportamiento que nadie más puede capturar, y ese comportamiento está alimentando un modelo que mejora más rápido que el de cualquier competidor? Si la respuesta es sí, tengo una candidata a velocidad de ontología. Si la respuesta es no — si la app es solo una app, si el dato es genérico, si el modelo no mejora con el uso — entonces no importa qué tan barata esté: es una tabla con buen diseño, no una máquina que compone.

---

## VIII. La Ontología También Gobierna Países

Y por si alguien todavía piensa que esto es un asunto de software empresarial gringo, déjenme cerrar con lo que más me sacudió de todo: la ontología no solo construye empresas. Gobierna Estados. O debería.

Andrés Arias escribió una pieza que recomiendo leer completa — *Ontología Fiscal: cómo un gemelo digital podría salvar a Colombia del abismo tributario* — y agarró el concepto y lo aplicó al lugar más doloroso que hay para un colombiano: las cuentas del Estado. Su tesis, que tomó prestada en parte de mi artículo de Palantir y llevó mucho más lejos, **es una frase que merece grabarse:** ***el déficit fiscal colombiano no es financiero. Es ontológico. No sabemos vernos a nosotros mismos.***

[![](https://substack-post-media.s3.amazonaws.com/public/images/b272a7de-e7de-43a0-89ab-d4db4f2bae32_1030x1030.png)ARIAS FINANCIAL ACADEMY

Ontología Fiscal: cómo un gemelo digital podría salvar a Colombia del abismo tributario

Accede al masterclass sobre Bitcoin o al de Opciones Financieras aquí…

Read more

a year ago · 67 likes · 15 comments · ARIAS FINANCIAL ACADEMY](https://andresfelipearias.substack.com/p/ontologia-fiscal-como-un-gemelo-digital?utm_source=substack&utm_campaign=post_embed&utm_medium=web)

Piénsenlo con el aeropuerto de la Sección II. Un “contribuyente” en la DIAN es un “cliente” en un banco y un “obligado” en la UGPP. La misma persona, tres nombres, tres sistemas que no se hablan. El Estado colombiano, escribe Arias, es un ciego con una biblioteca infinita: tiene todos los datos del mundo y no sabe cómo se conectan. Y un Estado que no puede verse a sí mismo solo sabe hacer una cosa cuando le falta plata: subir impuestos. El martillo de siempre.

La alternativa que plantea Arias es la misma que cobra millones en el sector privado: construir un gemelo digital del Estado, una ontología donde cada peso, cada contrato, cada flujo de caja y cada función burocrática estén conectados como lo están en la realidad. Y describe el ejemplo que lo hace concreto: un contrato inflado para comprar pupitres en un municipio, los mismos pupitres que ya compró la gobernación, mientras una tercera compra idéntica corre en el Ministerio de Educación. En un Estado analógico, esa anomalía nunca se detecta antes del desembolso y se traga miles de millones en sobreprecios invisibles. En un Estado con ontología, el pago se bloquea solo, en segundos, conectando facturas, proveedores y órdenes de pago a través de capas distintas del aparato público. La DIAN dejaría de operar como una Gestapo tributaria que persigue al azar, y pasaría a operar — la imagen es suya — como un francotirador con mira de precisión, que va por el evasor sofisticado y deja en paz al que paga bien. No se trata de exprimir más. Se trata de ver mejor. La misma claridad con la que Palantir ayudó a Occidente a hacer casi imposible la coordinación terrorista, aplicada a hacer casi imposible el desfalco.

Lo cuento porque cierra el círculo de por qué esto se volvió mi modelo mental maestro y no solo un truco para escoger acciones. La velocidad de ontología explica por qué Palantir vale lo que vale. Explica por qué Duolingo, Hims y Robinhood componen. Explica por qué la fábrica de medicamentos de Antonio se diseña a sí misma. Y explica, en negativo, por qué un país entero puede estar quebrado teniendo más datos que nunca en su historia. El que ve mejor, gana. En los mercados, en la medicina, en la guerra y en el presupuesto de una nación. Siempre fue así. Lo único nuevo es que ahora tenemos una palabra para medirlo, y una velocidad para perseguirlo.

---

## IX. El Lente

No les voy a vender que encontré la fórmula mágica. Les voy a contar qué cambió en mi cabeza, que es distinto.

Antes coleccionaba tesis. Una empresa con buen mercado por aquí, otra con buen equipo por allá, una tercera que estaba barata. Bolas brillantes, como las llamo cuando escribo sobre primeros principios. Ahora corro un solo lente sobre todo antes de mirar nada más: ¿qué tan rápido mejora el modelo que esta empresa tiene de su propio mundo, y tiene la interfaz para seguir alimentándolo? Solana sigue siendo, para que quede claro, mi convicción central en cripto — y no por casualidad: es la chain donde el comportamiento on-chain se captura y se compone más rápido. Pero ese es otro artículo. El de hoy es sobre el lente, no sobre una posición.

Y como todo lente que de verdad sirve, este también me dice cuándo *no* comprar. Cuando una empresa tiene datos pero no velocidad — cuando su modelo del mundo está congelado, cuando lleva años corriendo sobre la misma intuición sin reentrenar — ese es, casi siempre, un negocio que parece sólido y que el futuro va a desarmar en silencio. La pregunta no es cuántos datos tienes. Es qué tan rápido aprendes de ellos. Vale para una empresa, vale para un Estado, y si soy honesto, vale para un inversionista también. El que deja de actualizar su modelo del mundo se vuelve una tabla con buen diseño. Yo prefiero seguir reentrenando.

---

> **Día D — 14 de octubre de 2026, Auditorio Fundadores de EAFIT, Medellín.**
>
> [![](https://substack-post-media.s3.amazonaws.com/public/images/ca0ef252-2772-498f-866c-70de4690d8f2_1536x1024.png)](https://luma.com/eldiad?coupon=MODELOSMENTALES)
>
> **[MODELOSMENTALES](https://luma.com/eldiad?coupon=MODELOSMENTALES)** [(40% de descuento)](https://luma.com/eldiad?coupon=MODELOSMENTALES)

---

### Mi mamá tiene 76 años y es la única persona a la que le respondo cuando me pregunta qué acciones o cripto compro.

$BTC

$SOL
