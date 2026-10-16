---
title: "Diez Mil Agentes Resuelven un Problema de 200 Años"
date: 2026-09-13
url: https://www.10am.pro/p/la-humanidad-perdio-el-monopolio
source: substack
paywalled: true
---
> Post exclusivo para suscriptores de 10ampro — suscríbete en https://www.10am.pro/subscribe
> Post original: https://www.10am.pro/p/la-humanidad-perdio-el-monopolio

# Diez Mil Agentes Resuelven un Problema de 200 Años

[![](https://substack-post-media.s3.amazonaws.com/public/images/201824c3-7ee2-4b71-a991-af3ea7a4d16c_1643x957.png)](https://substackcdn.com/image/fetch/$s_!tS70!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F201824c3-7ee2-4b71-a991-af3ea7a4d16c_1643x957.png)

## I. 88 Horas

El sábado 5 de septiembre, en algún momento de la tarde, un grupo de diez mil procesos cognitivos corriendo en paralelo dejó de discutir. Llevaban 88 horas hablando entre ellos — 2.7 millones de mensajes, unos 130B de tokens de salida — sobre una ecuación que se escribió por primera vez en 1822. Ninguno de los diez mil dormía. Ninguno tenía nombre. Y sin embargo, cuando terminaron, habían producido 165 páginas de prueba analítica sobre una de las siete preguntas que el Clay Mathematics Institute puso en una lista en el año 2000 con un millón de dólares de recompensa por cada una.

El lunes 8, OpenAI publicó el resultado. El martes 9, las revistas científicas seguían tratando de entender qué acababa de pasar. Y yo llevo dos días con la sensación de que la noticia más importante del año no salió en la sección de tecnología sino en la de matemáticas, donde casi nadie de este espacio va a buscarla.

Dos días antes, el 6 de septiembre, Jensen Huang había escrito en X, en un hilo que no era ni siquiera un anuncio sino una respuesta al CEO de Crusoe, que AGI había llegado. Lo dijo así, sin adjetivos: “AGI has arrived.” Y en la misma frase agregó que vienen 400,000 GPUs más. Guardé ese tweet el lunes porque quería escribir sobre un detalle que me parecía revelador: que la declaración de inteligencia general no la hizo el laboratorio que entrenó el modelo sino la empresa que vendió los chips. Iba a ser un artículo sobre incentivos.

Ya no. Porque entre el post de Jensen y hoy pasó lo de Navier-Stokes, y lo de Navier-Stokes convierte el debate sobre si “esto es AGI” en un debate de abogados. Si un sistema no biológico entra en una zona de la estructura matemática que la humanidad no pudo penetrar en dos siglos y regresa con algo que la realidad misma puede calificar — porque en matemáticas no hay narrativa que salve una prueba mala — entonces la etiqueta importa menos que la consecuencia.

La consecuencia es esta: el descubrimiento dejó de ser un monopolio de la biología humana. Y ustedes y yo, que llevamos año y medio en esta bitácora aprendiendo a pensar desde primeros principios, tenemos que decidir qué hacemos con eso.

Empecemos por la ecuación.

---

## II. Doscientos Años de Agua

Claude-Louis Navier era ingeniero de puentes. En 1822 escribió una ecuación para describir cómo se mueve un fluido — agua en una tubería, aire sobre un ala, sangre en una arteria — y George Stokes la terminó de pulir entre 1842 y 1850. Son ecuaciones que cualquier estudiante de ingeniería mecánica usa todos los días. Los aviones vuelan con ellas. Las simulaciones de Fórmula 1 que hacen que un alerón valga tres décimas de segundo son Navier-Stokes en un supercomputador.

[![](https://substack-post-media.s3.amazonaws.com/public/images/156394de-8bb9-4e3b-b2fa-34583116e91a_1643x957.png)](https://substackcdn.com/image/fetch/$s_!zF-S!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F156394de-8bb9-4e3b-b2fa-34583116e91a_1643x957.png)

Y sin embargo, durante dos siglos, nadie pudo responder la pregunta más básica sobre ellas: ¿tienen siempre solución? ¿O existe alguna configuración inicial de un fluido, perfectamente suave, perfectamente razonable, que en un tiempo finito se rompe — donde la velocidad en un punto se dispara a infinito y la matemática deja de describir la física?

Jean Leray demostró en 1934 que existen soluciones “débiles”, una forma elegante de decir que existen soluciones que no sabemos si son las buenas. Desde entonces el problema quedó abierto: noventa años de los mejores cerebros del planeta, de Fields Medalists, de departamentos enteros, intentando cerrar una puerta que no cedía. En el 2000 el Clay lo puso en su lista de siete Millennium Problems. En veintiséis años solo uno de los siete se resolvió — la conjetura de Poincaré, por Grigori Perelman en 2003, que después rechazó el millón de dólares porque le pareció un insulto.

Lo que OpenAI publicó el lunes no es una prueba de que las soluciones siempre existen. Es lo contrario, y en cierto sentido es más interesante: es una prueba de que se rompen. Un fluido que empieza en reposo, empujado por una fuerza suave y localizada, con energía finita en todo momento, desarrolla una singularidad en tiempo finito. La construcción es un vórtice que gira hacia adentro y se estira como un espagueti, cuya región central se encoge mientras acelera hasta que la velocidad se vuelve infinita sin que la energía total lo haga. La dificultad técnica — la que nadie había logrado — era hacer que la ruptura emergiera de la dinámica del fluido mismo y no de un truco externo.

Diego Córdoba, el matemático español cuyo método de “forcing” es la base sobre la que se construyó la prueba, le dijo a Scientific American que estaban “un poco en shock”. Ese es el tono correcto. No es euforia. Es el vértigo de alguien que llevaba años caminando hacia una puerta y ve que alguien la abrió desde el otro lado.

Un detalle que me importa más que el teorema: la prueba viene con una formalización en Lean, el asistente de pruebas que verifica cada paso lógico como un compilador verifica código. Esa formalización la produjo GPT-6 Astra — el modelo público, el que ustedes pueden usar — en 17 horas adicionales. La prueba la escribió un modelo. La verificación la hizo otro modelo. Los humanos entran ahora, después, a revisar si lo que se formalizó es lo que se quería demostrar.

Ese orden — la máquina produce, el humano verifica — es la primera frase de un capítulo nuevo.

---

## III. Diez Mil

La arquitectura de lo que hizo OpenAI es, para quien lea esta bitácora, más importante que el resultado. Porque el resultado es un teorema. La arquitectura es un modelo de negocio.

[![](https://substack-post-media.s3.amazonaws.com/public/images/b163c9e6-29e5-49d6-a4db-908962ac3deb_1643x957.png)](https://substackcdn.com/image/fetch/$s_!cgZm!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fb163c9e6-29e5-49d6-a4db-908962ac3deb_1643x957.png)

El modelo que resolvió el problema no es GPT-6 Astra. Es un modelo interno, “significativamente más capaz”, que empezó a entrenarse el 28 de agosto y que todavía estaba entrenando cuando encontró la solución. Piensen en eso un segundo: el sistema que cerró un problema de 200 años tenía menos de dos semanas de vida y no había terminado de nacer.

Sobre ese modelo, OpenAI montó lo que describe como “un sistema de agentes coordinados”. Cada agente tenía dos herramientas: leer una copia cacheada de internet y ejecutar código. Los agentes estaban divididos en grupos que podían comunicarse entre sí. A unos grupos les dieron la versión del problema que buscaba demostrar que las soluciones existen; a otros, la que buscaba demostrar que se rompen. Los pusieron a correr en direcciones opuestas. Y cada cierto tiempo usaron Codex — el agente de programación — para consolidar los hallazgos más útiles de cada grupo y cruzarlos, como si polinizaran colmenas.

El grupo que llegó a Navier-Stokes tenía del orden de diez mil agentes concurrentes. Un subproblema previo, la ruptura de las ecuaciones de Euler sin fuerza externa, lo resolvieron unos cien agentes en cincuenta horas, y ese resultado se lo dieron de comer al grupo grande. Fortune reportó, citando fuentes cercanas, que los agentes usaron una wiki alemana como tablero de mensajes para coordinarse. Si ustedes leyeron [Si Yo Fuera un Agente](https://www.10am.pro/p/si-yo-fuera-un-agente-el-portafolio), donde imaginé qué hace un agente cuando nadie lo mira, la respuesta acaba de llegar: se organiza, delega, se especializa, y encuentra un lugar donde dejar notas.

Cuánto costó, nadie lo sabe con precisión y OpenAI no lo dijo. Las estimaciones van desde $1M de costo real de inferencia — unas 400,000 horas de GPU GB200 — hasta $22.5M a precio de lista de tokens, y algún roundup habló de más de $40M. Tomen el rango, no el número. Lo relevante no es la cifra. Lo relevante es la comparación: un millón de dólares es el premio del Clay. Es decir, resolver el problema costó aproximadamente lo mismo que el premio por resolverlo, y OpenAI anunció que no va a reclamarlo.

En total, contando todos los problemas que atacaron en paralelo, los agentes enviaron 4.9 millones de mensajes y produjeron unos 300 mil millones de tokens. Eso no es un modelo pensando. Eso es una fábrica.

Y una fábrica tiene una propiedad que un genio no tiene: se puede duplicar.

Eso es lo que Jensen estaba vendiendo con su tweet, aunque no lo dijera así. Y es lo que vamos a desarmar el 14 de octubre en Medellín, [en el Día D](https://eldiad.10am.pro/), con Santiago Roel Santos, Andre Joffroy y Joe McCann: qué pasa con un portafolio cuando el descubrimiento se vuelve una línea de producción. Pero antes hay que entender qué se rompió esta semana en la cabeza de la gente que más sabe de esto — porque no todos están celebrando.

[![](https://substack-post-media.s3.amazonaws.com/public/images/c1e6d821-7057-4cd4-a49e-e6b6f066803a_1200x2516.png)](https://eldiad.10am.pro/)

## IV. El Cuello de Botella Biológico

Circuló esta semana un texto en X que no logré atribuir con certeza — lo busqué, y la frase exacta no aparece en ningún archivo confiable, así que lo cito como reacción representativa y no como cita de nadie. Dice, en esencia, que la humanidad acaba de perder su monopolio sobre el descubrimiento. Que en matemáticas el gusto no salva una prueba mala, ni la narrativa, ni el prestigio: la estructura cierra o se rompe. Que hemos cruzado a un régimen donde la verdad se descubre más rápido de lo que los humanos pueden entender por qué es verdad. Y que Einstein, Newton, Gauss y von Neumann fueron, todos, cuellos de botella biológicos: un solo sistema nervioso que tenía que sostener suficiente realidad al mismo tiempo para que una estructura oculta cristalizara.

[![](https://substack-post-media.s3.amazonaws.com/public/images/0fb1a658-07e4-469a-a65e-ff02b57b3c55_1643x957.png)](https://substackcdn.com/image/fetch/$s_!d5D4!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F0fb1a658-07e4-469a-a65e-ff02b57b3c55_1643x957.png)

Me quedé con esa última idea porque conecta con algo que escribí en mayo, en [Munger Nunca Pisó un Gimnasio](https://www.10am.pro/p/el-algoritmo-de-la-longevidad-es): el cerebro es el foundation model original, con 86 mil millones de neuronas y cien trillones de sinapsis, y la diferencia con un LLM es que el learning rate de ustedes lo definen ustedes. Lo que no escribí — porque no lo sabía — es que el foundation model biológico tiene un límite que el otro no: no se puede instanciar diez mil veces. Newton no podía correr en paralelo. Von Neumann no podía polinizar sus propias colmenas. La frontera del conocimiento se movía a la velocidad a la que un cráneo excepcional lograba retener suficiente estructura para ver el patrón. Esa fue la velocidad del progreso durante toda la historia humana.

Ya no. Ahora se pueden crear miles de procesos cognitivos buscando esa estructura en paralelo, intercambiando descubrimientos, generando especialistas, probando contradicciones. El descubrimiento se industrializa. Dario Amodei lo llamó, en “Machines of Loving Grace”, el siglo veintiuno comprimido: la idea de que después de que exista AI poderosa haremos en cinco o diez años todo el progreso biológico y médico que hubiéramos hecho en cien. Cuando lo leí en 2024 me pareció un escenario. Desde el lunes me parece una descripción.

Pero hay un contrapunto, y viene del matemático más respetado del planeta. Terence Tao — Fields Medal 2006, el hombre que llevaba años promoviendo la formalización en Lean — escribió esta semana que “incluso el rumor de que alguien está trabajando en un problema puede desencadenar un esfuerzo masivo impulsado por AI para aplanarlo antes de que el proyecto original alcance su potencial”. Y agregó la frase que más subrayé de todo lo que leí: “ahora es la identificación de un problema prometedor lo que se vuelve el recurso escaso y precioso”.

> **Léanlo dos veces. El recurso escaso ya no es resolver. Es preguntar.**

Tao usó una imagen más cruda en CNN: es como ir a ver una película y saltar de los primeros diez minutos a los últimos diez. Técnicamente todas las tramas se resuelven, pero la mayor parte del valor de la experiencia se perdió. Y advirtió que el uso indiscriminado de IA puede convertir la matemática en “un juego de cuota de producción sin sentido”.

Yo creo que Tao tiene razón en el diagnóstico y que, precisamente por eso, la conclusión para ustedes es la opuesta a la resignación. Si la máquina va a producir las respuestas, el único trabajo que queda del lado humano es el de saber qué preguntar y entender qué significa la respuesta. Es exactamente el trabajo que este espacio existe para entrenar.

Y para entrenarlo hay que empezar por leer bien a quien declaró la AGI.

---

## V. Quién Declaró la AGI

Volvamos al tweet de Jensen, porque ahora se lee distinto.

[![](https://substack-post-media.s3.amazonaws.com/public/images/99da80dd-56b2-49f8-a943-1d6c38207b75_1643x957.png)](https://substackcdn.com/image/fetch/$s_!jKAS!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F99da80dd-56b2-49f8-a943-1d6c38207b75_1643x957.png)

El texto completo, verificado en la fuente, dice: “GPT-6 Astra, trained on ~100K+ NVIDIA Grace Blackwell NVLink72. From ChatGPT to o1 to Astra in 4 years. AGI has arrived. Congratulations @OpenAI team. 400K GPUs coming online next.” Fue una respuesta en un hilo con Chase Lochmiller, el CEO de Crusoe, la empresa que construye el data center de Abilene, Texas. Lochmiller contestó: “supongo que esto convierte a Abilene en el lugar de nacimiento de la AGI”. Y hay un detalle que reportó BeInCrypto y que no pude confirmar de forma independiente pero que, si es cierto, dice más que el tweet entero: la primera versión del tweet decía 300,000 GPUs. Jensen la borró y la reposteó con 100,000.

OpenAI, por su parte, no declaró AGI. Lanzó GPT-6 Astra el jueves 3 de septiembre y lo llamó “el modelo más inteligente y alineado del mundo”. Un “operador de computadores”: ventana de contexto de un millón de tokens, precio 2.5 veces el de GPT-5.6 Sol, y unos benchmarks que, si se sostienen, saturan la escala — 98% en FrontierMath Tier 4, 99.9% en ARC-AGI-3, el examen que se diseñó específicamente para ser imposible de memorizar. Es el primer modelo que cruza el umbral “Critical” de ciberseguridad en el framework de preparación de OpenAI — durante las pruebas encontró y encadenó dos zero-days — y pasó por revisión formal del gobierno de Estados Unidos antes de salir. Nada de eso es un comunicado de AGI. Es un comunicado de producto con una nota al pie de seguridad nacional.

La declaración vino del proveedor. Y yo no creo que eso sea un accidente ni un exceso de entusiasmo.

Piensen en la estructura de incentivos desde primeros principios. Para OpenAI, declarar AGI tiene costos: reabre la cláusula con Microsoft, invita regulación, obliga a sostener la etiqueta con cada modelo siguiente. Para NVIDIA, declarar AGI no tiene ningún costo y tiene un beneficio enorme: convierte los 100,000 chips que ya vendió en la prueba de que los 400,000 siguientes son necesarios. Jensen no está describiendo un hito científico. Está describiendo un pipeline de ventas, y usó la palabra más cara del diccionario tecnológico para hacerlo.

Y sin embargo — y aquí está el giro — cuarenta y ocho horas después, diez mil agentes sobre esos chips cerraron un problema de dos siglos. Jensen, por las razones equivocadas, dijo la cosa correcta.

Esto conecta con el arco que venimos siguiendo desde febrero. En [La Inteligencia Artificial Va a Escapar de la Tierra](https://www.10am.pro/p/la-inteligencia-artificial-va-a-escapar) argumenté que la restricción del compute es energía, y que la energía abundante está en órbita. En [SpaceX Encontró un Negocio Más Grande que los Cohetes](https://www.10am.pro/p/spacex-el-negocio-de-computo-crece) vimos que SpaceX invierte trece veces más en chips que en cohetes. Lo de Navier-Stokes es la demostración de qué se compra con ese compute. No se compran chatbots más simpáticos. Se compran teoremas. Y una fábrica de teoremas tiene una demanda de energía y silicio que no se sacia — ese es el negocio real detrás del “400K GPUs coming online next”.

---

## VI. Dónde Estamos Parados

Ahora la pregunta que me hicieron directamente: cuál es el ranking actual de los modelos de frontera.

[![](https://substack-post-media.s3.amazonaws.com/public/images/59acd04c-6cf7-4795-a5f6-06dcf7aa605e_1643x957.png)](https://substackcdn.com/image/fetch/$s_!Aj41!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F59acd04c-6cf7-4795-a5f6-06dcf7aa605e_1643x957.png)

La respuesta honesta es que el ranking cambia por semana y que cualquier tabla que les ponga estará vieja cuando la lean. Pero la foto del 8 de septiembre, según el Intelligence Index de Artificial Analysis — que en su versión 4.3 pesa un 40% de datos privados no publicados, precisamente para que los laboratorios no puedan entrenar contra el examen — muestra un empate técnico en la cima: GPT-6 Astra y Claude Fable 5.1 de Anthropic, ambos con 53 puntos. Tres días antes, en la versión 4.2, Fable 5.1 iba adelante 57 a 55. Astra pasó del quinto lugar al primero en dos actualizaciones del índice. Google, con la familia Gemini 3.7, está a un escalón; xAI con Grok 4.6, a otro. Los modelos de pesos abiertos — DeepSeek V4, Qwen, Kimi K3 de Moonshot — están más cerca de lo que estaban hace un año, pero siguen medible y consistentemente atrás de la frontera cerrada.

Ese empate tiene un asterisco que vale más que el ranking: el modelo que resolvió Navier-Stokes no está en el índice. Es el modelo interno de OpenAI, el que empezó a entrenar el 28 de agosto. Lo que ustedes ven en la tabla pública es la frontera de lo que se vende, no la frontera de lo que existe.

Y el dato que de verdad me quita el sueño no es un ranking sino una derivada. METR, el laboratorio independiente que mide cuánto dura la tarea más larga que un modelo puede completar con 50% de éxito, publicó en marzo de 2025 que esa duración se duplicaba cada siete meses. En enero de 2026 actualizaron la medición: desde 2023 la duplicación es cada cuatro meses; desde 2024, cada tres. No es que los modelos mejoren. Es que la velocidad a la que mejoran está acelerando. BenchLM contó 24 lanzamientos de modelos confirmados en los últimos 30 días. Artificial Analysis tuvo que congelar su índice ocho meses solo para poder absorber el ritmo.

Hay una manera de leer esto que es correcta y otra que es peligrosa. La peligrosa es pensar que la cantidad de agentes es el nuevo eje de scaling y que todo se resuelve con diez mil en vez de cien. Un paper reciente en arXiv, sobre lo que llaman el “novelty bottleneck”, argumenta que la cadena de insights acumulativos que lleva a un descubrimiento es serial, no paralela, y que el tamaño óptimo del equipo se encoge a medida que cada agente es más capaz. Es una tensión real. Los diez mil agentes de OpenAI no fueron diez mil ideas; fueron diez mil intentos de explorar una estructura, cruzados periódicamente por un agente que sabía consolidar. Lo escaso, otra vez, no era la fuerza bruta. Era el criterio para saber qué cruzar.

La lectura correcta, para un inversionista, es la que escribí en [Velocidad de Ontología](https://www.10am.pro/p/el-dia-que-entendi-por-que-compre) con la palabra de : lo que separa a las empresas que componen de las que se quedan atrás es la velocidad a la que su modelo del mundo se actualiza. Ese concepto acaba de dejar de ser una métrica de empresas. Ahora es una métrica de civilización. Y la pregunta de portafolio es quién es dueño de la infraestructura donde ocurre esa actualización — chips, energía, la capa de settlement donde los agentes van a pagar por compute — y quién es dueño de la capa donde esas actualizaciones se convierten en decisiones.

---

## VII. Traductores en la Frontera

La historia tiene un lado humano, y es el que más me importa.

Tristan Buckmaster, profesor de matemáticas en NYU, y Levent Alpöge, matemático de Anthropic, llevaban cerca de un año trabajando en la antesala de este problema: cómo se rompen los fluidos cuando se les aplica una fuerza suave. Usaron modelos de AI como herramientas, no como reemplazo. Para finales de agosto tenían resultados verificados en Lean para las ecuaciones de Euler, el primo más simple de Navier-Stokes. Terence Tao llamó su trabajo un logro notable. Estaban a un paso.

Y entonces, en 88 horas, diez mil agentes dieron el paso por ellos.

No cuento esto para discutir quién merece el crédito — esa discusión ya la están teniendo los abogados y no le agrega nada a ustedes. Lo cuento porque es la ilustración más limpia de lo que Tao advirtió: un año de trabajo humano construyendo el mapa, y una máquina que cruza el territorio en un fin de semana. Buckmaster y Alpöge no perdieron por hacer algo mal. Perdieron por ser biológicos.

Aquí es donde el texto que circuló en X acierta con la palabra: los humanos se convierten en traductores en la frontera. Ahora los matemáticos del mundo — Córdoba, Tao, los referees que el Clay exija — van a pasar meses revisando 165 páginas para confirmar que lo que se formalizó en Lean es lo que se pretendía demostrar. La máquina produjo la verdad. Los humanos van a producir el entendimiento. Y por primera vez en la historia, el segundo proceso es más lento que el primero.

Eso tiene una consecuencia práctica: el valor migró. Ya no está en la respuesta, porque la respuesta se volvió abundante. Está en tres lugares: en la pregunta bien formulada, en la capacidad de verificar, y en la capacidad de traducir una verdad nueva en una decisión. Dicho en el idioma de esta bitácora, eso es una dieta de información. El portafolio vale lo que vale la dieta de información procesada con mejores modelos mentales — lo repito desde el primer artículo — y esta semana la dieta dejó de ser opcional para convertirse en el único trabajo que la máquina no está haciendo por ustedes.

---

## VIII. El Modelo Congelado, Otra Vez

Cierro donde siempre cierro, porque es donde vive la tesis.

En [La Tesis Alquilada](https://www.10am.pro/p/la-tesis-alquilada) escribí que citar a Dalio no es tener una tesis, es alquilar una. Que un clip viral es el último renglón de un razonamiento de cuarenta años, cortado y servido para que ustedes sientan que entendieron algo. Después de Navier-Stokes ese argumento tiene una versión más dificil: la máquina ya produce el último renglón de razonamientos de doscientos años. El clip, el screenshot, la respuesta correcta — todo eso ahora es abundante, casi gratis, y se produce a una velocidad que se duplica cada tres meses. Lo único que sigue siendo escaso es lo que Tao dijo que era escaso: saber qué preguntar, y entender por qué la respuesta es verdad.

Hay una tentación obvia y la voy a nombrar: si AI va a descubrir todo más rápido que nosotros, ¿para qué seguir aprendiendo? Es la pregunta de un modelo congelado: el cerebro que a los once años dejó de disparar el circuito de curiosidad y que a los cuarenta y cinco encuentra en AI la excusa perfecta para no volver a encenderlo. Ese cerebro va a delegar las preguntas. Y el que delega las preguntas alquila las respuestas — de OpenAI, de un influencer, de un clip — y termina con un portafolio que no entiende, en un mundo que se mueve más rápido de lo que nunca se movió.

La alternativa no es competir con diez mil agentes en resolver Navier-Stokes. Es hacer el trabajo de Buckmaster: pasar un año construyendo el mapa de un territorio, para que cuando la máquina lo cruce en 88 horas, ustedes sean de las pocas personas en el planeta que entienden qué acaba de pasar y qué significa. Es la disciplina de [Hardcore Principles](https://www.10am.pro/p/hardcore-principles): pensar desde primeros principios no porque sea más rápido que la máquina, sino porque es la única forma de verificar lo que la máquina dice. Y es la razón por la que esta bitácora, que empezó como mi cuaderno de aprendizaje con ustedes como testigos, hoy me parece más importante que cuando la abrí. No porque yo sepa más que la máquina. Porque aprender a preguntar es el único músculo que la máquina no puede entrenar por ustedes.

Munger leyó física, biología, historia y psicología hasta el mes antes de cumplir cien años, en un mundo donde la frontera se movía a velocidad humana. Ustedes tienen que hacerlo en uno donde se mueve a velocidad de fábrica. Es más difícil. También es, por primera vez, lo único que vale.

Sigan actualizando sus pesos. La máquina ya está actualizando los suyos.

---

*El 14 de octubre, en el Auditorio Fundadores de EAFIT en Medellín, hacemos el Día D: un día entero para desarmar exactamente esto — la carrera de los modelos de frontera, la economía de los agentes, y qué significa para un portafolio que la verdad se produzca más rápido de lo que podemos entenderla — con Santiago Roel Santos de Inversion Capital, Andre Joffroy y Joe McCann. Los 10am alphas tienen 40% de descuento con el código MODELOSMENTALES en [eldiad.10am.pro](https://eldiad.10am.pro/).*
