# Pendientes de aprobación del Publicador

Actualizado: 2026-11-07 17:53 (-05:00) · ciclo 4 · modo `aprobacion`

Hay **56 clips y 167 envíos pendientes de aprobación** (TikTok, Instagram y YouTube). Van ordenados por ventana, de la que cierra antes a la que cierra después, y, si la ventana es la misma, por puntaje. El modo es `aprobacion`, así que no se publica nada hasta que lo apruebes.

## Antes de aprobar

- **Ninguna plataforma tiene credenciales en esta PC.** El script devuelve `sin_credenciales` en las cuatro. TikTok sigue activa en `config.json`, pero hay que volver a autorizarla. Hazlo en tu propia ventana de PowerShell, desde la carpeta del proyecto:
  `powershell -NoProfile -ExecutionPolicy Bypass -File legion/03-publicador/publicar.ps1 autorizar -Plataforma tiktok`
  YouTube e Instagram tampoco tienen credenciales ni están activas (`plataformas.md` §3 y §5). Puedes aprobar por adelantado: lo aprobado se sube cuando la plataforma esté lista, si la ventana sigue abierta.
- **5 ventanas cierran hoy, 2026-11-07:** `samulx-me-quedo-en-colombia`, `samulx-medellin-caracas`, `samulx-tour-por-colombia`, `samulx-sorpresa-filtrada`, `samulx-playa-medellin`. Si no se aprueban hoy, el próximo ciclo las marca vencidas.
- **Faltan videos.** 10 clips pendientes no tienen `clip.mp4` en esta copia (los del 2026-11-01 y los de «Tóxico»). Se pueden aprobar, pero para subirlos hay que volver a generarlos o copiarlos. Los del 2026-11-04 en adelante sí tienen el video.
- **Derechos:** salvo los 4 de «Tóxico» (`autorizado`), todo es `sin_verificar`. Solo se publica si lo apruebas expresamente, y siempre lleva el crédito a la fuente con el minuto.
- **TikTok, en modo borrador:** el video llega a tu bandeja y el texto se pega en la app. Como mucho caben 5 borradores pendientes por API cada 24 h, así que publica o descarta los que ya tengas antes de aprobar más.
- **Westcol, «¿CUANTO DINERO GANO LA PLENA?»:** en esos clips no se comprobó por la cara quién dice cada frase, así que los textos dicen «en el directo de Westcol» y no atribuyen las citas a nadie en concreto. Las cifras van como «dichas en el directo» o «sin verificar».
- **Vencidos este ciclo (15 entradas):** `lonche-seis-cifras`, `lonche-sueno-americano`, `westcol-cuerpo-35-anos`, `westcol-w-sound-700mil`, `westcol-w-sound-espana`, con ventana hasta el 2026-11-06. Siguen en `datos/publicador/envios/`. Una aprobación expresa los vuelve a activar.

## Clips

### 1. 2026-11-06-samulx-me-quedo-en-colombia

- **Gancho:** Samulx: 'me voy a quedar aquí un tiempo' · **Tipo:** `frase` · **Puntaje:** 78 · **Duración:** 26,5 s · **Ventana hasta:** 2026-11-07
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-06-samulx-me-quedo-en-colombia/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-06-samulx-me-quedo-en-colombia/ficha.md)
- **Fuente:** https://youtu.be/XvSs7RaRxzA?t=565 (Live Samulx, minuto 9:25)
- **Oportunidad del Cazador:** `tema-samulx-llega-a-colombia`
- **Aprobar:** `/publicador aprobar 2026-11-06-samulx-me-quedo-en-colombia`

#### TikTok

Envío: `datos/publicador/envios/2026-11-06-samulx-me-quedo-en-colombia__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-06-samulx-me-quedo-en-colombia:tiktok`

```text
Samulx: "me voy a quedar aquí un tiempo" 🇨🇴

¿Qué le enseñarías primero de Colombia?

Crédito: canal Live Samulx, «Peleare en Stream Fighters | Westcol quiere cargar a CHIARA, Samulx». Momento original desde el minuto 9:25: https://youtu.be/XvSs7RaRxzA?t=565

#Samulx #Colombia #Medellín #StreamFighters5 #Kick
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-06-samulx-me-quedo-en-colombia__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-06-samulx-me-quedo-en-colombia:instagram`

```text
Samulx se queda un tiempo en Colombia 🇨🇴

En casa de Westcol lo anuncia: "estamos aquí ya en Medellín… la gente que no creía en mí… Colombia, Stream Fighters, muchas cosas más".

¿Qué le enseñarías primero de Colombia?

Crédito: canal Live Samulx, «Peleare en Stream Fighters | Westcol quiere cargar a CHIARA, Samulx». Momento original desde el minuto 9:25: https://youtu.be/XvSs7RaRxzA?t=565

#Samulx #Colombia #Medellín #StreamFighters5 #Westcol
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-06-samulx-me-quedo-en-colombia__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-06-samulx-me-quedo-en-colombia:youtube`

**Título:** Samulx anuncia que se queda un tiempo en Colombia

**Descripción:**

```text
Samulx, en casa de Westcol: "me voy a quedar aquí un tiempo… Colombia, Stream Fighters, muchas cosas más".

¿Qué le enseñarías primero de Colombia?

Crédito: canal Live Samulx, «Peleare en Stream Fighters | Westcol quiere cargar a CHIARA, Samulx». Momento original desde el minuto 9:25: https://youtu.be/XvSs7RaRxzA?t=565

#Samulx #Colombia #Medellín #StreamFighters5
```

**Etiquetas:** Samulx, Colombia, Medellín, Stream Fighters 5, Westcol, Kick, Live Samulx

### 2. 2026-11-06-samulx-medellin-caracas

- **Gancho:** ¿Medellín se parece a Caracas? · **Tipo:** `humor` · **Puntaje:** 76 · **Duración:** 36,2 s · **Ventana hasta:** 2026-11-07
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-06-samulx-medellin-caracas/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-06-samulx-medellin-caracas/ficha.md)
- **Fuente:** https://youtu.be/hD58PIkuFVA?t=1214 (Samulx, minuto 20:14)
- **Oportunidad del Cazador:** `tema-samulx-llega-a-colombia`
- **Aprobar:** `/publicador aprobar 2026-11-06-samulx-medellin-caracas`

#### TikTok

Envío: `datos/publicador/envios/2026-11-06-samulx-medellin-caracas__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-06-samulx-medellin-caracas:tiktok`

```text
¿Medellín se parece a Caracas? La Ganga y Samulx lo discuten 😂 "Tengo agenda para 2080"

¿Se parecen o no?

Crédito: canal Samulx, «POR FIN ESTOY EN COLOMBIA 🙂🇨🇴 CONOCIENDO LA CASA DE WEST | Samulx». Momento original desde el minuto 20:14: https://youtu.be/hD58PIkuFVA?t=1214

#Samulx #Medellín #Caracas #Venezuela #Colombia
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-06-samulx-medellin-caracas__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-06-samulx-medellin-caracas:instagram`

```text
"Tengo agenda para 2080" 😂 Medellín vs. Caracas

En el primer día de Samulx en Medellín se discute si la ciudad se parece a Caracas: "todos los venezolanos dicen que esto se parece a Caracas". Y cuando sale la idea de ir a Venezuela, la respuesta: "tengo agenda para 2080".

¿Se parecen o no? Comenta.

Crédito: canal Samulx, «POR FIN ESTOY EN COLOMBIA 🙂🇨🇴 CONOCIENDO LA CASA DE WEST | Samulx». Momento original desde el minuto 20:14: https://youtu.be/hD58PIkuFVA?t=1214

#Samulx #Medellín #Caracas #Venezuela #Colombia
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-06-samulx-medellin-caracas__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-06-samulx-medellin-caracas:youtube`

**Título:** ¿Medellín se parece a Caracas? El primer día de Samulx en Colombia

**Descripción:**

```text
En el primer día de Samulx en Medellín se discute si la ciudad se parece a Caracas: "todos los venezolanos dicen que esto se parece a Caracas". La respuesta a ir a Venezuela: "tengo agenda para 2080".

¿Se parecen o no?

Crédito: canal Samulx, «POR FIN ESTOY EN COLOMBIA 🙂🇨🇴 CONOCIENDO LA CASA DE WEST | Samulx». Momento original desde el minuto 20:14: https://youtu.be/hD58PIkuFVA?t=1214

#Samulx #Medellín #Caracas #Venezuela
```

**Etiquetas:** Samulx, Medellín, Caracas, Venezuela, Colombia, Westcol, La Ganga

### 3. 2026-11-06-samulx-tour-por-colombia

- **Gancho:** Samulx planea un tour por Colombia · **Tipo:** `revelacion` · **Puntaje:** 75 · **Duración:** 46,9 s · **Ventana hasta:** 2026-11-07
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-06-samulx-tour-por-colombia/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-06-samulx-tour-por-colombia/ficha.md)
- **Fuente:** https://youtu.be/XvSs7RaRxzA?t=271 (Live Samulx, minuto 4:31)
- **Oportunidad del Cazador:** `tema-samulx-llega-a-colombia`
- **Aprobar:** `/publicador aprobar 2026-11-06-samulx-tour-por-colombia`

#### TikTok

Envío: `datos/publicador/envios/2026-11-06-samulx-tour-por-colombia__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-06-samulx-tour-por-colombia:tiktok`

```text
Samulx quiere hacer un tour por todas las ciudades de Colombia en stream 🇨🇴

¿Qué ciudad tiene que visitar primero?

Crédito: canal Live Samulx, «Peleare en Stream Fighters | Westcol quiere cargar a CHIARA, Samulx». Momento original desde el minuto 4:31: https://youtu.be/XvSs7RaRxzA?t=271

#Samulx #Colombia #TourPorColombia #Kick #Streamers
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-06-samulx-tour-por-colombia__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-06-samulx-tour-por-colombia:instagram`

```text
"Nunca había pisado Colombia… mentira, fui a Cartagena" 😂

Samulx se corrige solo ("cuando tenía como 8 años") y lanza su plan: "voy a hacer un tour por Colombia… todas las ciudades en stream. Ya tengo un mes completo de contenido".

¿Qué ciudad de Colombia tiene que visitar primero?

Crédito: canal Live Samulx, «Peleare en Stream Fighters | Westcol quiere cargar a CHIARA, Samulx». Momento original desde el minuto 4:31: https://youtu.be/XvSs7RaRxzA?t=271

#Samulx #Colombia #TourPorColombia #Medellín #Kick
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-06-samulx-tour-por-colombia__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-06-samulx-tour-por-colombia:youtube`

**Título:** El plan de Samulx: un tour por todas las ciudades de Colombia en stream

**Descripción:**

```text
Samulx cuenta que nunca había pisado Colombia ("mentira, fui a Cartagena cuando tenía como 8 años") y lanza su plan: "voy a hacer un tour por Colombia… todas las ciudades en stream".

¿Qué ciudad tiene que visitar primero?

Crédito: canal Live Samulx, «Peleare en Stream Fighters | Westcol quiere cargar a CHIARA, Samulx». Momento original desde el minuto 4:31: https://youtu.be/XvSs7RaRxzA?t=271

#Samulx #Colombia #TourPorColombia #Kick
```

**Etiquetas:** Samulx, Colombia, tour por Colombia, Medellín, Cartagena, Kick, streamers, Live Samulx

### 4. 2026-11-06-samulx-sorpresa-filtrada

- **Gancho:** La llegada sorpresa que se filtró · **Tipo:** `humor` · **Puntaje:** 74 · **Duración:** 40,5 s · **Ventana hasta:** 2026-11-07
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-06-samulx-sorpresa-filtrada/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-06-samulx-sorpresa-filtrada/ficha.md)
- **Fuente:** https://youtu.be/hD58PIkuFVA?t=189 (Samulx, minuto 3:09)
- **Oportunidad del Cazador:** `tema-samulx-llega-a-colombia`
- **Aprobar:** `/publicador aprobar 2026-11-06-samulx-sorpresa-filtrada`

#### TikTok

Envío: `datos/publicador/envios/2026-11-06-samulx-sorpresa-filtrada__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-06-samulx-sorpresa-filtrada:tiktok`

```text
La llegada sorpresa de Samulx a Colombia que se filtró 😂 "Todo el mundo ya sabía que era mentira"

¿Tú te la creíste?

Crédito: canal Samulx, «POR FIN ESTOY EN COLOMBIA 🙂🇨🇴 CONOCIENDO LA CASA DE WEST | Samulx». Momento original desde el minuto 3:09: https://youtu.be/hD58PIkuFVA?t=189

#Samulx #Westcol #LaGanga #Medellín #Kick
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-06-samulx-sorpresa-filtrada__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-06-samulx-sorpresa-filtrada:instagram`

```text
"Todo el mundo ya sabía que era mentira": la sorpresa fallida de Samulx 😂

La Ganga se ríe de su llegada "sorpresa" a Colombia: "es porque me filtraron" – "la actuación tuya fue muy mala, Sami". Y él se defiende: "hasta tengo el mismo outfit del video".

¿Tú te la creíste?

Crédito: canal Samulx, «POR FIN ESTOY EN COLOMBIA 🙂🇨🇴 CONOCIENDO LA CASA DE WEST | Samulx». Momento original desde el minuto 3:09: https://youtu.be/hD58PIkuFVA?t=189

#Samulx #Westcol #LaGanga #Medellín #Kick
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-06-samulx-sorpresa-filtrada__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-06-samulx-sorpresa-filtrada:youtube`

**Título:** Samulx explica por qué su llegada sorpresa a Colombia no funcionó

**Descripción:**

```text
La Ganga se ríe de la llegada "sorpresa" de Samulx: "todo el mundo ya sabía que era mentira" – "es porque me filtraron". Él se defiende: "hasta tengo el mismo outfit del video".

¿Tú te la creíste?

Crédito: canal Samulx, «POR FIN ESTOY EN COLOMBIA 🙂🇨🇴 CONOCIENDO LA CASA DE WEST | Samulx». Momento original desde el minuto 3:09: https://youtu.be/hD58PIkuFVA?t=189

#Samulx #Westcol #LaGanga #Kick
```

**Etiquetas:** Samulx, Westcol, La Ganga, Medellín, Colombia, Kick, streamers

### 5. 2026-11-06-samulx-playa-medellin

- **Gancho:** Lo primero que Samulx quiere ver en Medellín · **Tipo:** `humor` · **Puntaje:** 73 · **Duración:** 21,0 s · **Ventana hasta:** 2026-11-07
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-06-samulx-playa-medellin/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-06-samulx-playa-medellin/ficha.md)
- **Fuente:** https://youtu.be/hD58PIkuFVA?t=892 (Samulx, minuto 14:52)
- **Oportunidad del Cazador:** `tema-samulx-llega-a-colombia`
- **Aprobar:** `/publicador aprobar 2026-11-06-samulx-playa-medellin`

#### TikTok

Envío: `datos/publicador/envios/2026-11-06-samulx-playa-medellin__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-06-samulx-playa-medellin:tiktok`

```text
Lo primero que Samulx quiere conocer en Medellín… una playa 😂🏝️

¿Qué le recomiendas de verdad en Medellín?

Crédito: canal Samulx, «POR FIN ESTOY EN COLOMBIA 🙂🇨🇴 CONOCIENDO LA CASA DE WEST | Samulx». Momento original desde el minuto 14:52: https://youtu.be/hD58PIkuFVA?t=892

#Samulx #Medellín #Colombia #Humor #Kick
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-06-samulx-playa-medellin__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-06-samulx-playa-medellin:instagram`

```text
Samulx quiere playa… en Medellín 🏝️

Le preguntan qué quiere conocer primero y responde: "me dijeron que un lugar que era como de arena… palmeras… como playa".

¿Qué le recomiendas de verdad en Medellín?

Crédito: canal Samulx, «POR FIN ESTOY EN COLOMBIA 🙂🇨🇴 CONOCIENDO LA CASA DE WEST | Samulx». Momento original desde el minuto 14:52: https://youtu.be/hD58PIkuFVA?t=892

#Samulx #Medellín #Colombia #Westcol #Humor
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-06-samulx-playa-medellin__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-06-samulx-playa-medellin:youtube`

**Título:** ¿Qué quiere conocer Samulx en Medellín? Arena y palmeras

**Descripción:**

```text
Le preguntan a Samulx qué quiere conocer primero en Medellín: "me dijeron que un lugar que era como de arena… palmeras… como playa".

¿Qué le recomiendas de verdad en Medellín?

Crédito: canal Samulx, «POR FIN ESTOY EN COLOMBIA 🙂🇨🇴 CONOCIENDO LA CASA DE WEST | Samulx». Momento original desde el minuto 14:52: https://youtu.be/hD58PIkuFVA?t=892

#Samulx #Medellín #Colombia #Humor
```

**Etiquetas:** Samulx, Medellín, Colombia, Westcol, humor, Kick, playa

### 6. 2026-11-05-maluma-bebe-capo

- **Gancho:** Maluma: en Argentina le tiraron un bebé · **Tipo:** `historia` · **Puntaje:** 81 · **Duración:** 47,1 s · **Ventana hasta:** 2026-11-08
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-maluma-bebe-capo/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-maluma-bebe-capo/ficha.md)
- **Fuente:** https://youtu.be/iNxDQVDIer8?t=2933 (LUZU TV, minuto 48:53)
- **Aprobar:** `/publicador aprobar 2026-11-05-maluma-bebe-capo`

#### TikTok

Envío: `datos/publicador/envios/2026-11-05-maluma-bebe-capo__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-05-maluma-bebe-capo:tiktok`

```text
Maluma cuenta que en Argentina le pusieron un bebé en el carro 😳

¿Qué es lo más loco que has visto hacer a un fan?

Crédito: canal LUZU TV, «#FMLUZU | MALUMA NOS LLAMÓ EN VIVO + FERBO EN CONTRA DE DOMI…». Momento original desde el minuto 48:53: https://youtu.be/iNxDQVDIer8?t=2933

#Maluma #FMLuzu #Luzu #Argentina #Fans
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-05-maluma-bebe-capo__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-05-maluma-bebe-capo:instagram`

```text
"Me tiraron un bebé de 6 meses al capó" – Maluma

Maluma llamó en vivo a FM Luzu y contó lo que le pasó al salir de un restaurante en Argentina: miles de fans afuera y un bebé de unos 6 meses sobre el capó de su carro.

¿Qué es lo más loco que has visto hacer a un fan?

Crédito: canal LUZU TV, «#FMLUZU | MALUMA NOS LLAMÓ EN VIVO + FERBO EN CONTRA DE DOMI…». Momento original desde el minuto 48:53: https://youtu.be/iNxDQVDIer8?t=2933

#Maluma #FMLuzu #Luzu #Argentina #Fans
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-05-maluma-bebe-capo__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-05-maluma-bebe-capo:youtube`

**Título:** Maluma cuenta su anécdota más loca con fans en Argentina

**Descripción:**

```text
Maluma llamó en vivo a FM Luzu y contó lo que le pasó al salir de un restaurante en Argentina: miles de fans afuera y un bebé de unos 6 meses sobre el capó de su carro.

¿Qué es lo más loco que has visto hacer a un fan?

Crédito: canal LUZU TV, «#FMLUZU | MALUMA NOS LLAMÓ EN VIVO + FERBO EN CONTRA DE DOMI…». Momento original desde el minuto 48:53: https://youtu.be/iNxDQVDIer8?t=2933

#Maluma #FMLuzu #Luzu #Argentina
```

