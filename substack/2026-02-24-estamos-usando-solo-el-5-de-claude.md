---
title: "Estamos Usando Solo el 5% de Claude Code"
date: 2026-02-24
url: https://www.10am.pro/p/estamos-usando-solo-el-5-de-claude
source: substack
paywalled: true
---
> Post exclusivo para suscriptores de 10ampro — suscríbete en https://www.10am.pro/subscribe
> Post original: https://www.10am.pro/p/estamos-usando-solo-el-5-de-claude

# Estamos Usando Solo el 5% de Claude Code

[![](https://substack-post-media.s3.amazonaws.com/public/images/8bdff271-bf48-4210-a971-e9719b8e3725_2752x1536.png)](https://substack.com/@camilogomez321)

Llevo meses construyendo dashboards, analizando portafolios, creando artifacts y publicando en Vercel — todo desde Claude. Y hace poco me senté con [Camilo](https://substack.com/@camilogomez321), que sí sabe tirar código y dirige un equipo de ingeniería, a hacer un ejercicio simple: mostrarle exactamente cómo uso Claude para que me dijera qué estoy haciendo mal.

El resultado: Estaba apretando un tornillo de estrella con destornillador de pala.

No es que Claude no funcione. Es que la mayoría lo estamos usando como si fuera 2023 — una ventanita donde preguntamos cosas y copiamos respuestas. Eso ya no es ni el 10% de lo que esta herramienta puede hacer. Lo que viene a continuación son 17 tips concretos, extraídos de esa sesión en vivo, para que dejen de desperdiciar tokens, tiempo y plata. Sin teoría. Puro machete. Les recomiendo ir implementando uno a uno estos tips con su Claude abierto.

### 🧠 MEMORIA Y CONTEXTO

**1. Deja de abrir 50 chats. Usa Proyectos.**

**El problema:** Cada chat nuevo arranca desde cero. Claude no recuerda nada del anterior. Terminas con 50 conversaciones abiertas repitiendo contexto como loro.

**La solución:** Ve a Projects, crea un proyecto, súbele los archivos de contexto y las instrucciones. Cada conversación nueva dentro de ese proyecto ya tiene todo el background cargado. No más copy-paste del mismo briefing 20 veces.

**La clave:** Una conversación por tarea específica. “Rehacer el frontend” es una conversación. “Definir estrategia de producto” es otra. Mismo proyecto, contexto compartido, conversaciones separadas.

[![](https://substack-post-media.s3.amazonaws.com/public/images/d2b256be-2dc0-49cb-93f9-c0432d85247a_1536x1024.png)](https://substackcdn.com/image/fetch/$s_!vrYu!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fd2b256be-2dc0-49cb-93f9-c0432d85247a_1536x1024.png)

**2. Conversaciones cortas, no novelas.**

**El problema:** Opus tiene 1 millón de tokens de ventana de contexto. Suena enorme, pero se llena con los documentos que subes, tus preguntas y las respuestas de Claude. La calidad del output empieza a degradarse después del 60% de la ventana.

**La solución:** Trata cada conversación como una tarea con scope definido. Cuando termines esa tarea, abre otra conversación en el mismo proyecto. El contexto del proyecto persiste, la conversación se mantiene limpia.

[![](https://substack-post-media.s3.amazonaws.com/public/images/fba80c9d-45a8-4cac-adfa-07e3f5727a25_1536x1024.png)](https://substackcdn.com/image/fetch/$s_!JaCT!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Ffba80c9d-45a8-4cac-adfa-07e3f5727a25_1536x1024.png)

3. Activa la Memoria en Settings.

**El problema:** Claude no recuerda conversaciones pasadas entre sesiones. Le preguntas algo que ya resolvieron juntos y te mira como si fuera la primera vez.

**La solución:** Ve a Settings → Capabilities → Memory. Actívalo. Claude puede recordar contexto de chats anteriores y traer esa información a conversaciones nuevas. Viene apagado por default porque consume más contexto, pero el trade-off vale la pena si trabajas temas recurrentes.

[![](https://substack-post-media.s3.amazonaws.com/public/images/09f0e66c-0bf2-48ed-8897-ba9084c69047_1536x1024.png)](https://substackcdn.com/image/fetch/$s_!ByEW!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F09f0e66c-0bf2-48ed-8897-ba9084c69047_1536x1024.png)

**4. El truco “Goldfish Memory” (si prefieres control manual).**

Si quieres más control que el sistema de memoria nativo, crea un documento en Google Drive que funcione como memoria persistente. Le dices a Claude: “Cada vez que terminemos una sesión, actualiza este documento con el estado actual.” El doc guarda nombre, contexto, proyectos, URLs, preferencias, stack técnico y reglas de flujo de trabajo.

Es manual, pero te da un archivo que puedes revisar, editar y llevar a cualquier herramienta — no solo Claude.

[![](https://substack-post-media.s3.amazonaws.com/public/images/94fec63e-5cba-42f8-985a-fdbf83ffbd7e_1536x1024.png)](https://substackcdn.com/image/fetch/$s_!-74f!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F94fec63e-5cba-42f8-985a-fdbf83ffbd7e_1536x1024.png)

---

## ⚡ VELOCIDAD Y EFICIENCIA

**5. Abre múltiples ventanas. Trabaja en paralelo.**

**El problema:** Le pides a Claude una tarea pesada y te quedas mirando la pantalla esperando. Cambias de pestaña y cuando vuelves dice “Retry”. Perdiste todo.

**La solución:** Abre varias ventanas de Claude en tu navegador (o usa el celular como ventana adicional). Misma cuenta. Cada ventana trabaja independientemente. Puedes tener 5-6 tareas corriendo simultáneamente. Sí, consumen tokens más rápido, pero el tiempo que ahorras es brutal.

**Truco extra:** Deja la ventana que está procesando como pestaña activa en su propia ventana del browser. Abre las otras tareas en ventanas separadas. Así evitas el “Retry” que aparece cuando el navegador suspende la pestaña.

[![](https://substack-post-media.s3.amazonaws.com/public/images/fca86a1a-08f2-44e3-8ea0-274616d0f215_1536x1024.png)](https://substackcdn.com/image/fetch/$s_!kRzX!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Ffca86a1a-08f2-44e3-8ea0-274616d0f215_1536x1024.png)

**6. Habla en inglés. Ahorra 15-30% en tokens.**

Los modelos están entrenados mayoritariamente en inglés. Cuando interactúas en inglés consumes entre 15% y 30% menos tokens por la misma tarea. Además, para preguntas complejas y temas técnicos, genera mejores resultados porque el conocimiento profundo está documentado en inglés.

No tienes que hacer todo en inglés — las conversaciones casuales da igual. Pero cuando estés ejecutando tareas pesadas, el switch vale cada centavo.

[![](https://substack-post-media.s3.amazonaws.com/public/images/4d47ee91-918c-427e-ae9c-fa79ddd514da_1536x1024.png)](https://substackcdn.com/image/fetch/$s_!vhno!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F4d47ee91-918c-427e-ae9c-fa79ddd514da_1536x1024.png)

**7. Dile que sea breve. Literalmente.**

**El problema:** Claude te escribe ensayos cuando solo necesitas un dato. Cada palabra de su respuesta consume tokens de tu ventana de contexto.

**La solución:** Agrega instrucciones como “Answer in single sentences” o “Be concise” en tu prompt o en las instrucciones del proyecto. Le cortas las alas al consumo innecesario de tokens y mantienes la ventana de contexto limpia para lo que importa.

[![](https://substack-post-media.s3.amazonaws.com/public/images/a3495c30-7826-4ccb-826f-7f356341073d_1536x1024.png)](https://substackcdn.com/image/fetch/$s_!UQHX!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fa3495c30-7826-4ccb-826f-7f356341073d_1536x1024.png)

---

### 🔧 HERRAMIENTAS Y FEATURES

**8. Crea Skills para tareas repetitivas**.

**El problema:** Cada vez que quieres subir algo a GitHub o convertir un archivo a Word, tienes que explicarle el proceso completo. Eso se come contexto.

**La solución:** Ve a Settings → Capabilities → Skills. Crea un Skill especializado. Ejemplo: “Quiero un skill que se especialice en hacer commits a GitHub, manejo de branching y deployments.” Claude crea el skill, y después solo lo invocas por nombre o por contexto — si le dices “súbelo a Vercel”, ya sabe qué skill usar.

**Lo mejor:** El skill no carga contexto hasta que lo necesitas. No se come tu ventana de contexto permanentemente como lo haría un prompt largo en las instrucciones del proyecto.

[![](https://substack-post-media.s3.amazonaws.com/public/images/5e50f8ab-bad6-45d5-a0d7-7fba9aa763de_1536x1024.png)](https://substackcdn.com/image/fetch/$s_!DiBY!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F5e50f8ab-bad6-45d5-a0d7-7fba9aa763de_1536x1024.png)

**9. Prende Extended Thinking para las preguntas serias.**

Cuando necesitas análisis profundo — no una respuesta rápida — activa Extended Thinking. Claude piensa step-by-step antes de responder. Es más lento y consume más, pero la calidad del razonamiento sube dramáticamente.

Úsalo para decisiones de arquitectura, análisis financiero complejo, o cuando necesitas que conecte puntos entre múltiples fuentes. No lo prendas para preguntas simples.

[![](https://substack-post-media.s3.amazonaws.com/public/images/383601fd-fa25-431a-ba12-739da37f1b39_1536x1024.png)](https://substackcdn.com/image/fetch/$s_!jHLP!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F383601fd-fa25-431a-ba12-739da37f1b39_1536x1024.png)

**10. Research Mode para devorar información.**

Cuando necesitas que Claude se trague datos de múltiples fuentes web y te dé un análisis consolidado, activa el modo Research. Le das un tema y sale a investigar, lee páginas completas, y te devuelve un reporte con fuentes.

Ideal para: análisis competitivo, research de mercado, preparación de tesis de inversión.

[![](https://substack-post-media.s3.amazonaws.com/public/images/4a0a93df-8075-451a-a588-4107ccddb347_1536x1024.png)](https://substackcdn.com/image/fetch/$s_!Eb0g!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F4a0a93df-8075-451a-a588-4107ccddb347_1536x1024.png)

**11. Artifacts: tu mejor amigo visual.**

Si eres visual como yo, los artifacts son oro. Le tiras un Excel, le pides una visualización, y Claude te genera gráficas interactivas, tablas dinámicas y dashboards — todo renderizado en la misma ventana.

Puedes decirle “copia el estilo de este otro artifact” y te lo replica. Es como tener un diseñador de datos disponible 24/7. Vean todos los artifacts que he hecho [aqui](https://10ampro-hub.vercel.app/)

[![](https://substack-post-media.s3.amazonaws.com/public/images/1ed99d01-b417-4ba8-96fc-0288a0467a34_1536x1024.png)](https://substackcdn.com/image/fetch/$s_!SoXU!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F1ed99d01-b417-4ba8-96fc-0288a0467a34_1536x1024.png)

**12. De Artifact a producción: GitHub + Vercel.**

**El problema:** Los artifacts viven dentro de Claude. Cuando la conversación se pone pesada o el contexto se llena, se vuelven inestables.

**La solución:** Publica tus artifacts en GitHub y despliégalos en Vercel. Así tienes una URL permanente, puedes ir acumulando data en batches, y no dependes de que la conversación de Claude siga viva.

Es el camino que uso para todos mis dashboards: LiquidityFlow, EarningsWatch, BTC Pension, Race to Target.

[![](https://substack-post-media.s3.amazonaws.com/public/images/0d7b54d4-68ba-4000-9ef9-4bc2f76cefb2_1536x1024.png)](https://substackcdn.com/image/fetch/$s_!WdCe!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F0d7b54d4-68ba-4000-9ef9-4bc2f76cefb2_1536x1024.png)

---

### 🧩 ESTRATEGIA: SABER QUÉ PREGUNTAR

**13. No uses el LLM para lo que un script hace mejor.**

**El problema:** Le pides a Claude que te vaya a scrapear 30 links, extraiga datos, los procese y te dé insights. Se demora una eternidad, se cuelga, y te comiste todos los tokens del día.

**La solución:** Pregúntate: ¿voy a hacer esto todos los días con el mismo formato? Si la respuesta es sí, dile a Claude que te cree un scraper en Python. El script se ejecuta solo, te genera un Excel limpio, y después le pasas ese Excel a Claude para los insights.

No mates un mosco con un martillo. El LLM es para pensar, no para copiar datos de una página web.

[![](https://substack-post-media.s3.amazonaws.com/public/images/31512233-ca2b-4ebe-93c2-e7bcca05a23a_1536x1024.png)](https://substackcdn.com/image/fetch/$s_!bxMt!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F31512233-ca2b-4ebe-93c2-e7bcca05a23a_1536x1024.png)

**14. Parte las tareas grandes en pedazos.**

**El problema:** Le dices “analiza estos 100 links y dame un reporte” y la conversación explota.

**La solución:** Piensa en scope. Una tarea para un CFO no es lo mismo que una tarea para un contador junior. Si tu tarea se come toda la ventana de contexto, la calidad baja. Parte la tarea en 5 pedazos, abre 5 conversaciones dentro del mismo proyecto (en ventanas paralelas — tip #5), y procesa todo en media hora en vez de 4 horas esperando que se cuelgue.

[![](https://substack-post-media.s3.amazonaws.com/public/images/2d075a16-f126-4791-85c5-122eed57c2ee_1536x1024.png)](https://substackcdn.com/image/fetch/$s_!79KW!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F2d075a16-f126-4791-85c5-122eed57c2ee_1536x1024.png)

**15. Pre-prompt: pídele que te haga el prompt antes de ejecutar.**

Antes de tirarle un prompt complejo a Claude, especialmente si no eres técnico, usa una conversación limpia para pedirle: “Ayúdame a construir un prompt completo y detallado para [lo que quiero]. Pregúntame cosas que se me puedan estar escapando.”

Iterar en texto es mucho más barato que iterar en ejecución. Un prompt bien armado al inicio te ahorra 10 iteraciones después.

[![](https://substack-post-media.s3.amazonaws.com/public/images/4660ab3b-6dfc-4f33-9c1e-995a0ab6edf1_1536x1024.png)](https://substackcdn.com/image/fetch/$s_!Y1Z6!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F4660ab3b-6dfc-4f33-9c1e-995a0ab6edf1_1536x1024.png)

---

### 📱 CHAT vs. COWORK vs. CODE

**16. Entiende los tres modos.**

**Chat** = Interacción intelectual. Le preguntas, te responde, le pegas archivos, generas artifacts. Tú eres las manos — copias, pegas, ejecutas.

**Cowork** = Claude tiene manos para tareas no-técnicas. Le das acceso a carpetas específicas y puede manipular archivos directamente. “Revisa estos 200 Excels y dime cuáles son las 10 empresas con más Free Cash Flow” — lo hace solo, sin que toques nada.

**Code** = Claude tiene manos para tareas técnicas. Más permisos, más accesos. Para escribir y ejecutar código directamente.

**La regla:** Si estás copiando y pegando entre Claude y tu computador repetidamente, probablemente deberías estar en Cowork o Code, no en Chat.

[![](https://substack-post-media.s3.amazonaws.com/public/images/3b22e19c-34f4-46a5-bfe3-4003ce6b95cb_1536x1024.png)](https://substackcdn.com/image/fetch/$s_!lfOX!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F3b22e19c-34f4-46a5-bfe3-4003ce6b95cb_1536x1024.png)

### 17. En Cowork, limita el acceso por seguridad.

Cuando le das acceso a folders en Cowork, selecciona **solo la carpeta específica** para esa tarea. No le des acceso a tu carpeta raíz — si le dices “renombra todos los archivos de esta carpeta” y le diste acceso al escritorio completo, te puede renombrar todo el computador.

Selecciona el folder al inicio de la sesión. Un folder por tarea. Así Claude trabaja con libertad dentro de un sandbox controlado.

[![](https://substack-post-media.s3.amazonaws.com/public/images/886b09a2-247a-48f6-b510-e57618b10b83_1536x1024.png)](https://substackcdn.com/image/fetch/$s_!QlNA!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F886b09a2-247a-48f6-b510-e57618b10b83_1536x1024.png)

---

### 🎯 BONUS: El framework mental

Todo se reduce a una pregunta: **¿estoy usando el LLM donde agrega valor, o donde simplemente es caro y lento?**

* Scrapear datos → Script
* Transcribir videos → NotebookLM primero, luego Claude para insights
* Análisis profundo → Extended Thinking
* Investigación amplia → Research Mode
* Tareas recurrentes → Skills
* Visualización → Artifacts → Vercel
* Procesamiento batch de archivos → Cowork

La herramienta es absurdamente poderosa. El cuello de botella eres tú sabiendo cuándo usar qué. Nuevamente muchas gracias a Camilo que me ayudo a crear esta guía, obviamente síganlo
