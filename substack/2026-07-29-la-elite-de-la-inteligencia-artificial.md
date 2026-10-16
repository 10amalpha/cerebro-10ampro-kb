---
title: "La élite de la inteligencia artificial: cinco trayectorias que están reescribiendo el siglo XXI"
date: 2026-07-29
url: https://www.10am.pro/p/la-elite-de-la-inteligencia-artificial
source: substack
paywalled: true
---
> Post exclusivo para suscriptores de 10ampro — suscríbete en https://www.10am.pro/subscribe
> Post original: https://www.10am.pro/p/la-elite-de-la-inteligencia-artificial

# La élite de la inteligencia artificial: cinco trayectorias que están reescribiendo el siglo XXI

[![](https://substack-post-media.s3.amazonaws.com/public/images/c07ecfba-b61f-4432-9bee-2b94073c44df_2528x1686.jpeg)](https://substackcdn.com/image/fetch/$s_!ndRo!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fc07ecfba-b61f-4432-9bee-2b94073c44df_2528x1686.jpeg)

Uno huyó de la física teórica tras la muerte de su padre. Otro dejó Stanford porque el póker le enseñaba más sobre decisiones bajo incertidumbre que un salón de clases. Otro liquidó su primera empresa de videojuegos para irse a estudiar el hipocampo humano. Otro no pasó el examen que quería y terminó fundando el motor de búsqueda que hoy le compite a Google. Y el último se hizo millonario vendiendo un visor de PDF, se retiró tres años, y volvió para acuñar sin querer el término que define cómo se escribe software hoy: “vibe coding”.

No son los únicos nombres relevantes de esta industria, pero entre los cinco cubren casi todo el espectro de cómo se construye poder en la IA de 2026: la ciencia dura que produce los avances (Amodei, Hassabis), el capital y la gobernanza que los escalan (Altman), la disrupción de un mercado ya maduro (Srinivas) y la reinvención de cómo se escribe código (Steinberger). Ninguno tenía un plan maestro desde el día uno. Y esa es la parte útil de mirarlos de cerca: la IA que hoy parece inevitable fue, en cada caso, una serie de apuestas tomadas con información incompleta.

Este es un análisis que he intentado desarrollar con la información disponible. Sin embargo, se trata de **un documento vivo**. Si durante la lectura encuentras datos más precisos, actualizados o mejor validados, te agradecería que los compartieras para poder ajustarlo y enriquecerlo. El objetivo es que este texto sea de verdadero valor para todos los que estamos interesados en conocer con mayor profundidad a las personas que están impulsando el desarrollo de esta tecnología tan extraordinaria.

### Dario Amodei: la ciencia de la escala y la obsesión con la seguridad

[![](https://substack-post-media.s3.amazonaws.com/public/images/aef099a0-dedb-4b6b-8078-250590e0abe9_2528x1684.jpeg)](https://substackcdn.com/image/fetch/$s_!ilBW!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Faef099a0-dedb-4b6b-8078-250590e0abe9_2528x1684.jpeg)

Amodei nació en 1983 en San Francisco. Su papá era un inmigrante italiano, artesano del cuero, de la Toscana; su mamá gestionaba proyectos para bibliotecas en Berkeley. Desde chico fue matemáticas y física puras —a los 17 ya competía en la Olimpiada de Física de Estados Unidos—. Su hermana menor, Daniela, nacida en 1987, terminaría siendo su socia de vida en el proyecto que hoy dirigen juntos.

La trayectoria dio un giro brusco a mediados de los 2000. Empezó en Caltech, se graduó en Física en Stanford en 2006, y ese mismo año murió su padre tras una enfermedad rara y prolongada. Ese golpe le cambió el rumbo completo: en Princeton, Amodei abandonó la física teórica y se metió de lleno en biología y electrofisiología de redes neuronales. Estaba convencido de que la medicina convencional no resolvía con suficiente rapidez enfermedades como la que se llevó a su papá. Su tesis sobre procesamiento visual en la retina ganó el Premio Hertz dos años seguidos. Después hizo un postdoctorado en Stanford aplicando espectrometría de masas a biomarcadores de cáncer.

Entró a la industria en 2014, en Baidu, co-liderando un sistema de reconocimiento de voz que el MIT Technology Review calificó como tecnología disruptiva. Pasó brevemente por Google Brain y en 2016 llegó a OpenAI, donde para 2018 ya era vicepresidente de Investigación. Ahí coordinó GPT-2 y GPT-3, co-desarrolló el RLHF —la técnica que le enseña a un modelo de lenguaje a comportarse— y formuló matemáticamente las *scaling laws*: la idea de que el error de un modelo baja de forma predecible según cuánto cómputo, datos y tamaño le metas. Esa sola ecuación justificó cientos de millones de dólares en infraestructura dentro de OpenAI.

A finales de 2020 hubo desacuerdos sobre el rumbo comercial de la empresa, y Amodei se fue con Daniela y un grupo de investigadores clave a fundar Anthropic en 2021, bajo una estructura legal de Corporación de Beneficio Público —**que obliga a la empresa a pesar el interés público, no solo el retorno a accionistas**—. **Ahí desarrollaron la “IA Constitucional” y construyeron los modelos Claude con la seguridad y la interpretabilidad como prioridad explícita, no como nota al pie.**

El crecimiento desde entonces ha sido brutal. Para que tengas el dato: Anthropic cerró en septiembre de 2025 una Serie F de 13.000 millones a una valoración de 183.000 millones. Cinco meses después, Serie G a 380.000 millones. Y para junio de 2026, presentó de forma confidencial su salida a bolsa a una valoración de 965.000 millones, tras una Serie H de 65.000 millones. Los ingresos anualizados pasaron de 1.000 millones en diciembre de 2024 a 14.000 millones catorce meses después, y a 30.000 millones para marzo de 2026 —con un *run rate* de 45.000 millones hasta mayo, superando a OpenAI en esa métrica puntual—. Claude Code, el producto de programación asistida, pasó de cero a 2.500 millones anualizados en menos de un año.

Lo que más me interesa de Amodei no son las cifras, sino cómo Anthropic gasta plata en cosas que no dan retorno inmediato: **El equipo de interpretabilidad mecanicista** —el que trata de entender literalmente qué pasa dentro de las “neuronas” de un modelo cuando responde algo— es de los más grandes del mundo dedicados solo a esa pregunta. Es una apuesta lenta y cara, pero coherente con su tesis: entender por qué un modelo hace lo que hace es, a largo plazo, ventaja competitiva, no solo ética de escaparate.

En enero de 2026 publicó su ensayo *The Adolescence of Technology*, que pegó más fuerte que el anterior. Ahí clasifica los riesgos de la IA avanzada en cinco categorías —desalineación, bioterrorismo, totalitarismo, disrupción económica y desestabilización— y predice que hasta el 50% de los empleos administrativos de nivel inicial podrían desaparecer en uno a cinco años. (Vale la pena aclarar algo que el documento original mezclaba: la estrategia de “Entente” —la coalición de democracias usando su ventaja en IA para contener a regímenes autoritarios— no es de este ensayo, sino del anterior, *Machines of Loving Grace*, de octubre de 2024.)

> Ahí hay una lección que aplica más allá del mundo de la IA: la mejor forma de defender una convicción no es repetirla en un discurso, es meterla en los estatutos. Cualquier empresa puede decir que le importa la seguridad; muy pocas aceptan que esa prioridad les cueste velocidad de verdad frente a la competencia.

De los cinco, Amodei **es el único con un doctorado completo en neurociencia experimental, y se nota**: Convierte pérdida personal en rigor institucional de una manera que ninguno de sus pares replica. La muerte del papá lo llevó a la biología; la salida de OpenAI lo llevó a construir una empresa cuya estructura legal lo obliga a priorizar seguridad sobre velocidad. Es el que más ha logrado convertir una convicción filosófica en arquitectura corporativa real.

---

### Sam Altman: capital, narrativa y gobernanza bajo presión

[![](https://substack-post-media.s3.amazonaws.com/public/images/52099eea-2a28-4bf9-a9f6-3a847fc6fceb_2048x2048.jpeg)](https://substackcdn.com/image/fetch/$s_!Jh2e!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F52099eea-2a28-4bf9-a9f6-3a847fc6fceb_2048x2048.jpeg)

Altman nació el 22 de abril de 1985 en Chicago, en una familia judía que se mudó a Missouri en 1989. Mamá dermatóloga, papá agente inmobiliario. Es el mayor de cuatro hermanos. A los ocho años le regalaron una Macintosh y ahí aprendió a programar y a desarmar hardware. A los 17, en su colegio, hizo pública su homosexualidad y promovió carteles de “Espacio Seguro” —una muestra temprana de que este hombre siempre estuvo dispuesto a meterse a cambiar el entorno, mucho antes de que eso significaba dirigir la empresa de IA más valiosa del planeta.

Entró a Stanford en 2003 a estudiar Ciencias de la Computación y **se salió dos años después, convencido de que las partidas de póker con sus compañeros le enseñaban más sobre decisiones con información imperfecta que las clases**. A los 19 cofundó Loopt, una app de geolocalización financiada en el primer lote de Y Combinator. Nunca tuvo tracción real y se vendió en 2012 por 43,4 millones de dólares. Con ese dinero montó, junto a su hermano, la firma de inversión Hydrazine. **Paul Graham vio en él algo que valía la pena apostar y lo puso al frente de Y Combinator en 2014**.

Ahí, entre 2014 y 2019, financió a más de 5.000 empresas —Airbnb, Stripe, Reddit, DoorDash, Instacart— y su portafolio superó los 65.000 millones de valoración para 2015. En paralelo construyó fortuna propia apostándole a cosas de ciencia dura: preside la junta de Helion Energy (fusión nuclear), invirtió en Retro Biosciences (longevidad celular) y co-financió con Peter Thiel una startup de terapia génica.

**En diciembre de 2015 cofundó OpenAI, motivado por el miedo de que Google se quedará con el monopolio de la inteligencia artificial general**. Convencer a gente como Ilya Sutskever y al propio Amodei de sumarse le tomó negociación personal sostenida. En 2019 asumió como CEO de tiempo completo y llevó a OpenAI hacia un modelo híbrido de “ganancia limitada”, necesario para meterle el capital y el cómputo que exige competir en la frontera.

Esa aceleración —y su estilo de negociar— explotó el 17 de noviembre de 2023, cuando la junta lo destituyó alegando que ya “no tenía confianza en su capacidad de liderar” la organización. Microsoft, socio clave, se enteró casi al mismo tiempo que todo el mundo y su acción cayó. La amenaza de renuncia colectiva de casi 800 empleados —básicamente toda la plantilla— y la presión de Microsoft lo devolvieron al cargo cinco días después, con junta nueva de arranque.

Ese episodio no fue un accidente aislado. Es la manifestación más visible de una tensión que atraviesa toda su carrera y, de hecho, buena parte de la gobernanza de la industria hoy: la misión fundacional de “beneficiar a toda la humanidad” contra la necesidad de levantar cientos de miles de millones de dólares para seguir compitiendo. Es la misma tensión que llevó a Amodei a irse dos años antes. Altman, a diferencia de Amodei, la resolvió quedándose adentro y renegociando desde el poder: OpenAI completó su transición hacia una estructura con fines de lucro más convencional, con la fundación original como accionista. Sus críticos lo ven como una dilución progresiva del compromiso inicial.

En lo personal, se casó el 10 de enero de 2024 en Hawái con Oliver Mulherin, ingeniero de software australiano al que conoció, según cuenta él mismo, “e**n el jacuzzi de Peter Thiel a las tres de la mañana**” en 2015. Tuvieron su primer hijo por gestación subrogada en febrero de 2025.

Vale la pena notar el contraste con Amodei: los dos enfrentaron la misma tensión —misión versus capital— y la resolvieron de manera opuesta. Uno se fue y fundó algo nuevo con una estructura legal que lo blindara. El otro se quedó, peleó por el control y renegoció las reglas desde adentro. Ninguna de las dos rutas es obviamente la correcta; son, simplemente, dos formas distintas de responder a la misma pregunta sobre quién manda cuando la plata y la misión empiezan a chocar.

> Lo distintivo de Altman en este grupo no es su formación técnica —**es el único que no terminó una carrera**— sino su dominio del capital y de la narrativa. Mientras Amodei formalizaba leyes de escalado y Hassabis resolvía el plegamiento de proteínas, Altman armó la maquinaria de financiamiento, reclutamiento y gobernanza que permitió que esas ideas se volvieran productos usados por cientos de millones de personas. Entendió, antes que casi nadie, que esta carrera no se gana solo en el laboratorio: se gana también en la sala de juntas.

---

### Demis Hassabis: del ajedrez y la neurociencia al Nobel

[![](https://substack-post-media.s3.amazonaws.com/public/images/2d45b772-d645-4963-93dc-0a682d1718a5_2048x2048.jpeg)](https://substackcdn.com/image/fetch/$s_!82IO!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F2d45b772-d645-4963-93dc-0a682d1718a5_2048x2048.jpeg)

Hassabis nació en Londres el 27 de julio de 1976, el mayor de tres hermanos de ascendencia grecochipriota y singapurense. **Aprendió ajedrez a los cuatro años y a los 13 ya era Maestro de Ajedrez con Elo 2300**, capitaneando las selecciones juveniles de Inglaterra. Con las ganancias de los torneos se compró su primera computadora, una ZX Spectrum, en la que aprendió a programar solo, con manuales técnicos, y diseñó su primer sistema de IA —basado en el juego Reversi— en una Commodore Amiga.

Terminó el colegio dos años antes de lo normal, a los 16, y Cambridge le pidió tomar un año sabático por su edad. Lo aprovechó para unirse a Bullfrog Productions, donde co-diseñó *Theme Park* (1994), un videojuego que fue un éxito comercial real. En 1997 se graduó con doble Primera Clase en Ciencias de la Computación en Cambridge, capitaneando el equipo de ajedrez tres años seguidos. Después fundó Elixir Studios en 1998, y entre 1998 y 2003 se coronó cinco veces campeón mundial del Pentamind, la competencia combinada de juegos mentales.

**En 2005 liquidó su estudio de videojuegos** —rentable, funcionando— para irse a estudiar el cerebro humano. Su apuesta: que la neurociencia cognitiva tenía las claves para construir inteligencia artificial general. Doctorado en UCL en 2009, sobre memoria autobiográfica, imaginación y el hipocampo. Después de estancias postdoctorales en Harvard y MIT, cofundó DeepMind en Londres en 2010 con una misión sin rodeos: “resolver la inteligencia” y aplicar esa solución a los grandes problemas científicos de la humanidad. Google la compró en 2014, la transacción corporativa más grande de la multinacional en Europa hasta ese momento.

**DeepMind, bajo su mando, construyó un modelo de investigación inspirado en la época dorada de los Laboratorios Bell**: Rigor científico con ingeniería a escala industrial. Llegó a la fama mundial en 2016 con AlphaGo, venciendo al campeón Lee Sedol en Go. Pero su aporte más grande fue en ciencias de la vida: AlphaFold resolvió el problema del plegamiento de proteínas, un desafío de más de cincuenta años que consiste en predecir la forma tridimensional de una proteína a partir de su secuencia de aminoácidos.

Vale la pena parar aquí un segundo, porque esto sí es un antes y un después medible. Antes de AlphaFold, determinar la estructura de una sola proteína por cristalografía de rayos X le podía tomar a un laboratorio años de trabajo y cientos de miles de dólares. AlphaFold2 redujo eso, para casi todas las proteínas conocidas, a minutos de cómputo. La base de datos que DeepMind publicó gratis —con las estructuras predichas de prácticamente todas las proteínas catalogadas— hoy es infraestructura básica para desarrollo de fármacos y diseño de enzimas industriales.

> Ese trabajo le ganó el Nobel de Química en 2024, compartido con su colaborador John Jumper y con David Baker (reconocido en la otra mitad del premio). Hassabis sigue dirigiendo Google DeepMind, con una estructura que divide recursos casi 50/50 entre investigación de “cielo azul” y el escalado de modelos comerciales como Gemini.

De los cinco, **es el único que llegó a la IA por la puerta de la ciencia básica**, no de la ingeniería ni de los negocios. **Y es el único con un Nobel que lo respalda**. Su convicción se sostuvo casi treinta años sin desviarse: entender la mente humana era el atajo correcto para construir máquinas inteligentes.

Lo que más rescato de su historia no es el Nobel —eso es la consecuencia, no la causa—. Es que en 2005, con un estudio de videojuegos que funcionaba y generaba plata, decidió cerrarlo para irse a hacer un doctorado sin ninguna certeza de que la neurociencia le sirviera para algo comercial. Esa clase de apuesta, hecha desde una posición cómoda y sin necesidad real de arriesgarse, es la que casi nadie hace.

###### Te recomiendo este documental de Demis en Youtube.

---

### Aravind Srinivas: del examen que no pasó al motor que le compite a Google

[![](https://substack-post-media.s3.amazonaws.com/public/images/f4c1606f-06f9-48fd-8f10-38f6a582e846_2048x2048.jpeg)](https://substackcdn.com/image/fetch/$s_!XVY2!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Ff4c1606f-06f9-48fd-8f10-38f6a582e846_2048x2048.jpeg)

Srinivas nació el 7 de junio de 1994 en Chennai, India. Su mamá, Jayanthi, siempre quiso estudiar en un Instituto Indio de Tecnología (IIT) y no pudo; esa aspiración no cumplida marcó cómo crió a su hijo. Aravind quería estudiar Ciencias de la Computación, pero no alcanzó la nota de corte en el examen nacional JEE y terminó en Ingeniería Eléctrica en el IIT de Madrás. Lo que en su momento se sintió como un fracaso le terminó dando algo mejor: un dominio profundo de teoría de señales y sistemas dinámicos que después le dio ventaja modelando redes neuronales matemáticamente.

Hizo su doctorado en Berkeley (2021), bajo Pieter Abbeel, sobre aprendizaje por refuerzo y representaciones visuales por contraste. De ahí salieron CURL y CPCv2 —este último coescrito con gente de DeepMind— y la arquitectura BoTNet. **Pasó por OpenAI, DeepMind y Google Brain en estancias de investigación.**

**Trabajando como investigador en OpenAI**, identificó un problema concreto: **La forma en que la gente busca información en internet seguía atrapada en el paradigma de indexación de Google, y los modelos de lenguaje grandes tendían a alucinar —inventar cosas con total confianza**—. En agosto de **2022 fundó Perplexity** AI con Denis Yarats, Johnny Ho y Andy Konwinski: un motor de respuesta conversacional basado en veracidad de fuentes y citas verificables.

El crecimiento ha sido una lección de “acción sobre planificación”, como él mismo lo describe. La valoración pasó de 150 millones a comienzos de 2023 a 20.000 millones en septiembre de 2025 —133 veces en menos de tres años— y a 21.210 millones a comienzos de 2026. En julio de 2025 lanzaron Comet, un navegador con IA integrada, primero para el plan más caro y gratis desde octubre. Comet resume, investiga, describe imágenes, redacta correos: le está peleando terreno directo al paradigma de búsqueda que Google definió por veinticinco años.

Eso sí, el crecimiento no ha sido gratis en términos de conflicto. El modelo de negocio de Perplexity —resumir contenido de terceros en vez de simplemente enlazarlo— le ha generado roces serios con editores y medios, que sienten que la plata se está quedando del lado equivocado de la cadena. Srinivas lo ha resuelto por ahora con acuerdos de licenciamiento selectivos, pero no hay todavía un consenso de industria sobre cómo debería funcionar esa relación.

Srinivas es, de los cinco, el que mejor ilustra cómo un fracaso académico puntual —no entrar a la carrera que quería— se puede convertir, años después, en la base técnica de una de las apuestas más serias contra el monopolio de Google. Es también el más joven del grupo y, probablemente, el que opera con el ciclo más corto entre idea y producto en el mercado.

> Hay algo particular en cómo Srinivas construye marca personal: **Casi ningún fundador de este nivel pública tanto contenido técnico propio en redes como él**. Convirtió la costumbre académica de explicar papers en hilos de Twitter/X en una herramienta de distribución de producto, sin pagarle a nadie por eso. Es marketing hecho con la misma lógica de “acción sobre planificación” que aplica en producto: publicar seguido, ver qué resuena, ajustar.

---

### Peter Steinberger: del PDF al “vibe coding”

[![](https://substack-post-media.s3.amazonaws.com/public/images/83c30c9e-6882-41ef-9e7f-2ca1209f92ab_2048x2048.jpeg)](https://substackcdn.com/image/fetch/$s_!-JaA!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F83c30c9e-6882-41ef-9e7f-2ca1209f92ab_2048x2048.jpeg)

Steinberger nació en 1986 en zona rural de Austria. A los 14 años tocó una computadora por primera vez, prestada por un huésped de verano en su casa, y ahí arrancó todo. Estudió informática médica en la Universidad Tecnológica de Viena entre 2004 y 2010, y fue de los primeros en Austria en enseñar desarrollo formal para iOS.

Su primera empresa, PSPDFKit, nació casi de casualidad en 2011. Mientras esperaba su visa de trabajo para irse a San Francisco como ingeniero senior, aprovechó el tiempo libre para construir un motor de PDF de alto rendimiento para iPad. El componente generó más plata que un trabajo de tiempo completo antes de que la visa siquiera se aprobara. Se devolvió a Viena y se dedicó a hacer crecer PSPDFKit con sus cofundadores.

Al contrario de la norma en Silicon Valley, manejó PSPDFKit *bootstrapped* —sin financiamiento externo— **durante trece años, hasta volverla el estándar de la industria para PDFs en apps móviles, usado por más de mil millones de personas**, con clientes como Apple y Dropbox. En octubre de 2021, quemado por lo que él mismo llamó el “*burnout* de gestionar personas”, **aceptó una inversión estratégica de Insight Partners por 116 millones de dólares**. Vale aclarar algo: No fue una venta total. Los fundadores conservaron parte de sus acciones; lo que hicieron fue salirse de sus roles operativos de tiempo completo. Empezó un retiro de tres años.

A finales de 2024 volvió a tocar código, jugando con modelos de lenguaje de frontera para automatizar flujos de trabajo. En mayo de 2025 fundó en Viena Amantus Machina, con la idea de construir “la próxima generación de agentes de IA hiperpersonales”. En noviembre de ese año lanzó Clawdbot, un asistente local capaz de controlar una computadora con lenguaje natural. El proyecto —rebautizado Moltbot brevemente y consolidado en enero de 2026 como OpenClaw— explotó como nunca se había visto en GitHub: 9.000 estrellas en 24 horas, más de 247.000 en menos de tres meses. Le tomó menos tiempo llegar ahí que a React o Linux acumular cifras comparables en años.

La forma en que construyó OpenClaw terminó acuñando el término “vibe coding”: el humano deja de escribir cada línea y pasa a supervisar y diseñar el sistema, mientras agentes de IA coordinados hacen la escritura real del código. Bajo ese enfoque, Steinberger llegó a registrar más de 6.600 *commits* en un solo mes, y defiende sin pena la práctica de “enviar código que no leo”, priorizando velocidad sobre perfección, siempre que existan mecanismos de revisión y autoevaluación que eviten que el agente se salga del carril.

Lo interesante de OpenClaw no es solo la velocidad de adopción, sino lo que revela: un solo desarrollador, sin ronda de financiamiento, sin equipo, le sacó más tracción que proyectos respaldados por las compañías más grandes del mundo. Eso obligó a toda la industria a hacerse una pregunta incómoda: si un agente personal autónomo lo puede construir una sola persona en semanas con herramientas ya disponibles, ¿qué tan defendible es realmente la ventaja de los laboratorios grandes en esa categoría?

El 15 de febrero de 2026, el propio Sam Altman anunció que Steinberger se sumaba a OpenAI a liderar infraestructura de agentes personales, en un *acqui-hire*: contrataron al talento, no compraron el producto. La disputa fue más reñida de lo normal —Meta también hizo oferta, con Zuckerberg escribiéndole personalmente por WhatsApp—. Steinberger se fue con OpenAI por el acceso a modelos de frontera, cómputo y distribución a cientos de millones de usuarios de ChatGPT. Como parte del acuerdo, OpenClaw pasó a una fundación independiente de código abierto bajo licencia MIT, con OpenAI de patrocinador. Ya instalado ahí, no se guardó las críticas al marco regulatorio europeo, que según él hace inviable competir con la infraestructura de Estados Unidos.

> Es, de los cinco, el caso más atípico: sin doctorado, sin ronda histórica, más de una década construyendo software de nicho —literalmente, un visor de PDF— antes de retirarse a los 35. Su relevancia hoy no viene de una teoría, sino de haber demostrado, a escala masiva y frente a toda la industria, que la relación entre humano y código se podía invertir por completo.

Y hay algo casi irónico en el cierre de su historia: **Pasó tres años retirado, aburrido de gestionar personas, y terminó construyendo una herramienta que, en esencia, gestiona agentes en vez de personas**. Cambió un tipo de management por otro, solo que el segundo no se queja, no renuncia y trabaja de noche.

---

### Lo que conecta a los cinco

El ecosistema de IA de hoy funciona con una transferencia constante de metodología científica hacia plataformas corporativas de escalado masivo, y estas cinco trayectorias son la mejor evidencia de eso. Amodei y Hassabis pusieron las bases teóricas —leyes de escala de un lado, interpretación inspirada en neurobiología del otro—. Altman metió el capital que hizo posible validar esas leyes en sistemas cada vez más caros de entrenar. Srinivas convirtió esas capacidades en una herramienta que le pelea el terreno a la indexación que Google dominó por 25 años. Y Steinberger usó esas mismas herramientas para automatizar el propio proceso de escribir software, cerrando un ciclo medio inquietante: la IA diseñando y desplegando sus propias actualizaciones de código, con supervisión humana cada vez más ligera.

Hay un patrón que vale la pena nombrar: **Cuatro de los cinco tuvieron un quiebre biográfico específico antes de meterse de lleno en la IA**. La muerte del papá de Amodei lo mandó de la física a la neurociencia. El examen que Srinivas no pasó lo desvió hacia Ingeniería Eléctrica, y ese rodeo le dio las herramientas matemáticas que usaría después. El *burnout* de Steinberger lo mandó a un retiro del que volvió por accidente. **Hasta Hassabis, con la trayectoria más lineal del grupo, tomó la decisión deliberada de cerrar una empresa rentable para estudiar el cerebro sin ninguna garantía de que eso tuviera aplicación comercial**. Solo Altman es la excepción: su camino, de Loopt a OpenAI, fue una progresión casi sin quiebres de apuestas cada vez más grandes sobre capital y gobernanza.

Y hay algo más que casi nadie menciona: **Estos cinco no compiten en compartimentos separados, se cruzan todo el tiempo**. Amodei reclutó y perdió gente frente a Altman dentro de OpenAI antes de fundar Anthropic. Srinivas pasó por OpenAI y coescribió papers con gente de DeepMind. Steinberger construyó OpenClaw usando en gran parte los modelos Claude de Anthropic, y terminó trabajando para OpenAI, el competidor directo de Anthropic. **La “élite de la IA” no es un conjunto de empresas peleando en silos: es una red densa de personas que se formaron, contrataron y volvieron a cruzar entre sí, casi siempre dentro de las mismas cuatro o cinco instituciones** —Stanford, Berkeley, OpenAI, DeepMind aparecen, en distintas combinaciones, en las cinco biografías.

Esto tiene una implicación práctica que casi nunca se discute: **el talento en esta industria se mueve dentro de una red tan chiquita que las decisiones de una persona** —irse, quedarse, fundar algo nuevo— reconfiguran el mapa competitivo completo casi de inmediato. No es un mercado laboral normal con miles de candidatos intercambiables; es un puñado de personas que se conocen entre sí, y cada movimiento individual mueve miles de millones de dólares en valoración de las empresas involucradas.

---

### Tres cosas que valen la pena quedarse

Ninguno de estos cinco perfiles es una fórmula replicable. Sería ingenuo pensar que basta con perder a un padre, fallar un examen o quemarse gestionando una empresa para terminar liderando un laboratorio de frontera. Pero sí hay patrones que trascienden la anécdota:

La especialización profunda en un dominio aparentemente ajeno a la IA —neurociencia para Amodei y Hassabis, teoría de señales para Srinivas— terminó siendo ventaja competitiva más duradera que la formación genérica en ingeniería de software. Los años que Hassabis pasó estudiando el hipocampo no fueron un desvío: fueron, en retrospectiva, la inversión que le dio una intuición que sus pares sin esa formación no tenían.

Ninguno de los cinco esperó a tener la solución completa antes de moverse. Srinivas lo dice mejor que nadie: “la acción produce información”. Pero el patrón se repite en los cinco: Steinberger lanzó Clawdbot como proyecto de fin de semana sin plan de negocio; Hassabis cerró una empresa rentable para estudiar algo sin garantía comercial; Amodei fundó Anthropic sin certeza de que una estructura de Beneficio Público pudiera competir con laboratorios financiados de forma convencional. En los cinco casos, la convicción llegó antes que la evidencia de que iba a funcionar.

> Y lo más incómodo: el capital y la gobernanza importan tanto como la ciencia. Amodei y Hassabis produjeron avances científicos genuinamente originales, pero ninguno de los dos habría podido escalarlos sin resolver, en algún momento, lo mismo que Altman resolvió mejor que nadie: convencer a inversionistas de meter decenas de miles de millones de dólares en una apuesta cuyo retorno depende de que la tecnología siga mejorando a un ritmo que nadie puede garantizar. La ciencia abre la puerta. El capital decide qué tan grande se construye del otro lado.

---

*¿Estás listo para el Dia D? El [Día D](https://eldiad.10am.pro/) es un día entero desarmando los sistemas operativos cognitivos que de verdad mueven la aguja — no teoría, no inspiración, la mecánica. Los 10am alphas tienen 40% off con el cupón MODELOSMENTALES. Ahí nos vemos.*

[![](https://substack-post-media.s3.amazonaws.com/public/images/a196fd28-9bbf-4e34-9d70-2bcc9fd8c2be_1080x3215.png)](https://luma.com/eldiad?coupon=MODELOSMENTALES)

---

## Fuentes

* [Dario Amodei — Wikipedia](https://en.wikipedia.org/wiki/Dario_Amodei)
* [Dario Amodei — sitio personal](https://darioamodei.com/)
* [The Adolescence of Technology — Dario Amodei](https://darioamodei.com/essay/the-adolescence-of-technology)
* [Machines of Loving Grace — Dario Amodei](https://darioamodei.com/essay/machines-of-loving-grace)
* [Anthropic CEO Dario Amodei warns AI’s “adolescence” — Fortune](https://fortune.com/2026/01/27/anthropic-ceo-dario-amodei-essay-warning-ai-adolescence-test-humanity-risks-remedies/)
* [Anthropic raises $30B Series G at $380B valuation — Anthropic](https://www.anthropic.com/news/anthropic-raises-30-billion-series-g-funding-380-billion-post-money-valuation)
* [Anthropic raises $65B Series H at $965B valuation — Anthropic](https://www.anthropic.com/news/series-h)
* [Anthropic hits $14B in ARR — SaaStr](https://www.saastr.com/anthropic-just-hit-14-billion-in-arr-up-from-1-billion-just-14-months-ago/)
* [Anthropic set to hit $10.9B in revenue Q2 — CNBC](https://www.cnbc.com/2026/05/20/anthropic-revenue-explosive-growth-ipo-profitable-quarter.html)
* [Sam Altman — Wikipedia](https://en.wikipedia.org/wiki/Sam_Altman)
* [Sam Altman — Biography](https://www.biography.com/business-leaders/a65810455/sam-altman)
* [Removal of Sam Altman from OpenAI — Wikipedia](https://en.wikipedia.org/wiki/Removal_of_Sam_Altman_from_OpenAI)
* [OpenAI officially announces Altman’s return — CNN](https://www.cnn.com/2023/11/29/tech/openai-sam-altman-board-microsoft/index.html)
* [Who is Sam Altman’s partner? — Newsweek](https://www.newsweek.com/sam-altman-partner-oliver-mulherin-open-ai-1922107)
* [Sam Altman on parenting — Fortune](https://fortune.com/2025/08/22/sam-altman-parenting-raising-child-better-decisions-humanity/)
* [Demis Hassabis — Academy of Achievement](https://achievement.org/achiever/demis-hassabis-ph-d/)
* [The Nobel Prize in Chemistry 2024 — NobelPrize.org](https://www.nobelprize.org/prizes/chemistry/2024/press-release/)
* [DeepMind’s Hassabis and Jumper win Nobel — TechCrunch](https://techcrunch.com/2024/10/09/deepminds-demis-hassabis-and-john-jumper-scoop-nobel-prize-in-chemistry-for-alphafold/)
* [Demis Hassabis & John Jumper awarded Nobel Prize — Google DeepMind](https://deepmind.google/blog/demis-hassabis-john-jumper-awarded-nobel-prize-in-chemistry/)
* [Aravind Srinivas — Grokipedia](https://grokipedia.com/page/aravind-srinivas)
* [Perplexity AI — Wikipedia](https://en.wikipedia.org/wiki/Perplexity_AI)
* [How Perplexity AI reached $9B valuation — AI Funding Tracker](https://aifundingtracker.com/perplexity-ai-valuation-growth-strategy/)
* [Representation Learning for Perception and Control — eScholarship](https://escholarship.org/content/qt5sn0t1gt/qt5sn0t1gt_noSplash_d65ad256f9d02f7da66f4445b8bc4a7c.pdf)
* [Peter Steinberger (programmer) — Wikipedia](https://en.wikipedia.org/wiki/Peter_Steinberger_(programmer))
* [PSPDFKit announces €100M investment from Insight Partners — Insight Partners](https://www.insightpartners.com/ideas/pspdfkit-announces-e100-million-strategic-investment-from-insight-partners-to-fuel-growth/)
* [The creator of Clawd: “I ship code I don’t read” — Pragmatic Engineer](https://newsletter.pragmaticengineer.com/p/the-creator-of-clawd-i-ship-code)
* [The Story of OpenClaw: From Clawdbot to 250K Stars — OpenClaw MasterClass](https://tenten.co/openclaw/en/blog/openclaw-history)
* [The Lobster That Broke GitHub — N9O](https://n9o.xyz/posts/202602-steipete-openclaw-openai/)
* [OpenAI Acqui-Hires OpenClaw Creator — AIToolsReview](https://aitoolsreview.co.uk/insights/openai-acquihires-openclaw)
* [OpenAI hires OpenClaw founder, transitions project to foundation — DigiTimes](https://www.digitimes.com/news/a20260216VL209/openai-open-source-talent.html)
