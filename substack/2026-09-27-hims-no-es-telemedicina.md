---
title: "HIMS No Es Telemedicina"
date: 2026-09-27
url: https://www.10am.pro/p/hims-no-es-telemedicina
source: substack
paywalled: true
---
> Post exclusivo para suscriptores de 10ampro — suscríbete en https://www.10am.pro/subscribe
> Post original: https://www.10am.pro/p/hims-no-es-telemedicina

# HIMS No Es Telemedicina

[![](https://substack-post-media.s3.amazonaws.com/public/images/5b88a51a-f7ed-4ad9-8d0b-05cae374301d_1642x958.png)](https://substackcdn.com/image/fetch/$s_!bLPu!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F5b88a51a-f7ed-4ad9-8d0b-05cae374301d_1642x958.png)

## I. El Mensaje del Viernes

El viernes pasado, a las 11:59 de la mañana, me llegaron tres mensajes reenviados al chat de 10ampro. Un amigo que vive en Estados Unidos, después del live de la semana pasada, contándome su experiencia con HIMS. Pidió las pastillas de weight loss, le cobraron dos veces $150 de la cuenta, nunca le llegaron, canceló la suscripción y no recibió ni un correo diciendo perdón. La frase textual, con la ortografía y la rabia intactas: muy linda la página, pero les importó un culo mi problema. Y remató con lo que remata todo el mundo: después de esa experiencia no puedo ser objetivo hablando de HIMS.

Le respondí lo que respondo siempre, y que se ha vuelto casi un reflejo en el chat de 10am: las anécdotas no son estadísticas. Pero me quedé pensando, porque ese mensaje es la versión emocional de un argumento que llevo meses refutando en su versión racional. El argumento va así:  es una telemedicina. Una página bonita, un formulario, un médico que firma la receta en cuatro minutos y una farmacia que despacha. Cualquiera con capital puede montar eso. Amazon lo puede montar. Novo Nordisk lo puede montar. Y si OpenAI decide un día ponerle un médico y una farmacia a ChatGPT, se acabó.

Cuando lo escribo así de seguido suena convincente. Es la misma seguridad con la que en 2021 se decía que [Robinhood](https://www.10am.pro/p/el-puente-de-los-124-trillones-como) era una app de trading para adolescentes con confeti, y con la que en 2022 se decía que [Palantir](https://www.10am.pro/p/palantir-la-compania-mas-importante) era una consultora con buen marketing. Ya escribí sobre las dos, y sobre lo que pasó cuando el mercado por fin entendió [la ontología de Palantir](https://www.10am.pro/p/palantir-q2-2026-el-dia-que-wall) y [los trece carriles del puente de Robinhood](https://www.10am.pro/p/robinhood-el-puente-ya-tiene-13-carriles). Hoy toca la tercera, y la voy a escribir con un frame que no es mío, porque como confesé en [La Tesis Alquilada](https://www.10am.pro/p/la-tesis-alquilada), la única forma honesta de usar una tesis ajena es pagarla en horas y decir de quién es.

El 15 de septiembre Antonio Linares publicó *[The State of the Ontology Velocity](https://antoniolinares.substack.com/p/the-state-of-the-ontology-velocity)* , su update de earnings de Spotify, Duolingo y HIMS. Lo leí dos veces, con el mismo cuidado con que leí su deep dive de Recursion el día que entendí [por qué había comprado PLTR](https://www.10am.pro/p/el-dia-que-entendi-por-que-compre). La segunda vez entendí que Antonio había escrito, sin proponérselo, la refutación completa del argumento de la telemedicina. Y que HIMS es el caso más limpio de los tres, precisamente porque es el que el mercado menos entiende. Así que este artículo tiene dos mitades: primero les traduzco el frame, y después lo uso para desarmar, uno por uno, los alegatos que me llegan al chat.

---

## II. El Loop, No los Datos

La frase que abre el artículo de Antonio es la que hay que grabarse: el dato no es el activo, el loop cerrado es. Y la definición es precisa. Un loop cerrado es un sistema que observa una intervención, observa el resultado de esa intervención, y atribuye la una al otro. La escala da volumen. El loop cerrado da volumen etiquetado, que es el único tipo de volumen que le enseña a una AI a automatizar algo.

[![](https://substack-post-media.s3.amazonaws.com/public/images/978e7ab7-129e-4bea-aaf5-d5e517f35dc2_1642x958.png)](https://substackcdn.com/image/fetch/$s_!mycp!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F978e7ab7-129e-4bea-aaf5-d5e517f35dc2_1642x958.png)

Piensen en la diferencia. Google sabe qué buscaron ustedes. No sabe si lo que encontraron les sirvió. Un hospital tiene su historia clínica. No sabe qué pasó con ustedes después de salir por la puerta. La mayoría de las empresas del mundo tienen el primer lado del loop, la intervención, y no tienen el segundo, el desenlace. Y sin desenlace no hay etiqueta. Y sin etiqueta el dato es ruido caro.

Antonio pone esta distinción en el centro por una razón que ustedes ya me han leído en [Velocidad de Ontología](https://www.10am.pro/p/el-dia-que-entendi-por-que-compre): la capa del modelo se está desplomando en precio. Duolingo movió un feature de treinta centavos por uso a menos de un centavo este trimestre, cambiando a modelos de pesos abiertos, y Luis von Ahn dijo en el call que la calidad es indistinguible para la mayoría de lo que hacen. Spotify construyó un router interno, Chirp, que manda cada tarea al modelo más barato que cumpla el nivel de calidad requerido, incluyendo modelos open source que ellos mismos hospedan, y mide el gasto de inferencia hasta el nivel del ingeniero individual. Gustav Söderström lo resumió en una frase que me voy a robar: no pagamos dos veces por el mismo razonamiento.

> **Cuando la inteligencia cuesta casi nada, el excedente entero se lo lleva quien sea dueño de la infraestructura que convierte un modelo genérico en uno específico. La inteligencia se vuelve un commodity de entrada. El loop no. Por eso Antonio insiste en que la métrica no es cuántos datos tiene una empresa. Es qué tan rápido convierte comportamiento en un desenlace verificado, y qué tan apretado ese desenlace alimenta la siguiente interacción. Velocidad de ontología, medida en revoluciones por unidad de tiempo.**

Lo que más me sirvió del artículo es una tabla que Antonio arma con cuatro casillas. La misma secuencia, tres distancias. Las cuatro casillas son escala, loop cerrado, ontología, y vendido con margen. Spotify tiene las cuatro llenas: 777M de usuarios mensuales, un loop de play, skip y save que corre desde 2010 con 3.4T de eventos diarios, un taste model que ningún competidor puede comprar, y ya cobra por ambos lados del mercado. Duolingo tiene tres y media: escala, loop, ontología, y la casilla del margen a medias porque le devuelve los ahorros al usuario en vez de cobrarlos. Y HIMS tiene tres casillas llenas y la cuarta vacía, con una anotación en rojo: flujo de caja libre negativo mientras la ontología se vuelve más densa.

[![](https://substack-post-media.s3.amazonaws.com/public/images/60a4a8d4-402b-402b-9aef-4666b158a084_2542x1598.png)](https://antoniolinares.substack.com/p/the-state-of-the-ontology-velocity)

Léanlo con cuidado, porque ahí está todo el artículo. El mercado ve la cuarta casilla vacía y concluye que el negocio es malo. Antonio ve las tres primeras llenas y concluye que la cuarta es cuestión de tiempo, igual que lo fue para Spotify. Y la pregunta de si HIMS es o no es telemedicina se resuelve completa mirando la segunda casilla: ¿cierra el loop, o no lo cierra?

---

## III. Lo Que Es una Telemedicina

Para saber si HIMS es telemedicina primero hay que definir qué es una telemedicina, y la definición es esta: un canal de acceso. Ustedes llenan un formulario, un médico licenciado lo revisa, firma una receta, y una farmacia de terceros despacha. Tres proveedores distintos, tres sistemas distintos, y en el mejor de los casos una notificación de que el paquete salió. Intake e intervención. Ni seguimiento ni desenlace. El médico no sabe si ustedes se tomaron la pastilla. La farmacia no sabe si les hizo efecto. La plataforma no sabe nada de nada, porque su modelo de negocio termina en el momento en que cobra la consulta.

Eso es una telemedicina, y el mercado tiene toda la razón en valorarla mal, porque el historial de esa categoría es un cementerio. Teladoc, la empresa que fue sinónimo de telemedicina durante la pandemia, compró Livongo en octubre de 2020 por $18.5B con la idea de agregarle datos de pacientes crónicos a su canal de video. Dieciocho meses después registró un impairment de $6.6B en un solo trimestre, y en el año completo de 2022 los impairments sumaron $13.4B. Este trimestre reportó $607M de revenue, cayendo 4%, con BetterHelp cayendo 12%, y la acción tocó $7.70 después del reporte. WW International, que compró Sequence para meterse en GLP-1, se declaró en bancarrota en mayo de 2025. Walmart cerró sus 51 clínicas y su servicio de salud virtual en abril de 2024 diciendo, textualmente, que no había un modelo de negocio sostenible.

[![](https://substack-post-media.s3.amazonaws.com/public/images/a0948c5a-5404-4dbf-bb20-759d70e6d7ef_1643x957.png)](https://substackcdn.com/image/fetch/$s_!1jxW!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fa0948c5a-5404-4dbf-bb20-759d70e6d7ef_1643x957.png)

Pongan esos números al lado de HIMS. El mismo trimestre en que Teladoc reportó $607M cayendo 4%, HIMS reportó $753M creciendo 38%, con 2.9M de suscriptores creciendo 19% y revenue mensual por suscriptor subiendo de $76 a $92. Las dos empresas guían un EBITDA ajustado parecido para 2026, alrededor de $300M en el punto medio. Una viene de $18.5B de adquisiciones destruidas. La otra viene de nueve años de construir algo que Teladoc nunca construyó, y que es la única diferencia que importa.

Y aquí quiero que paren un segundo, porque este es el punto donde el argumento de la telemedicina se cae solo. Si HIMS fuera una telemedicina, le habría pasado lo que le pasó a Teladoc, a WW, a Walmart. Los canales de acceso mueren cuando el acceso deja de ser escaso, y el acceso a un médico por video dejó de ser escaso en 2020. HIMS creció 38% en 2026 vendiendo cosas que en teoría cualquiera puede vender: finasteride genérico, sildenafil genérico, y la píldora de Wegovy que Novo le vende a quien quiera comprarla. Los números completos del trimestre están en el [reporte de agosto](https://www.10am.pro/p/hims-q2-2026-longevity-as-a-service); hoy no los repito, los uso. Lo que no puede vender cualquiera es lo que pasa después de la venta. Y eso es exactamente lo que vamos a desarmar en la segunda mitad, casilla por casilla, con los números del trimestre en la mano.

Es también, para que no se me olvide, el tipo de lente que vamos a pasar un día entero afilando en el Día D en Medellín, el 14 de octubre: cómo distinguir un canal de un loop antes de que el mercado lo distinga por ustedes. Los detalles y el cupón de los alphas están al final. Ahora, el loop.

[Vea Antonio Linares en el DIA D](https://eldiad.10am.pro/)

## IV. Los Cuatro Eslabones

Mo ElShenawy, el CTO que llegó de Cruise y de Amazon, dijo en el call del 10 de agosto la frase que define la tesis: creen ser la única empresa operando un loop cerrado que incluye el intake, el tratamiento, el seguimiento y el desenlace, a esta escala. Cuatro eslabones. Una telemedicina tiene el primero y una parte del segundo. HIMS tiene los cuatro, y cada uno es una pieza de infraestructura que hay que construir físicamente, no un feature que se programa en un sprint.

[![](https://substack-post-media.s3.amazonaws.com/public/images/a74179e4-58cb-4422-96c9-6f2bc7f9d482_1642x958.png)](https://substackcdn.com/image/fetch/$s_!V3Ed!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fa74179e4-58cb-4422-96c9-6f2bc7f9d482_1642x958.png)

El intake es el que todo el mundo ve, la página bonita del mensaje de mi amigo. Es la puerta, y es una puerta que tardó nueve años en aprender a hacer las preguntas correctas sin que la persona sienta vergüenza de contestar. Como escribí en [Velocidad de Ontología](https://www.10am.pro/p/el-dia-que-entendi-por-que-compre), la interfaz no es el producto: es la jeringa con la que se extrae el dato que alimenta el modelo. Un competidor puede copiar el diseño. No puede copiar los nueve años de saber qué pregunta produce qué respuesta en qué paciente.

El tratamiento es donde la telemedicina tradicional subcontrata, y donde HIMS es dueña. Dudum habló en el call de más de un millón de pies cuadrados de farmacias y laboratorios propios, con capacidad de compounding estéril. Eso incluye las farmacias 503A y 503B, el laboratorio de pruebas, y la facilidad en California donde hoy están corriendo validación y pruebas de estabilidad de los APIs de los péptidos que la FDA recomendó en julio, la historia que ya les conté en [La Cárcel de los Péptidos](https://www.10am.pro/p/el-negocio-mas-grande-del-que-nadie) y que sigue sin regla final. Una empresa que compra la molécula en una farmacia de terceros no sabe qué lote le llegó a quién ni cuándo. Una empresa que la fabrica y la despacha sí. Ese dato, quién recibió qué exactamente y en qué fecha, es el primer eslabón de la etiqueta.

El seguimiento es el que separa un canal de una plataforma, y es donde este trimestre trajo la evidencia más limpia. Desde julio HIMS desplegó por fases la nueva experiencia de cuidado en Hers Weight Loss, la categoría más compleja que operan, con AI como sistema operativo y no como chatbot decorativo. Los resultados: las pacientes mandan tres veces más mensajes que antes, la AI responde el 80% de esas preguntas dentro de protocolos escritos por los médicos de la compañía, y las tareas no clínicas que caían sobre humanos bajaron cerca de 50%. Cada uno de esos mensajes es información que antes se perdía. Dosis, efecto secundario, qué está funcionando y qué no. Tres veces más señal, a la mitad del costo de capturarla.

Y el desenlace es el eslabón que casi nadie cierra, el que Antonio marca en su diagrama con una flecha roja. HIMS sabe si la persona renovó o canceló, si subió o bajó de peso, si el nivel de testosterona se movió en el siguiente examen de sangre, si el efecto secundario que reportó a las once de la noche terminó en un ajuste de dosis o en un abandono. Yemi Okupe, el CFO, lo dijo de pasada: las cohortes con la experiencia nueva cancelan menos. Esa es la etiqueta cerrándose. Intervención, resultado, atribución. Nueve años de eso, millones de veces, sobre casi tres millones de cuerpos.

Ahora vuelvan a ElShenawy, porque también dijo lo otro: saben que los modelos de AI se están volviendo commodity, y que la única forma de construir una infraestructura de AI que mejore desenlaces clínicos es midiendo esos desenlaces. Es la tesis de Antonio dicha por el CTO de la empresa sin que ninguno de los dos haya leído al otro. La inteligencia se compra. El loop se construye. Y el loop de HIMS lleva nueve años corriendo mientras el mercado la valora como si fuera un formulario con receta.

---

## V. La Anécdota y la Estadística

Vuelvo al mensaje del viernes, porque no voy a hacer lo que hacen los bulls que me irritan: pretender que no existe.

[![](https://substack-post-media.s3.amazonaws.com/public/images/20cfb4c4-ef4b-4163-bf72-2f433edcda17_1642x958.png)](https://substackcdn.com/image/fetch/$s_!LaXR!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F20cfb4c4-ef4b-4163-bf72-2f433edcda17_1642x958.png)

La experiencia de mi amigo es real. Y no es aislada, porque la FTC demandó a la compañía el 29 de julio, después de tres años de investigación, por prácticas de suscripción y cancelación. La demanda dice, entre otras cosas, que a la mayoría de los clientes se les cobraba poco después del intake, que la fecha del siguiente cobro no estaba clara, y que el botón de cancelar estaba enterrado detrás de varios pasos. Cobrado dos veces, sin claridad, sin respuesta: el mensaje de mi amigo cabe casi palabra por palabra en la queja del regulador. HIMS provisionó $47.5M este trimestre, dijo que va a defenderse, y hay una demanda colectiva de accionistas en fila detrás. Nada de eso es gratis.

Pero miren de qué trata la queja y de qué no trata. Trata del eslabón uno, el intake, y de la plomería del cobro. No trata de si la testosterona funcionó, ni de si la dosis de semaglutida se ajustó a tiempo, ni de si el modelo del cuerpo de cada paciente mejora con cada interacción. Es una queja sobre la caja registradora de una tienda de nueve años, no sobre lo que la tienda sabe. Y una caja registradora se arregla con un cambio de diseño y un cheque al regulador. Un loop de nueve años no se construye con ninguna de las dos.

Ahora la estadística. HIMS tiene 2.9M de suscriptores pagando $92 al mes en promedio, lo que implica varios millones de despachos pagados por trimestre. En cualquier operación de ese tamaño hay cobros duplicados, paquetes perdidos y correos sin responder, y cada uno de ellos es una persona furiosa con razón. La pregunta de inversión no es si existen. Es la tasa, y la dirección de la tasa. Y la dirección la dio el trimestre: la base creció 19%, el revenue por suscriptor creció 21%, marketing como porcentaje de revenue bajó cinco puntos a 34%, y la compañía sigue diciendo que retiene la mayoría significativa del revenue de quienes pasan de los dos años de suscripción. Una empresa cuyos clientes se van furiosos no crece la base y el ticket al mismo tiempo mientras gasta menos en adquirirlos.

Y aquí está el detalle que convierte la anécdota en evidencia a favor. ¿Qué fue lo que arregló el despliegue de AI en Hers desde julio? Actualizaciones de pedidos, preguntas generales de efectos secundarios, la carga de soporte no clínico. Exactamente el tipo de falla que le pasó a mi amigo. Las tareas no clínicas bajaron cerca de 50% y las cohortes cancelan menos. La empresa está usando el loop para arreglar la caja registradora. Una telemedicina, que no tiene loop, no puede hacer eso: solo puede contratar más gente en un call center en Manila y rezar. HIMS redujo de forma significativa su dependencia de proveedores externos de soporte este trimestre porque el sistema que ya conoce al paciente contesta antes de que la persona tenga que llamar.

Mi amigo tuvo la experiencia de HIMS 2025. La cohorte de Hers de julio está teniendo la de HIMS 2027. Yo invierto en la segunda.

---

## VI. Por Qué Novo, Amazon y OpenAI No La Copian

El alegato más sofisticado del chat no es el de mi amigo. Es el de quien dice: está bien, es un loop, pero el loop lo pueden construir los grandes. Vamos por partes, porque cada candidato tiene un eslabón que le falta y que no tiene incentivo para construir.

[![](https://substack-post-media.s3.amazonaws.com/public/images/592ddb45-e5fd-4559-b2e5-a3b4c2c6fa04_1642x958.png)](https://substackcdn.com/image/fetch/$s_!00_g!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F592ddb45-e5fd-4559-b2e5-a3b4c2c6fa04_1642x958.png)

Novo Nordisk fabrica la molécula más deseada del planeta y decidió en marzo que HIMS es su canal, no su competidor. ¿Por qué no lo hace directo? Porque Novo es una empresa de manufactura farmacéutica con un ciclo de decisión de años, sin farmacia de compounding, sin red de médicos, sin experiencia de intake, y con un incentivo regulatorio enorme a no ser dueña de la relación clínica con el paciente. Lo que Novo quiere, y Dudum lo dijo en el call, es exactamente lo contrario de competir: quiere acercarse a los datos de adherencia, efectos secundarios y dosis que solo el loop de HIMS produce. Si ustedes fabrican drogas, no pueden esperar a ponerle las manos a los biomarcadores. Novo no compite con el loop. Novo le compra acceso al loop.

Amazon tiene la logística y la farmacia, y lleva años sin lograr el resto. Walmart, que tiene más tiendas que nadie en el país, cerró sus 51 clínicas en 2024 y lo dijo sin rodeos: no hay modelo de negocio. El problema de los retailers es que la salud no es una categoría de retail. **El cliente no vuelve porque el precio es bueno. Vuelve porque el sistema lo conoce, y para que un sistema conozca a alguien tiene que haber cerrado el loop con esa persona varias veces.** Amazon puede despachar la pastilla más rápido que nadie. No sabe si funcionó, y su cultura no está construida para averiguarlo.

Y los frontier models, que son el riesgo que más respeto y el que puse de quinto en los asteriscos del [reporte de agosto](https://www.10am.pro/p/hims-q2-2026-longevity-as-a-service). ChatGPT puede darles el mejor consejo de salud que hayan recibido en su vida. Lo que no puede hacer es enterarse de si lo siguieron y de qué pasó después. No receta, no despacha, no ve el examen de sangre de tres meses después. Dudum lo dijo: los frontier labs dan consejo del día a día, HIMS acompaña al paciente desde la primera pregunta hasta el tratamiento y el seguimiento. Un frontier model tiene inteligencia infinita y cero desenlaces. HIMS tiene inteligencia comprada y nueve años de desenlaces. En el mundo que Antonio describe, donde la inteligencia vale un centavo, sé de qué lado prefiero estar.

Lo que ninguno de los tres puede comprar es tiempo. El loop de Spotify corre desde 2010 y por eso el taste model no se puede replicar con un cheque. El loop de HIMS corre desde 2017. Cada trimestre que un competidor gasta decidiendo si construir la farmacia o comprarla, HIMS cierra otros cuantos millones de desenlaces. La brecha se compone. Esa es la definición de velocidad de ontología, y es la razón por la que la respuesta a cualquiera puede copiarla es la misma para HIMS que para [Palantir](https://www.10am.pro/p/palantir-vs-todos): sí, en teoría, si empiezan hace nueve años.

---

## VII. La Cuarta Casilla

Quedan dos cosas: la casilla vacía y el precio.

La casilla vacía es vendido con margen, y la anotación en rojo de Antonio es exacta: flujo de caja libre negativo mientras la ontología se vuelve más densa. Este trimestre fueron $68M negativos, por el capital de trabajo que exige vender Wegovy de marca en vez de compounded. El margen bruto cayó de 76% a 64%. Y el mercado, que valora el negocio por lo que vendió el trimestre pasado y no por lo que aprende cada día, castigó a la acción hasta cerca de $29, que son unos $6.9B de capitalización, poco más de dos veces el revenue guiado de 2026. Teladoc, con revenue cayendo y el mismo EBITDA guiado, vale un tercio de eso. El mercado está diciendo que un loop de nueve años vale tres veces un canal de acceso en descomposición. Yo digo que vale mucho más que eso, y la razón es cómo se llena la cuarta casilla.

[![](https://substack-post-media.s3.amazonaws.com/public/images/4f2bfc9c-4cb0-41ec-8fd9-711c2aa6c005_1642x958.png)](https://substackcdn.com/image/fetch/$s_!fg_-!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F4f2bfc9c-4cb0-41ec-8fd9-711c2aa6c005_1642x958.png)

Se llena de dos formas y las dos están en el roadmap. La primera es el playbook que ya corrieron en sexual health y hair loss durante años, y que Okupe explicó en el call: la escala baja el costo, el precio baja con él, el mercado direccionable se expande, la retención sube, y el lifetime value termina más alto con margen más ancho. Van a correrlo en weight loss antes de fin de año, financiado en parte con los ahorros de la AI, que la gerencia espera que se pague sola en 12 a 18 meses. Deflación como estrategia de conquista, otra vez.

La segunda es la que describí en el reporte de agosto y que hoy, con el frame de Antonio, se lee distinto: la membresía. El concierge médico que las familias de Diamandis pagan a $100,000 al año, vendido por suscripción con labs incluidos, wearables conectados y una vista 360 de la salud de cada persona. Eso no es un producto nuevo. Es la cuarta casilla. Es HIMS cobrando por el loop en vez de cobrar por la pastilla. Spotify cobra a los oyentes y a los sellos por un taste model que ninguno de los dos puede construir solo. HIMS va a cobrarles a los pacientes por la ontología de su propio cuerpo, y a las farmacéuticas, como Novo ya está pidiendo, por acceso a lo que esa ontología sabe sobre qué funciona en qué cuerpo antes de administrarlo. Nadie vende eso hoy. Todos lo van a querer.

Y aquí cierro el círculo con [Healthspan per Token](https://www.10am.pro/p/biology-is-code), el stack de tres capas: leer biología, orquestar, escribir biología. Las capas de lectura y escritura van a tener competencia feroz y márgenes de commodity, como los modelos de Duolingo a un centavo. La capa que orquesta y es dueña de la relación es la que cobra renta al stack completo. HIMS es la capa de orquestación del cuerpo humano a escala de consumo masivo, y este trimestre mostró los primeros números duros de que el loop funciona en las dos direcciones al mismo tiempo: más señal capturada y menos costo de capturarla.

---

## VIII. Lo Que la Gente No Está Viendo

La pregunta del título tiene una respuesta de una línea. HIMS no es telemedicina porque la telemedicina termina donde HIMS empieza: en el momento en que la receta sale por la puerta y nadie vuelve a saber qué pasó.

Lo que la gente no está viendo es que las tres empresas del artículo de Antonio son la misma máquina en tres industrias, y que HIMS es la que está más atrás en la secuencia y por eso la más barata. Spotify cerró las cuatro casillas y el mercado la premió tarde. Duolingo cerró tres y media y el mercado se sobreajustó a bookings. HIMS cerró tres, y hasta le tokenizaron la mitad de las acciones en un [primitive nuevo](https://www.10am.pro/p/la-creacion-de-un-primitive-nuevo) antes de que Wall Street la entendiera, y el mercado, con la cuarta vacía y una demanda de la FTC en el titular, decidió que es un call center con receta a dos veces ventas.

El mensaje de mi amigo lo voy a guardar. Es el mejor recordatorio de que el intake todavía tiene fallas, de que la caja registradora hay que arreglarla, y de que la FTC no va a ser barata. Pero también es el mejor recordatorio de en qué eslabón vive la queja y en cuál vive el valor. [No es lloradera](https://www.10am.pro/p/no-es-lloradera-es-opcionalidad), es opcionalidad: la queja es el precio de entrada, y el loop es lo que se compra con ese precio. Se quejan de la puerta. Yo compro lo que hay detrás.

Sigo long HIMS.

---

> **Día D — 14 de octubre, Auditorio Fundadores de EAFIT, Medellín.**
>
> Registro en **eldiad.10am.pro**. Los 10am alphas entran con el cupón **MODELOSMENTALES** (40% de descuento).

[DIA D -40%](https://luma.com/eldiad?coupon=MODELOSMENTALES)