**Etiquetas:** Maluma, FM Luzu, Luzu TV, Maluma Argentina, Maluma fans, anécdota

### 7. 2026-11-05-maluma-loco-por-girar

- **Gancho:** Maluma: que no me escuche mi mujer · **Tipo:** `frase` · **Puntaje:** 75 · **Duración:** 55,5 s · **Ventana hasta:** 2026-11-08
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-maluma-loco-por-girar/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-maluma-loco-por-girar/ficha.md)
- **Fuente:** https://youtu.be/iNxDQVDIer8?t=3059 (LUZU TV, minuto 50:59)
- **Aprobar:** `/publicador aprobar 2026-11-05-maluma-loco-por-girar`

#### TikTok

Envío: `datos/publicador/envios/2026-11-05-maluma-loco-por-girar__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-05-maluma-loco-por-girar:tiktok`

```text
Maluma: "Que no me escuche mi mujer…" 🎤

¿Te pasa lo mismo con tu trabajo?

Crédito: canal LUZU TV, «#FMLUZU | MALUMA NOS LLAMÓ EN VIVO + FERBO EN CONTRA DE DOMI…». Momento original desde el minuto 50:59: https://youtu.be/iNxDQVDIer8?t=3059

#Maluma #FMLuzu #Gira #Papá #Música
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-05-maluma-loco-por-girar__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-05-maluma-loco-por-girar:instagram`

```text
Maluma confiesa que extraña los escenarios

En FM Luzu, Maluma se sincera: ama a su familia, pero "estoy loco por salir de la casa e irme a girar… para ser un buen padre hay que trabajar de manera individual".

¿Te pasa lo mismo con tu trabajo?

Crédito: canal LUZU TV, «#FMLUZU | MALUMA NOS LLAMÓ EN VIVO + FERBO EN CONTRA DE DOMI…». Momento original desde el minuto 50:59: https://youtu.be/iNxDQVDIer8?t=3059

#Maluma #FMLuzu #Gira #Papá #Música
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-05-maluma-loco-por-girar__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-05-maluma-loco-por-girar:youtube`

**Título:** Maluma, entre ser papá y volver a girar por el mundo

**Descripción:**

```text
En FM Luzu, Maluma se sincera: ama a su familia, pero "estoy loco por salir de la casa e irme a girar… para ser un buen padre hay que trabajar de manera individual".

¿Te pasa lo mismo con tu trabajo?

Crédito: canal LUZU TV, «#FMLUZU | MALUMA NOS LLAMÓ EN VIVO + FERBO EN CONTRA DE DOMI…». Momento original desde el minuto 50:59: https://youtu.be/iNxDQVDIer8?t=3059

#Maluma #FMLuzu #Gira #Papá
```

**Etiquetas:** Maluma, FM Luzu, Luzu TV, Maluma gira, Maluma papá, música

### 8. 2026-11-01-kris-r-critica-trap-bogota

- **Gancho:** Su crítica al concierto de Kris R · **Tipo:** `frase` · **Puntaje:** 73 · **Duración:** 41,8 s · **Ventana hasta:** 2026-11-08
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** clip.mp4: el archivo no está en esta copia del proyecto (no es un error: la entrada se puede aprobar igual, pero para subirlo hace falta el video) · **Ficha:** [ficha.md](../clipero/clips/2026-11-01-kris-r-critica-trap-bogota/ficha.md)
- **Fuente:** https://youtu.be/hSV5nuZ5w_I?t=0 (ElWerik Podcast, minuto 0:00)
- **Aprobar:** `/publicador aprobar 2026-11-01-kris-r-critica-trap-bogota`

#### TikTok

Envío: `datos/publicador/envios/2026-11-01-kris-r-critica-trap-bogota__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-01-kris-r-critica-trap-bogota:tiktok`

```text
"Nadie le abrió": la crítica de un podcast de Bogotá al concierto de Kris R

¿El artista grande debe abrirle la tarima a los nuevos de la ciudad?

Crédito: canal ElWerik Podcast, «KRIS R y el TRAP DE BOGOTÁ: crítica al CONCIERTO y lo que pasó en el BACKSTAGE». Momento original desde el minuto 0:00: https://youtu.be/hSV5nuZ5w_I?t=0

#KrisR #Trap #TrapColombiano #Bogotá #MovistarArena
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-01-kris-r-critica-trap-bogota__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-01-kris-r-critica-trap-bogota:instagram`

```text
¿Kris R debió darle la tarima a los artistas de Bogotá?

Un podcast de Bogotá le pone un pero al concierto de Kris R en el Movistar Arena: el año pasado abrieron artistas de la ciudad y este año "nadie le abrió". Es la opinión de los podcasters. ¿Le debía esa tarima a la escena local o no era su responsabilidad?

¿El artista grande debe abrirle la tarima a los nuevos de la ciudad?

Crédito: canal ElWerik Podcast, «KRIS R y el TRAP DE BOGOTÁ: crítica al CONCIERTO y lo que pasó en el BACKSTAGE». Momento original desde el minuto 0:00: https://youtu.be/hSV5nuZ5w_I?t=0

#KrisR #Trap #TrapColombiano #Bogotá #MovistarArena
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-01-kris-r-critica-trap-bogota__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-01-kris-r-critica-trap-bogota:youtube`

**Título:** La crítica al concierto de Kris R en el Movistar Arena | ElWerik Podcast

**Descripción:**

```text
Un podcast de Bogotá le pone un pero al concierto de Kris R en el Movistar Arena: el año pasado abrieron artistas de la ciudad y este año "nadie le abrió". Es la opinión de los podcasters. ¿Le debía esa tarima a la escena local o no era su responsabilidad?

¿El artista grande debe abrirle la tarima a los nuevos de la ciudad?

Crédito: canal ElWerik Podcast, «KRIS R y el TRAP DE BOGOTÁ: crítica al CONCIERTO y lo que pasó en el BACKSTAGE». Momento original desde el minuto 0:00: https://youtu.be/hSV5nuZ5w_I?t=0

#KrisR #Trap #TrapColombiano #Bogotá
```

**Etiquetas:** Kris R, trap, trap colombiano, Bogotá, Movistar Arena, ElWerik Podcast

### 9. 2026-11-01-chanty-freestyle-dame-hombro

- **Gancho:** Freestyle de 'dame hombro' en El Poblado · **Tipo:** `humor` · **Puntaje:** 72 · **Duración:** 37,3 s · **Ventana hasta:** 2026-11-08
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** clip.mp4: el archivo no está en esta copia del proyecto (no es un error: la entrada se puede aprobar igual, pero para subirlo hace falta el video) · **Ficha:** [ficha.md](../clipero/clips/2026-11-01-chanty-freestyle-dame-hombro/ficha.md)
- **Fuente:** https://youtu.be/1TF93cD11g0?t=764 (The Chanty, minuto 12:44)
- **Oportunidad del Cazador:** `audio-dame-hombro`
- **Aprobar:** `/publicador aprobar 2026-11-01-chanty-freestyle-dame-hombro`

#### TikTok

Envío: `datos/publicador/envios/2026-11-01-chanty-freestyle-dame-hombro__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-01-chanty-freestyle-dame-hombro:tiktok`

```text
Le dijo "dame hombro" a The Chanty y le improvisó esto en plena calle

¿A quién le dirías "dame hombro"? Etiquétalo

Crédito: canal The Chanty, «FIESTA DE DISFRACES COMO JUSTIN BIEBER». Momento original desde el minuto 12:44: https://youtu.be/1TF93cD11g0?t=764

#DameHombro #TheChanty #Freestyle #Medellín #ElPoblado
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-01-chanty-freestyle-dame-hombro__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-01-chanty-freestyle-dame-hombro:instagram`

```text
"Dame hombro, voy para dentro": el freestyle que le soltó a The Chanty

Un rapero de la calle en El Poblado le improvisa a The Chanty, disfrazado de Justin Bieber, con el "dame hombro" del momento. ¿Qué nota le pones?

¿A quién le dirías "dame hombro"? Etiquétalo

Crédito: canal The Chanty, «FIESTA DE DISFRACES COMO JUSTIN BIEBER». Momento original desde el minuto 12:44: https://youtu.be/1TF93cD11g0?t=764

#DameHombro #TheChanty #Freestyle #Medellín #ElPoblado
```

### 10. 2026-11-01-kris-r-avion-musica-desechable

- **Gancho:** Escuchó la canción… y lo bajaron del avión · **Tipo:** `historia` · **Puntaje:** 67 · **Duración:** 42,3 s · **Ventana hasta:** 2026-11-08
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** clip.mp4: el archivo no está en esta copia del proyecto (no es un error: la entrada se puede aprobar igual, pero para subirlo hace falta el video) · **Ficha:** [ficha.md](../clipero/clips/2026-11-01-kris-r-avion-musica-desechable/ficha.md)
- **Fuente:** https://youtu.be/hSV5nuZ5w_I?t=384 (ElWerik Podcast, minuto 6:24)
- **Aprobar:** `/publicador aprobar 2026-11-01-kris-r-avion-musica-desechable`

#### TikTok

Envío: `datos/publicador/envios/2026-11-01-kris-r-avion-musica-desechable__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-01-kris-r-avion-musica-desechable:tiktok`

```text
Se perdió 2 semanas y media, volvió y su canción favorita ya no sonaba

¿Qué canción pegada dejaste de oír en dos semanas?

Crédito: canal ElWerik Podcast, «KRIS R y el TRAP DE BOGOTÁ: crítica al CONCIERTO y lo que pasó en el BACKSTAGE». Momento original desde el minuto 6:24: https://youtu.be/hSV5nuZ5w_I?t=384

#Música #MúsicaUrbana #Trap #IndustriaMusical #Podcast
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-01-kris-r-avion-musica-desechable__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-01-kris-r-avion-musica-desechable:instagram`

```text
"Me di cuenta de que la música es muy desechable"

Se sentó en el avión con su canción nueva favorita en los audífonos, y lo bajaron. Dos semanas y media después, nadie la estaba escuchando. "Ahí me di cuenta de que la música es muy desechable".

¿Qué canción pegada dejaste de oír en dos semanas?

Crédito: canal ElWerik Podcast, «KRIS R y el TRAP DE BOGOTÁ: crítica al CONCIERTO y lo que pasó en el BACKSTAGE». Momento original desde el minuto 6:24: https://youtu.be/hSV5nuZ5w_I?t=384

#Música #MúsicaUrbana #Trap #IndustriaMusical #Podcast
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-01-kris-r-avion-musica-desechable__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-01-kris-r-avion-musica-desechable:youtube`

**Título:** La historia del avión que le cambió la idea de la música | ElWerik Podcast

**Descripción:**

```text
Se sentó en el avión con su canción nueva favorita en los audífonos, y lo bajaron. Dos semanas y media después, nadie la estaba escuchando. "Ahí me di cuenta de que la música es muy desechable".

¿Qué canción pegada dejaste de oír en dos semanas?

Crédito: canal ElWerik Podcast, «KRIS R y el TRAP DE BOGOTÁ: crítica al CONCIERTO y lo que pasó en el BACKSTAGE». Momento original desde el minuto 6:24: https://youtu.be/hSV5nuZ5w_I?t=384

#Música #MúsicaUrbana #Trap #IndustriaMusical
```

**Etiquetas:** música, música urbana, trap, industria musical, ElWerik Podcast, podcast

### 11. 2026-11-01-kris-r-almighty-miedo

- **Gancho:** Le dio miedo saludar a Almighty · **Tipo:** `humor` · **Puntaje:** 66 · **Duración:** 17,6 s · **Ventana hasta:** 2026-11-08
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** clip.mp4: el archivo no está en esta copia del proyecto (no es un error: la entrada se puede aprobar igual, pero para subirlo hace falta el video) · **Ficha:** [ficha.md](../clipero/clips/2026-11-01-kris-r-almighty-miedo/ficha.md)
- **Fuente:** https://youtu.be/hSV5nuZ5w_I?t=253 (ElWerik Podcast, minuto 4:13)
- **Aprobar:** `/publicador aprobar 2026-11-01-kris-r-almighty-miedo`

#### TikTok

Envío: `datos/publicador/envios/2026-11-01-kris-r-almighty-miedo__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-01-kris-r-almighty-miedo:tiktok`

```text
Pasó al lado de Almighty en el backstage y no lo saludó: "Me dio miedo" 😅

¿Tú lo habrías saludado?

Crédito: canal ElWerik Podcast, «KRIS R y el TRAP DE BOGOTÁ: crítica al CONCIERTO y lo que pasó en el BACKSTAGE». Momento original desde el minuto 4:13: https://youtu.be/hSV5nuZ5w_I?t=253

#Almighty #KrisR #Backstage #Trap #MúsicaUrbana
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-01-kris-r-almighty-miedo__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-01-kris-r-almighty-miedo:instagram`

```text
"Pasé por el lado de Almighty, no lo saludé, me dio miedo"

En el backstage del concierto de Kris R se cruzó con Almighty y no se atrevió a saludarlo. "Yo soy más precavido cuando los artistas no me conocen".

¿Tú lo habrías saludado?

Crédito: canal ElWerik Podcast, «KRIS R y el TRAP DE BOGOTÁ: crítica al CONCIERTO y lo que pasó en el BACKSTAGE». Momento original desde el minuto 4:13: https://youtu.be/hSV5nuZ5w_I?t=253

#Almighty #KrisR #Backstage #Trap #MúsicaUrbana
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-01-kris-r-almighty-miedo__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-01-kris-r-almighty-miedo:youtube`

**Título:** Le dio miedo saludar a Almighty en el concierto de Kris R | ElWerik Podcast

**Descripción:**

```text
En el backstage del concierto de Kris R se cruzó con Almighty y no se atrevió a saludarlo. "Yo soy más precavido cuando los artistas no me conocen".

¿Tú lo habrías saludado?

Crédito: canal ElWerik Podcast, «KRIS R y el TRAP DE BOGOTÁ: crítica al CONCIERTO y lo que pasó en el BACKSTAGE». Momento original desde el minuto 4:13: https://youtu.be/hSV5nuZ5w_I?t=253

#Almighty #KrisR #Backstage #Trap
```

**Etiquetas:** Almighty, Kris R, backstage, trap, ElWerik Podcast, música urbana

### 12. 2026-11-05-westcol-batisenal-w

- **Gancho:** Westcol quiere una batiseñal en Medellín · **Tipo:** `revelacion` · **Puntaje:** 75 · **Duración:** 25,3 s · **Ventana hasta:** 2026-11-09
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-westcol-batisenal-w/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-westcol-batisenal-w/ficha.md)
- **Fuente:** https://youtu.be/LgnQHaFVvyo?t=65 (WestCOL, minuto 1:05)
- **Aprobar:** `/publicador aprobar 2026-11-05-westcol-batisenal-w`

#### TikTok

Envío: `datos/publicador/envios/2026-11-05-westcol-batisenal-w__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-05-westcol-batisenal-w:tiktok`

```text
Westcol quiere una "batiseñal" con la W en el cielo de Medellín 🦇

¿Se la aprueban?

Crédito: canal WestCOL, «ESTE ES MI NUEVO SET-UP | WESTCOL». Momento original desde el minuto 1:05: https://youtu.be/LgnQHaFVvyo?t=65

#Westcol #Medellín #Kick #Streamers #W
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-05-westcol-batisenal-w__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-05-westcol-batisenal-w:instagram`

```text
Cuando Westcol prenda stream, la W en el cielo

"Quiero hacer una batiseñal, que la W se ponga en el cielo… que cuando Westcol prenda stream se active la W". La idea de Westcol para Medellín.

¿Se la aprueban?

Crédito: canal WestCOL, «ESTE ES MI NUEVO SET-UP | WESTCOL». Momento original desde el minuto 1:05: https://youtu.be/LgnQHaFVvyo?t=65

#Westcol #Medellín #Kick #Streamers #W
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-05-westcol-batisenal-w__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-05-westcol-batisenal-w:youtube`

**Título:** La idea más loca de Westcol: una batiseñal de la W en Medellín

**Descripción:**

```text
"Quiero hacer una batiseñal, que la W se ponga en el cielo… que cuando Westcol prenda stream se active la W". La idea de Westcol para Medellín.

¿Se la aprueban?

Crédito: canal WestCOL, «ESTE ES MI NUEVO SET-UP | WESTCOL». Momento original desde el minuto 1:05: https://youtu.be/LgnQHaFVvyo?t=65

#Westcol #Medellín #Kick #Streamers
```

**Etiquetas:** Westcol, batiseñal, Medellín, Kick, streamers, la W

### 13. 2026-11-06-westcol-cuanto-hizo-la-plena

- **Gancho:** ¿Cuánto dinero hizo La Plena? · **Tipo:** `revelacion` · **Puntaje:** 85 · **Duración:** 56,6 s · **Ventana hasta:** 2026-11-10
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-06-westcol-cuanto-hizo-la-plena/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-06-westcol-cuanto-hizo-la-plena/ficha.md)
- **Fuente:** https://youtu.be/XcgyVpbHNlw?t=616 (WestCOL, minuto 10:16)
- **Aprobar:** `/publicador aprobar 2026-11-06-westcol-cuanto-hizo-la-plena`

#### TikTok

Envío: `datos/publicador/envios/2026-11-06-westcol-cuanto-hizo-la-plena__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-06-westcol-cuanto-hizo-la-plena:tiktok`

```text
¿Cuánto dinero hizo La Plena? En el directo de Westcol sacan la cuenta: "yo creo que por ahí… 6 millones" 💸 (estimación, no cifra oficial)

¿Crees que hizo más o menos?

Crédito: canal WestCOL, «¿CUANTO DINERO GANO LA PLENA ? 🤑 | WESTCOL». Momento original desde el minuto 10:16: https://youtu.be/XcgyVpbHNlw?t=616

#Westcol #LaPlena #WSound #Beéle #Spotify
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-06-westcol-cuanto-hizo-la-plena__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-06-westcol-cuanto-hizo-la-plena:instagram`

```text
¿Cuánto dinero hizo La Plena? "Yo creo que por ahí… 6 millones" 💸

En el directo de Westcol le ponen número a «La Plena» (W Sound 05, con Beéle y Ovy On The Drums) y explican la cuenta con Spotify y Europa. Son estimaciones dichas en el directo, no cifras oficiales.

¿Crees que hizo más o menos?

Crédito: canal WestCOL, «¿CUANTO DINERO GANO LA PLENA ? 🤑 | WESTCOL». Momento original desde el minuto 10:16: https://youtu.be/XcgyVpbHNlw?t=616

#Westcol #LaPlena #WSound #Beéle #OvyOnTheDrums
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-06-westcol-cuanto-hizo-la-plena__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-06-westcol-cuanto-hizo-la-plena:youtube`

**Título:** ¿Cuánto ganó La Plena? La cuenta en el directo de Westcol (W Sound 05)

**Descripción:**

```text
En el directo de Westcol preguntan cuánto dinero hizo «La Plena» (W Sound 05, con Beéle y Ovy On The Drums): "yo creo que por ahí… 6 millones", con la cuenta de Spotify y Europa. Son estimaciones, no cifras oficiales.

¿Crees que hizo más o menos?

Crédito: canal WestCOL, «¿CUANTO DINERO GANO LA PLENA ? 🤑 | WESTCOL». Momento original desde el minuto 10:16: https://youtu.be/XcgyVpbHNlw?t=616

#Westcol #LaPlena #WSound #Beéle
```

