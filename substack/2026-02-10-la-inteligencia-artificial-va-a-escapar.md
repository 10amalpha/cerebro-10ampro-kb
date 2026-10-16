---
title: "La Inteligencia Artificial Va a Escapar de la Tierra"
date: 2026-02-10
url: https://www.10am.pro/p/la-inteligencia-artificial-va-a-escapar
source: substack
paywalled: true
---
> Post exclusivo para suscriptores de 10ampro — suscríbete en https://www.10am.pro/subscribe
> Post original: https://www.10am.pro/p/la-inteligencia-artificial-va-a-escapar

# La Inteligencia Artificial Va a Escapar de la Tierra

[![](https://substack-post-media.s3.amazonaws.com/public/images/97d6bff0-180e-4218-803f-291aa7d7a43d_1536x1024.png)](https://substackcdn.com/image/fetch/$s_!ZX2l!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F97d6bff0-180e-4218-803f-291aa7d7a43d_1536x1024.png)

En algún momento de los próximos 18 meses, alguien en un data center de Texas va a hacer una llamada que no quiere hacer. Va a decir que tiene un millón de GPUs nuevas, recién salidas de AMD o NVIDIA, apiladas en una bodega. Y que no las puede encender. No porque le falte software. No porque le falte talento. Porque le faltan electrones.

Ese momento va a marcar el fin de una era y el comienzo de otra. La era donde la inteligencia artificial se fabrica en la Tierra. Y la era donde se fabrica en el espacio.

Siempre he dicho que sentarse a escuchar un podcast o un earnings call de Elon Musk es básicamente un masterclass civilizacional. Es que el tipo habla de álabes de turbina, escudos térmicos y ontología de redes satelitales con la misma naturalidad con la que un chef habla de la sal.

> En el último que grabó con uno de los hermanos Collison — los fundadores de Stripe — entendí algo que venía armando en mi cabeza hace meses pero no había logrado articular: por qué xAI y SpaceX se van a fusionar, por qué un merger con Tesla no solo es posible sino inevitable a nivel de ingeniería, y cómo tres empresas que el mercado insiste en valorar por separado están construyendo, pieza por pieza, la misma máquina. La más ambiciosa en la historia de la humanidad.

### I. The Wall

Estados Unidos consume medio terawatt de electricidad. Esa cifra lleva décadas prácticamente plana. La capacidad pico instalada supera un terawatt, pero el promedio real ronda la mitad por el ciclo día-noche.

Ahora pensemos en lo que pide un cluster de 330,000 GPUs de última generación. No solo los chips. El networking. Los CPUs de soporte. El almacenamiento. La refrigeración para el peor día del año. El margen de reserva para cuando hay que apagar un generador y hacer mantenimiento. Cuando se suma todo el consumo real a nivel de generación es casi tres veces el consumo nominal del chip. Cada gigawatt de capacidad instalada en data centers equivale a una quinta parte de un punto porcentual de toda la electricidad del país.

Y la producción de chips se duplica cada dos años. La generación eléctrica no.

[![](https://substack-post-media.s3.amazonaws.com/public/images/2081bfab-b7f6-4c59-b24e-3f3ed1de5068_2720x1568.png)](https://substackcdn.com/image/fetch/$s_!ZCGx!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F2081bfab-b7f6-4c59-b24e-3f3ed1de5068_2720x1568.png)

¿Por qué no? Porque las utilities no son startups. Un estudio de interconexión eléctrica tarda un año. Una turbina de gas nueva tiene lista de espera hasta 2030. Y dentro de esa turbina, el cuello de botella real son los álabes del rotor — piezas que solo tres fundiciones en el mundo saben fabricar. Después de la turbina viene el transformador eléctrico, con 12 meses de espera. Después el permiso municipal. Después la conexión a la red. Cada eslabón es un cuello de botella. No es un problema de dinero. Es un problema de física y de tiempo de fabricación.

La curva exponencial de los chips va a chocar contra la línea plana de la generación eléctrica. Y cuando eso pase, la pregunta obvia es: ¿de dónde salen los electrones?

La respuesta está a 550 kilómetros de altura.

### II. El Arbitraje que Nadie Está Viendo

Un panel solar en un techo en Nevada opera al 25% de su capacidad teórica. Se apaga de noche. Las nubes lo bloquean. La atmósfera absorbe un 30% de la energía antes de que llegue a la celda. Necesita vidrio grueso para resistir granizo. Necesita marcos pesados para resistir viento. Necesita baterías para cubrir las horas sin sol.

En el espacio no hay nada de eso. No hay noche, no hay estaciones, no hay nubes, no hay atmósfera. El sol pega directo, las 24 horas, los 365 días. El factor de capacidad salta de 25% a 99%. La eficiencia por panel se multiplica por cinco. Y cuando se elimina el costo de las baterías — que en tierra son el componente más caro del sistema — el factor real se acerca a diez veces.

[![](https://substack-post-media.s3.amazonaws.com/public/images/b2825d0d-b0d1-43ef-a832-c4f0a5bd68b8_2720x1568.png)](https://substackcdn.com/image/fetch/$s_!HhbK!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fb2825d0d-b0d1-43ef-a832-c4f0a5bd68b8_2720x1568.png)

Otro dato de esos que nos encantan por ser [puro first principles thinking](https://open.substack.com/pub/10am/p/first-principles-thinking-el-manual?utm_campaign=post-expanded-share&utm_medium=web): los paneles solares para espacio son más baratos de fabricar que los terrestres. No necesitan vidrio grueso contra granizo. No necesitan marcos pesados contra viento. No necesitan resistir nada porque en órbita no hay clima. Son más livianos, más simples, más baratos. Punto.

La ecuación se reduce a dos variables. En tierra: panel robusto más baterías más terreno más permisos, dividido por un factor de capacidad del 25%. En espacio: panel liviano más costo de lanzamiento, dividido por un factor de capacidad del 99% y cinco veces más sol. La única variable que impide que el espacio gane hoy es el costo de poner un kilo en órbita.

Y ahí entra Starship.

### III. El Tren de Carga

Nada de lo anterior funciona sin un vehículo capaz de mover masa al espacio de forma económica y frecuente. Ese vehículo existe. Se llama Starship. Y es, según su propio equipo, la máquina más compleja jamás construida.

[![](https://substack-post-media.s3.amazonaws.com/public/images/8b681fc2-38c5-482d-97d4-3cbfc93d7464_2668x1344.png)](https://substackcdn.com/image/fetch/$s_!q5OF!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F8b681fc2-38c5-482d-97d4-3cbfc93d7464_2668x1344.png)

No lo es por un margen incremental. Nadie en la historia ha logrado la reutilización orbital completa. Muchas personas brillantes, con presupuestos enormes, lo intentaron y fracasaron. El motor que impulsa Starship — el Raptor 3 — es el motor cohete más avanzado que existe, operando en un régimen donde cualquier error menor produce una explosión catastrófica. En el despegue, Starship genera más de 100 gigawatts de potencia. El 20% de toda la generación eléctrica de Estados Unidos. En un solo instante.

Los números que se proyectan son extraordinarios: 10,000 lanzamientos al año. Un lanzamiento por hora. Con una flota de 20 a 30 naves en rotación, cada una con un ciclo de 30 horas entre despegue y reabastecimiento, la cadencia es alcanzable. Para poner en perspectiva: una décima de terawatt de capacidad de inteligencia artificial en espacio requiere esos 10,000 vuelos anuales. SpaceX ya se está preparando para una cadencia de hasta 30,000.

[![](https://substack-post-media.s3.amazonaws.com/public/images/79db02ff-7ee9-4734-b8d1-b0047fcc05d9_2464x1332.png)](https://substackcdn.com/image/fetch/$s_!3FrQ!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F79db02ff-7ee9-4734-b8d1-b0047fcc05d9_2464x1332.png)

El problema de ingeniería más importante que queda es el escudo térmico reutilizable. Nadie ha construido jamás un escudo que sobreviva múltiples reentradas orbitales sin mantenimiento extensivo. Las pastillas de freno de un auto también son consumibles, pero duran decenas de miles de kilómetros. El escudo de Starship necesita alcanzar esa misma durabilidad. Sin eso, cada nave requiere la inspección de 40,000 placas entre vuelos, y la cadencia se colapsa.

Pero la trayectoria dice que va a funcionar. Y si funciona, SpaceX se convierte en algo sin precedente en la historia: una empresa que lanza cada año más capacidad de inteligencia artificial al espacio que todo lo que existe acumulado en la Tierra.

Un dato contraintuitivo ilustra la filosofía que hace esto posible. Starship fue diseñado originalmente en fibra de carbono. Liviano, sexy, high-tech. Pero alguien hizo la cuenta completa. A temperaturas criogénicas — y tanto el metano líquido como el oxígeno líquido son criogénicos — el acero inoxidable 300 endurecido (el mismo del cybertruck) por deformación alcanza una relación resistencia-peso comparable a la fibra de carbono. A un costo 50 veces menor. Se puede soldar al aire libre. Se puede modificar en el campo. Y su punto de fusión es el doble que el del aluminio, lo que permite reducir a la mitad el escudo térmico de un lado y eliminarlo completamente del otro.

[![](https://substack-post-media.s3.amazonaws.com/public/images/c895ce34-005c-496e-a621-941d6ada90b7_2464x1310.png)](https://substackcdn.com/image/fetch/$s_!3lSH!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fc895ce34-005c-496e-a621-941d6ada90b7_2464x1310.png)

El cohete de acero pesa menos que el de fibra de carbono. Una conclusión que solo aparece cuando analizas el sistema completo desde primeros principios y no desde la analogía convencional de que liviano significa fibra de carbono.

Eso es ingeniería. Y eso es lo que va a determinar quién fabrica el token más barato.

### IV. Dos Patentes que Muestran Equipos Ingenieria Trabajando Juntos

(sigo una cuenta en X dedicada nada mas a track patentes de Tesla, SpaceX y xAI)

A principios de 2026, mientras Wall Street debatía cuánto valdría una fusión entre SpaceX y xAI, algo mucho más revelador estaba ocurriendo en la oficina de patentes de Estados Unidos. Y pasó completamente desapercibido.

El 4 de diciembre de 2025, Tesla publicó la patente US20250368267A1. Describe un techo de vehículo fabricado en polímero transparente a radiofrecuencias — policarbonato, ABS o ASA — que reemplaza el metal convencional. Dentro de ese techo, integrado como componente estructural, va un hub de comunicaciones completo: antena satelital apuntando al cielo, antena LTE apuntando al horizonte, Bluetooth, procesadores, micrófonos. No es un techo con una antena encima. Es una antena que también funciona como techo.

Ocho semanas después, el 3 de febrero de 2026, SpaceX recibió la patente US12542605B1. Resuelve el problema más difícil de las comunicaciones satelitales en órbita baja: el handoff a 27,000 kilómetros por hora.

[![](https://substack-post-media.s3.amazonaws.com/public/images/e74cb93a-8849-433b-8098-8741f0018917_2720x1568.png)](https://substackcdn.com/image/fetch/$s_!VLcF!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fe74cb93a-8849-433b-8098-8741f0018917_2720x1568.png)

Los satélites Starlink orbitan a 550 kilómetros y completan una vuelta a la Tierra cada 95 minutos. Para un teléfono normal, conectarse a un satélite LEO es como intentar mantener una llamada mientras la torre celular se mueve a velocidad de avión supersónico. Cada cambio de satélite genera una actualización de red. Multiplica eso por millones de dispositivos y el resultado es un colapso de señalización.

La solución de SpaceX es elegante. En lugar de que el dispositivo rastree al satélite, el satélite pretende ser la zona geográfica. SpaceX divide la superficie terrestre en sub-áreas fijas, cada una con un código virtual permanente. Cuando un satélite pasa sobre una zona, sus haces se mapean dinámicamente al código de esa zona. El satélite cambia. El haz se desplaza. Pero el código que ve el dispositivo permanece idéntico. Desde la perspectiva del teléfono, o del automóvil, la red nunca se movió.

Y aquí está la parte que importa: las dos patentes se diseñaron en paralelo, se publicaron con semanas de diferencia, y encajan sin una sola pieza redundante. Tesla abre el vehículo al cielo reemplazando el metal que bloquea señales. SpaceX hace que la constelación sea compatible con cualquier dispositivo LTE estándar, sin modificar hardware ni software. La patente de SpaceX lo dice explícitamente: el sistema funciona con “cualquier dispositivo capaz de comunicarse con una torre celular terrestre”, incluyendo “un teléfono móvil comercial”.

El módem que ya existe dentro de cada Tesla es exactamente eso: un dispositivo LTE estándar. Hoy opera a través de AT&T. Mañana, con el techo de polímero y la capa de virtualización de SpaceX, ese mismo módem habla directo con Starlink. Sin intermediarios. Sin carriers.

La implicación inmediata: cada Tesla vendido se convierte en un suscriptor de Starlink a $9.99 al mes. Con más de 10 millones de vehículos en la flota global, eso son $1.2B de dólares en revenue recurrente anual que hoy van a AT&T y mañana van a SpaceX. Pero el revenue es lo de menos. Un Tesla estacionado, con techo transparente a radiofrecuencias y antena apuntando al cielo, es el cliente ideal de una constelación LEO: estacionario, con línea de vista limpia, conectado 24 horas. SpaceX ya está instalando terminales Starlink en los Superchargers de Tesla.

Los ingenieros que diseñaron el techo de Tesla sabían exactamente qué frecuencias necesitaba la capa de virtualización de SpaceX. Porque son, en la práctica, el mismo equipo resolviendo el mismo problema desde dos entidades legales distintas.

Las patentes no son “coincidencia”

## V. Por Qué las Tres Empresas Necesitan Ser Una Sola

SpaceX necesita inteligencia artificial para tres cosas que no puede hacer solo: optimizar Starlink en tiempo real — routing dinámico de haces entre millones de usuarios —, procesar la telemetría de Starship para acelerar la cadencia de lanzamiento, y eventualmente operar data centers orbitales. xAI tiene los modelos, el talento, y Colossus para entrenamiento a escala. Pero xAI no tiene chips propios, no tiene manufactura, no tiene la mayor fuente de datos de mundo real del planeta, y no tiene acceso al espacio. Tesla tiene los datos, los robots, las baterías, los paneles solares y el chip de inferencia. Pero no tiene modelos de frontera ni logística orbital.

[![](https://substack-post-media.s3.amazonaws.com/public/images/011ab9a3-1bef-4e59-b790-2eadcc11e790_2720x1568.png)](https://substackcdn.com/image/fetch/$s_!UOTN!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F011ab9a3-1bef-4e59-b790-2eadcc11e790_2720x1568.png)

Operando como tres empresas separadas, cada transferencia de tecnología requiere contratos, aprobaciones de junta, negociaciones de propiedad intelectual, due diligence. Fricción. Y esta carrera no tolera fricción. Cuando el ciclo de iteración de Starship es de 30 horas y el ciclo de entrenamiento de un modelo de frontera es de semanas, la diferencia entre un email entre compañías y un canal de Slack interno puede ser la diferencia entre llegar primero y llegar segundo.

La fusión SpaceX-xAI por un valor de $1.25T, resuelve lo urgente: unificar la inteligencia con la logística orbital. El modelo necesita compute. El compute necesita energía. La energía más barata está en el espacio. El espacio necesita Starship. Todo eso bajo un mismo techo elimina meses de negociación en cada decisión técnica.

La fusión con Tesla es más compleja — empresa pública, accionistas minoritarios, reguladores — pero la convergencia de ingeniería ya es un hecho consumado. Las patentes lo demuestran. Los Superchargers con Starlink lo demuestran. El chip AI5 de Tesla ejecutando modelos de xAI lo demuestra. FSD entrenado en infraestructura xAI lo demuestra. Optimus controlado por Grok lo demuestra.

Lo que Wall Street interpreta como tres compañías con un accionista común, los equipos de ingeniería lo viven como un solo proyecto con tres nóminas diferentes.

### VI. La Mano

De todos los problemas de ingeniería en esta historia, hay uno que revela por qué la ingeniería importa más que cualquier algoritmo.

Los tres desafíos de los robots humanoides son: inteligencia de mundo real, la mano, y manufactura a escala. De los tres, la mano es más difícil que los otros dos combinados.

La mano humana tiene una densidad de grados de libertad, sensibilidad táctil y rango de movimiento que no existe en ningún catálogo de componentes mecánicos. A ningún precio. No hay proveedor. No hay estándar. Hay que diseñar desde cero cada motor, cada engranaje, cada circuito de potencia, cada sensor, cada algoritmo de control. Ninguna empresa en el mundo — incluyendo las docenas de startups chinas de robótica humanoide — ha demostrado una mano con los grados de libertad completos de la mano humana. Este problema no se resuelve con más datos de entrenamiento ni con modelos más grandes. Se resuelve con diseño mecánico desde primeros principios, iteración obsesiva y manufactura de precisión.

[![](https://substack-post-media.s3.amazonaws.com/public/images/4dbbd724-2e8f-4812-88ec-3716fdfdc6af_2720x1568.png)](https://substackcdn.com/image/fetch/$s_!Z2Gj!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F4dbbd724-2e8f-4812-88ec-3716fdfdc6af_2720x1568.png)

Pero hay una conexión que pocas personas ven. La inteligencia que Tesla desarrolló para conducción autónoma transfiere directamente al robot. Ambos sistemas son fundamentalmente lo mismo: video de entrada a 1.5 gigabytes por segundo, compresión masiva en múltiples etapas donde hay que ignorar lo irrelevante y priorizar lo crítico, y comandos de control como salida a 2 kilobytes por segundo. Fotones de entrada, control motor de salida. La misma arquitectura de compresión-correlación. El robot simplemente tiene más grados de libertad que el automóvil.

Y cuando el robot puede operar 24/7 en una línea de ensamblaje, la recursividad cambia todo: robots que fabrican robots. Cada unidad nueva acelera la producción de la siguiente. No es una exponencial simple. Es una exponencial que se alimenta a sí misma. El interés compuesto aplicado a la manufactura.

Optimus Gen 3 está diseñado para producción de un millón de unidades al año. Gen 4 escalaría a diez millones. La fase inicial es agonizantemente lenta porque cada componente es diseño personalizado — no existe cadena de suministro previa. Pero una vez que la curva despega, el techo es astronómico.

### VII. MacroHard = Digital Optimus

Todo lo anterior — la energía orbital, los lanzamientos masivos, los robots, las fábricas de chips — converge en un producto: The Human Digital Twin “MacroHard”

Las compañías más valiosas del mundo producen output digital. Nvidia envía archivos por FTP a Taiwán para que fabriquen sus chips. Apple envía diseños a China. Microsoft no manufactura nada. Meta, Google, Alphabet — todo es digital. Si se puedes emular a un humano operando una computadora — cualquier aplicación, cualquier flujo, correos, diseño de chips en Cadence y Synopsys, código, servicio al cliente — tienes acceso instantáneo a billones de dólares en mercado direccionable.

[![](https://substack-post-media.s3.amazonaws.com/public/images/d5fdb230-7df2-4b3b-8297-fc289230f29b_1968x1072.png)](https://substackcdn.com/image/fetch/$s_!ZdLZ!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fd5fdb230-7df2-4b3b-8297-fc289230f29b_1968x1072.png)

Solo el servicio al cliente — un trabajo que realizan personas de inteligencia promedio usando aplicaciones que ya existen — representa cerca de un punto porcentual de la economía mundial. Un billón de dólares en gasto. Y no requiere integración con APIs corporativas. Solo necesita que la inteligencia artificial pueda operar el mismo software que ya usa la empresa de outsourcing.

La estrategia declarada es empezar por lo más simple y escalar. Servicio al cliente primero. Tareas administrativas después. Diseño de chips. CAD mecánico. Cada nivel desbloquea más revenue y más datos de entrenamiento. El revenue actual de las compañías de AI — $20B OpenAI, $15BAnthropic, $1B xAI — es un error de redondeo frente al mercado real.

> El mercado no es vender suscripciones a chatbots. El mercado es reemplazar toda tarea cognitiva que un humano hace frente a una pantalla.

### VIII. El Horizonte

La Tierra recibe aproximadamente la mitad de una billonésima de la energía del Sol. Si capturara una millonésima — apenas el doble de lo que nos llega — tendría 100,000 veces más electricidad que toda la generación actual de la civilización humana.

Lanzando desde la Tierra con Starship se puede alcanzar un terawatt por año de capacidad AI en espacio antes de encontrar limitaciones de combustible. Más allá de eso, la solución es un driver de masa en la Luna. El suelo lunar tiene 20% de silicio y abundante aluminio. Se puede minar el silicio, fabricar celdas solares en la Luna, y lanzar satélites AI al espacio profundo a 2.5 kilómetros por segundo usando aceleración electromagnética. Sin combustible. Con esa arquitectura, un petawatt al año es alcanzable.

[![](https://substack-post-media.s3.amazonaws.com/public/images/01eaf5df-94d4-4fbc-8ddc-b7b323cdfbdc_2472x1286.png)](https://substackcdn.com/image/fetch/$s_!cq-J!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F01eaf5df-94d4-4fbc-8ddc-b7b323cdfbdc_2472x1286.png)

Estos son los números que se discuten en las revisiones de ingeniería semanales en Starbase. No son ciencia ficción. Son problemas de ingeniería con soluciones identificables, cronogramas estimables y dependencias mapeables.

La predicción concreta: en cinco años, la capacidad de AI lanzada al espacio cada año superará la totalidad de capacidad AI acumulada en la Tierra. Y escalando.

No existe ningún camino basado exclusivamente en infraestructura terrestre que alcance estas cifras. No con las turbinas vendidas hasta 2030. No con los transformadores con 12 meses de espera que ademas ([Tesla le compra a una empresa en Pereira](https://www.magnetron.com.co/es/)). No con los permisos que toman años. No con las utilities que operan a velocidad gubernamental.

### IX. Ingeniería

Las diferencias entre los modelos de AI de las distintas compañías son menores que la diferencia temporal. Todos están mucho más adelante que hace 24 meses. Las ideas fluyen entre empresas con los empleados que rotan. Es raro ver más de seis meses de ventaja sostenible en algoritmos.

Si todos van a converger en capacidades similares de software, ¿qué determina quién gana?

Quién puede encender más chips, antes. Quién resuelve los cuellos de botella de álabes de turbina, transformadores eléctricos, permisos, refrigeración, y eventualmente acceso al espacio.

Eso no es un problema de investigación. Es un problema de ingeniería.

La distinción importa. Un laboratorio investiga. Una corporación ejecuta. Las empresas de AI que se autodenominan “labs” son corporaciones maximizadoras de revenue. La vasta mayoría de lo que se hará en el futuro es ingeniería, no descubrimiento de nuevos algoritmos. Una vez que comprendes las leyes fundamentales de la física — y no son tantas — todo lo demás es ingeniería.

La filosofía de gestión que emerge de esta realidad es también de ingeniería: identificar el factor limitante, aplicar urgencia, establecer deadlines agresivos pero no imposibles, y revisar cada semana si se está convergiendo hacia la solución. Sin presentaciones bonitas. Sin adulaciones. Solo la pregunta: ¿estamos convergiendo o no?

[![La línea temporal de xAI: De la adquisición de Twitter por $44B en 2022 a una valoración de $230B en enero 2026. Consolidación a velocidad sin precedentes.](https://substack-post-media.s3.amazonaws.com/public/images/401d10e7-559e-4e14-86e3-92bac884befa_1552x1010.png "La línea temporal de xAI: De la adquisición de Twitter por $44B en 2022 a una valoración de $230B en enero 2026. Consolidación a velocidad sin precedentes.")](https://substackcdn.com/image/fetch/$s_!PFBX!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F401d10e7-559e-4e14-86e3-92bac884befa_1552x1010.png)

El futuro de la inteligencia artificial no se decide en un paper académico ni en un benchmark. Se decide en una fundición de “turbine blades and vanes”, en una línea de ensamblaje de robots humanoides, en un launch pad en la costa del Golfo de México, y eventualmente, en una planta de procesamiento de regolito lunar.

La ingeniería es el factor limitante. Y quien resuelve el factor limitante, gana.

No dejen de ver el podcast con Elon