**Etiquetas:** Westcol, La Plena, W Sound 05, Beéle, Ovy On The Drums, Spotify, regalías, música urbana

### 14. 2026-11-05-westcol-dinero-parqueado

- **Gancho:** A Westcol le desespera el dinero parqueado · **Tipo:** `frase` · **Puntaje:** 80 · **Duración:** 28,6 s · **Ventana hasta:** 2026-11-10
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-westcol-dinero-parqueado/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-westcol-dinero-parqueado/ficha.md)
- **Fuente:** https://youtu.be/LgnQHaFVvyo?t=923 (WestCOL, minuto 15:23)
- **Aprobar:** `/publicador aprobar 2026-11-05-westcol-dinero-parqueado`

#### TikTok

Envío: `datos/publicador/envios/2026-11-05-westcol-dinero-parqueado__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-05-westcol-dinero-parqueado:tiktok`

```text
Por qué Westcol no se compra el Lamborghini (todavía) 💸

¿Lambo o invertir?

Crédito: canal WestCOL, «ESTE ES MI NUEVO SET-UP | WESTCOL». Momento original desde el minuto 15:23: https://youtu.be/LgnQHaFVvyo?t=923

#Westcol #Lamborghini #Inversión #Dinero #Emprendimiento
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-05-westcol-dinero-parqueado__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-05-westcol-dinero-parqueado:instagram`

```text
"3.000 millones parqueados que podrían ser 10.000" 💸

Westcol explica qué lo frena para comprar el Lamborghini: "si tengo un Lambo de 3.000 millones parqueado, esos 3.000 millones los pudiera estar generando para hacer 6.000, 10.000. Así es que se hace plata".

¿Lambo o invertir?

Crédito: canal WestCOL, «ESTE ES MI NUEVO SET-UP | WESTCOL». Momento original desde el minuto 15:23: https://youtu.be/LgnQHaFVvyo?t=923

#Westcol #Lamborghini #Inversión #Dinero #Emprendimiento
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-05-westcol-dinero-parqueado__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-05-westcol-dinero-parqueado:youtube`

**Título:** Westcol explica por qué no deja la plata quieta en un carro

**Descripción:**

```text
Westcol explica qué lo frena para comprar el Lamborghini: "si tengo un Lambo de 3.000 millones parqueado, esos 3.000 millones los pudiera estar generando para hacer 6.000, 10.000. Así es que se hace plata".

¿Lambo o invertir?

Crédito: canal WestCOL, «ESTE ES MI NUEVO SET-UP | WESTCOL». Momento original desde el minuto 15:23: https://youtu.be/LgnQHaFVvyo?t=923

#Westcol #Lamborghini #Inversión #Dinero
```

**Etiquetas:** Westcol, Westcol Lamborghini, inversión, dinero, emprendimiento, finanzas

### 15. 2026-11-05-westcol-regateo-revuelto

- **Gancho:** Regateando el Lamborghini de un millón de dólares · **Tipo:** `confrontacion` · **Puntaje:** 79 · **Duración:** 54,3 s · **Ventana hasta:** 2026-11-10
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-westcol-regateo-revuelto/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-westcol-regateo-revuelto/ficha.md)
- **Fuente:** https://youtu.be/KhuFp9eIyVU?t=832 (WestCOL, minuto 13:52)
- **Aprobar:** `/publicador aprobar 2026-11-05-westcol-regateo-revuelto`

#### TikTok

Envío: `datos/publicador/envios/2026-11-05-westcol-regateo-revuelto__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-05-westcol-regateo-revuelto:tiktok`

```text
"Háblame en dólares, yo no hablo en dinero pobre" 😂 El regateo por el Lamborghini Revuelto

¿Cuánto descuento le darías a la ganga?

Crédito: canal WestCOL, «FUI A VER MI PROXIMO SUPER AUTO 🔥 | WESTCOL». Momento original desde el minuto 13:52: https://youtu.be/KhuFp9eIyVU?t=832

#Westcol #Lamborghini #Revuelto #RRAutos #Medellín
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-05-westcol-regateo-revuelto__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-05-westcol-regateo-revuelto:instagram`

```text
Así se regatea un Lamborghini de 1,1 millones de dólares

En RR Autos, con el Lamborghini Revuelto: "¿cuánto cuesta?" "3.670" "Háblame en dólares, yo no hablo en dinero pobre". Y luego, el descuento de la ganga: 10 %, 30 %, publicidad todo el año… todo en tono de broma.

¿Cuánto descuento le darías a la ganga?

Crédito: canal WestCOL, «FUI A VER MI PROXIMO SUPER AUTO 🔥 | WESTCOL». Momento original desde el minuto 13:52: https://youtu.be/KhuFp9eIyVU?t=832

#Westcol #Lamborghini #Revuelto #RRAutos #Medellín
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-05-westcol-regateo-revuelto__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-05-westcol-regateo-revuelto:youtube`

**Título:** Piden el "descuento de la ganga" por el Lamborghini Revuelto

**Descripción:**

```text
En RR Autos, con el Lamborghini Revuelto: "¿cuánto cuesta?" "3.670" "Háblame en dólares, yo no hablo en dinero pobre". Y luego, el descuento de la ganga: 10 %, 30 %, publicidad todo el año… todo en tono de broma.

¿Cuánto descuento le darías a la ganga?

Crédito: canal WestCOL, «FUI A VER MI PROXIMO SUPER AUTO 🔥 | WESTCOL». Momento original desde el minuto 13:52: https://youtu.be/KhuFp9eIyVU?t=832

#Westcol #Lamborghini #Revuelto #RRAutos
```

**Etiquetas:** Westcol, Lamborghini Revuelto, Westcol Lamborghini, RR Autos, regateo, carros de lujo

### 16. 2026-11-06-westcol-pago-por-reaccionar

- **Gancho:** Lo que paga una disquera por reaccionar · **Tipo:** `revelacion` · **Puntaje:** 77 · **Duración:** 51,2 s · **Ventana hasta:** 2026-11-10
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-06-westcol-pago-por-reaccionar/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-06-westcol-pago-por-reaccionar/ficha.md)
- **Fuente:** https://youtu.be/XcgyVpbHNlw?t=37 (WestCOL, minuto 0:37)
- **Aprobar:** `/publicador aprobar 2026-11-06-westcol-pago-por-reaccionar`

#### TikTok

Envío: `datos/publicador/envios/2026-11-06-westcol-pago-por-reaccionar__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-06-westcol-pago-por-reaccionar:tiktok`

```text
Lo que le paga una disquera a un streamer por reaccionar a un tema 💸 "$200.000 en la música no es nada"

¿Cuánto cobrarías tú por reaccionar a una canción?

Crédito: canal WestCOL, «¿CUANTO DINERO GANO LA PLENA ? 🤑 | WESTCOL». Momento original desde el minuto 0:37: https://youtu.be/XcgyVpbHNlw?t=37

#Westcol #Streamers #IndustriaMusical #Kick #Dinero
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-06-westcol-pago-por-reaccionar__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-06-westcol-pago-por-reaccionar:instagram`

```text
"$200.000 en la música no es nada, eso vale un videoclip" 💸

En el directo de Westcol hablan de lo que pagan las disqueras a los streamers: "a mí una disquera me ha pagado $10.000 por reaccionar un tema". Y la pulla: "a usted todavía le falta mucha cancha". Cifras dichas en el directo, sin verificar.

¿Cuánto cobrarías tú por reaccionar a una canción?

Crédito: canal WestCOL, «¿CUANTO DINERO GANO LA PLENA ? 🤑 | WESTCOL». Momento original desde el minuto 0:37: https://youtu.be/XcgyVpbHNlw?t=37

#Westcol #Streamers #IndustriaMusical #Kick #Dinero
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-06-westcol-pago-por-reaccionar__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-06-westcol-pago-por-reaccionar:youtube`

**Título:** Cuánto paga una disquera por reaccionar a un tema | Directo de Westcol

**Descripción:**

```text
En el directo de Westcol hablan de lo que pagan las disqueras a los streamers: "$200.000 en la música no es nada, eso vale un videoclip… a mí una disquera me ha pagado $10.000 por reaccionar un tema". Cifras dichas en el directo, sin verificar.

¿Cuánto cobrarías tú por reaccionar a una canción?

Crédito: canal WestCOL, «¿CUANTO DINERO GANO LA PLENA ? 🤑 | WESTCOL». Momento original desde el minuto 0:37: https://youtu.be/XcgyVpbHNlw?t=37

#Westcol #Streamers #IndustriaMusical #Kick
```

**Etiquetas:** Westcol, streamers, disqueras, industria musical, reacciones, Kick, dinero

### 17. 2026-11-05-revuelto-beneficio-tributario

- **Gancho:** El beneficio tributario del Lambo híbrido · **Tipo:** `consejo` · **Puntaje:** 76 · **Duración:** 46,0 s · **Ventana hasta:** 2026-11-10
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-revuelto-beneficio-tributario/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-revuelto-beneficio-tributario/ficha.md)
- **Fuente:** https://youtu.be/KhuFp9eIyVU?t=293 (WestCOL, minuto 4:53)
- **Aprobar:** `/publicador aprobar 2026-11-05-revuelto-beneficio-tributario`

#### TikTok

Envío: `datos/publicador/envios/2026-11-05-revuelto-beneficio-tributario__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-05-revuelto-beneficio-tributario:tiktok`

```text
Por qué un Lamborghini híbrido puede ser "una compra de negocio", según su vendedor

¿Te lo comprarías por los impuestos?

Crédito: canal WestCOL, «FUI A VER MI PROXIMO SUPER AUTO 🔥 | WESTCOL». Momento original desde el minuto 4:53: https://youtu.be/KhuFp9eIyVU?t=293

#Westcol #Lamborghini #Revuelto #Impuestos #Empresa
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-05-revuelto-beneficio-tributario__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-05-revuelto-beneficio-tributario:instagram`

```text
El beneficio tributario del Lamborghini Revuelto, según su vendedor

En RR Autos le explican a Westcol el beneficio tributario de comprar el Revuelto a nombre de una empresa que facture: "5 % del IVA y el 50 % del valor del carro en la renta a 12 años". Westcol: "A mí me serviría, porque yo facturo". Es lo que se dice en el video, no asesoría tributaria.

¿Te lo comprarías por los impuestos?

Crédito: canal WestCOL, «FUI A VER MI PROXIMO SUPER AUTO 🔥 | WESTCOL». Momento original desde el minuto 4:53: https://youtu.be/KhuFp9eIyVU?t=293

#Westcol #Lamborghini #Revuelto #Impuestos #Empresa
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-05-revuelto-beneficio-tributario__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-05-revuelto-beneficio-tributario:youtube`

**Título:** Westcol escucha el beneficio tributario del Lamborghini Revuelto

**Descripción:**

```text
En RR Autos le explican a Westcol el beneficio tributario de comprar el Revuelto a nombre de una empresa que facture: "5 % del IVA y el 50 % del valor del carro en la renta a 12 años". Westcol: "A mí me serviría, porque yo facturo". Es lo que se dice en el video, no asesoría tributaria.

¿Te lo comprarías por los impuestos?

Crédito: canal WestCOL, «FUI A VER MI PROXIMO SUPER AUTO 🔥 | WESTCOL». Momento original desde el minuto 4:53: https://youtu.be/KhuFp9eIyVU?t=293

#Westcol #Lamborghini #Revuelto #Impuestos
```

**Etiquetas:** Westcol, Lamborghini Revuelto, beneficio tributario, impuestos, empresa, RR Autos

### 18. 2026-11-05-westcol-precio-lambo-bajara

- **Gancho:** Westcol predice cuánto bajará el Lambo · **Tipo:** `prediccion` · **Puntaje:** 75 · **Duración:** 39,2 s · **Ventana hasta:** 2026-11-10
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-westcol-precio-lambo-bajara/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-westcol-precio-lambo-bajara/ficha.md)
- **Fuente:** https://youtu.be/LgnQHaFVvyo?t=515 (WestCOL, minuto 8:35)
- **Aprobar:** `/publicador aprobar 2026-11-05-westcol-precio-lambo-bajara`

#### TikTok

Envío: `datos/publicador/envios/2026-11-05-westcol-precio-lambo-bajara__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-05-westcol-precio-lambo-bajara:tiktok`

```text
Westcol: "Ese Lambo va a bajar a 2.000 millones en 2 o 3 meses"

Comenta si crees que baja; en 3 meses lo vemos

Crédito: canal WestCOL, «ESTE ES MI NUEVO SET-UP | WESTCOL». Momento original desde el minuto 8:35: https://youtu.be/LgnQHaFVvyo?t=515

#Westcol #Lamborghini #Revuelto #Carros #Colombia
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-05-westcol-precio-lambo-bajara__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-05-westcol-precio-lambo-bajara:instagram`

```text
La predicción de Westcol sobre el precio del Lamborghini Revuelto

Westcol no se compra todavía el Lamborghini Revuelto: en su opinión, su precio en Colombia va a bajar a 2.000 millones de pesos "en 2 o 3 meses", cuando empiecen a traer más. ¿Tiene razón?

Comenta si crees que baja; en 3 meses lo vemos

Crédito: canal WestCOL, «ESTE ES MI NUEVO SET-UP | WESTCOL». Momento original desde el minuto 8:35: https://youtu.be/LgnQHaFVvyo?t=515

#Westcol #Lamborghini #Revuelto #Carros #Colombia
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-05-westcol-precio-lambo-bajara__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-05-westcol-precio-lambo-bajara:youtube`

**Título:** ¿Bajará el Lamborghini Revuelto? Westcol cree que sí

**Descripción:**

```text
Westcol no se compra todavía el Lamborghini Revuelto: en su opinión, su precio en Colombia va a bajar a 2.000 millones de pesos "en 2 o 3 meses", cuando empiecen a traer más. ¿Tiene razón?

Comenta si crees que baja; en 3 meses lo vemos

Crédito: canal WestCOL, «ESTE ES MI NUEVO SET-UP | WESTCOL». Momento original desde el minuto 8:35: https://youtu.be/LgnQHaFVvyo?t=515

#Westcol #Lamborghini #Revuelto #Carros
```

**Etiquetas:** Westcol, Lamborghini Revuelto, precio Lamborghini, carros, Colombia, predicción

### 19. 2026-11-06-kick-house-coming-soon

- **Gancho:** La Ganga anuncia la Kick House · **Tipo:** `revelacion` · **Puntaje:** 73 · **Duración:** 32,3 s · **Ventana hasta:** 2026-11-10
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-06-kick-house-coming-soon/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-06-kick-house-coming-soon/ficha.md)
- **Fuente:** https://youtu.be/hD58PIkuFVA?t=374 (Samulx, minuto 6:14)
- **Oportunidad del Cazador:** `tema-samulx-llega-a-colombia`
- **Aprobar:** `/publicador aprobar 2026-11-06-kick-house-coming-soon`

#### TikTok

Envío: `datos/publicador/envios/2026-11-06-kick-house-coming-soon__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-06-kick-house-coming-soon:tiktok`

```text
"Kick House coming soon" 👀 La Ganga adelanta lo que viene con Samulx en Colombia

¿Quién debería entrar a la Kick House?

Crédito: canal Samulx, «POR FIN ESTOY EN COLOMBIA 🙂🇨🇴 CONOCIENDO LA CASA DE WEST | Samulx». Momento original desde el minuto 6:14: https://youtu.be/hD58PIkuFVA?t=374

#KickHouse #Samulx #Westcol #LaGanga #Kick
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-06-kick-house-coming-soon__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-06-kick-house-coming-soon:instagram`

```text
La Ganga adelanta la Kick House 👀

"Kick House coming soon, y no voy a decir más nada". Y aclara: "Sami se va a quedar mucho tiempo porque la idea es que hagamos mucho contenido". Es un adelanto: no hay fecha.

¿Quién debería entrar a la Kick House?

Crédito: canal Samulx, «POR FIN ESTOY EN COLOMBIA 🙂🇨🇴 CONOCIENDO LA CASA DE WEST | Samulx». Momento original desde el minuto 6:14: https://youtu.be/hD58PIkuFVA?t=374

#KickHouse #Samulx #Westcol #LaGanga #Kick
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-06-kick-house-coming-soon__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-06-kick-house-coming-soon:youtube`

**Título:** La Ganga adelanta la Kick House con Samulx: "coming soon"

**Descripción:**

```text
"Kick House coming soon, y no voy a decir más nada". La Ganga aclara que Samulx se queda "mucho tiempo porque la idea es que hagamos mucho contenido". Es un adelanto, sin fecha.

¿Quién debería entrar a la Kick House?

Crédito: canal Samulx, «POR FIN ESTOY EN COLOMBIA 🙂🇨🇴 CONOCIENDO LA CASA DE WEST | Samulx». Momento original desde el minuto 6:14: https://youtu.be/hD58PIkuFVA?t=374

#KickHouse #Samulx #Westcol #Kick
```

**Etiquetas:** Kick House, Samulx, Westcol, La Ganga, Kick, Medellín, streamers

### 20. 2026-11-05-maluma-juan-luis-primero

- **Gancho:** Maluma: Juan Luis primero que Maluma · **Tipo:** `emotivo` · **Puntaje:** 71 · **Duración:** 28,6 s · **Ventana hasta:** 2026-11-10
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-maluma-juan-luis-primero/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-maluma-juan-luis-primero/ficha.md)
- **Fuente:** https://youtu.be/iNxDQVDIer8?t=3435 (LUZU TV, minuto 57:15)
- **Aprobar:** `/publicador aprobar 2026-11-05-maluma-juan-luis-primero`

#### TikTok

Envío: `datos/publicador/envios/2026-11-05-maluma-juan-luis-primero__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-05-maluma-juan-luis-primero:tiktok`

```text
Maluma: "si la gente quiere amar a Juan Luis primero que a Maluma, para mí esa es la prioridad" ❤️

¿Te gusta más Maluma o Juan Luis?

Crédito: canal LUZU TV, «#FMLUZU | MALUMA NOS LLAMÓ EN VIVO + FERBO EN CONTRA DE DOMI…». Momento original desde el minuto 57:15: https://youtu.be/iNxDQVDIer8?t=3435

#Maluma #JuanLuis #FMLuzu #MúsicaUrbana #Medellín
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-05-maluma-juan-luis-primero__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-05-maluma-juan-luis-primero:instagram`

```text
Maluma y lo más importante para él ❤️

En FM Luzu, sobre su nuevo álbum: "ya tampoco puedo ocultar quién soy… mi familia para mí es lo más importante… si la gente quiere amar a Juan Luis primero que a Maluma, para mí esa es la prioridad".

¿Te gusta más Maluma o Juan Luis?

Crédito: canal LUZU TV, «#FMLUZU | MALUMA NOS LLAMÓ EN VIVO + FERBO EN CONTRA DE DOMI…». Momento original desde el minuto 57:15: https://youtu.be/iNxDQVDIer8?t=3435

#Maluma #JuanLuis #FMLuzu #Luzu #MúsicaUrbana
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-05-maluma-juan-luis-primero__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-05-maluma-juan-luis-primero:youtube`

**Título:** Maluma: "si la gente quiere amar a Juan Luis primero que a Maluma" | FM Luzu

**Descripción:**

```text
Maluma, en FM Luzu, sobre su nuevo álbum: "ya tampoco puedo ocultar quién soy… mi familia para mí es lo más importante".

¿Te gusta más Maluma o Juan Luis?

Crédito: canal LUZU TV, «#FMLUZU | MALUMA NOS LLAMÓ EN VIVO + FERBO EN CONTRA DE DOMI…». Momento original desde el minuto 57:15: https://youtu.be/iNxDQVDIer8?t=3435

#Maluma #JuanLuis #FMLuzu #MúsicaUrbana
```

**Etiquetas:** Maluma, Juan Luis, FM Luzu, Luzu TV, nuevo álbum, música urbana, Medellín

### 21. 2026-11-05-westcol-asi-pagaria-el-lambo

- **Gancho:** Así pagaría Westcol el Lamborghini · **Tipo:** `frase` · **Puntaje:** 71 · **Duración:** 35,1 s · **Ventana hasta:** 2026-11-10
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-westcol-asi-pagaria-el-lambo/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-westcol-asi-pagaria-el-lambo/ficha.md)
- **Fuente:** https://youtu.be/KhuFp9eIyVU?t=1145 (WestCOL, minuto 19:05)
- **Aprobar:** `/publicador aprobar 2026-11-05-westcol-asi-pagaria-el-lambo`

#### TikTok

Envío: `datos/publicador/envios/2026-11-05-westcol-asi-pagaria-el-lambo__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-05-westcol-asi-pagaria-el-lambo:tiktok`

```text
Así pagaría Westcol el Lamborghini Revuelto 🏎️ "Le doy 1.000 palos de inicial, la Hammer, y lo otro lo saco a crédito"

¿Tú lo comprarías así?

Crédito: canal WestCOL, «FUI A VER MI PROXIMO SUPER AUTO 🔥 | WESTCOL». Momento original desde el minuto 19:05: https://youtu.be/KhuFp9eIyVU?t=1145

#Westcol #Lamborghini #Revuelto #RRAutos #Carros
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-05-westcol-asi-pagaria-el-lambo__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-05-westcol-asi-pagaria-el-lambo:instagram`

```text
"Le doy 1.000 palos de inicial, la Hammer, y lo otro lo saco a crédito" 🏎️

En RR Autos, Westcol hace la cuenta para el Lamborghini Revuelto. ¿Y por qué no lo hace? "Porque es un hombre estratégico".

¿Tú lo comprarías así?

Crédito: canal WestCOL, «FUI A VER MI PROXIMO SUPER AUTO 🔥 | WESTCOL». Momento original desde el minuto 19:05: https://youtu.be/KhuFp9eIyVU?t=1145

#Westcol #Lamborghini #Revuelto #RRAutos #Carros
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-05-westcol-asi-pagaria-el-lambo__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-05-westcol-asi-pagaria-el-lambo:youtube`

**Título:** Así pagaría Westcol el Lamborghini Revuelto: inicial, la Hammer y crédito

**Descripción:**

```text
En RR Autos, Westcol explica cómo pagaría el Revuelto: "le doy 1.000 palos de inicial, la Hammer, y lo otro lo saco a crédito". ¿Por qué no lo hace? "Porque es un hombre estratégico".

¿Tú lo comprarías así?

Crédito: canal WestCOL, «FUI A VER MI PROXIMO SUPER AUTO 🔥 | WESTCOL». Momento original desde el minuto 19:05: https://youtu.be/KhuFp9eIyVU?t=1145

#Westcol #Lamborghini #Revuelto #RRAutos
```

**Etiquetas:** Westcol, Lamborghini Revuelto, Lamborghini, RR Autos, carros de lujo, Medellín, Kick

### 22. 2026-11-05-maluma-sos-maluma

- **Gancho:** Maluma llama en vivo a FM Luzu · **Tipo:** `reaccion` · **Puntaje:** 69 · **Duración:** 25,7 s · **Ventana hasta:** 2026-11-10
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-maluma-sos-maluma/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-maluma-sos-maluma/ficha.md)
- **Fuente:** https://youtu.be/iNxDQVDIer8?t=2671 (LUZU TV, minuto 44:31)
- **Aprobar:** `/publicador aprobar 2026-11-05-maluma-sos-maluma`

#### TikTok

Envío: `datos/publicador/envios/2026-11-05-maluma-sos-maluma__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-05-maluma-sos-maluma:tiktok`

```text
"¿Sos Maluma?" "Afirmativo" 😂 La llamada sorpresa a FM Luzu

¿Qué le preguntarías a Maluma?

Crédito: canal LUZU TV, «#FMLUZU | MALUMA NOS LLAMÓ EN VIVO + FERBO EN CONTRA DE DOMI…». Momento original desde el minuto 44:31: https://youtu.be/iNxDQVDIer8?t=2671

#Maluma #FMLuzu #Luzu #Argentina #MúsicaUrbana
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-05-maluma-sos-maluma__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-05-maluma-sos-maluma:instagram`

```text
Maluma llama en vivo a FM Luzu 📞

"¿Estás en Argentina?" "No, pero pronto estaré por allá, estoy loco por volver". "¿Sos Maluma?" "Afirmativo".

¿Qué le preguntarías a Maluma?

Crédito: canal LUZU TV, «#FMLUZU | MALUMA NOS LLAMÓ EN VIVO + FERBO EN CONTRA DE DOMI…». Momento original desde el minuto 44:31: https://youtu.be/iNxDQVDIer8?t=2671

#Maluma #FMLuzu #Luzu #Argentina #MúsicaUrbana
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-05-maluma-sos-maluma__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-05-maluma-sos-maluma:youtube`

**Título:** La reacción de FM Luzu cuando Maluma llamó en vivo

**Descripción:**

```text
FM Luzu recibe una videollamada sorpresa: "¿Estás en Argentina?" "No, pero pronto estaré por allá, estoy loco por volver". "¿Sos Maluma?" "Afirmativo".

¿Qué le preguntarías a Maluma?

Crédito: canal LUZU TV, «#FMLUZU | MALUMA NOS LLAMÓ EN VIVO + FERBO EN CONTRA DE DOMI…». Momento original desde el minuto 44:31: https://youtu.be/iNxDQVDIer8?t=2671

#Maluma #FMLuzu #Luzu #Argentina
```

**Etiquetas:** Maluma, FM Luzu, Luzu TV, Argentina, videollamada, música urbana

### 23. 2026-11-05-maluma-tiempo-largo-argentina

- **Gancho:** Maluma: 'más pronto de lo que esperan' · **Tipo:** `revelacion` · **Puntaje:** 69 · **Duración:** 27,7 s · **Ventana hasta:** 2026-11-10
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-maluma-tiempo-largo-argentina/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-maluma-tiempo-largo-argentina/ficha.md)
- **Fuente:** https://youtu.be/iNxDQVDIer8?t=3316 (LUZU TV, minuto 55:16)
- **Aprobar:** `/publicador aprobar 2026-11-05-maluma-tiempo-largo-argentina`

#### TikTok

Envío: `datos/publicador/envios/2026-11-05-maluma-tiempo-largo-argentina__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-05-maluma-tiempo-largo-argentina:tiktok`

```text
Maluma: "me voy a pasar un tiempo largo" en Argentina 👀 "Es más pronto de lo que ustedes esperan"

¿Dónde lo quieres ver?

Crédito: canal LUZU TV, «#FMLUZU | MALUMA NOS LLAMÓ EN VIVO + FERBO EN CONTRA DE DOMI…». Momento original desde el minuto 55:16: https://youtu.be/iNxDQVDIer8?t=3316

#Maluma #Argentina #FMLuzu #Gira #MúsicaUrbana
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-05-maluma-tiempo-largo-argentina__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-05-maluma-tiempo-largo-argentina:instagram`

```text
"Es más pronto de lo que ustedes esperan" 👀 Maluma

En FM Luzu, sobre su vuelta a Argentina: "yo creo que me voy a pasar un tiempo largo… estamos programando conciertos brutales". No dio fechas.

¿Dónde lo quieres ver?

Crédito: canal LUZU TV, «#FMLUZU | MALUMA NOS LLAMÓ EN VIVO + FERBO EN CONTRA DE DOMI…». Momento original desde el minuto 55:16: https://youtu.be/iNxDQVDIer8?t=3316

#Maluma #Argentina #FMLuzu #Gira #MúsicaUrbana
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-05-maluma-tiempo-largo-argentina__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-05-maluma-tiempo-largo-argentina:youtube`

**Título:** Maluma adelanta su vuelta a Argentina: "más pronto de lo que esperan" | FM Luzu

**Descripción:**

```text
Maluma, en FM Luzu, sobre su vuelta a Argentina: "yo creo que me voy a pasar un tiempo largo… estamos programando conciertos brutales… es más pronto de lo que ustedes esperan". No dio fechas.

¿Dónde lo quieres ver?

Crédito: canal LUZU TV, «#FMLUZU | MALUMA NOS LLAMÓ EN VIVO + FERBO EN CONTRA DE DOMI…». Momento original desde el minuto 55:16: https://youtu.be/iNxDQVDIer8?t=3316

#Maluma #Argentina #FMLuzu #MúsicaUrbana
```

**Etiquetas:** Maluma, Argentina, FM Luzu, Luzu TV, conciertos, gira, música urbana

### 24. 2026-11-06-lonche-un-ano-despues

- **Gancho:** Así llegó Lonche hace un año · **Tipo:** `historia` · **Puntaje:** 76 · **Duración:** 35,2 s · **Ventana hasta:** 2026-11-12
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-06-lonche-un-ano-despues/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-06-lonche-un-ano-despues/ficha.md)
- **Fuente:** https://youtu.be/XcgyVpbHNlw?t=1128 (WestCOL, minuto 18:48)
- **Aprobar:** `/publicador aprobar 2026-11-06-lonche-un-ano-despues`

#### TikTok

Envío: `datos/publicador/envios/2026-11-06-lonche-un-ano-despues__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-06-lonche-un-ano-despues:tiktok`

```text
Cómo llegó Lonche a una fiesta hace un año, contado en el directo de Westcol. Un año después: "Ferrari, Rolls Royce" 🏎️

¿Quién ha subido más rápido: Lonche o Westcol?

Crédito: canal WestCOL, «¿CUANTO DINERO GANO LA PLENA ? 🤑 | WESTCOL». Momento original desde el minuto 18:48: https://youtu.be/XcgyVpbHNlw?t=1128

#Lonche #Westcol #Kick #Streamers #México
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-06-lonche-un-ano-despues__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-06-lonche-un-ano-despues:instagram`

```text
"Un año después… Ferrari, Rolls Royce"

En el directo de Westcol recuerdan cómo llegó Lonche a una fiesta familiar hace un año, "cuando todavía no tenía nada", y lo comparan con lo de hoy. Lonche no sale en el clip: lo cuentan de él.

¿Quién ha subido más rápido: Lonche o Westcol?

Crédito: canal WestCOL, «¿CUANTO DINERO GANO LA PLENA ? 🤑 | WESTCOL». Momento original desde el minuto 18:48: https://youtu.be/XcgyVpbHNlw?t=1128

#Lonche #Westcol #LaGanga #Kick #Streamers
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-06-lonche-un-ano-despues__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-06-lonche-un-ano-despues:youtube`

**Título:** Cómo llegó Lonche hace un año, contado en el directo de Westcol

**Descripción:**

```text
En el directo de Westcol recuerdan cómo llegó Lonche a una fiesta familiar hace un año, "cuando todavía no tenía nada", y lo comparan con hoy: "un año después… Ferrari, Rolls Royce". Lonche no sale en el clip.

¿Quién ha subido más rápido: Lonche o Westcol?

Crédito: canal WestCOL, «¿CUANTO DINERO GANO LA PLENA ? 🤑 | WESTCOL». Momento original desde el minuto 18:48: https://youtu.be/XcgyVpbHNlw?t=1128

#Lonche #Westcol #Kick #Streamers
```

**Etiquetas:** Lonche, Westcol, Kick, streamers, Ferrari, Rolls Royce, México

### 25. 2026-11-06-westcol-si-fuera-mexicano

- **Gancho:** Si hubiera nacido en México… · **Tipo:** `frase` · **Puntaje:** 75 · **Duración:** 63,4 s · **Ventana hasta:** 2026-11-12
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-06-westcol-si-fuera-mexicano/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-06-westcol-si-fuera-mexicano/ficha.md)
- **Fuente:** https://youtu.be/XcgyVpbHNlw?t=1166 (WestCOL, minuto 19:26)
- **Aprobar:** `/publicador aprobar 2026-11-06-westcol-si-fuera-mexicano`

#### TikTok

Envío: `datos/publicador/envios/2026-11-06-westcol-si-fuera-mexicano__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-06-westcol-si-fuera-mexicano:tiktok`

```text
"Si yo hubiera nacido en México, debería tener por ahí 15, 20 millones de seguidores" 🇲🇽🇨🇴 La comparación en el directo de Westcol

¿Tiene razón? ¿México o Colombia?

Crédito: canal WestCOL, «¿CUANTO DINERO GANO LA PLENA ? 🤑 | WESTCOL». Momento original desde el minuto 19:26: https://youtu.be/XcgyVpbHNlw?t=1166

#Westcol #México #Colombia #Streamers #CreadoresDeContenido
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-06-westcol-si-fuera-mexicano__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-06-westcol-si-fuera-mexicano:instagram`

```text
México vs. Colombia: ¿por qué los números de los creadores mexicanos son más grandes? 🇲🇽🇨🇴

En el directo de Westcol: "si yo hubiera nacido en México, debería tener por ahí 15, 20 millones de seguidores por lo grande que es México". Comparan un número 1 en México ("un millón de streams") con uno en Colombia ("300.000"). Cifras dichas en el directo.

¿Tiene razón? ¿México o Colombia?

Crédito: canal WestCOL, «¿CUANTO DINERO GANO LA PLENA ? 🤑 | WESTCOL». Momento original desde el minuto 19:26: https://youtu.be/XcgyVpbHNlw?t=1166

#Westcol #México #Colombia #Streamers #CreadoresDeContenido
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-06-westcol-si-fuera-mexicano__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-06-westcol-si-fuera-mexicano:youtube`

**Título:** Un número 1 en México vs. un número 1 en Colombia | Directo de Westcol

**Descripción:**

```text
"Si yo hubiera nacido en México, debería tener por ahí 15, 20 millones de seguidores". En el directo de Westcol comparan un número 1 en México ("un millón de streams") con uno en Colombia ("300.000"). Cifras dichas en el directo.

¿Tiene razón? ¿México o Colombia?

Crédito: canal WestCOL, «¿CUANTO DINERO GANO LA PLENA ? 🤑 | WESTCOL». Momento original desde el minuto 19:26: https://youtu.be/XcgyVpbHNlw?t=1166

#Westcol #México #Colombia #Streamers
```

**Etiquetas:** Westcol, México, Colombia, streamers, Spotify, creadores de contenido, Kick

### 26. 2026-11-06-ovy-cancion-en-pelicula

- **Gancho:** Lo que más dinero deja en la música · **Tipo:** `consejo` · **Puntaje:** 73 · **Duración:** 27,0 s · **Ventana hasta:** 2026-11-12
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-06-ovy-cancion-en-pelicula/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-06-ovy-cancion-en-pelicula/ficha.md)
- **Fuente:** https://youtu.be/XcgyVpbHNlw?t=726 (WestCOL, minuto 12:06)
- **Aprobar:** `/publicador aprobar 2026-11-06-ovy-cancion-en-pelicula`

#### TikTok

Envío: `datos/publicador/envios/2026-11-06-ovy-cancion-en-pelicula__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-06-ovy-cancion-en-pelicula:tiktok`

```text
Lo que más dinero deja en la música, según el consejo de Ovy On The Drums que contaron en el directo de Westcol 🎬💸

¿Qué canción latina debería sonar en una película?

Crédito: canal WestCOL, «¿CUANTO DINERO GANO LA PLENA ? 🤑 | WESTCOL». Momento original desde el minuto 12:06: https://youtu.be/XcgyVpbHNlw?t=726

#OvyOnTheDrums #Westcol #IndustriaMusical #Regalías #MúsicaUrbana
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-06-ovy-cancion-en-pelicula__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-06-ovy-cancion-en-pelicula:instagram`

```text
"Lo que más deja dinero es que pongan una canción tuya en una película" 🎬💸

En el directo de Westcol cuentan lo que les dijo Ovy On The Drums: con una canción en una película como Los Avengers, "de una a 10 palos". El ejemplo: Wiz Khalifa con la de Rápido y furioso. Ovy no sale en el clip y las cifras no están verificadas.

¿Qué canción latina debería sonar en una película?

Crédito: canal WestCOL, «¿CUANTO DINERO GANO LA PLENA ? 🤑 | WESTCOL». Momento original desde el minuto 12:06: https://youtu.be/XcgyVpbHNlw?t=726

#OvyOnTheDrums #Westcol #IndustriaMusical #Regalías #MúsicaUrbana
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-06-ovy-cancion-en-pelicula__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-06-ovy-cancion-en-pelicula:youtube`

**Título:** El consejo de Ovy On The Drums sobre el dinero en la música | Directo de Westcol

**Descripción:**

```text
En el directo de Westcol cuentan lo que les dijo Ovy On The Drums: "lo que más deja dinero es que pongan una canción tuya en una película". El ejemplo: Wiz Khalifa con la de Rápido y furioso. Ovy no sale en el clip y las cifras no están verificadas.

¿Qué canción latina debería sonar en una película?

Crédito: canal WestCOL, «¿CUANTO DINERO GANO LA PLENA ? 🤑 | WESTCOL». Momento original desde el minuto 12:06: https://youtu.be/XcgyVpbHNlw?t=726

#OvyOnTheDrums #Westcol #IndustriaMusical #Regalías
```

**Etiquetas:** Ovy On The Drums, Westcol, W Sound, industria musical, regalías, música en películas, Wiz Khalifa

### 27. 2026-11-06-bad-bunny-luian-historia

- **Gancho:** Bad Bunny y Luian: la historia que cuentan · **Tipo:** `historia` · **Puntaje:** 69 · **Duración:** 37,6 s · **Ventana hasta:** 2026-11-12
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-06-bad-bunny-luian-historia/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-06-bad-bunny-luian-historia/ficha.md)
- **Fuente:** https://youtu.be/XcgyVpbHNlw?t=873 (WestCOL, minuto 14:33)
- **Aprobar:** `/publicador aprobar 2026-11-06-bad-bunny-luian-historia`

#### TikTok

Envío: `datos/publicador/envios/2026-11-06-bad-bunny-luian-historia__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-06-bad-bunny-luian-historia:tiktok`

```text
La historia (sin confirmar) de Bad Bunny y DJ Luian que contaron en el directo de Westcol

¿Tú lo habrías hecho?

Crédito: canal WestCOL, «¿CUANTO DINERO GANO LA PLENA ? 🤑 | WESTCOL». Momento original desde el minuto 14:33: https://youtu.be/XcgyVpbHNlw?t=873

#BadBunny #DJLuian #Westcol #IndustriaMusical #MúsicaUrbana
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-06-bad-bunny-luian-historia__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-06-bad-bunny-luian-historia:instagram`

```text
"Creo que le dio 3 millones de dólares, algo así": lo que se cuenta de Bad Bunny y DJ Luian

En el directo de Westcol cuentan, "más o menos así, no tengo los números exactos", que Bad Bunny le habría recomprado a DJ Luian el porcentaje que tenía de él. Es una versión sin confirmar; ninguno de los dos sale en el clip.

¿Tú lo habrías hecho?

Crédito: canal WestCOL, «¿CUANTO DINERO GANO LA PLENA ? 🤑 | WESTCOL». Momento original desde el minuto 14:33: https://youtu.be/XcgyVpbHNlw?t=873

#BadBunny #DJLuian #Westcol #IndustriaMusical #MúsicaUrbana
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-06-bad-bunny-luian-historia__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-06-bad-bunny-luian-historia:youtube`

**Título:** Lo que se cuenta del negocio entre Bad Bunny y DJ Luian (versión sin confirmar)

**Descripción:**

```text
En el directo de Westcol cuentan, "más o menos así, no tengo los números exactos", que Bad Bunny le habría recomprado a DJ Luian el porcentaje que tenía de él: "creo que le dio 3 millones de dólares, algo así". Es una versión sin confirmar.

¿Tú lo habrías hecho?

Crédito: canal WestCOL, «¿CUANTO DINERO GANO LA PLENA ? 🤑 | WESTCOL». Momento original desde el minuto 14:33: https://youtu.be/XcgyVpbHNlw?t=873

#BadBunny #DJLuian #Westcol #MúsicaUrbana
```

**Etiquetas:** Bad Bunny, DJ Luian, Westcol, industria musical, música urbana, reguetón

### 28. 2026-11-06-samulx-peleador-sorpresa

- **Gancho:** Samulx confirma: pelea en Stream Fighters 5 · **Tipo:** `revelacion` · **Puntaje:** 88 · **Duración:** 51,7 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-06-samulx-peleador-sorpresa/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-06-samulx-peleador-sorpresa/ficha.md)
- **Fuente:** https://youtu.be/XvSs7RaRxzA?t=455 (Live Samulx, minuto 7:35)
- **Oportunidad del Cazador:** `tema-stream-fighters-5`
- **Aprobar:** `/publicador aprobar 2026-11-06-samulx-peleador-sorpresa`

#### TikTok

Envío: `datos/publicador/envios/2026-11-06-samulx-peleador-sorpresa__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-06-samulx-peleador-sorpresa:tiktok`

```text
Samulx es el peleador sorpresa de Stream Fighters 5 🥊 "Los veo el 14 de noviembre en Bogotá"

¿Contra quién debería pelear Samulx?

Crédito: canal Live Samulx, «Peleare en Stream Fighters | Westcol quiere cargar a CHIARA, Samulx». Momento original desde el minuto 7:35: https://youtu.be/XvSs7RaRxzA?t=455

#Samulx #StreamFighters5 #Westcol #Boxeo #Kick
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-06-samulx-peleador-sorpresa__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-06-samulx-peleador-sorpresa:instagram`

```text
"Soy el peleador sorpresa": Samulx pelea el 14 de noviembre en Bogotá 🥊

Enseña el video de su anuncio y lo confirma en directo: "Sí, yo voy a ser el peleador sorpresa… a mi amigo no lo iba a dejar solo". No dice contra quién pelea.

¿Contra quién debería pelear? Comenta tu predicción.

Crédito: canal Live Samulx, «Peleare en Stream Fighters | Westcol quiere cargar a CHIARA, Samulx». Momento original desde el minuto 7:35: https://youtu.be/XvSs7RaRxzA?t=455

#Samulx #StreamFighters5 #StreamFighters #Westcol #Boxeo
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-06-samulx-peleador-sorpresa__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-06-samulx-peleador-sorpresa:youtube`

**Título:** Samulx confirma: es el peleador sorpresa de Stream Fighters 5

**Descripción:**

```text
Samulx enseña el video de su anuncio ("soy el peleador sorpresa de Stream Fighters, los veo el 14 de noviembre en Bogotá") y lo confirma en directo: "a mi amigo no lo iba a dejar solo".

¿Contra quién debería pelear?

Crédito: canal Live Samulx, «Peleare en Stream Fighters | Westcol quiere cargar a CHIARA, Samulx». Momento original desde el minuto 7:35: https://youtu.be/XvSs7RaRxzA?t=455

#Samulx #StreamFighters5 #Boxeo #Kick
```

**Etiquetas:** Samulx, Stream Fighters 5, Stream Fighters, peleador sorpresa, Westcol, boxeo, Kick, Live Samulx

### 29. 2026-11-05-westcol-robot-sin-seguridad

- **Gancho:** Westcol le quitará la seguridad al robot · **Tipo:** `revelacion` · **Puntaje:** 83 · **Duración:** 60,4 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-westcol-robot-sin-seguridad/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-westcol-robot-sin-seguridad/ficha.md)
- **Fuente:** https://youtu.be/Xrwm98iaWY8?t=40 (WestCOL, minuto 0:40)
- **Oportunidad del Cazador:** `tema-stream-fighters-5`
- **Aprobar:** `/publicador aprobar 2026-11-05-westcol-robot-sin-seguridad`

#### TikTok

Envío: `datos/publicador/envios/2026-11-05-westcol-robot-sin-seguridad__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-05-westcol-robot-sin-seguridad:tiktok`

```text
Westcol va a quitarle la seguridad a su robot para Stream Fighters 🤖

¿Lo dejarías pelear sin seguridad?

Crédito: canal WestCOL, «SAQUE A LA CALLE POR PRIMERA VEZ A MI ROBOT DE $100.000 | WESTCOL». Momento original desde el minuto 0:40: https://youtu.be/Xrwm98iaWY8?t=40

#Westcol #StreamFighters #Robot #Kick #Streamers
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-05-westcol-robot-sin-seguridad__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-05-westcol-robot-sin-seguridad:instagram`

```text
"Va a quedar más peligroso que RoboCop" 🤖

Westcol cuenta que van a venir técnicos a quitarle las medidas de seguridad a su robot, que lo usará en Stream Fighters y que, según le contó un socio, otro robot "le arrancó un dedo a un trabajador". ¿Es buena idea?

¿Lo dejarías pelear sin seguridad?

Crédito: canal WestCOL, «SAQUE A LA CALLE POR PRIMERA VEZ A MI ROBOT DE $100.000 | WESTCOL». Momento original desde el minuto 0:40: https://youtu.be/Xrwm98iaWY8?t=40

#Westcol #StreamFighters #Robot #Kick #Streamers
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-05-westcol-robot-sin-seguridad__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-05-westcol-robot-sin-seguridad:youtube`

**Título:** Westcol va a quitarle la seguridad a su robot de 100.000 dólares

**Descripción:**

```text
Westcol cuenta que van a venir técnicos a quitarle las medidas de seguridad a su robot, que lo usará en Stream Fighters y que, según le contó un socio, otro robot "le arrancó un dedo a un trabajador". ¿Es buena idea?

¿Lo dejarías pelear sin seguridad?

Crédito: canal WestCOL, «SAQUE A LA CALLE POR PRIMERA VEZ A MI ROBOT DE $100.000 | WESTCOL». Momento original desde el minuto 0:40: https://youtu.be/Xrwm98iaWY8?t=40

#Westcol #StreamFighters #Robot #Kick
```

**Etiquetas:** Westcol, Westcol robot, Stream Fighters 5, robot humanoide, Kick, streamers Colombia

### 30. 2026-11-05-westcol-negocio-blessd-discoteca

- **Gancho:** Westcol cuenta el negocio que hizo con Blessd · **Tipo:** `historia` · **Puntaje:** 83 · **Duración:** 54,3 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-westcol-negocio-blessd-discoteca/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-westcol-negocio-blessd-discoteca/ficha.md)
- **Fuente:** https://youtu.be/LgnQHaFVvyo?t=994 (WestCOL, minuto 16:34)
- **Oportunidad del Cazador:** `tema-stream-fighters-5`
- **Aprobar:** `/publicador aprobar 2026-11-05-westcol-negocio-blessd-discoteca`

#### TikTok

Envío: `datos/publicador/envios/2026-11-05-westcol-negocio-blessd-discoteca__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-05-westcol-negocio-blessd-discoteca:tiktok`

```text
Westcol cuenta que le dio su camioneta a Blessd a cambio de 3 canciones 💸

¿Fue buen negocio para los dos?

Crédito: canal WestCOL, «ESTE ES MI NUEVO SET-UP | WESTCOL». Momento original desde el minuto 16:34: https://youtu.be/LgnQHaFVvyo?t=994

#Westcol #Blessd #StreamFighters #Medellín #Kick
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-05-westcol-negocio-blessd-discoteca__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-05-westcol-negocio-blessd-discoteca:instagram`

```text
El negocio de Westcol con Blessd en su discoteca 💸

Westcol cuenta cómo hacía negocios con artistas en su discoteca: a Blessd ("el Bendito") le dio su camioneta a cambio de cantar tres canciones. A pocos días de enfrentarse en Stream Fighters 5.

¿Fue buen negocio para los dos?

Crédito: canal WestCOL, «ESTE ES MI NUEVO SET-UP | WESTCOL». Momento original desde el minuto 16:34: https://youtu.be/LgnQHaFVvyo?t=994

#Westcol #Blessd #StreamFighters #Medellín #Kick
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-05-westcol-negocio-blessd-discoteca__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-05-westcol-negocio-blessd-discoteca:youtube`

**Título:** Westcol cuenta el negocio que hizo con Blessd en su discoteca

**Descripción:**

```text
Westcol cuenta cómo hacía negocios con artistas en su discoteca: a Blessd ("el Bendito") le dio su camioneta a cambio de cantar tres canciones. A pocos días de enfrentarse en Stream Fighters 5.

¿Fue buen negocio para los dos?

Crédito: canal WestCOL, «ESTE ES MI NUEVO SET-UP | WESTCOL». Momento original desde el minuto 16:34: https://youtu.be/LgnQHaFVvyo?t=994

#Westcol #Blessd #StreamFighters #Medellín
```

**Etiquetas:** Westcol, Blessd, Westcol Blessd, Stream Fighters 5, discoteca, negocios

### 31. 2026-11-05-westcol-robot-ascensor

- **Gancho:** La primera vez del robot en un ascensor · **Tipo:** `humor` · **Puntaje:** 80 · **Duración:** 38,4 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-westcol-robot-ascensor/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-westcol-robot-ascensor/ficha.md)
- **Fuente:** https://youtu.be/Xrwm98iaWY8?t=968 (WestCOL, minuto 16:08)
- **Oportunidad del Cazador:** `formato-robot-humanoide-en-la-calle`
- **Aprobar:** `/publicador aprobar 2026-11-05-westcol-robot-ascensor`

#### TikTok

Envío: `datos/publicador/envios/2026-11-05-westcol-robot-ascensor__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-05-westcol-robot-ascensor:tiktok`

```text
Metieron el robot de Westcol en un ascensor… "si empieza a dar puño aquí, morimos todos"

¿Te subirías a ese ascensor?

Crédito: canal WestCOL, «SAQUE A LA CALLE POR PRIMERA VEZ A MI ROBOT DE $100.000 | WESTCOL». Momento original desde el minuto 16:08: https://youtu.be/Xrwm98iaWY8?t=968

#Westcol #Robot #StreamFighters #Kick #Humor
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-05-westcol-robot-ascensor__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-05-westcol-robot-ascensor:instagram`

```text
El robot de Westcol en un ascensor 😳🤖

Westcol sube a su robot humanoide a un ascensor del centro comercial: "eso pesa demasiado… si empieza a dar puño aquí, morimos todos". Y el robot manda un puñito.

¿Te subirías a ese ascensor?

Crédito: canal WestCOL, «SAQUE A LA CALLE POR PRIMERA VEZ A MI ROBOT DE $100.000 | WESTCOL». Momento original desde el minuto 16:08: https://youtu.be/Xrwm98iaWY8?t=968

#Westcol #Robot #StreamFighters #Kick #Humor
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-05-westcol-robot-ascensor__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-05-westcol-robot-ascensor:youtube`

**Título:** Westcol sube a su robot humanoide a un ascensor

**Descripción:**

```text
Westcol sube a su robot humanoide a un ascensor del centro comercial: "eso pesa demasiado… si empieza a dar puño aquí, morimos todos". Y el robot manda un puñito.

¿Te subirías a ese ascensor?

Crédito: canal WestCOL, «SAQUE A LA CALLE POR PRIMERA VEZ A MI ROBOT DE $100.000 | WESTCOL». Momento original desde el minuto 16:08: https://youtu.be/Xrwm98iaWY8?t=968

#Westcol #Robot #StreamFighters #Kick
```

**Etiquetas:** Westcol, Westcol robot, robot humanoide, robot ascensor, Stream Fighters, humor

### 32. 2026-11-06-ganga-el-que-pierde-se-sale

- **Gancho:** Regla de la Ganga en Stream Fighters · **Tipo:** `revelacion` · **Puntaje:** 78 · **Duración:** 24,1 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-06-ganga-el-que-pierde-se-sale/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-06-ganga-el-que-pierde-se-sale/ficha.md)
- **Fuente:** https://youtu.be/XvSs7RaRxzA?t=513 (Live Samulx, minuto 8:33)
- **Oportunidad del Cazador:** `tema-stream-fighters-5`
- **Aprobar:** `/publicador aprobar 2026-11-06-ganga-el-que-pierde-se-sale`

#### TikTok

Envío: `datos/publicador/envios/2026-11-06-ganga-el-que-pierde-se-sale__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-06-ganga-el-que-pierde-se-sale:tiktok`

```text
La regla de la Ganga para Stream Fighters 5: el que pierde se sale de la ganga 🥊

¿Quién de la Ganga crees que pierde?

Crédito: canal Live Samulx, «Peleare en Stream Fighters | Westcol quiere cargar a CHIARA, Samulx». Momento original desde el minuto 8:33: https://youtu.be/XvSs7RaRxzA?t=513

#StreamFighters5 #LaGanga #Samulx #Westcol #Kick
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-06-ganga-el-que-pierde-se-sale__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-06-ganga-el-que-pierde-se-sale:instagram`

```text
"Cuatro peleadores acá": la Ganga llega a Stream Fighters 5 con una regla 🥊

En casa de Westcol, la Ganga cuenta que tiene cuatro peleadores en el evento y fija la apuesta, en broma entre amigos: "ninguno de la ganga puede perder… el que pierde se sale de la ganga".

¿Quién de la Ganga crees que pierde?

Crédito: canal Live Samulx, «Peleare en Stream Fighters | Westcol quiere cargar a CHIARA, Samulx». Momento original desde el minuto 8:33: https://youtu.be/XvSs7RaRxzA?t=513

#StreamFighters5 #LaGanga #Samulx #Westcol #Boxeo
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-06-ganga-el-que-pierde-se-sale__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-06-ganga-el-que-pierde-se-sale:youtube`

**Título:** La apuesta de la Ganga antes de Stream Fighters 5: el que pierde se sale

**Descripción:**

```text
La Ganga cuenta que tiene cuatro peleadores en Stream Fighters 5 y fija la regla, en broma entre amigos: "el que pierde se sale de la ganga".

¿Quién de la Ganga crees que pierde?

Crédito: canal Live Samulx, «Peleare en Stream Fighters | Westcol quiere cargar a CHIARA, Samulx». Momento original desde el minuto 8:33: https://youtu.be/XvSs7RaRxzA?t=513

#StreamFighters5 #LaGanga #Samulx #Kick
```

**Etiquetas:** Stream Fighters 5, La Ganga, Samulx, Westcol, boxeo, Kick, Live Samulx

### 33. 2026-11-02-toxico-celos-completo

- **Gancho:** Celos hasta del aire · **Tipo:** `frase` · **Puntaje:** 78 · **Duración:** 21,2 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `autorizado`.
- **Video:** clip.mp4: el archivo no está en esta copia del proyecto (no es un error: la entrada se puede aprobar igual, pero para subirlo hace falta el video) · **Ficha:** [ficha.md](../clipero/clips/2026-11-02-toxico-celos-completo/ficha.md)
- **Fuente:** https://youtu.be/bip8ttg-VeE?t=126 (Lalo Ocampo, minuto 2:06)
- **Aprobar:** `/publicador aprobar 2026-11-02-toxico-celos-completo`

#### TikTok

Envío: `datos/publicador/envios/2026-11-02-toxico-celos-completo__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-02-toxico-celos-completo:tiktok`

```text
Celos del aire, de la luna y del sol | Lalo Ocampo - Tóxico

Mándasela a quien tiene celos hasta del sol.

Crédito: Lalo Ocampo, «Tóxico» (video oficial, 31-oct-2026). Canción completa (minuto 2:06): https://youtu.be/bip8ttg-VeE?t=126

#LaloOcampo #Tóxico #Celos #MúsicaUrbana #NuevaMúsica
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-02-toxico-celos-completo__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-02-toxico-celos-completo:instagram`

```text
Dedícasela a tu persona celosa: «Tóxico», de Lalo Ocampo.

"Yo tengo celos del aire porque acaricia tu piel": el gancho de lo nuevo de Lalo Ocampo, entero. Mándasela a quien tiene celos hasta del sol.

Crédito: Lalo Ocampo, «Tóxico» (video oficial, 31-oct-2026). Canción completa (minuto 2:06): https://youtu.be/bip8ttg-VeE?t=126

#LaloOcampo #Tóxico #Celos #MúsicaUrbana #NuevaMúsica
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-02-toxico-celos-completo__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-02-toxico-celos-completo:youtube`

**Título:** Lalo Ocampo - Tóxico (los celos): "Yo tengo celos del aire"

**Descripción:**

```text
"Yo tengo celos del aire porque acaricia tu piel": el gancho de «Tóxico», lo nuevo de Lalo Ocampo (video oficial, 31-oct-2026). Mándasela a quien tiene celos hasta del sol.

Crédito: canal Lalo Ocampo, «Tóxico» (video oficial). Canción completa desde el minuto 2:06: https://youtu.be/bip8ttg-VeE?t=126

#LaloOcampo #Tóxico #Celos #MúsicaUrbana
```

**Etiquetas:** Lalo Ocampo, Tóxico, Lalo Ocampo Tóxico, celos del aire, canción de celos, música urbana, nueva música, estreno

### 34. 2026-11-02-toxico-coro-eres-mia

- **Gancho:** El coro más tóxico · **Tipo:** `frase` · **Puntaje:** 76 · **Duración:** 21,7 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `autorizado`.
- **Video:** clip.mp4: el archivo no está en esta copia del proyecto (no es un error: la entrada se puede aprobar igual, pero para subirlo hace falta el video) · **Ficha:** [ficha.md](../clipero/clips/2026-11-02-toxico-coro-eres-mia/ficha.md)
- **Fuente:** https://youtu.be/bip8ttg-VeE?t=84 (Lalo Ocampo, minuto 1:24)
- **Aprobar:** `/publicador aprobar 2026-11-02-toxico-coro-eres-mia`

#### TikTok

Envío: `datos/publicador/envios/2026-11-02-toxico-coro-eres-mia__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-02-toxico-coro-eres-mia:tiktok`

```text
"Eres mía y de nadie más": el coro de «Tóxico», de Lalo Ocampo.

Etiqueta a tu tóxico o a tu tóxica.

Crédito: Lalo Ocampo, «Tóxico» (video oficial, 31-oct-2026). Canción completa (minuto 1:24): https://youtu.be/bip8ttg-VeE?t=84

#LaloOcampo #Tóxico #EresMía #MúsicaUrbana #NuevaMúsica
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-02-toxico-coro-eres-mia__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-02-toxico-coro-eres-mia:instagram`

```text
El coro de «Tóxico», de Lalo Ocampo: "Porque eres mía y de nadie más".

Lo nuevo de Lalo Ocampo, del video oficial estrenado el 31 de octubre. Etiqueta a tu tóxico o a tu tóxica.

Crédito: Lalo Ocampo, «Tóxico» (video oficial). Canción completa (minuto 1:24): https://youtu.be/bip8ttg-VeE?t=84

#LaloOcampo #Tóxico #EresMía #MúsicaUrbana #Estreno
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-02-toxico-coro-eres-mia__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-02-toxico-coro-eres-mia:youtube`

**Título:** Lalo Ocampo - Tóxico (coro): "Porque eres mía y de nadie más"

**Descripción:**

```text
El coro de «Tóxico», lo nuevo de Lalo Ocampo (video oficial, 31-oct-2026). ¿A quién se la dedicas?

Crédito: canal Lalo Ocampo, «Tóxico» (video oficial). Canción completa desde el minuto 1:24: https://youtu.be/bip8ttg-VeE?t=84

#LaloOcampo #Tóxico #EresMía #MúsicaUrbana
```

**Etiquetas:** Lalo Ocampo, Tóxico, Lalo Ocampo Tóxico, Tóxico coro, eres mía y de nadie más, música urbana, nueva música, estreno

### 35. 2026-11-05-westcol-robot-piquete

- **Gancho:** Westcol: su robot tiene más piquete · **Tipo:** `humor` · **Puntaje:** 75 · **Duración:** 26,6 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-westcol-robot-piquete/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-westcol-robot-piquete/ficha.md)
- **Fuente:** https://youtu.be/Xrwm98iaWY8?t=2643 (WestCOL, minuto 44:03)
- **Oportunidad del Cazador:** `formato-robot-humanoide-en-la-calle`
- **Aprobar:** `/publicador aprobar 2026-11-05-westcol-robot-piquete`

#### TikTok

Envío: `datos/publicador/envios/2026-11-05-westcol-robot-piquete__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-05-westcol-robot-piquete:tiktok`

```text
"No hay nadie que tenga más piquete que ese robot" – Westcol 🤖

¿Quién tiene más piquete, el robot o Westcol?

Crédito: canal WestCOL, «SAQUE A LA CALLE POR PRIMERA VEZ A MI ROBOT DE $100.000 | WESTCOL». Momento original desde el minuto 44:03: https://youtu.be/Xrwm98iaWY8?t=2643

#Westcol #Robot #Piquete #Medellín #Kick
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-05-westcol-robot-piquete__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-05-westcol-robot-piquete:instagram`

```text
El robot de Westcol con outfit de lujo en el centro comercial

Con el robot vestido de marca y un iPhone en la mano, Westcol lo tiene claro: "No hay nadie que tenga más piquete que ese robot en este momento en el mundo".

¿Quién tiene más piquete, el robot o Westcol?

Crédito: canal WestCOL, «SAQUE A LA CALLE POR PRIMERA VEZ A MI ROBOT DE $100.000 | WESTCOL». Momento original desde el minuto 44:03: https://youtu.be/Xrwm98iaWY8?t=2643

#Westcol #Robot #Piquete #Medellín #Kick
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-05-westcol-robot-piquete__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-05-westcol-robot-piquete:youtube`

**Título:** Westcol pasea su robot vestido de marca en el centro comercial

**Descripción:**

```text
Con el robot vestido de marca y un iPhone en la mano, Westcol lo tiene claro: "No hay nadie que tenga más piquete que ese robot en este momento en el mundo".

¿Quién tiene más piquete, el robot o Westcol?

Crédito: canal WestCOL, «SAQUE A LA CALLE POR PRIMERA VEZ A MI ROBOT DE $100.000 | WESTCOL». Momento original desde el minuto 44:03: https://youtu.be/Xrwm98iaWY8?t=2643

#Westcol #Robot #Piquete #Medellín
```

**Etiquetas:** Westcol, Westcol robot, robot humanoide, piquete, Medellín, humor

### 36. 2026-11-05-westcol-robot-tienda

- **Gancho:** ¿Puede entrar un robot a una tienda? · **Tipo:** `humor` · **Puntaje:** 72 · **Duración:** 56,8 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-westcol-robot-tienda/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-westcol-robot-tienda/ficha.md)
- **Fuente:** https://youtu.be/Xrwm98iaWY8?t=1198 (WestCOL, minuto 19:58)
- **Oportunidad del Cazador:** `formato-robot-humanoide-en-la-calle`
- **Aviso:** En los primeros segundos aparece de perfil el empleado de la tienda, una persona privada (lo señala la ficha). Decide antes de aprobar si lo aceptas o pides al Clipero recortar la entrada.
- **Aprobar:** `/publicador aprobar 2026-11-05-westcol-robot-tienda`

#### TikTok

Envío: `datos/publicador/envios/2026-11-05-westcol-robot-tienda__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-05-westcol-robot-tienda:tiktok`

```text
¿Puede entrar un robot a una tienda? Westcol lo intenta 🤖😂

¿Lo dejarías entrar a tu tienda?

Crédito: canal WestCOL, «SAQUE A LA CALLE POR PRIMERA VEZ A MI ROBOT DE $100.000 | WESTCOL». Momento original desde el minuto 19:58: https://youtu.be/Xrwm98iaWY8?t=1198

#Westcol #Robot #RobotHumanoide #Medellín #Humor
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-05-westcol-robot-tienda__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-05-westcol-robot-tienda:instagram`

```text
"Es que él tiene mala fama" 🤖😂

Westcol llega con su robot a una tienda de ropa ("voy a comprarle ropita al robot"), pero primero pregunta si puede entrar: "es juicioso, se porta bien… tuvo un error y ya".

¿Lo dejarías entrar a tu tienda?

Crédito: canal WestCOL, «SAQUE A LA CALLE POR PRIMERA VEZ A MI ROBOT DE $100.000 | WESTCOL». Momento original desde el minuto 19:58: https://youtu.be/Xrwm98iaWY8?t=1198

#Westcol #Robot #RobotHumanoide #Medellín #Humor
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-05-westcol-robot-tienda__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-05-westcol-robot-tienda:youtube`

**Título:** Westcol lleva a su robot humanoide a una tienda de ropa

**Descripción:**

```text
Westcol llega con su robot a una tienda de ropa: "voy a comprarle ropita al robot". Primero pregunta si puede entrar: "es juicioso, se porta bien… es que él tiene mala fama".

¿Lo dejarías entrar a tu tienda?

Crédito: canal WestCOL, «SAQUE A LA CALLE POR PRIMERA VEZ A MI ROBOT DE $100.000 | WESTCOL». Momento original desde el minuto 19:58: https://youtu.be/Xrwm98iaWY8?t=1198

#Westcol #Robot #RobotHumanoide #Humor
```

**Etiquetas:** Westcol, Westcol robot, robot humanoide, centro comercial, humor, Medellín, Kick

### 37. 2026-11-05-westcol-robot-boxeo

- **Gancho:** ¿Quién boxea mejor: el robot o él? · **Tipo:** `humor` · **Puntaje:** 72 · **Duración:** 63,9 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-westcol-robot-boxeo/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-westcol-robot-boxeo/ficha.md)
- **Fuente:** https://youtu.be/Xrwm98iaWY8?t=457 (WestCOL, minuto 7:37)
- **Oportunidad del Cazador:** `tema-stream-fighters-5`
- **Aviso:** El que intenta el combo no está identificado por la cara; el texto no lo nombra.
- **Aprobar:** `/publicador aprobar 2026-11-05-westcol-robot-boxeo`

#### TikTok

Envío: `datos/publicador/envios/2026-11-05-westcol-robot-boxeo__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-05-westcol-robot-boxeo:tiktok`

```text
¿Quién boxea mejor: el robot de Westcol o su amigo? 🥊🤖

¿Quién gana?

Crédito: canal WestCOL, «SAQUE A LA CALLE POR PRIMERA VEZ A MI ROBOT DE $100.000 | WESTCOL». Momento original desde el minuto 7:37: https://youtu.be/Xrwm98iaWY8?t=457

#Westcol #Robot #Boxeo #Kick #Humor
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-05-westcol-robot-boxeo__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-05-westcol-robot-boxeo:instagram`

```text
El robot de Westcol tira un combo de boxeo 🥊🤖

Westcol activa el modo "boxing combo" y lo compara con uno de la Ganga: "le aseguro que ese tiene mejor técnica que usted… ¿quién lo está haciendo mejor, el robot o este man?".

¿Quién gana: el robot o él?

Crédito: canal WestCOL, «SAQUE A LA CALLE POR PRIMERA VEZ A MI ROBOT DE $100.000 | WESTCOL». Momento original desde el minuto 7:37: https://youtu.be/Xrwm98iaWY8?t=457

#Westcol #Robot #RobotHumanoide #Boxeo #Humor
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-05-westcol-robot-boxeo__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-05-westcol-robot-boxeo:youtube`

**Título:** Westcol pone a boxear a su robot humanoide

**Descripción:**

```text
Westcol activa el modo "boxing combo" de su robot y lo compara con uno de la Ganga: "¿quién lo está haciendo mejor, el robot o este man?".

¿Quién gana: el robot o él?

Crédito: canal WestCOL, «SAQUE A LA CALLE POR PRIMERA VEZ A MI ROBOT DE $100.000 | WESTCOL». Momento original desde el minuto 7:37: https://youtu.be/Xrwm98iaWY8?t=457

#Westcol #Robot #Boxeo #Kick
```

**Etiquetas:** Westcol, Westcol robot, robot humanoide, boxeo, robot boxeo, humor, Kick

### 38. 2026-11-02-toxico-verso-mando-la-ubi

- **Gancho:** POV: tu novio es tóxico · **Tipo:** `frase` · **Puntaje:** 72 · **Duración:** 31,4 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `autorizado`.
- **Video:** clip.mp4: el archivo no está en esta copia del proyecto (no es un error: la entrada se puede aprobar igual, pero para subirlo hace falta el video) · **Ficha:** [ficha.md](../clipero/clips/2026-11-02-toxico-verso-mando-la-ubi/ficha.md)
- **Fuente:** https://youtu.be/bip8ttg-VeE?t=52 (Lalo Ocampo, minuto 0:52)
- **Aprobar:** `/publicador aprobar 2026-11-02-toxico-verso-mando-la-ubi`

#### TikTok

Envío: `datos/publicador/envios/2026-11-02-toxico-verso-mando-la-ubi__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-02-toxico-verso-mando-la-ubi:tiktok`

```text
POV: tu novio es tóxico y te manda la ubi | Lalo Ocampo - Tóxico

"Mando la ubi y espero la respuesta". ¿Conoces a alguien así?

Crédito: Lalo Ocampo, «Tóxico» (video oficial, 31-oct-2026). Canción completa (minuto 0:52): https://youtu.be/bip8ttg-VeE?t=52

#LaloOcampo #Tóxico #NovioTóxico #POV #MúsicaUrbana
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-02-toxico-verso-mando-la-ubi__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-02-toxico-verso-mando-la-ubi:instagram`

```text
"Mando la ubi y espero la respuesta": el primer verso de «Tóxico», de Lalo Ocampo.

POV: tu novio es tóxico. Lo nuevo de Lalo Ocampo, del video oficial estrenado el 31 de octubre. ¿Conoces a alguien así?

Crédito: Lalo Ocampo, «Tóxico» (video oficial). Canción completa (minuto 0:52): https://youtu.be/bip8ttg-VeE?t=52

#LaloOcampo #Tóxico #NovioTóxico #POV #MúsicaUrbana
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-02-toxico-verso-mando-la-ubi__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-02-toxico-verso-mando-la-ubi:youtube`

**Título:** Lalo Ocampo - Tóxico: "Mando la ubi y espero la respuesta"

**Descripción:**

```text
El primer verso de «Tóxico», lo nuevo de Lalo Ocampo (video oficial, 31-oct-2026): "Mando la ubi y espero la respuesta". ¿Conoces a alguien así?

Crédito: canal Lalo Ocampo, «Tóxico» (video oficial). Canción completa desde el minuto 0:52: https://youtu.be/bip8ttg-VeE?t=52

#LaloOcampo #Tóxico #NovioTóxico #MúsicaUrbana
```

**Etiquetas:** Lalo Ocampo, Tóxico, Lalo Ocampo Tóxico, novio tóxico, mando la ubi, música urbana, nueva música, estreno

### 39. 2026-11-02-toxico-intro-celos-aire

- **Gancho:** Lalo Ocampo estrena «Tóxico» · **Tipo:** `frase` · **Puntaje:** 68 · **Duración:** 19,6 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `autorizado`.
- **Video:** clip.mp4: el archivo no está en esta copia del proyecto (no es un error: la entrada se puede aprobar igual, pero para subirlo hace falta el video) · **Ficha:** [ficha.md](../clipero/clips/2026-11-02-toxico-intro-celos-aire/ficha.md)
- **Fuente:** https://youtu.be/bip8ttg-VeE?t=0 (Lalo Ocampo, minuto 0:00)
- **Aprobar:** `/publicador aprobar 2026-11-02-toxico-intro-celos-aire`

#### TikTok

Envío: `datos/publicador/envios/2026-11-02-toxico-intro-celos-aire__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-02-toxico-intro-celos-aire:tiktok`

```text
Lalo Ocampo estrena «Tóxico»: celos hasta del aire.

¿Celos del aire: romántico o tóxico? ¿De qué tienes celos tú? Te leo.

Crédito: Lalo Ocampo, «Tóxico» (video oficial, 31-oct-2026). Canción completa (minuto 0:00): https://youtu.be/bip8ttg-VeE?t=0

#LaloOcampo #Tóxico #Celos #MúsicaUrbana #NuevaMúsica
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-02-toxico-intro-celos-aire__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-02-toxico-intro-celos-aire:instagram`

```text
"Yo tengo celos del aire porque acaricia tu piel": así arranca «Tóxico», de Lalo Ocampo.

Los primeros 20 segundos del video oficial, estrenado el 31 de octubre. ¿Celos del aire: romántico o tóxico? ¿De qué tienes celos tú?

Crédito: Lalo Ocampo, «Tóxico» (video oficial). Canción completa (minuto 0:00): https://youtu.be/bip8ttg-VeE?t=0

#LaloOcampo #Tóxico #Celos #MúsicaUrbana #Estreno
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-02-toxico-intro-celos-aire__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-02-toxico-intro-celos-aire:youtube`

**Título:** Lalo Ocampo - Tóxico (los primeros 20 segundos)

**Descripción:**

```text
Así empieza «Tóxico», lo nuevo de Lalo Ocampo (video oficial, 31-oct-2026): "Yo tengo celos del aire porque acaricia tu piel". ¿Celos del aire: romántico o tóxico?

Crédito: canal Lalo Ocampo, «Tóxico» (video oficial). Canción completa desde el minuto 0:00: https://youtu.be/bip8ttg-VeE?t=0

#LaloOcampo #Tóxico #MúsicaUrbana #Estreno
```

**Etiquetas:** Lalo Ocampo, Tóxico, Lalo Ocampo Tóxico, Tóxico video oficial, celos, música urbana, nueva música, estreno

### 40. 2026-11-04-parceritos-decimas-abuelo

- **Gancho:** Lokillo le escribió estas décimas a su abuelo · **Tipo:** `emotivo` · **Puntaje:** 79 · **Duración:** 66,9 s · **Ventana hasta:** 2026-11-19
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-04-parceritos-decimas-abuelo/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-04-parceritos-decimas-abuelo/ficha.md)
- **Fuente:** https://youtu.be/4hGozORt3Ds?t=2162 (Los Parceritos, minuto 36:02)
- **Aprobar:** `/publicador aprobar 2026-11-04-parceritos-decimas-abuelo`

#### TikTok

Envío: `datos/publicador/envios/2026-11-04-parceritos-decimas-abuelo__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-04-parceritos-decimas-abuelo:tiktok`

```text
Lokillo le escribió esto a su abuelo antes de que muriera 🕊️

¿Qué le dirías a tu abuelo si pudieras?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 36:02: https://youtu.be/4hGozORt3Ds?t=2162

#LosParceritos #Lokillo #Décimas #Trova #Poesía
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-04-parceritos-decimas-abuelo__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-04-parceritos-decimas-abuelo:instagram`

```text
Las décimas de Lokillo para su abuelo 🕊️

En pleno capítulo de humor, Lokillo pide un momento: "no es humor". Lee las décimas que escribió mientras miraba a su abuelo postrado en una cama, poco antes de que muriera.

¿Qué le dirías a tu abuelo si pudieras?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 36:02: https://youtu.be/4hGozORt3Ds?t=2162

#LosParceritos #Lokillo #Décimas #Trova #Poesía
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-04-parceritos-decimas-abuelo__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-04-parceritos-decimas-abuelo:youtube`

**Título:** Lokillo lee las décimas que le escribió a su abuelo

**Descripción:**

```text
En pleno capítulo de humor, Lokillo pide un momento: "no es humor". Lee las décimas que escribió mientras miraba a su abuelo postrado en una cama, poco antes de que muriera.

¿Qué le dirías a tu abuelo si pudieras?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 36:02: https://youtu.be/4hGozORt3Ds?t=2162

#LosParceritos #Lokillo #Décimas #Trova
```

**Etiquetas:** Los Parceritos, Lokillo, décimas, trova, abuelo, poesía

### 41. 2026-11-04-parceritos-filosofo-o-reggaetonero

- **Gancho:** ¿Filósofo, poeta o reggaetonero? · **Tipo:** `humor` · **Puntaje:** 77 · **Duración:** 53,4 s · **Ventana hasta:** 2026-11-19
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-04-parceritos-filosofo-o-reggaetonero/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-04-parceritos-filosofo-o-reggaetonero/ficha.md)
- **Fuente:** https://youtu.be/4hGozORt3Ds?t=1360 (Los Parceritos, minuto 22:40)
- **Aprobar:** `/publicador aprobar 2026-11-04-parceritos-filosofo-o-reggaetonero`

#### TikTok

Envío: `datos/publicador/envios/2026-11-04-parceritos-filosofo-o-reggaetonero__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-04-parceritos-filosofo-o-reggaetonero:tiktok`

```text
¿Filósofo, poeta o reguetonero? El profe de Un poeta adivina 😂

¿Cuál adivinaste tú?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 22:40: https://youtu.be/4hGozORt3Ds?t=1360

#LosParceritos #UbeimarRios #UnPoeta #Filosofia #Humor
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-04-parceritos-filosofo-o-reggaetonero__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-04-parceritos-filosofo-o-reggaetonero:instagram`

```text
Le leen frases a Ubeimar Ríos: ¿Nietzsche, Pizarnik o un reguetonero?

Juego en Los Parceritos con Ubeimar Ríos, profe de filosofía y protagonista de 'Un poeta': le leen una frase y tiene que decir si la dijo un filósofo, un poeta o un reguetonero. Nietzsche "del Grupo Niche", Alejandra Pizarnik… y la tercera.

¿Cuál adivinaste tú?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 22:40: https://youtu.be/4hGozORt3Ds?t=1360

#LosParceritos #UbeimarRios #UnPoeta #Filosofia #Humor
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-04-parceritos-filosofo-o-reggaetonero__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-04-parceritos-filosofo-o-reggaetonero:youtube`

**Título:** ¿Filósofo, poeta o reguetonero? Le leen frases a Ubeimar Ríos 😂

**Descripción:**

```text
Juego en Los Parceritos con Ubeimar Ríos, profe de filosofía y protagonista de 'Un poeta': le leen una frase y tiene que decir si la dijo un filósofo, un poeta o un reguetonero. Nietzsche "del Grupo Niche", Alejandra Pizarnik… y la tercera.

¿Cuál adivinaste tú?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 22:40: https://youtu.be/4hGozORt3Ds?t=1360

#LosParceritos #UbeimarRios #UnPoeta #Filosofia
```

**Etiquetas:** Los Parceritos, Ubeimar Ríos, Un poeta, Lokillo, filosofía, humor

### 42. 2026-11-04-parceritos-poeta-corre-feo

- **Gancho:** Le preguntan a Ubeimar Ríos por qué corre así · **Tipo:** `humor` · **Puntaje:** 72 · **Duración:** 16,5 s · **Ventana hasta:** 2026-11-19
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-04-parceritos-poeta-corre-feo/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-04-parceritos-poeta-corre-feo/ficha.md)
- **Fuente:** https://youtu.be/4hGozORt3Ds?t=294 (Los Parceritos, minuto 4:54)
- **Aprobar:** `/publicador aprobar 2026-11-04-parceritos-poeta-corre-feo`

#### TikTok

Envío: `datos/publicador/envios/2026-11-04-parceritos-poeta-corre-feo__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-04-parceritos-poeta-corre-feo:tiktok`

```text
"¿Por qué corre tan feo?" 😂 Le preguntan al protagonista de Un poeta

¿Ya viste Un poeta?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 4:54: https://youtu.be/4hGozORt3Ds?t=294

#LosParceritos #UbeimarRios #UnPoeta #CineColombiano #Humor
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-04-parceritos-poeta-corre-feo__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-04-parceritos-poeta-corre-feo:instagram`

```text
La carrera de Un poeta, explicada por su protagonista

La pregunta "muy importante" de Los Parceritos a Ubeimar Ríos, protagonista de 'Un poeta': ¿por qué corre tan feo? "Porque no sé correr, hermano… y ahí Simón me puso a correr".

¿Ya viste Un poeta?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 4:54: https://youtu.be/4hGozORt3Ds?t=294

#LosParceritos #UbeimarRios #UnPoeta #CineColombiano #Humor
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-04-parceritos-poeta-corre-feo__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-04-parceritos-poeta-corre-feo:youtube`

**Título:** ¿Por qué corre así el poeta? 😂 | Los Parceritos

**Descripción:**

```text
La pregunta "muy importante" de Los Parceritos a Ubeimar Ríos, protagonista de 'Un poeta': ¿por qué corre tan feo? "Porque no sé correr, hermano… y ahí Simón me puso a correr".

¿Ya viste Un poeta?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 4:54: https://youtu.be/4hGozORt3Ds?t=294

#LosParceritos #UbeimarRios #UnPoeta #CineColombiano
```

**Etiquetas:** Los Parceritos, Ubeimar Ríos, Un poeta, cine colombiano, Lokillo, humor

### 43. 2026-11-04-parceritos-billete-diomedes

- **Gancho:** ¿Quién debería estar en los billetes? · **Tipo:** `humor` · **Puntaje:** 72 · **Duración:** 55,7 s · **Ventana hasta:** 2026-11-19
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-04-parceritos-billete-diomedes/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-04-parceritos-billete-diomedes/ficha.md)
- **Fuente:** https://youtu.be/4hGozORt3Ds?t=1798 (Los Parceritos, minuto 29:58)
- **Aprobar:** `/publicador aprobar 2026-11-04-parceritos-billete-diomedes`

#### TikTok

Envío: `datos/publicador/envios/2026-11-04-parceritos-billete-diomedes__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-04-parceritos-billete-diomedes:tiktok`

```text
¿Quién debería estar en el billete de 100.000? 😂

¿A quién pondrías tú en el billete de 100.000?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 29:58: https://youtu.be/4hGozORt3Ds?t=1798

#LosParceritos #UbeimarRios #GomezJattin #Diomedes #Humor
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-04-parceritos-billete-diomedes__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-04-parceritos-billete-diomedes:instagram`

```text
El poeta propone a Raúl Gómez Jattin… y Los Parceritos a Diomedes

Ubeimar Ríos, el profe de 'Un poeta', pone en el billete de 100.000 al poeta que más despreciaba el dinero, Raúl Gómez Jattin, y recita "Los habitantes de mi aldea dicen que soy un hombre despreciable y peligroso…". La respuesta de Los Parceritos: Diomedes, "porque ese no lo cambiaba nadie".

¿A quién pondrías tú en el billete de 100.000?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 29:58: https://youtu.be/4hGozORt3Ds?t=1798

#LosParceritos #UbeimarRios #GomezJattin #Diomedes #Humor
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-04-parceritos-billete-diomedes__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-04-parceritos-billete-diomedes:youtube`

**Título:** ¿Quién debería ir en los billetes de Colombia? 😂

**Descripción:**

```text
Ubeimar Ríos, el profe de 'Un poeta', pone en el billete de 100.000 al poeta que más despreciaba el dinero, Raúl Gómez Jattin, y recita "Los habitantes de mi aldea dicen que soy un hombre despreciable y peligroso…". La respuesta de Los Parceritos: Diomedes, "porque ese no lo cambiaba nadie".

¿A quién pondrías tú en el billete de 100.000?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 29:58: https://youtu.be/4hGozORt3Ds?t=1798

#LosParceritos #UbeimarRios #GomezJattin #Diomedes
```

**Etiquetas:** Los Parceritos, Ubeimar Ríos, Gómez Jattin, Diomedes, billetes Colombia, humor

### 44. 2026-11-04-parceritos-billete-popo

- **Gancho:** La pregunta más profunda para un filósofo · **Tipo:** `humor` · **Puntaje:** 71 · **Duración:** 58,6 s · **Ventana hasta:** 2026-11-19
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-04-parceritos-billete-popo/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-04-parceritos-billete-popo/ficha.md)
- **Fuente:** https://youtu.be/4hGozORt3Ds?t=2101 (Los Parceritos, minuto 35:01)
- **Aprobar:** `/publicador aprobar 2026-11-04-parceritos-billete-popo`

#### TikTok

Envío: `datos/publicador/envios/2026-11-04-parceritos-billete-popo__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-04-parceritos-billete-popo:tiktok`

```text
La pregunta más profunda que le han hecho a un filósofo 😂

¿Tú lo sacarías? Sé sincero

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 35:01: https://youtu.be/4hGozORt3Ds?t=2101

#LosParceritos #Lokillo #UbeimarRios #Humor #Comedia
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-04-parceritos-billete-popo__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-04-parceritos-billete-popo:instagram`

```text
Se te cae un billete en la taza… ¿lo sacas?

"Voy a poner preguntas más de literatura, más profundas y más poéticas": si estás en el baño y se te cae un billete de 5.000 en la taza, ¿metes la mano? El profe de filosofía responde: "depende si lo necesito mucho".

¿Tú lo sacarías? Sé sincero

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 35:01: https://youtu.be/4hGozORt3Ds?t=2101

#LosParceritos #Lokillo #UbeimarRios #Humor #Comedia
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-04-parceritos-billete-popo__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-04-parceritos-billete-popo:youtube`

**Título:** ¿Sacarías el billete? La pregunta de Los Parceritos al profe 😂

**Descripción:**

```text
"Voy a poner preguntas más de literatura, más profundas y más poéticas": si estás en el baño y se te cae un billete de 5.000 en la taza, ¿metes la mano? El profe de filosofía responde: "depende si lo necesito mucho".

¿Tú lo sacarías? Sé sincero

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 35:01: https://youtu.be/4hGozORt3Ds?t=2101

#LosParceritos #Lokillo #UbeimarRios #Humor
```

**Etiquetas:** Los Parceritos, Lokillo, Ubeimar Ríos, humor, comedia, Colombia

### 45. 2026-11-04-parceritos-flor-abeja

- **Gancho:** Así hacían poesía Los Parceritos · **Tipo:** `humor` · **Puntaje:** 71 · **Duración:** 27,4 s · **Ventana hasta:** 2026-11-19
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-04-parceritos-flor-abeja/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-04-parceritos-flor-abeja/ficha.md)
- **Fuente:** https://youtu.be/4hGozORt3Ds?t=1597 (Los Parceritos, minuto 26:37)
- **Aprobar:** `/publicador aprobar 2026-11-04-parceritos-flor-abeja`

#### TikTok

Envío: `datos/publicador/envios/2026-11-04-parceritos-flor-abeja__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-04-parceritos-flor-abeja:tiktok`

```text
Los Parceritos intentan hacer poesía bonita… 😂

Termina tú el verso 👇

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 26:37: https://youtu.be/4hGozORt3Ds?t=1597

#LosParceritos #Lokillo #Trova #Poesia #Humor
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-04-parceritos-flor-abeja__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-04-parceritos-flor-abeja:instagram`

```text
"Si tú fueras una flor y yo una abeja…" 😂

Los Parceritos le explican al profe que en sus inicios hacían trovas bonitas, con figuras literarias… y lo demuestran.

Termina tú el verso 👇

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 26:37: https://youtu.be/4hGozORt3Ds?t=1597

#LosParceritos #Lokillo #Trova #Poesia #Humor
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-04-parceritos-flor-abeja__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-04-parceritos-flor-abeja:youtube`

**Título:** Cuando un trovador intenta ser romántico 😂 | Los Parceritos

**Descripción:**

```text
Los Parceritos le explican al profe que en sus inicios hacían trovas bonitas, con figuras literarias… y lo demuestran.

Termina tú el verso 👇

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 26:37: https://youtu.be/4hGozORt3Ds?t=1597

#LosParceritos #Lokillo #Trova #Poesia
```

**Etiquetas:** Los Parceritos, Lokillo, trova, poesía, humor, Colombia

### 46. 2026-11-04-parceritos-borracho-ensayo

- **Gancho:** Llegó borracho al ensayo de Un poeta · **Tipo:** `historia` · **Puntaje:** 71 · **Duración:** 58,9 s · **Ventana hasta:** 2026-11-19
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-04-parceritos-borracho-ensayo/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-04-parceritos-borracho-ensayo/ficha.md)
- **Fuente:** https://youtu.be/4hGozORt3Ds?t=491 (Los Parceritos, minuto 8:11)
- **Aprobar:** `/publicador aprobar 2026-11-04-parceritos-borracho-ensayo`

#### TikTok

Envío: `datos/publicador/envios/2026-11-04-parceritos-borracho-ensayo__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-04-parceritos-borracho-ensayo:tiktok`

```text
El protagonista de Un poeta llegó borracho al ensayo… y el director lo grabó

¿Qué harías tú si te graban así?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 8:11: https://youtu.be/4hGozORt3Ds?t=491

#LosParceritos #UbeimarRios #UnPoeta #SimonMesa #CineColombiano
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-04-parceritos-borracho-ensayo__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-04-parceritos-borracho-ensayo:instagram`

```text
Llegó borracho al ensayo y eso era justo lo que el director quería 🍺

Después de una marcha de profesores, Ubeimar Ríos llegó "totalmente borracho" al ensayo de la escena de la carrera de 'Un poeta'. Lo regañaron… y días después el director, Simón Mesa, le enseñó el video: "lo que necesito es que en la película esté así, pero sin tomarse un solo trago".

¿Qué harías tú si te graban así?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 8:11: https://youtu.be/4hGozORt3Ds?t=491

#LosParceritos #UbeimarRios #UnPoeta #SimonMesa #CineColombiano
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-04-parceritos-borracho-ensayo__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-04-parceritos-borracho-ensayo:youtube`

**Título:** La historia del ensayo borracho de Un poeta

**Descripción:**

```text
Después de una marcha de profesores, Ubeimar Ríos llegó "totalmente borracho" al ensayo de la escena de la carrera de 'Un poeta'. Lo regañaron… y días después el director, Simón Mesa, le enseñó el video: "lo que necesito es que en la película esté así, pero sin tomarse un solo trago".

¿Qué harías tú si te graban así?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 8:11: https://youtu.be/4hGozORt3Ds?t=491

#LosParceritos #UbeimarRios #UnPoeta #SimonMesa
```

**Etiquetas:** Los Parceritos, Ubeimar Ríos, Un poeta, Simón Mesa, cine colombiano, anécdota

### 47. 2026-11-04-parceritos-profesor-sobra

- **Gancho:** ¿Qué profesor sobra en los colegios? · **Tipo:** `frase` · **Puntaje:** 70 · **Duración:** 30,6 s · **Ventana hasta:** 2026-11-19
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-04-parceritos-profesor-sobra/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-04-parceritos-profesor-sobra/ficha.md)
- **Fuente:** https://youtu.be/4hGozORt3Ds?t=2494 (Los Parceritos, minuto 41:34)
- **Aprobar:** `/publicador aprobar 2026-11-04-parceritos-profesor-sobra`

#### TikTok

Envío: `datos/publicador/envios/2026-11-04-parceritos-profesor-sobra__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-04-parceritos-profesor-sobra:tiktok`

```text
"Sobra el profesor que lleva 40 años con el mismo librito"

¿Tuviste un profe así?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 41:34: https://youtu.be/4hGozORt3Ds?t=2494

#LosParceritos #UbeimarRios #Educacion #Profesores #UnPoeta
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-04-parceritos-profesor-sobra__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-04-parceritos-profesor-sobra:instagram`

```text
Un profe de filosofía dice qué profesores sobran (y se incluye)

Ubeimar Ríos, profe de filosofía pensionado y protagonista de 'Un poeta': sobra el profesor "que lleva 40 años con el mismo librito amarillo" y los que no están contextualizados. Aclara que no todos son así, y se incluye: "no sé inglés".

¿Tuviste un profe así?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 41:34: https://youtu.be/4hGozORt3Ds?t=2494

#LosParceritos #UbeimarRios #Educacion #Profesores #UnPoeta
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-04-parceritos-profesor-sobra__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-04-parceritos-profesor-sobra:youtube`

**Título:** ¿Qué profesor sobra en los colegios? Responde un profe de filosofía

**Descripción:**

```text
Ubeimar Ríos, profe de filosofía pensionado y protagonista de 'Un poeta': sobra el profesor "que lleva 40 años con el mismo librito amarillo" y los que no están contextualizados. Aclara que no todos son así, y se incluye: "no sé inglés".

¿Tuviste un profe así?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 41:34: https://youtu.be/4hGozORt3Ds?t=2494

#LosParceritos #UbeimarRios #Educacion #Profesores
```

**Etiquetas:** Los Parceritos, Ubeimar Ríos, educación, profesores, colegio, Un poeta

### 48. 2026-11-04-parceritos-novela-mas-corta

- **Gancho:** La novela más corta del mundo · **Tipo:** `humor` · **Puntaje:** 70 · **Duración:** 31,0 s · **Ventana hasta:** 2026-11-19
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-04-parceritos-novela-mas-corta/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-04-parceritos-novela-mas-corta/ficha.md)
- **Fuente:** https://youtu.be/4hGozORt3Ds?t=2038 (Los Parceritos, minuto 33:58)
- **Aprobar:** `/publicador aprobar 2026-11-04-parceritos-novela-mas-corta`

#### TikTok

Envío: `datos/publicador/envios/2026-11-04-parceritos-novela-mas-corta__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-04-parceritos-novela-mas-corta:tiktok`

```text
La novela más corta del mundo cabe en 6 palabras

Escribe tu novela en 6 palabras 👇

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 33:58: https://youtu.be/4hGozORt3Ds?t=2038

#LosParceritos #UbeimarRios #Literatura #Humor #Colombia
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-04-parceritos-novela-mas-corta__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-04-parceritos-novela-mas-corta:instagram`

```text
"Soy hijo de mi hermano. Esa es mi tragedia" 😳

Para el billete de 2.000, el profe propone a Carlos Mario Garcés, autor, según cuenta, de "la novela más corta del mundo": "Soy hijo de mi hermano. Esa es mi tragedia". Los Parceritos le encuentran otra lectura.

Escribe tu novela en 6 palabras 👇

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 33:58: https://youtu.be/4hGozORt3Ds?t=2038

#LosParceritos #UbeimarRios #Literatura #Humor #Colombia
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-04-parceritos-novela-mas-corta__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-04-parceritos-novela-mas-corta:youtube`

**Título:** ¿La conocías? La novela más corta del mundo | Los Parceritos

**Descripción:**

```text
Para el billete de 2.000, el profe propone a Carlos Mario Garcés, autor, según cuenta, de "la novela más corta del mundo": "Soy hijo de mi hermano. Esa es mi tragedia". Los Parceritos le encuentran otra lectura.

Escribe tu novela en 6 palabras 👇

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 33:58: https://youtu.be/4hGozORt3Ds?t=2038

#LosParceritos #UbeimarRios #Literatura #Humor
```

**Etiquetas:** Los Parceritos, Ubeimar Ríos, novela más corta, literatura, humor, Colombia

### 49. 2026-11-04-parceritos-el-paseo

- **Gancho:** ¿La mejor película colombiana de la historia? · **Tipo:** `humor` · **Puntaje:** 68 · **Duración:** 21,4 s · **Ventana hasta:** 2026-11-19
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-04-parceritos-el-paseo/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-04-parceritos-el-paseo/ficha.md)
- **Fuente:** https://youtu.be/4hGozORt3Ds?t=153 (Los Parceritos, minuto 2:33)
- **Aprobar:** `/publicador aprobar 2026-11-04-parceritos-el-paseo`

#### TikTok

Envío: `datos/publicador/envios/2026-11-04-parceritos-el-paseo__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-04-parceritos-el-paseo:tiktok`

```text
¿La mejor película colombiana? "Las cinco que he visto son El paseo" 😂

¿Cuál es para ti la mejor película colombiana?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 2:33: https://youtu.be/4hGozORt3Ds?t=153

#LosParceritos #UbeimarRios #UnPoeta #ElPaseo #CineColombiano
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-04-parceritos-el-paseo__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-04-parceritos-el-paseo:instagram`

```text
El protagonista de Un poeta y El paseo 1, 2, 3, 4…

Los Parceritos le dicen a Ubeimar Ríos que 'Un poeta' es la mejor película de la historia del cine colombiano. Su respuesta: "habré visto cuatro o cinco películas colombianas… y las cinco son El paseo".

¿Cuál es para ti la mejor película colombiana?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 2:33: https://youtu.be/4hGozORt3Ds?t=153

#LosParceritos #UbeimarRios #UnPoeta #ElPaseo #CineColombiano
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-04-parceritos-el-paseo__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-04-parceritos-el-paseo:youtube`

**Título:** ¿Un poeta es la mejor película colombiana? Responde su protagonista

**Descripción:**

```text
Los Parceritos le dicen a Ubeimar Ríos que 'Un poeta' es la mejor película de la historia del cine colombiano. Su respuesta: "habré visto cuatro o cinco películas colombianas… y las cinco son El paseo".

¿Cuál es para ti la mejor película colombiana?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 2:33: https://youtu.be/4hGozORt3Ds?t=153

#LosParceritos #UbeimarRios #UnPoeta #ElPaseo
```

**Etiquetas:** Los Parceritos, Ubeimar Ríos, Un poeta, El paseo, cine colombiano, humor

### 50. 2026-11-04-parceritos-poesia-protesta

- **Gancho:** Poesía de protesta, versión Parceritos · **Tipo:** `humor` · **Puntaje:** 67 · **Duración:** 37,2 s · **Ventana hasta:** 2026-11-19
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-04-parceritos-poesia-protesta/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-04-parceritos-poesia-protesta/ficha.md)
- **Fuente:** https://youtu.be/4hGozORt3Ds?t=1995 (Los Parceritos, minuto 33:15)
- **Aprobar:** `/publicador aprobar 2026-11-04-parceritos-poesia-protesta`

#### TikTok

Envío: `datos/publicador/envios/2026-11-04-parceritos-poesia-protesta__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-04-parceritos-poesia-protesta:tiktok`

```text
Poesía de protesta vs. poesía de Los Parceritos 😂

¿Con cuál te quedas?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 33:15: https://youtu.be/4hGozORt3Ds?t=1995

#LosParceritos #UbeimarRios #Poesia #Humor #Colombia
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-04-parceritos-poesia-protesta__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-04-parceritos-poesia-protesta:instagram`

```text
El profe recita poesía de protesta… y la respuesta de Los Parceritos

El profe recita a Carlos Enrique Ortiz, "Caliche": "mientras un hombre más sangra en la zanja amordazado, un político más habla…". Los Parceritos responden con su propia escuela.

¿Con cuál te quedas?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 33:15: https://youtu.be/4hGozORt3Ds?t=1995

#LosParceritos #UbeimarRios #Poesia #Humor #Colombia
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-04-parceritos-poesia-protesta__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-04-parceritos-poesia-protesta:youtube`

**Título:** Poesía de protesta, versión Los Parceritos 😂

**Descripción:**

```text
El profe recita a Carlos Enrique Ortiz, "Caliche": "mientras un hombre más sangra en la zanja amordazado, un político más habla…". Los Parceritos responden con su propia escuela.

¿Con cuál te quedas?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 33:15: https://youtu.be/4hGozORt3Ds?t=1995

#LosParceritos #UbeimarRios #Poesia #Humor
```

**Etiquetas:** Los Parceritos, Ubeimar Ríos, poesía, poesía de protesta, humor, Colombia

### 51. 2026-11-04-parceritos-poema-cuarto-oscuro

- **Gancho:** Ubeimar Ríos recita un texto inédito · **Tipo:** `emotivo` · **Puntaje:** 66 · **Duración:** 43,4 s · **Ventana hasta:** 2026-11-19
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-04-parceritos-poema-cuarto-oscuro/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-04-parceritos-poema-cuarto-oscuro/ficha.md)
- **Fuente:** https://youtu.be/4hGozORt3Ds?t=1498 (Los Parceritos, minuto 24:58)
- **Aprobar:** `/publicador aprobar 2026-11-04-parceritos-poema-cuarto-oscuro`

#### TikTok

Envío: `datos/publicador/envios/2026-11-04-parceritos-poema-cuarto-oscuro__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-04-parceritos-poema-cuarto-oscuro:tiktok`

```text
El protagonista de Un poeta recita un texto suyo inédito

¿Qué es para ti la poesía?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 24:58: https://youtu.be/4hGozORt3Ds?t=1498

#LosParceritos #UbeimarRios #UnPoeta #Poesia #Colombia
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-04-parceritos-poema-cuarto-oscuro__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-04-parceritos-poema-cuarto-oscuro:instagram`

```text
"La poesía, dicen, es como un cuarto a oscuras…" — Ubeimar Ríos

Le piden un texto que se quedó en el archivo y Ubeimar Ríos lo recita: "La poesía, dicen, es como un cuarto a oscuras…".

¿Qué es para ti la poesía?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 24:58: https://youtu.be/4hGozORt3Ds?t=1498

#LosParceritos #UbeimarRios #UnPoeta #Poesia #Colombia
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-04-parceritos-poema-cuarto-oscuro__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-04-parceritos-poema-cuarto-oscuro:youtube`

**Título:** Ubeimar Ríos recita un texto inédito | Los Parceritos

**Descripción:**

```text
Le piden un texto que se quedó en el archivo y Ubeimar Ríos lo recita: "La poesía, dicen, es como un cuarto a oscuras…".

¿Qué es para ti la poesía?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 24:58: https://youtu.be/4hGozORt3Ds?t=1498

#LosParceritos #UbeimarRios #UnPoeta #Poesia
```

**Etiquetas:** Los Parceritos, Ubeimar Ríos, Un poeta, poesía, texto inédito, Colombia

### 52. 2026-11-04-parceritos-vomitar-premios

- **Gancho:** Corrió hasta vomitar y le predijeron premios · **Tipo:** `historia` · **Puntaje:** 66 · **Duración:** 30,6 s · **Ventana hasta:** 2026-11-19
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-04-parceritos-vomitar-premios/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-04-parceritos-vomitar-premios/ficha.md)
- **Fuente:** https://youtu.be/4hGozORt3Ds?t=403 (Los Parceritos, minuto 6:43)
- **Aprobar:** `/publicador aprobar 2026-11-04-parceritos-vomitar-premios`

#### TikTok

Envío: `datos/publicador/envios/2026-11-04-parceritos-vomitar-premios__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-04-parceritos-vomitar-premios:tiktok`

```text
Corrió hasta vomitar… y le predijeron premios 🏆

¿Se cumplió la predicción?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 6:43: https://youtu.be/4hGozORt3Ds?t=403

#LosParceritos #UbeimarRios #UnPoeta #CineColombiano #Cannes
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-04-parceritos-vomitar-premios__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-04-parceritos-vomitar-premios:instagram`

```text
"Llore lo que quiera, pero se va a ganar varios premios"

Rodando la carrera de 'Un poeta', Ubeimar Ríos ya no podía más: 70 personas gritándole "¡poeta, poeta!", terminó vomitando junto a un árbol y llorando del esfuerzo. Entonces la tercera asistente de dirección le dijo que iba a ganar premios como mejor actor.

¿Se cumplió la predicción?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 6:43: https://youtu.be/4hGozORt3Ds?t=403

#LosParceritos #UbeimarRios #UnPoeta #CineColombiano #Cannes
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-04-parceritos-vomitar-premios__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-04-parceritos-vomitar-premios:youtube`

**Título:** Así se grabó la carrera de Un poeta, según su protagonista

**Descripción:**

```text
Rodando la carrera de 'Un poeta', Ubeimar Ríos ya no podía más: 70 personas gritándole "¡poeta, poeta!", terminó vomitando junto a un árbol y llorando del esfuerzo. Entonces la tercera asistente de dirección le dijo que iba a ganar premios como mejor actor.

¿Se cumplió la predicción?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 6:43: https://youtu.be/4hGozORt3Ds?t=403

#LosParceritos #UbeimarRios #UnPoeta #CineColombiano
```

**Etiquetas:** Los Parceritos, Ubeimar Ríos, Un poeta, cine colombiano, rodaje, anécdota

### 53. 2026-11-04-parceritos-fracaso-objetividad

- **Gancho:** ¿Qué se necesita para aceptar el fracaso? · **Tipo:** `frase` · **Puntaje:** 65 · **Duración:** 40,4 s · **Ventana hasta:** 2026-11-19
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-04-parceritos-fracaso-objetividad/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-04-parceritos-fracaso-objetividad/ficha.md)
- **Fuente:** https://youtu.be/4hGozORt3Ds?t=1098 (Los Parceritos, minuto 18:18)
- **Aprobar:** `/publicador aprobar 2026-11-04-parceritos-fracaso-objetividad`

#### TikTok

Envío: `datos/publicador/envios/2026-11-04-parceritos-fracaso-objetividad__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-04-parceritos-fracaso-objetividad:tiktok`

```text
¿Qué se necesita para aceptar el fracaso? Una palabra

¿Estás de acuerdo?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 18:18: https://youtu.be/4hGozORt3Ds?t=1098

#LosParceritos #UbeimarRios #UnPoeta #Filosofia #Fracaso
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-04-parceritos-fracaso-objetividad__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-04-parceritos-fracaso-objetividad:instagram`

```text
"Yo soy fracasado en literatura" — el protagonista de Un poeta

Ubeimar Ríos sobre lo que comparte con Óscar, su personaje en 'Un poeta': ser profe, el trago… y el fracaso en la literatura. ¿Qué se necesita para aceptar el fracaso? "Objetividad".

¿Estás de acuerdo?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 18:18: https://youtu.be/4hGozORt3Ds?t=1098

#LosParceritos #UbeimarRios #UnPoeta #Filosofia #Fracaso
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-04-parceritos-fracaso-objetividad__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-04-parceritos-fracaso-objetividad:youtube`

**Título:** La respuesta de un filósofo sobre el fracaso | Ubeimar Ríos

**Descripción:**

```text
Ubeimar Ríos sobre lo que comparte con Óscar, su personaje en 'Un poeta': ser profe, el trago… y el fracaso en la literatura. ¿Qué se necesita para aceptar el fracaso? "Objetividad".

¿Estás de acuerdo?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 13: EL POETA». Momento original desde el minuto 18:18: https://youtu.be/4hGozORt3Ds?t=1098

#LosParceritos #UbeimarRios #UnPoeta #Filosofia
```

**Etiquetas:** Los Parceritos, Ubeimar Ríos, Un poeta, filosofía, fracaso, reflexión

### 54. 2026-11-06-kris-r-musica-cambia-vida

- **Gancho:** Cómo la música le cambió la vida a Kris R · **Tipo:** `frase` · **Puntaje:** 73 · **Duración:** 27,8 s · **Ventana hasta:** 2026-11-20
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-06-kris-r-musica-cambia-vida/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-06-kris-r-musica-cambia-vida/ficha.md)
- **Fuente:** https://youtu.be/XcgyVpbHNlw?t=127 (WestCOL, minuto 2:07)
- **Aprobar:** `/publicador aprobar 2026-11-06-kris-r-musica-cambia-vida`

#### TikTok

Envío: `datos/publicador/envios/2026-11-06-kris-r-musica-cambia-vida__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-06-kris-r-musica-cambia-vida:tiktok`

```text
"La música en un segundito te cambia la vida": hablan de Kris R en el directo de Westcol 🎤

¿La música o el streaming: qué cambia la vida más rápido?

Crédito: canal WestCOL, «¿CUANTO DINERO GANO LA PLENA ? 🤑 | WESTCOL». Momento original desde el minuto 2:07: https://youtu.be/XcgyVpbHNlw?t=127

#KrisR #Westcol #MúsicaUrbana #Trap #Colombia
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-06-kris-r-musica-cambia-vida__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-06-kris-r-musica-cambia-vida:instagram`

```text
"La música en un segundito te cambia la vida"

En el directo de Westcol ponen de ejemplo a Kris R: "ya con tres cadenas, dos G-Wagon, compró casa… La gente busca una oportunidad durante 10 años". Kris R no sale en el clip: se habla de él.

¿La música o el streaming: qué cambia la vida más rápido?

Crédito: canal WestCOL, «¿CUANTO DINERO GANO LA PLENA ? 🤑 | WESTCOL». Momento original desde el minuto 2:07: https://youtu.be/XcgyVpbHNlw?t=127

#KrisR #Westcol #MúsicaUrbana #Trap #Colombia
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-06-kris-r-musica-cambia-vida__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-06-kris-r-musica-cambia-vida:youtube`

**Título:** "La música te cambia la vida": el ejemplo de Kris R en el directo de Westcol

**Descripción:**

```text
En el directo de Westcol ponen de ejemplo a Kris R: "ya con tres cadenas, dos G-Wagon, compró casa… la música en un segundito te cambia la vida". Kris R no sale en el clip.

¿La música o el streaming: qué cambia la vida más rápido?

Crédito: canal WestCOL, «¿CUANTO DINERO GANO LA PLENA ? 🤑 | WESTCOL». Momento original desde el minuto 2:07: https://youtu.be/XcgyVpbHNlw?t=127

#KrisR #Westcol #MúsicaUrbana #Trap
```

**Etiquetas:** Kris R, Westcol, música urbana, trap, trap colombiano, Colombia, streamers

### 55. 2026-11-01-kris-r-musica-cada-semana

- **Gancho:** Así se pegó Kris R · **Tipo:** `consejo` · **Puntaje:** 72 · **Duración:** 59,8 s · **Ventana hasta:** 2026-11-20
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** clip.mp4: el archivo no está en esta copia del proyecto (no es un error: la entrada se puede aprobar igual, pero para subirlo hace falta el video) · **Ficha:** [ficha.md](../clipero/clips/2026-11-01-kris-r-musica-cada-semana/ficha.md)
- **Fuente:** https://youtu.be/hSV5nuZ5w_I?t=431 (ElWerik Podcast, minuto 7:11)
- **Aprobar:** `/publicador aprobar 2026-11-01-kris-r-musica-cada-semana`

#### TikTok

Envío: `datos/publicador/envios/2026-11-01-kris-r-musica-cada-semana__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-01-kris-r-musica-cada-semana:tiktok`

```text
3 palos en una canción y desaparecer: el error de los artistas nuevos, según ElWerik Podcast

Si estás empezando: ¿un tema caro o música cada semana?

Crédito: canal ElWerik Podcast, «KRIS R y el TRAP DE BOGOTÁ: crítica al CONCIERTO y lo que pasó en el BACKSTAGE». Momento original desde el minuto 7:11: https://youtu.be/hSV5nuZ5w_I?t=431

#KrisR #Trap #ArtistasNuevos #MúsicaIndependiente #MúsicaUrbana
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-01-kris-r-musica-cada-semana__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-01-kris-r-musica-cada-semana:instagram`

```text
Así se pegó Kris R, según quien dice conocerlo desde el principio

En ElWerik Podcast cuentan cómo se pegó Kris R, según quien dice conocerlo desde el principio: una camarita, música cada semana y un catálogo que se fue armando. ¿Y el error de los nuevos? Invertir 3 millones en un tema y desaparecer cuatro o cinco meses.

Si estás empezando: ¿un tema caro o música cada semana?

Crédito: canal ElWerik Podcast, «KRIS R y el TRAP DE BOGOTÁ: crítica al CONCIERTO y lo que pasó en el BACKSTAGE». Momento original desde el minuto 7:11: https://youtu.be/hSV5nuZ5w_I?t=431

#KrisR #Trap #ArtistasNuevos #MúsicaIndependiente #MúsicaUrbana
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-01-kris-r-musica-cada-semana__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-01-kris-r-musica-cada-semana:youtube`

**Título:** Cómo se pegó Kris R, según ElWerik Podcast: música cada semana

**Descripción:**

```text
En ElWerik Podcast cuentan cómo se pegó Kris R, según quien dice conocerlo desde el principio: una camarita, música cada semana y un catálogo que se fue armando. ¿Y el error de los nuevos? Invertir 3 millones en un tema y desaparecer cuatro o cinco meses.

Si estás empezando: ¿un tema caro o música cada semana?

Crédito: canal ElWerik Podcast, «KRIS R y el TRAP DE BOGOTÁ: crítica al CONCIERTO y lo que pasó en el BACKSTAGE». Momento original desde el minuto 7:11: https://youtu.be/hSV5nuZ5w_I?t=431

#KrisR #Trap #ArtistasNuevos #MúsicaIndependiente
```

**Etiquetas:** Kris R, trap, artistas nuevos, música independiente, ElWerik Podcast, industria musical

### 56. 2026-11-01-kris-r-primer-estadio

- **Gancho:** De 20 personas… ¿a su primer estadio? · **Tipo:** `prediccion` · **Puntaje:** 71 · **Duración:** 36,7 s · **Ventana hasta:** 2026-11-20
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** clip.mp4: el archivo no está en esta copia del proyecto (no es un error: la entrada se puede aprobar igual, pero para subirlo hace falta el video) · **Ficha:** [ficha.md](../clipero/clips/2026-11-01-kris-r-primer-estadio/ficha.md)
- **Fuente:** https://youtu.be/hSV5nuZ5w_I?t=551 (ElWerik Podcast, minuto 9:11)
- **Aprobar:** `/publicador aprobar 2026-11-01-kris-r-primer-estadio`

#### TikTok

Envío: `datos/publicador/envios/2026-11-01-kris-r-primer-estadio__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-01-kris-r-primer-estadio:tiktok`

```text
Lo vio con 20 personas en una discoteca. Ahora predice su primer estadio

¿Kris R llena un estadio en 2027? Sí o no

Crédito: canal ElWerik Podcast, «KRIS R y el TRAP DE BOGOTÁ: crítica al CONCIERTO y lo que pasó en el BACKSTAGE». Momento original desde el minuto 9:11: https://youtu.be/hSV5nuZ5w_I?t=551

#KrisR #Trap #TrapColombiano #MovistarArena #MúsicaUrbana
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-01-kris-r-primer-estadio__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-01-kris-r-primer-estadio:instagram`

```text
¿Kris R llena un estadio el año que viene? Un podcaster cree que sí

"Una primera vez fue una discoteca allá en Medellín, 20 personas". Después 200, después el Royal Center, y este año el Movistar. En ElWerik Podcast se atreven a predecir: el año que viene, su primer estadio. Es su opinión, no un anuncio. ¿Lo logra?

¿Kris R llena un estadio en 2027? Sí o no

Crédito: canal ElWerik Podcast, «KRIS R y el TRAP DE BOGOTÁ: crítica al CONCIERTO y lo que pasó en el BACKSTAGE». Momento original desde el minuto 9:11: https://youtu.be/hSV5nuZ5w_I?t=551

#KrisR #Trap #TrapColombiano #MovistarArena #MúsicaUrbana
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-01-kris-r-primer-estadio__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-01-kris-r-primer-estadio:youtube`

**Título:** De una discoteca de 20 personas al Movistar: la subida de Kris R | ElWerik Podcast

**Descripción:**

```text
"Una primera vez fue una discoteca allá en Medellín, 20 personas". Después 200, después el Royal Center, y este año el Movistar. En ElWerik Podcast se atreven a predecir: el año que viene, su primer estadio. Es su opinión, no un anuncio. ¿Lo logra?

¿Kris R llena un estadio en 2027? Sí o no

Crédito: canal ElWerik Podcast, «KRIS R y el TRAP DE BOGOTÁ: crítica al CONCIERTO y lo que pasó en el BACKSTAGE». Momento original desde el minuto 9:11: https://youtu.be/hSV5nuZ5w_I?t=551

#KrisR #Trap #TrapColombiano #MovistarArena
```

**Etiquetas:** Kris R, trap, trap colombiano, Movistar Arena, ElWerik Podcast, estadio

## Comandos

- Aprobar todas las plataformas de un clip: `/publicador aprobar <clip-id>`
- Aprobar una sola plataforma: `/publicador aprobar <clip-id>:<plataforma>` (por ejemplo, `/publicador aprobar 2026-11-06-samulx-me-quedo-en-colombia:tiktok`)
- Aprobar todo lo pendiente: `/publicador aprobar todo`
- Rechazar: `/publicador rechazar <clip-id> <motivo>`
- Cambiar un texto: por ejemplo, `/publicador cambia el título de YouTube de <clip-id> por ...`
