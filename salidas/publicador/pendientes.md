# Pendientes de aprobación del Publicador

Actualizado: 2026-11-09 17:42 (-05:00) · ciclo 5 · modo `aprobacion`

Hay **75 clips y 225 envíos pendientes de aprobación** (TikTok, Instagram y YouTube). Van ordenados por ventana, de la que cierra antes a la que cierra después, y, si la ventana es la misma, por puntaje. El modo es `aprobacion`, así que no se publica nada hasta que lo apruebes.

## Antes de aprobar

- **Ninguna plataforma tiene credenciales en esta PC.** El script devuelve `sin_credenciales` en las cuatro. TikTok sigue activa en `config.json`, pero hay que volver a autorizarla. Hazlo en tu propia ventana de PowerShell, desde la carpeta del proyecto:
  `powershell -NoProfile -ExecutionPolicy Bypass -File legion/03-publicador/publicar.ps1 autorizar -Plataforma tiktok`
  YouTube e Instagram tampoco tienen credenciales ni están activas (`plataformas.md` §3 y §5). Puedes aprobar por adelantado: lo aprobado se sube cuando la plataforma esté lista, si la ventana sigue abierta.
- **1 ventana cierra hoy, 2026-11-09:** `2026-11-05-westcol-batisenal-w`. Si no se aprueba hoy, el próximo ciclo la marca vencida.
- **Faltan videos.** 4 clips pendientes no tienen `clip.mp4` en esta copia: `2026-11-02-toxico-celos-completo`, `2026-11-02-toxico-coro-eres-mia`, `2026-11-02-toxico-verso-mando-la-ubi`, `2026-11-02-toxico-intro-celos-aire`. Se pueden aprobar, pero para subirlos hay que volver a generarlos o copiarlos.
- **Derechos:** salvo `2026-11-02-toxico-celos-completo`, `2026-11-02-toxico-coro-eres-mia`, `2026-11-02-toxico-verso-mando-la-ubi`, `2026-11-02-toxico-intro-celos-aire` (`autorizado`), todo es `sin_verificar`. Solo se publica si lo apruebas expresamente, y siempre lleva el crédito a la fuente con el minuto.
- **TikTok, en modo borrador:** el video llega a tu bandeja y el texto se pega en la app. Como mucho caben 5 borradores pendientes por API cada 24 h, así que publica o descarta los que ya tengas antes de aprobar más.
- **Westcol, «¿CUANTO DINERO GANO LA PLENA?»:** en esos clips no se comprobó por la cara quién dice cada frase, así que los textos dicen «en el directo de Westcol» y no atribuyen las citas a nadie en concreto.
- **Cifras y afirmaciones de Westcol** (motosierra del robot, producción de Win Sports, 500 personas, 100.000 dólares por artista, 25.000 del Patek, 300.000 del carro, pony de Uribe): los textos las presentan como dichas por él, sin verificar.
- **Vencidos este ciclo (11 clips):** `2026-11-05-maluma-bebe-capo`, `2026-11-05-maluma-loco-por-girar`, `2026-11-01-chanty-freestyle-dame-hombro`, `2026-11-01-kris-r-critica-trap-bogota`, `2026-11-01-kris-r-avion-musica-desechable`, `2026-11-01-kris-r-almighty-miedo`, `2026-11-06-samulx-me-quedo-en-colombia`, `2026-11-06-samulx-medellin-caracas`, `2026-11-06-samulx-tour-por-colombia`, `2026-11-06-samulx-sorpresa-filtrada`, `2026-11-06-samulx-playa-medellin`. Siguen en `datos/publicador/envios/`. Una aprobación expresa los vuelve a activar.

## Clips

### 1. 2026-11-05-westcol-batisenal-w

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

### 2. 2026-11-06-westcol-cuanto-hizo-la-plena

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

### 3. 2026-11-05-westcol-dinero-parqueado

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

### 4. 2026-11-05-westcol-regateo-revuelto

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

### 5. 2026-11-06-westcol-pago-por-reaccionar

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

### 6. 2026-11-05-revuelto-beneficio-tributario

- **Gancho:** El beneficio tributario del Lambo híbrido · **Tipo:** `consejo` · **Puntaje:** 76 · **Duración:** 46 s · **Ventana hasta:** 2026-11-10
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

### 7. 2026-11-05-westcol-precio-lambo-bajara

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

### 8. 2026-11-06-kick-house-coming-soon

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

### 9. 2026-11-05-maluma-juan-luis-primero

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

### 10. 2026-11-05-westcol-asi-pagaria-el-lambo

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

### 11. 2026-11-05-maluma-tiempo-largo-argentina

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

### 12. 2026-11-05-maluma-sos-maluma

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

### 13. 2026-11-05-westcol-carro-en-cada-ciudad

- **Gancho:** ¿Un carro en cada ciudad? · **Tipo:** `humor` · **Puntaje:** 71 · **Duración:** 58,6 s · **Ventana hasta:** 2026-11-11
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-westcol-carro-en-cada-ciudad/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-westcol-carro-en-cada-ciudad/ficha.md)
- **Fuente:** https://youtu.be/KhuFp9eIyVU?t=973 (WestCOL, minuto 16:13)
- **Aprobar:** `/publicador aprobar 2026-11-05-westcol-carro-en-cada-ciudad`

#### TikTok

Envío: `datos/publicador/envios/2026-11-05-westcol-carro-en-cada-ciudad__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-05-westcol-carro-en-cada-ciudad:tiktok`

```text
¿Un carro en cada ciudad? La respuesta en RR Autos 😂

¿Un carro en cada ciudad o prestado?

Crédito: canal WestCOL, «FUI A VER MI PROXIMO SUPER AUTO 🔥 | WESTCOL». Momento original desde el minuto 16:13: https://youtu.be/KhuFp9eIyVU?t=973

#Westcol #LaGanga #Carros #Humor
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-05-westcol-carro-en-cada-ciudad__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-05-westcol-carro-en-cada-ciudad:instagram`

```text
"Para eso tengo a Diego que me presta los carros" 😂

En RR Autos, la Ganga discute si "un hombre de verdad" tendría un carro en cada ciudad.

¿Un carro en cada ciudad o prestado?

Crédito: canal WestCOL, «FUI A VER MI PROXIMO SUPER AUTO 🔥 | WESTCOL». Momento original desde el minuto 16:13: https://youtu.be/KhuFp9eIyVU?t=973

#Westcol #LaGanga #Carros #Humor
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-05-westcol-carro-en-cada-ciudad__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-05-westcol-carro-en-cada-ciudad:youtube`

**Título:** La Ganga discute si hace falta un carro en cada ciudad

**Descripción:**

```text
En RR Autos, la Ganga discute si "un hombre de verdad" tendría un carro en cada ciudad. La respuesta: "para eso tengo a Diego que me presta los carros".

¿Un carro en cada ciudad o prestado?

Crédito: canal WestCOL, «FUI A VER MI PROXIMO SUPER AUTO 🔥 | WESTCOL». Momento original desde el minuto 16:13: https://youtu.be/KhuFp9eIyVU?t=973

#Westcol #LaGanga #Carros #Humor
```

**Etiquetas:** Westcol, la Ganga, RR Autos, carros, humor, Kick

### 14. 2026-11-05-westcol-perderias-300mil

- **Gancho:** Lo que pierdes al comprar ese carro · **Tipo:** `consejo` · **Puntaje:** 70 · **Duración:** 28,8 s · **Ventana hasta:** 2026-11-11
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-westcol-perderias-300mil/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-westcol-perderias-300mil/ficha.md)
- **Fuente:** https://youtu.be/LgnQHaFVvyo?t=829 (WestCOL, minuto 13:49)
- **Aprobar:** `/publicador aprobar 2026-11-05-westcol-perderias-300mil`

#### TikTok

Envío: `datos/publicador/envios/2026-11-05-westcol-perderias-300mil__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-05-westcol-perderias-300mil:tiktok`

```text
Westcol: "En el momento que usted haga esa compra aquí en Colombia son 300.000 perdidos" 🚗

¿Comprarías un carro sabiendo esto?

Crédito: canal WestCOL, «ESTE ES MI NUEVO SET-UP | WESTCOL». Momento original desde el minuto 13:49: https://youtu.be/LgnQHaFVvyo?t=829

#Westcol #Carros #Lujo #Colombia
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-05-westcol-perderias-300mil__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-05-westcol-perderias-300mil:instagram`

```text
Lo que dice Westcol antes de comprar un súper carro en Colombia 🚗

"Hay carros que usted compra y si los vende le puede sacar ganancia… Usted compra ese carro, papi, le va a perder plata".

¿Comprarías un carro sabiendo esto?

Crédito: canal WestCOL, «ESTE ES MI NUEVO SET-UP | WESTCOL». Momento original desde el minuto 13:49: https://youtu.be/LgnQHaFVvyo?t=829

#Westcol #Carros #Lujo #Colombia
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-05-westcol-perderias-300mil__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-05-westcol-perderias-300mil:youtube`

**Título:** Westcol: hay carros que pierden 300.000 apenas los compras

**Descripción:**

```text
"Usted compra ese carro, papi, le va a perder plata. En el momento que usted haga esa compra aquí en Colombia son 300.000 perdidos." La cifra es la que él da; no es un consejo financiero.

¿Comprarías un carro sabiendo esto?

Crédito: canal WestCOL, «ESTE ES MI NUEVO SET-UP | WESTCOL». Momento original desde el minuto 13:49: https://youtu.be/LgnQHaFVvyo?t=829

#Westcol #Carros #Lujo #Colombia
```

**Etiquetas:** Westcol, carros, súper carro, Colombia, lujo, depreciación

### 15. 2026-11-05-westcol-retiro-de-streamer

- **Gancho:** Westcol: apartamento de retiro de streamer · **Tipo:** `frase` · **Puntaje:** 69 · **Duración:** 34,3 s · **Ventana hasta:** 2026-11-11
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-westcol-retiro-de-streamer/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-westcol-retiro-de-streamer/ficha.md)
- **Fuente:** https://youtu.be/LgnQHaFVvyo?t=289 (WestCOL, minuto 4:49)
- **Aprobar:** `/publicador aprobar 2026-11-05-westcol-retiro-de-streamer`

#### TikTok

Envío: `datos/publicador/envios/2026-11-05-westcol-retiro-de-streamer__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-05-westcol-retiro-de-streamer:tiktok`

```text
Westcol: "Esto es un apartamento de retiro de streamer" 🎮

¿Qué le falta al set?

Crédito: canal WestCOL, «ESTE ES MI NUEVO SET-UP | WESTCOL». Momento original desde el minuto 4:49: https://youtu.be/LgnQHaFVvyo?t=289

#Westcol #SetUp #Streamer #Kick
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-05-westcol-retiro-de-streamer__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-05-westcol-retiro-de-streamer:instagram`

```text
"El paraíso de un hombre": así es el set nuevo de Westcol 🎮

"Esto es un apartamento de retiro de streamer. Los streamers todavía no han llegado a este tipo de cosas aquí en Latam".

¿Qué le falta al set?

Crédito: canal WestCOL, «ESTE ES MI NUEVO SET-UP | WESTCOL». Momento original desde el minuto 4:49: https://youtu.be/LgnQHaFVvyo?t=289

#Westcol #SetUp #Streamer #Kick
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-05-westcol-retiro-de-streamer__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-05-westcol-retiro-de-streamer:youtube`

**Título:** Westcol: "Esto es un apartamento de retiro de streamer"

**Descripción:**

```text
Westcol enseña su set nuevo: "Los streamers todavía no han llegado a este tipo de cosas aquí en Latam".

¿Qué le falta al set?

Crédito: canal WestCOL, «ESTE ES MI NUEVO SET-UP | WESTCOL». Momento original desde el minuto 4:49: https://youtu.be/LgnQHaFVvyo?t=289

#Westcol #SetUp #Streamer #Kick
```

**Etiquetas:** Westcol, set up, streamer, Kick, Latam, gaming

### 16. 2026-11-05-maluma-bizarrap-martinis

- **Gancho:** Maluma: 'no sabía que era tan buena gente' · **Tipo:** `frase` · **Puntaje:** 67 · **Duración:** 39,5 s · **Ventana hasta:** 2026-11-11
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-maluma-bizarrap-martinis/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-maluma-bizarrap-martinis/ficha.md)
- **Fuente:** https://youtu.be/iNxDQVDIer8?t=3214 (LUZU TV, minuto 53:34)
- **Aprobar:** `/publicador aprobar 2026-11-05-maluma-bizarrap-martinis`

#### TikTok

Envío: `datos/publicador/envios/2026-11-05-maluma-bizarrap-martinis__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-05-maluma-bizarrap-martinis:tiktok`

```text
Maluma sobre Bizarrap: "No sabía que ese cabrón también era tan buena gente" 🎤

¿Quieres la sesión de Maluma con Bizarrap?

Crédito: canal LUZU TV, «#FMLUZU | MALUMA NOS LLAMÓ EN VIVO + FERBO EN CONTRA DE DOMI Y EL EQUIPO ROSA + VARONES CON TALENTO». Momento original desde el minuto 53:34: https://youtu.be/iNxDQVDIer8?t=3214

#Maluma #Bizarrap #BzrpMusicSessions #Shakira #FMLuzu
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-05-maluma-bizarrap-martinis__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-05-maluma-bizarrap-martinis:instagram`

```text
¿Se viene una sesión de Maluma con Bizarrap? 🎤

Coincidieron en el concierto de Shakira en Madrid: "aparte de muchos martinis, hablamos de la vida". Y Maluma suelta: "sería bonito tener una oportunidad de hacer una sesión con él".

¿Quieres la sesión de Maluma con Bizarrap?

Crédito: canal LUZU TV, «#FMLUZU | MALUMA NOS LLAMÓ EN VIVO + FERBO EN CONTRA DE DOMI Y EL EQUIPO ROSA + VARONES CON TALENTO». Momento original desde el minuto 53:34: https://youtu.be/iNxDQVDIer8?t=3214

#Maluma #Bizarrap #BzrpMusicSessions #Shakira #FMLuzu
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-05-maluma-bizarrap-martinis__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-05-maluma-bizarrap-martinis:youtube`

**Título:** ¿Se viene la Bzrp Session de Maluma?

**Descripción:**

```text
En FM Luzu, Maluma cuenta que coincidió con Bizarrap en el concierto de Shakira en Madrid y que "sería bonito tener una oportunidad de hacer una sesión con él". Es un deseo, no un anuncio.

¿Quieres la sesión de Maluma con Bizarrap?

Crédito: canal LUZU TV, «#FMLUZU | MALUMA NOS LLAMÓ EN VIVO + FERBO EN CONTRA DE DOMI Y EL EQUIPO ROSA + VARONES CON TALENTO». Momento original desde el minuto 53:34: https://youtu.be/iNxDQVDIer8?t=3214

#Maluma #Bizarrap #BzrpMusicSessions #Shakira
```

**Etiquetas:** Maluma, Bizarrap, Bzrp Music Sessions, Shakira, FM Luzu, Luzu TV

### 17. 2026-11-06-lonche-un-ano-despues

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

### 18. 2026-11-06-westcol-si-fuera-mexicano

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

### 19. 2026-11-06-ovy-cancion-en-pelicula

- **Gancho:** Lo que más dinero deja en la música · **Tipo:** `consejo` · **Puntaje:** 73 · **Duración:** 27 s · **Ventana hasta:** 2026-11-12
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

### 20. 2026-11-09-westcol-amigo-de-toda-la-vida

- **Gancho:** Westcol, antes de recoger a Samulx · **Tipo:** `emotivo` · **Puntaje:** 72 · **Duración:** 53,1 s · **Ventana hasta:** 2026-11-12
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-09-westcol-amigo-de-toda-la-vida/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-09-westcol-amigo-de-toda-la-vida/ficha.md)
- **Fuente:** https://youtu.be/nug3h47QoTY?t=5 (WestCOL Exclusive, minuto 0:05)
- **Aprobar:** `/publicador aprobar 2026-11-09-westcol-amigo-de-toda-la-vida`

#### TikTok

Envío: `datos/publicador/envios/2026-11-09-westcol-amigo-de-toda-la-vida__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-09-westcol-amigo-de-toda-la-vida:tiktok`

```text
Westcol, antes de recoger a Samulx: "uno de mis mejores amigos de toda la vida" 🇨🇴

Etiqueta a tu amigo de toda la vida.

Crédito: canal WestCOL Exclusive, «PRIMERA VEZ DE SAMULX EN COLOMBIA». Momento original desde el minuto 0:05: https://youtu.be/nug3h47QoTY?t=5

#Westcol #Samulx #Amistad #Medellín #Colombia
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-09-westcol-amigo-de-toda-la-vida__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-09-westcol-amigo-de-toda-la-vida:instagram`

```text
8 años de amistad y Samulx por fin viene a Colombia 🇨🇴

Antes de ir a recogerlo al aeropuerto, Westcol cuenta que lo conoce desde hace unos 8 años y que quiere mostrarle "todo lo que hemos logrado": su casa, la guarida, los restaurantes y Medellín.

Etiqueta a tu amigo de toda la vida.

Crédito: canal WestCOL Exclusive, «PRIMERA VEZ DE SAMULX EN COLOMBIA». Momento original desde el minuto 0:05: https://youtu.be/nug3h47QoTY?t=5

#Westcol #Samulx #Amistad #Medellín #Colombia
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-09-westcol-amigo-de-toda-la-vida__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-09-westcol-amigo-de-toda-la-vida:youtube`

**Título:** Westcol antes de recoger a Samulx: "le quiero mostrar todo lo que hemos logrado"

**Descripción:**

```text
Antes de recoger a Samulx en el aeropuerto, Westcol cuenta que lo conoce desde hace unos 8 años, que Samulx llevaba "12 o 15 años" sin salir de Estados Unidos y que quiere mostrarle su casa, la guarida y Medellín.

Etiqueta a tu amigo de toda la vida.

Crédito: canal WestCOL Exclusive, «PRIMERA VEZ DE SAMULX EN COLOMBIA». Momento original desde el minuto 0:05: https://youtu.be/nug3h47QoTY?t=5

#Westcol #Samulx #Amistad #Medellín
```

**Etiquetas:** Westcol, Samulx, Medellín, Colombia, amistad, WestCOL Exclusive

### 21. 2026-11-09-dj-mario-responde-bananirou

- **Gancho:** DJ Mario responde a Bananirou · **Tipo:** `humor` · **Puntaje:** 69 · **Duración:** 37,7 s · **Ventana hasta:** 2026-11-12
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-09-dj-mario-responde-bananirou/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-09-dj-mario-responde-bananirou/ficha.md)
- **Fuente:** https://youtu.be/m6P9-CnFt4k?t=1552 (HAGAMOS TENDENCIA, minuto 25:52)
- **Aprobar:** `/publicador aprobar 2026-11-09-dj-mario-responde-bananirou`

#### TikTok

Envío: `datos/publicador/envios/2026-11-09-dj-mario-responde-bananirou__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-09-dj-mario-responde-bananirou:tiktok`

```text
DJ Mario responde a Bananirou: "¿Creéis que voy a reportar tres shorts?" 😂

¿De qué lado estás?

Crédito: canal HAGAMOS TENDENCIA, «RESUMEN SEMANAL: BANANIROU vs DJ MARIO - COSCU Y LA CHILENA HABLAN DE TIAGO - DUKI BAJÓ EL REMIX» (fragmento de un directo de DJ Mario). Momento original desde el minuto 25:52: https://youtu.be/m6P9-CnFt4k?t=1552

#DJMario #Bananirou #Streamers #Humor
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-09-dj-mario-responde-bananirou__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-09-dj-mario-responde-bananirou:instagram`

```text
DJ Mario responde a Bananirou y a los argentinos 😂

"Llevo un día entero en Twitter con argentinos… lleva robándome contenido 12 años y haciéndome millonario a mi costa. ¿Creéis que voy a reportar tres shorts?"

¿De qué lado estás?

Crédito: canal HAGAMOS TENDENCIA, «RESUMEN SEMANAL: BANANIROU vs DJ MARIO - COSCU Y LA CHILENA HABLAN DE TIAGO - DUKI BAJÓ EL REMIX» (fragmento de un directo de DJ Mario). Momento original desde el minuto 25:52: https://youtu.be/m6P9-CnFt4k?t=1552

#DJMario #Bananirou #Streamers #Humor
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-09-dj-mario-responde-bananirou__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-09-dj-mario-responde-bananirou:youtube`

**Título:** DJ Mario responde a Bananirou: "¿Creéis que voy a reportar tres shorts?"

**Descripción:**

```text
DJ Mario cierra en tono de broma la pelea con Bananirou: "lleva robándome contenido 12 años y haciéndome millonario a mi costa. ¿Creéis que voy a reportar tres shorts?".

¿De qué lado estás?

Crédito: canal HAGAMOS TENDENCIA, «RESUMEN SEMANAL: BANANIROU vs DJ MARIO - COSCU Y LA CHILENA HABLAN DE TIAGO - DUKI BAJÓ EL REMIX» (fragmento de un directo de DJ Mario). Momento original desde el minuto 25:52: https://youtu.be/m6P9-CnFt4k?t=1552

#DJMario #Bananirou #Streamers #Humor
```

**Etiquetas:** DJ Mario, Bananirou, streamers, Twitter, shorts, humor

### 22. 2026-11-06-bad-bunny-luian-historia

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

### 23. 2026-11-09-samulx-guarida-vacia

- **Gancho:** Samulx conoce la guarida... ya vacía · **Tipo:** `reaccion` · **Puntaje:** 68 · **Duración:** 42 s · **Ventana hasta:** 2026-11-12
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-09-samulx-guarida-vacia/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-09-samulx-guarida-vacia/ficha.md)
- **Fuente:** https://youtu.be/nug3h47QoTY?t=533 (WestCOL Exclusive, minuto 8:53)
- **Aprobar:** `/publicador aprobar 2026-11-09-samulx-guarida-vacia`

#### TikTok

Envío: `datos/publicador/envios/2026-11-09-samulx-guarida-vacia__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-09-samulx-guarida-vacia:tiktok`

```text
Samulx conoce la guarida… cuando ya está vacía

¿Qué momento de la guarida no olvidas?

Crédito: canal WestCOL Exclusive, «PRIMERA VEZ DE SAMULX EN COLOMBIA». Momento original desde el minuto 8:53: https://youtu.be/nug3h47QoTY?t=533

#Samulx #Westcol #LaGuarida #LaGanga #WSound
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-09-samulx-guarida-vacia__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-09-samulx-guarida-vacia:instagram`

```text
"Todos estos años la vi por internet": Samulx entra a la guarida de la Ganga

Su primera vez en la guarida llega justo cuando la están desmontando: "ya está todo abandonado". El estudio de la W Sound "todavía sigue ahí".

¿Qué momento de la guarida no olvidas?

Crédito: canal WestCOL Exclusive, «PRIMERA VEZ DE SAMULX EN COLOMBIA». Momento original desde el minuto 8:53: https://youtu.be/nug3h47QoTY?t=533

#Samulx #Westcol #LaGuarida #LaGanga #WSound
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-09-samulx-guarida-vacia__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-09-samulx-guarida-vacia:youtube`

**Título:** Samulx entra por primera vez a la guarida de Westcol… y ya está vacía

**Descripción:**

```text
Samulx conoce por primera vez la guarida, que vio "todos estos años por internet", justo cuando la están desmontando. El estudio de la W Sound "todavía sigue ahí".

¿Qué momento de la guarida no olvidas?

Crédito: canal WestCOL Exclusive, «PRIMERA VEZ DE SAMULX EN COLOMBIA». Momento original desde el minuto 8:53: https://youtu.be/nug3h47QoTY?t=533

#Samulx #Westcol #LaGuarida #LaGanga
```

**Etiquetas:** Samulx, Westcol, la guarida, la Ganga, W Sound, Medellín

### 24. 2026-11-09-duki-remix-murio

- **Gancho:** Duki enterró el remix que prometió · **Tipo:** `revelacion` · **Puntaje:** 67 · **Duración:** 34,4 s · **Ventana hasta:** 2026-11-12
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-09-duki-remix-murio/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-09-duki-remix-murio/ficha.md)
- **Fuente:** https://youtu.be/m6P9-CnFt4k?t=744 (HAGAMOS TENDENCIA, minuto 12:24)
- **Aprobar:** `/publicador aprobar 2026-11-09-duki-remix-murio`

#### TikTok

Envío: `datos/publicador/envios/2026-11-09-duki-remix-murio__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-09-duki-remix-murio:tiktok`

```text
Duki confirma que el remix de She Don't Give a Fo no va a salir: "Ya fue, fue una mala idea" 🎤

¿Querías el remix?

Crédito: canal HAGAMOS TENDENCIA, «RESUMEN SEMANAL: BANANIROU vs DJ MARIO - COSCU Y LA CHILENA HABLAN DE TIAGO - DUKI BAJÓ EL REMIX» (fragmento del directo de Duki). Momento original desde el minuto 12:24: https://youtu.be/m6P9-CnFt4k?t=744

#Duki #SheDontGiveAFo #Trap #MúsicaUrbana #Argentina
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-09-duki-remix-murio__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-09-duki-remix-murio:instagram`

```text
"Ya fue, fue una mala idea" 🎤 Duki y el remix que prometió en 2021

Había prometido un remix de "She Don't Give a Fo" para los cinco años de la canción. En su directo lo enterró: "Es difícil hacer un remix y que salga bien".

¿Querías el remix?

Crédito: canal HAGAMOS TENDENCIA, «RESUMEN SEMANAL: BANANIROU vs DJ MARIO - COSCU Y LA CHILENA HABLAN DE TIAGO - DUKI BAJÓ EL REMIX» (fragmento del directo de Duki). Momento original desde el minuto 12:24: https://youtu.be/m6P9-CnFt4k?t=744

#Duki #SheDontGiveAFo #Trap #MúsicaUrbana #Argentina
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-09-duki-remix-murio__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-09-duki-remix-murio:youtube`

**Título:** Duki confirma que no saldrá el remix de She Don't Give a Fo

**Descripción:**

```text
En 2021 Duki prometió un remix de "She Don't Give a Fo" para los cinco años de la canción. En su directo lo descartó: "Ya fue… fue una mala idea… es difícil hacer un remix y que salga bien".

¿Querías el remix?

Crédito: canal HAGAMOS TENDENCIA, «RESUMEN SEMANAL: BANANIROU vs DJ MARIO - COSCU Y LA CHILENA HABLAN DE TIAGO - DUKI BAJÓ EL REMIX» (fragmento del directo de Duki). Momento original desde el minuto 12:24: https://youtu.be/m6P9-CnFt4k?t=744

#Duki #SheDontGiveAFo #Trap #MúsicaUrbana
```

**Etiquetas:** Duki, She Don't Give a Fo, remix, trap argentino, música urbana, Argentina

### 25. 2026-11-09-modo-diablo-nueva-camada

- **Gancho:** Modo Diablo a la nueva camada · **Tipo:** `frase` · **Puntaje:** 70 · **Duración:** 39,5 s · **Ventana hasta:** 2026-11-13
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-09-modo-diablo-nueva-camada/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-09-modo-diablo-nueva-camada/ficha.md)
- **Fuente:** https://youtu.be/m6P9-CnFt4k?t=787 (HAGAMOS TENDENCIA, minuto 13:07)
- **Aprobar:** `/publicador aprobar 2026-11-09-modo-diablo-nueva-camada`

#### TikTok

Envío: `datos/publicador/envios/2026-11-09-modo-diablo-nueva-camada__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-09-modo-diablo-nueva-camada:tiktok`

```text
Modo Diablo a la nueva camada: "Hay gente que quiere ser famosa por ser famosa" 🎤

¿Fama o música?

Crédito: canal HAGAMOS TENDENCIA, «RESUMEN SEMANAL: BANANIROU vs DJ MARIO - COSCU Y LA CHILENA HABLAN DE TIAGO - DUKI BAJÓ EL REMIX» (fragmento del directo de Duki). Momento original desde el minuto 13:07: https://youtu.be/m6P9-CnFt4k?t=787

#Duki #ModoDiablo #NeoPistea #YSYA #Trap
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-09-modo-diablo-nueva-camada__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-09-modo-diablo-nueva-camada:instagram`

```text
"Hay gente que quiere ser famosa por ser famosa" 🎤 Modo Diablo a la nueva camada

En el directo de Duki antes de la preescucha de su álbum: "…la fama fue una consecuencia".

¿Fama o música?

Crédito: canal HAGAMOS TENDENCIA, «RESUMEN SEMANAL: BANANIROU vs DJ MARIO - COSCU Y LA CHILENA HABLAN DE TIAGO - DUKI BAJÓ EL REMIX» (fragmento del directo de Duki). Momento original desde el minuto 13:07: https://youtu.be/m6P9-CnFt4k?t=787

#Duki #ModoDiablo #NeoPistea #YSYA #Trap
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-09-modo-diablo-nueva-camada__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-09-modo-diablo-nueva-camada:youtube`

**Título:** Modo Diablo: el consejo a los artistas nuevos sobre la fama

**Descripción:**

```text
En el directo de Duki, Modo Diablo le habla a la nueva camada: "Hay gente que quiere ser famosa por ser famosa… la fama fue una consecuencia".

¿Fama o música?

Crédito: canal HAGAMOS TENDENCIA, «RESUMEN SEMANAL: BANANIROU vs DJ MARIO - COSCU Y LA CHILENA HABLAN DE TIAGO - DUKI BAJÓ EL REMIX» (fragmento del directo de Duki). Momento original desde el minuto 13:07: https://youtu.be/m6P9-CnFt4k?t=787

#Duki #ModoDiablo #NeoPistea #YSYA
```

**Etiquetas:** Duki, Modo Diablo, YSY A, Neo Pistea, trap argentino, música urbana, fama

### 26. 2026-11-06-samulx-peleador-sorpresa

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

### 27. 2026-11-05-westcol-negocio-blessd-discoteca

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

### 28. 2026-11-05-westcol-robot-sin-seguridad

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

### 29. 2026-11-09-westcol-robot-motosierra

- **Gancho:** Westcol le puso una motosierra a su robot · **Tipo:** `revelacion` · **Puntaje:** 82 · **Duración:** 52,6 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-09-westcol-robot-motosierra/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-09-westcol-robot-motosierra/ficha.md)
- **Fuente:** https://youtu.be/S5v1BWnXdaI?t=600 (WestCOL, minuto 10:00)
- **Oportunidad del Cazador:** `tema-stream-fighters-5`
- **Aprobar:** `/publicador aprobar 2026-11-09-westcol-robot-motosierra`

#### TikTok

Envío: `datos/publicador/envios/2026-11-09-westcol-robot-motosierra__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-09-westcol-robot-motosierra:tiktok`

```text
Westcol dice que le quitaron la seguridad a su robot y que le mandó poner una motosierra 🤖

¿Qué robot gana, el de Westcol o el de Blessd? Deja tu predicción.

Crédito: canal WestCOL, «Stream Fighters 5 va a ser HISTÓRICO (Mis expectativas) | WESTCOL». Momento original desde el minuto 10:00: https://youtu.be/S5v1BWnXdaI?t=600

#Westcol #StreamFighters5 #Robot #Blessd #Kick
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-09-westcol-robot-motosierra__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-09-westcol-robot-motosierra:instagram`

```text
Cuatro patadas voladoras y una motosierra: así dice Westcol que llega su robot a Stream Fighters 5 🤖

Cuenta que a su robot le quitaron las medidas de seguridad, que le mandó quitar una mano para ponerle una motosierra y que entrará con él al evento. Y le habla al "Bendito" (Blessd), su rival en el combate de robots.

¿Qué robot gana, el de Westcol o el de Blessd? Deja tu predicción.

Crédito: canal WestCOL, «Stream Fighters 5 va a ser HISTÓRICO (Mis expectativas) | WESTCOL». Momento original desde el minuto 10:00: https://youtu.be/S5v1BWnXdaI?t=600

#Westcol #StreamFighters5 #Robot #Blessd #Kick
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-09-westcol-robot-motosierra__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-09-westcol-robot-motosierra:youtube`

**Título:** El robot de Westcol para Stream Fighters 5 ya no tiene seguridad

**Descripción:**

```text
A una semana de Stream Fighters 5, Westcol cuenta que a su robot le quitaron las medidas de seguridad, que puede tirar "cuatro patadas voladoras seguidas" y que le mandó poner una motosierra en lugar de una mano. Es lo que él cuenta; en el clip no se ve el robot.

¿Qué robot gana, el de Westcol o el de Blessd? Deja tu predicción.

Crédito: canal WestCOL, «Stream Fighters 5 va a ser HISTÓRICO (Mis expectativas) | WESTCOL». Momento original desde el minuto 10:00: https://youtu.be/S5v1BWnXdaI?t=600

#Westcol #StreamFighters5 #Robot #Blessd
```

**Etiquetas:** Westcol, Stream Fighters 5, robot, Blessd, motosierra, Kick

### 30. 2026-11-09-westcol-willito-relevo-lonche

- **Gancho:** ¿Willito no le dará relevo a Lonche? · **Tipo:** `revelacion` · **Puntaje:** 80 · **Duración:** 32,8 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-09-westcol-willito-relevo-lonche/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-09-westcol-willito-relevo-lonche/ficha.md)
- **Fuente:** https://youtu.be/S5v1BWnXdaI?t=372 (WestCOL, minuto 6:12)
- **Oportunidad del Cazador:** `tema-stream-fighters-5`
- **Aprobar:** `/publicador aprobar 2026-11-09-westcol-willito-relevo-lonche`

#### TikTok

Envío: `datos/publicador/envios/2026-11-09-westcol-willito-relevo-lonche__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-09-westcol-willito-relevo-lonche:tiktok`

```text
¿Willito no le va a dar relevo a Lonche en Stream Fighters 5? 🥊

¿Ganan Willito y Lonche o Chanty y Samulx?

Crédito: canal WestCOL, «Stream Fighters 5 va a ser HISTÓRICO (Mis expectativas) | WESTCOL». Momento original desde el minuto 6:12: https://youtu.be/S5v1BWnXdaI?t=372

#StreamFighters5 #Westcol #Lonche #Willito #Kick
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-09-westcol-willito-relevo-lonche__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-09-westcol-willito-relevo-lonche:instagram`

```text
Westcol: "los únicos que no tienen hambre son Willy y Lonche" 🥊

Le llegó la información de que Willito "supuestamente" les ganará a los dos con una mano y no le dará relevo a Lonche, en la pelea de relevos contra Chanty y Samulx.

¿Ganan Willito y Lonche o Chanty y Samulx?

Crédito: canal WestCOL, «Stream Fighters 5 va a ser HISTÓRICO (Mis expectativas) | WESTCOL». Momento original desde el minuto 6:12: https://youtu.be/S5v1BWnXdaI?t=372

#StreamFighters5 #Westcol #Lonche #Willito #Kick
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-09-westcol-willito-relevo-lonche__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-09-westcol-willito-relevo-lonche:youtube`

**Título:** Willito y Lonche contra Chanty y Samulx: el rumor del relevo en Stream Fighters 5

**Descripción:**

```text
Westcol dice que Stream Fighters 5 es el evento con más peleas sin casco y comenta un rumor ("supuestamente", "me llegó esa información"): que Willito no le dará relevo a Lonche en la pelea contra Chanty y Samulx.

¿Ganan Willito y Lonche o Chanty y Samulx?

Crédito: canal WestCOL, «Stream Fighters 5 va a ser HISTÓRICO (Mis expectativas) | WESTCOL». Momento original desde el minuto 6:12: https://youtu.be/S5v1BWnXdaI?t=372

#StreamFighters5 #Westcol #Lonche #Willito
```

**Etiquetas:** Stream Fighters 5, Westcol, Willito, Lonche, Chanty, Samulx

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

### 32. 2026-11-02-toxico-celos-completo

- **Gancho:** Celos hasta del aire · **Tipo:** `frase` · **Puntaje:** 78 · **Duración:** 21,2 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `autorizado`.
- **Video:** [clip.mp4](../clipero/clips/2026-11-02-toxico-celos-completo/clip.mp4) (no está en esta copia) · **Ficha:** [ficha.md](../clipero/clips/2026-11-02-toxico-celos-completo/ficha.md)
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

### 33. 2026-11-06-ganga-el-que-pierde-se-sale

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

### 34. 2026-11-09-westcol-cadenas-ganga-rey

- **Gancho:** Si Rey pierde, se queda sin cadena · **Tipo:** `revelacion` · **Puntaje:** 76 · **Duración:** 38,9 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-09-westcol-cadenas-ganga-rey/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-09-westcol-cadenas-ganga-rey/ficha.md)
- **Fuente:** https://youtu.be/ybjXHgxGBMo?t=513 (WestCOL, minuto 8:33)
- **Oportunidad del Cazador:** `tema-stream-fighters-5`
- **Aprobar:** `/publicador aprobar 2026-11-09-westcol-cadenas-ganga-rey`

#### TikTok

Envío: `datos/publicador/envios/2026-11-09-westcol-cadenas-ganga-rey__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-09-westcol-cadenas-ganga-rey:tiktok`

```text
Siete cadenas para la Ganga en Stream Fighters 5… y Rey se puede quedar sin la suya ⛓️

¿Rey gana su pelea o se queda sin cadena?

Crédito: canal WestCOL, «Me GASTÉ $100.000 DÓLARES en un RICHARD MILLE (Valió la pena?) | WESTCOL». Momento original desde el minuto 8:33: https://youtu.be/ybjXHgxGBMo?t=513

#StreamFighters5 #Westcol #LaGanga #Reydelacity #Kick
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-09-westcol-cadenas-ganga-rey__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-09-westcol-cadenas-ganga-rey:instagram`

```text
Si Rey pierde en Stream Fighters 5, se queda sin cadena ⛓️

Westcol anuncia que en el camerino el joyero de Alto Rango le entregará a la Ganga siete cadenas, "va a ser sorpresa". Y recuerda que Rey dijo que si no gana se va de la Ganga: "se le quita esa cadena".

¿Rey gana su pelea o se queda sin cadena?

Crédito: canal WestCOL, «Me GASTÉ $100.000 DÓLARES en un RICHARD MILLE (Valió la pena?) | WESTCOL». Momento original desde el minuto 8:33: https://youtu.be/ybjXHgxGBMo?t=513

#StreamFighters5 #Westcol #LaGanga #Reydelacity #Kick
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-09-westcol-cadenas-ganga-rey__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-09-westcol-cadenas-ganga-rey:youtube`

**Título:** La sorpresa de Westcol para la Ganga en Stream Fighters 5

**Descripción:**

```text
Westcol anuncia que en el camerino de Stream Fighters 5 el joyero de Alto Rango le entregará a la Ganga siete cadenas. Y recuerda que Rey dijo que si no gana se va de la Ganga: "se le quita esa cadena".

¿Rey gana su pelea o se queda sin cadena?

Crédito: canal WestCOL, «Me GASTÉ $100.000 DÓLARES en un RICHARD MILLE (Valió la pena?) | WESTCOL». Momento original desde el minuto 8:33: https://youtu.be/ybjXHgxGBMo?t=513

#StreamFighters5 #Westcol #LaGanga #Reydelacity
```

**Etiquetas:** Stream Fighters 5, Westcol, la Ganga, Reydelacity, cadenas, Alto Rango

### 35. 2026-11-02-toxico-coro-eres-mia

- **Gancho:** El coro más tóxico · **Tipo:** `frase` · **Puntaje:** 76 · **Duración:** 21,7 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `autorizado`.
- **Video:** [clip.mp4](../clipero/clips/2026-11-02-toxico-coro-eres-mia/clip.mp4) (no está en esta copia) · **Ficha:** [ficha.md](../clipero/clips/2026-11-02-toxico-coro-eres-mia/ficha.md)
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

### 36. 2026-11-09-westcol-artistas-sorpresa

- **Gancho:** El truco de los artistas sorpresa · **Tipo:** `revelacion` · **Puntaje:** 76 · **Duración:** 34,3 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-09-westcol-artistas-sorpresa/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-09-westcol-artistas-sorpresa/ficha.md)
- **Fuente:** https://youtu.be/S5v1BWnXdaI?t=305 (WestCOL, minuto 5:05)
- **Oportunidad del Cazador:** `tema-stream-fighters-5`
- **Aprobar:** `/publicador aprobar 2026-11-09-westcol-artistas-sorpresa`

#### TikTok

Envío: `datos/publicador/envios/2026-11-09-westcol-artistas-sorpresa__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-09-westcol-artistas-sorpresa:tiktok`

```text
Por qué algunos artistas llegan "de sorpresa" a los eventos, según Westcol 🎤

¿Qué artista crees que llega de sorpresa?

Crédito: canal WestCOL, «Stream Fighters 5 va a ser HISTÓRICO (Mis expectativas) | WESTCOL». Momento original desde el minuto 5:05: https://youtu.be/S5v1BWnXdaI?t=305

#StreamFighters5 #Westcol #MúsicaUrbana #Kick #Colombia
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-09-westcol-artistas-sorpresa__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-09-westcol-artistas-sorpresa:instagram`

```text
El truco de los artistas sorpresa, según Westcol 🎤

A Stream Fighters 5 irán muchos artistas, pero algunos no se anuncian: si se anuncian, dice, "tiene que dar 100.000 dólares más" por estar firmados con una disquera. Si llegan de sorpresa, "le estoy haciendo un favor a un parcero".

¿Qué artista crees que llega de sorpresa?

Crédito: canal WestCOL, «Stream Fighters 5 va a ser HISTÓRICO (Mis expectativas) | WESTCOL». Momento original desde el minuto 5:05: https://youtu.be/S5v1BWnXdaI?t=305

#StreamFighters5 #Westcol #MúsicaUrbana #Kick #Colombia
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-09-westcol-artistas-sorpresa__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-09-westcol-artistas-sorpresa:youtube`

**Título:** Stream Fighters 5: por qué hay artistas que no se pueden anunciar

**Descripción:**

```text
Westcol adelanta que a Stream Fighters 5 irán muchos artistas y explica por qué algunos llegan de sorpresa: anunciarlos, dice, costaría "100.000 dólares más" por su disquera. La cifra es la que él da.

¿Qué artista crees que llega de sorpresa?

Crédito: canal WestCOL, «Stream Fighters 5 va a ser HISTÓRICO (Mis expectativas) | WESTCOL». Momento original desde el minuto 5:05: https://youtu.be/S5v1BWnXdaI?t=305

#StreamFighters5 #Westcol #MúsicaUrbana #Kick
```

**Etiquetas:** Stream Fighters 5, Westcol, artistas, música urbana, Kick, Colombia

### 37. 2026-11-05-westcol-robot-piquete

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

### 38. 2026-11-09-westcol-stream-fighters-vendido

- **Gancho:** Stream Fighters 5: todo vendido · **Tipo:** `frase` · **Puntaje:** 75 · **Duración:** 44,2 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-09-westcol-stream-fighters-vendido/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-09-westcol-stream-fighters-vendido/ficha.md)
- **Fuente:** https://youtu.be/S5v1BWnXdaI?t=9 (WestCOL, minuto 0:09)
- **Oportunidad del Cazador:** `tema-stream-fighters-5`
- **Aprobar:** `/publicador aprobar 2026-11-09-westcol-stream-fighters-vendido`

#### TikTok

Envío: `datos/publicador/envios/2026-11-09-westcol-stream-fighters-vendido__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-09-westcol-stream-fighters-vendido:tiktok`

```text
Westcol: "El que no confía en Stream Fighters no está confiando en lo que la W es capaz de hacer" 🔥

¿Vas a ver Stream Fighters 5?

Crédito: canal WestCOL, «Stream Fighters 5 va a ser HISTÓRICO (Mis expectativas) | WESTCOL». Momento original desde el minuto 0:09: https://youtu.be/S5v1BWnXdaI?t=9

#StreamFighters5 #Westcol #LaW #Kick
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-09-westcol-stream-fighters-vendido__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-09-westcol-stream-fighters-vendido:instagram`

```text
Westcol: "Gracias a Dios todo está vendido" 🔥

A una semana del evento (y con "unas que otras entradas" todavía), dice que Stream Fighters 5 se llenará más y más rápido que el año pasado, y les responde a quienes lo critican.

¿Vas a ver Stream Fighters 5?

Crédito: canal WestCOL, «Stream Fighters 5 va a ser HISTÓRICO (Mis expectativas) | WESTCOL». Momento original desde el minuto 0:09: https://youtu.be/S5v1BWnXdaI?t=9

#StreamFighters5 #Westcol #LaW #Kick
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-09-westcol-stream-fighters-vendido__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-09-westcol-stream-fighters-vendido:youtube`

**Título:** Westcol responde a los que critican Stream Fighters 5

**Descripción:**

```text
A una semana del evento, Westcol dice que Stream Fighters 5 está vendido ("quedan unas que otras entradas") y responde a sus críticos: "El que no confía en Stream Fighters no está confiando en lo que la W es capaz de hacer".

¿Vas a ver Stream Fighters 5?

Crédito: canal WestCOL, «Stream Fighters 5 va a ser HISTÓRICO (Mis expectativas) | WESTCOL». Momento original desde el minuto 0:09: https://youtu.be/S5v1BWnXdaI?t=9

#StreamFighters5 #Westcol #LaW #Kick
```

**Etiquetas:** Stream Fighters 5, Westcol, la W, Kick, evento, Colombia

### 39. 2026-11-09-samulx-energia-latina

- **Gancho:** Samulx, tras su tour por Medellín · **Tipo:** `emotivo` · **Puntaje:** 74 · **Duración:** 37,6 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-09-samulx-energia-latina/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-09-samulx-energia-latina/ficha.md)
- **Fuente:** https://youtu.be/O5LzrzMAbXM?t=5636 (WestCOL, minuto 1:33:56)
- **Aprobar:** `/publicador aprobar 2026-11-09-samulx-energia-latina`

#### TikTok

Envío: `datos/publicador/envios/2026-11-09-samulx-energia-latina__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-09-samulx-energia-latina:tiktok`

```text
Samulx después de recorrer Medellín con Westcol: "Quería sentir otra vez esta energía de Latinoamérica" 🇨🇴

¿Qué lugar de Medellín le falta conocer a Samulx?

Crédito: canal WestCOL, «ENTRAMOS a los barrios más PELIGROSOS de Medellín con SAMULX | WESTCOL». Momento original desde el minuto 1:33:56: https://youtu.be/O5LzrzMAbXM?t=5636

#Samulx #Westcol #Medellín #Colombia #IRL
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-09-samulx-energia-latina__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-09-samulx-energia-latina:instagram`

```text
Lo que sintió Samulx en su primer tour por Medellín con Westcol 🇨🇴

"Quería sentir otra vez esta energía de Latinoamérica, de la cultura latina. Eso se perdió allá". Y quedan en volver al barrio "de verdad".

¿Qué lugar de Medellín le falta conocer a Samulx?

Crédito: canal WestCOL, «ENTRAMOS a los barrios más PELIGROSOS de Medellín con SAMULX | WESTCOL». Momento original desde el minuto 1:33:56: https://youtu.be/O5LzrzMAbXM?t=5636

#Samulx #Westcol #Medellín #Colombia #IRL
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-09-samulx-energia-latina__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-09-samulx-energia-latina:youtube`

**Título:** Samulx tras su tour por Medellín: "Eso se perdió allá"

**Descripción:**

```text
Westcol le pregunta a Samulx qué le pareció el recorrido: "Quería sentir otra vez esta energía de Latinoamérica, de la cultura latina. Eso se perdió allá".

¿Qué lugar de Medellín le falta conocer a Samulx?

Crédito: canal WestCOL, «ENTRAMOS a los barrios más PELIGROSOS de Medellín con SAMULX | WESTCOL». Momento original desde el minuto 1:33:56: https://youtu.be/O5LzrzMAbXM?t=5636

#Samulx #Westcol #Medellín #Colombia
```

**Etiquetas:** Samulx, Westcol, Medellín, Colombia, IRL, Latinoamérica

### 40. 2026-11-09-westcol-plaza-3-am

- **Gancho:** El primer trabajo de Westcol en Medellín · **Tipo:** `historia` · **Puntaje:** 74 · **Duración:** 43,7 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-09-westcol-plaza-3-am/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-09-westcol-plaza-3-am/ficha.md)
- **Fuente:** https://youtu.be/O5LzrzMAbXM?t=4116 (WestCOL, minuto 1:08:36)
- **Aprobar:** `/publicador aprobar 2026-11-09-westcol-plaza-3-am`

#### TikTok

Envío: `datos/publicador/envios/2026-11-09-westcol-plaza-3-am__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-09-westcol-plaza-3-am:tiktok`

```text
Westcol se iba a las 3 de la mañana a alzar bultos en la plaza 🍉

¿Cuál fue tu primer trabajo?

Crédito: canal WestCOL, «ENTRAMOS a los barrios más PELIGROSOS de Medellín con SAMULX | WESTCOL». Momento original desde el minuto 1:08:36: https://youtu.be/O5LzrzMAbXM?t=4116

#Westcol #Samulx #Medellín #IRL #Kick
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-09-westcol-plaza-3-am__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-09-westcol-plaza-3-am:instagram`

```text
Antes de los millones: el trabajo de Westcol en la plaza de Medellín 🍉

Pasando por la plaza mayorista, le cuenta a Samulx que trabajó ahí alzando bultos y en un puesto de frutas: "me iba a las 3 de la mañana… ese era mi trabajo".

¿Cuál fue tu primer trabajo?

Crédito: canal WestCOL, «ENTRAMOS a los barrios más PELIGROSOS de Medellín con SAMULX | WESTCOL». Momento original desde el minuto 1:08:36: https://youtu.be/O5LzrzMAbXM?t=4116

#Westcol #Samulx #Medellín #IRL #Kick
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-09-westcol-plaza-3-am__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-09-westcol-plaza-3-am:youtube`

**Título:** Westcol le muestra a Samulx dónde trabajaba de joven

**Descripción:**

```text
En la plaza mayorista de Medellín, Westcol le explica a Samulx qué es "la plaza" y cuenta que trabajó ahí alzando bultos y en un puesto de frutas: "me iba a las 3 de la mañana".

¿Cuál fue tu primer trabajo?

Crédito: canal WestCOL, «ENTRAMOS a los barrios más PELIGROSOS de Medellín con SAMULX | WESTCOL». Momento original desde el minuto 1:08:36: https://youtu.be/O5LzrzMAbXM?t=4116

#Westcol #Samulx #Medellín #IRL
```

**Etiquetas:** Westcol, Samulx, Medellín, plaza mayorista, primer trabajo, IRL

### 41. 2026-11-05-westcol-robot-como-mi-hijo

- **Gancho:** Westcol vistió a su robot · **Tipo:** `humor` · **Puntaje:** 73 · **Duración:** 46,5 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-westcol-robot-como-mi-hijo/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-westcol-robot-como-mi-hijo/ficha.md)
- **Fuente:** https://youtu.be/Xrwm98iaWY8?t=2010 (WestCOL, minuto 33:30)
- **Oportunidad del Cazador:** `formato-robot-humanoide-en-la-calle`
- **Aprobar:** `/publicador aprobar 2026-11-05-westcol-robot-como-mi-hijo`

#### TikTok

Envío: `datos/publicador/envios/2026-11-05-westcol-robot-como-mi-hijo__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-05-westcol-robot-como-mi-hijo:tiktok`

```text
Westcol vistió a su robot y ahora dice que es como su hijo 🤖

¿Le queda bien la ropa al robot?

Crédito: canal WestCOL, «SAQUE A LA CALLE POR PRIMERA VEZ A MI ROBOT DE $100.000 | WESTCOL». Momento original desde el minuto 33:30: https://youtu.be/Xrwm98iaWY8?t=2010

#Westcol #Robot #StreamFighters5 #Humor #Kick
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-05-westcol-robot-como-mi-hijo__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-05-westcol-robot-como-mi-hijo:instagram`

```text
"Es como mi hijo, papi": Westcol y su robot vestido 🤖

Vistieron al robot para que "se parezca lo más posible a un humano" y Westcol no se aguanta: "me siento orgulloso de mi hijo".

¿Le queda bien la ropa al robot?

Crédito: canal WestCOL, «SAQUE A LA CALLE POR PRIMERA VEZ A MI ROBOT DE $100.000 | WESTCOL». Momento original desde el minuto 33:30: https://youtu.be/Xrwm98iaWY8?t=2010

#Westcol #Robot #StreamFighters5 #Humor #Kick
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-05-westcol-robot-como-mi-hijo__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-05-westcol-robot-como-mi-hijo:youtube`

**Título:** Así quedó el robot de Westcol después de vestirlo

**Descripción:**

```text
Vistieron al robot de Westcol para que "se parezca lo más posible a un humano". Su reacción: "Es como mi hijo… me siento orgulloso de mi hijo".

¿Le queda bien la ropa al robot?

Crédito: canal WestCOL, «SAQUE A LA CALLE POR PRIMERA VEZ A MI ROBOT DE $100.000 | WESTCOL». Momento original desde el minuto 33:30: https://youtu.be/Xrwm98iaWY8?t=2010

#Westcol #Robot #StreamFighters5 #Humor
```

**Etiquetas:** Westcol, robot, Stream Fighters 5, humor, Kick, robot humanoide

### 42. 2026-11-09-westcol-restaurante-infinito

- **Gancho:** ¿Un restaurante gratis para la gente de la calle? · **Tipo:** `revelacion` · **Puntaje:** 72 · **Duración:** 54,6 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-09-westcol-restaurante-infinito/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-09-westcol-restaurante-infinito/ficha.md)
- **Fuente:** https://youtu.be/O5LzrzMAbXM?t=1594 (WestCOL, minuto 26:34)
- **Aprobar:** `/publicador aprobar 2026-11-09-westcol-restaurante-infinito`

#### TikTok

Envío: `datos/publicador/envios/2026-11-09-westcol-restaurante-infinito__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-09-westcol-restaurante-infinito:tiktok`

```text
¿Un "restaurante infinito" con comida gratis para la gente de la calle? 🍽️ La idea que sale en el IRL de Westcol con Samulx

¿Debería hacerse?

Crédito: canal WestCOL, «ENTRAMOS a los barrios más PELIGROSOS de Medellín con SAMULX | WESTCOL». Momento original desde el minuto 26:34: https://youtu.be/O5LzrzMAbXM?t=1594

#Westcol #Samulx #Medellín #Envigado #IRL
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-09-westcol-restaurante-infinito__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-09-westcol-restaurante-infinito:instagram`

```text
"Con 20 millones de pesos al mes, uno alimenta esa gente" 🍽️

Recorriendo Envigado, en el IRL de Westcol con Samulx se plantea montar un "restaurante infinito" con almuerzo, comida y cena. Samulx cuenta que en Estados Unidos, cuando trabajaba en un restaurante, tenían que botar la comida por miedo a demandas.

¿Debería hacerse?

Crédito: canal WestCOL, «ENTRAMOS a los barrios más PELIGROSOS de Medellín con SAMULX | WESTCOL». Momento original desde el minuto 26:34: https://youtu.be/O5LzrzMAbXM?t=1594

#Westcol #Samulx #Medellín #Envigado #IRL
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-09-westcol-restaurante-infinito__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-09-westcol-restaurante-infinito:youtube`

**Título:** ¿Por qué en Estados Unidos botan la comida? Samulx responde

**Descripción:**

```text
Recorriendo Envigado sale la idea de un "restaurante infinito" para los habitantes de calle (es un deseo, no un anuncio). Samulx cuenta que en Estados Unidos, en el restaurante donde trabajaba, botaban la comida por miedo a demandas.

¿Debería hacerse?

Crédito: canal WestCOL, «ENTRAMOS a los barrios más PELIGROSOS de Medellín con SAMULX | WESTCOL». Momento original desde el minuto 26:34: https://youtu.be/O5LzrzMAbXM?t=1594

#Westcol #Samulx #Medellín #Envigado
```

**Etiquetas:** Westcol, Samulx, Envigado, Medellín, restaurante, habitantes de calle

### 43. 2026-11-05-westcol-robot-salto

- **Gancho:** A ver si el robot rompe el techo · **Tipo:** `reaccion` · **Puntaje:** 72 · **Duración:** 41,7 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-westcol-robot-salto/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-westcol-robot-salto/ficha.md)
- **Fuente:** https://youtu.be/Xrwm98iaWY8?t=2376 (WestCOL, minuto 39:36)
- **Oportunidad del Cazador:** `formato-robot-humanoide-en-la-calle`
- **Aprobar:** `/publicador aprobar 2026-11-05-westcol-robot-salto`

#### TikTok

Envío: `datos/publicador/envios/2026-11-05-westcol-robot-salto__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-05-westcol-robot-salto:tiktok`

```text
El robot de Westcol salta dentro de una tienda (y lo aplauden) 🤖

¿Lo dejarías entrar a tu tienda?

Crédito: canal WestCOL, «SAQUE A LA CALLE POR PRIMERA VEZ A MI ROBOT DE $100.000 | WESTCOL». Momento original desde el minuto 39:36: https://youtu.be/Xrwm98iaWY8?t=2376

#Westcol #Robot #StreamFighters5 #Kick
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-05-westcol-robot-salto__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-05-westcol-robot-salto:instagram`

```text
"A ver si ese sí rompe el techo" 🤖

Westcol le pide a su robot "otro saltico más alto". Lo aplauden, y él mismo concluye: "esto aquí está muy peligroso, la verdad".

¿Lo dejarías entrar a tu tienda?

Crédito: canal WestCOL, «SAQUE A LA CALLE POR PRIMERA VEZ A MI ROBOT DE $100.000 | WESTCOL». Momento original desde el minuto 39:36: https://youtu.be/Xrwm98iaWY8?t=2376

#Westcol #Robot #StreamFighters5 #Kick
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-05-westcol-robot-salto__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-05-westcol-robot-salto:youtube`

**Título:** El salto del robot de Westcol antes de Stream Fighters 5

**Descripción:**

```text
Westcol le pide al robot "otro saltico más alto, a ver si ese sí rompe el techo". Su conclusión: "esto aquí está muy peligroso, la verdad".

¿Lo dejarías entrar a tu tienda?

Crédito: canal WestCOL, «SAQUE A LA CALLE POR PRIMERA VEZ A MI ROBOT DE $100.000 | WESTCOL». Momento original desde el minuto 39:36: https://youtu.be/Xrwm98iaWY8?t=2376

#Westcol #Robot #StreamFighters5 #Kick
```

**Etiquetas:** Westcol, robot, salto, Stream Fighters 5, Kick, robot humanoide

### 44. 2026-11-02-toxico-verso-mando-la-ubi

- **Gancho:** POV: tu novio es tóxico · **Tipo:** `frase` · **Puntaje:** 72 · **Duración:** 31,4 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `autorizado`.
- **Video:** [clip.mp4](../clipero/clips/2026-11-02-toxico-verso-mando-la-ubi/clip.mp4) (no está en esta copia) · **Ficha:** [ficha.md](../clipero/clips/2026-11-02-toxico-verso-mando-la-ubi/ficha.md)
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

### 45. 2026-11-05-westcol-robot-tienda

- **Gancho:** ¿Puede entrar un robot a una tienda? · **Tipo:** `humor` · **Puntaje:** 72 · **Duración:** 56,8 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-westcol-robot-tienda/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-westcol-robot-tienda/ficha.md)
- **Fuente:** https://youtu.be/Xrwm98iaWY8?t=1198 (WestCOL, minuto 19:58)
- **Oportunidad del Cazador:** `formato-robot-humanoide-en-la-calle`
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

### 46. 2026-11-05-westcol-robot-boxeo

- **Gancho:** ¿Quién boxea mejor: el robot o él? · **Tipo:** `humor` · **Puntaje:** 72 · **Duración:** 63,9 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-westcol-robot-boxeo/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-westcol-robot-boxeo/ficha.md)
- **Fuente:** https://youtu.be/Xrwm98iaWY8?t=457 (WestCOL, minuto 7:37)
- **Oportunidad del Cazador:** `tema-stream-fighters-5`
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

### 47. 2026-11-09-westcol-pony-de-uribe

- **Gancho:** Westcol: 'Álvaro Uribe me regaló un pony' · **Tipo:** `humor` · **Puntaje:** 71 · **Duración:** 45,2 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-09-westcol-pony-de-uribe/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-09-westcol-pony-de-uribe/ficha.md)
- **Fuente:** https://youtu.be/O5LzrzMAbXM?t=553 (WestCOL, minuto 9:13)
- **Aprobar:** `/publicador aprobar 2026-11-09-westcol-pony-de-uribe`

#### TikTok

Envío: `datos/publicador/envios/2026-11-09-westcol-pony-de-uribe__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-09-westcol-pony-de-uribe:tiktok`

```text
Una cabra casi se come la perla de Westcol… y luego suelta lo del pony de Uribe 🐐

¿Le crees lo del pony?

Crédito: canal WestCOL, «ENTRAMOS a los barrios más PELIGROSOS de Medellín con SAMULX | WESTCOL». Momento original desde el minuto 9:13: https://youtu.be/O5LzrzMAbXM?t=553

#Westcol #Samulx #Majalo #Humor #IRL
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-09-westcol-pony-de-uribe__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-09-westcol-pony-de-uribe:instagram`

```text
"Voy a traer para acá el pony que me regaló Álvaro Uribe" 🐐

En el establo de Majalo, una cabra se quiere comer "la perlita cara" de Westcol, y él suelta lo del pony.

¿Le crees lo del pony?

Crédito: canal WestCOL, «ENTRAMOS a los barrios más PELIGROSOS de Medellín con SAMULX | WESTCOL». Momento original desde el minuto 9:13: https://youtu.be/O5LzrzMAbXM?t=553

#Westcol #Samulx #Majalo #Humor #IRL
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-09-westcol-pony-de-uribe__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-09-westcol-pony-de-uribe:youtube`

**Título:** Westcol, las cabras de Majalo y "el pony que me regaló Álvaro Uribe"

**Descripción:**

```text
En el establo de Majalo, una cabra intenta comerse la perla del arete de Westcol, que suelta: "voy a traer para acá el pony que me regaló Álvaro Uribe". Es lo que él dice; no está verificado.

¿Le crees lo del pony?

Crédito: canal WestCOL, «ENTRAMOS a los barrios más PELIGROSOS de Medellín con SAMULX | WESTCOL». Momento original desde el minuto 9:13: https://youtu.be/O5LzrzMAbXM?t=553

#Westcol #Samulx #Majalo #Humor
```

**Etiquetas:** Westcol, Majalo, Samulx, cabras, pony, humor

### 48. 2026-11-09-westcol-calatrava-llegaba-tarde

- **Gancho:** Por qué Westcol llegaba tarde a jugar · **Tipo:** `historia` · **Puntaje:** 70 · **Duración:** 49,2 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-09-westcol-calatrava-llegaba-tarde/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-09-westcol-calatrava-llegaba-tarde/ficha.md)
- **Fuente:** https://youtu.be/O5LzrzMAbXM?t=2287 (WestCOL, minuto 38:07)
- **Aprobar:** `/publicador aprobar 2026-11-09-westcol-calatrava-llegaba-tarde`

#### TikTok

Envío: `datos/publicador/envios/2026-11-09-westcol-calatrava-llegaba-tarde__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-09-westcol-calatrava-llegaba-tarde:tiktok`

```text
Samulx descubre por qué Westcol siempre llegaba tarde a jugar Counter 😂

¿Cuánto caminabas para llegar a estudiar?

Crédito: canal WestCOL, «ENTRAMOS a los barrios más PELIGROSOS de Medellín con SAMULX | WESTCOL». Momento original desde el minuto 38:07: https://youtu.be/O5LzrzMAbXM?t=2287

#Westcol #Samulx #Calatrava #Itagüí #Medellín
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-09-westcol-calatrava-llegaba-tarde__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-09-westcol-calatrava-llegaba-tarde:instagram`

```text
Dos horas subiendo a pie: el camino diario de Westcol en Calatrava

Salía a estudiar a las 6 y llegaba a las 8: "me demoraba dos horitas subiendo". Samulx: "Con razón cuando llegaba para jugar Counter llegaba tarde".

¿Cuánto caminabas para llegar a estudiar?

Crédito: canal WestCOL, «ENTRAMOS a los barrios más PELIGROSOS de Medellín con SAMULX | WESTCOL». Momento original desde el minuto 38:07: https://youtu.be/O5LzrzMAbXM?t=2287

#Westcol #Samulx #Calatrava #Itagüí #Medellín
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-09-westcol-calatrava-llegaba-tarde__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-09-westcol-calatrava-llegaba-tarde:youtube`

**Título:** Westcol le muestra a Samulx el camino que subía a pie de joven

**Descripción:**

```text
En Calatrava, Westcol le enseña a Samulx el camino que hacía a pie todos los días: "me demoraba dos horitas subiendo". Samulx: "Con razón cuando llegaba para jugar Counter llegaba tarde".

¿Cuánto caminabas para llegar a estudiar?

Crédito: canal WestCOL, «ENTRAMOS a los barrios más PELIGROSOS de Medellín con SAMULX | WESTCOL». Momento original desde el minuto 38:07: https://youtu.be/O5LzrzMAbXM?t=2287

#Westcol #Samulx #Calatrava #Itagüí
```

**Etiquetas:** Westcol, Samulx, Calatrava, Itagüí, Medellín, Counter

### 49. 2026-11-09-westcol-produccion-win-sports

- **Gancho:** Stream Fighters 5: producción de Win Sports · **Tipo:** `revelacion` · **Puntaje:** 70 · **Duración:** 27,2 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-09-westcol-produccion-win-sports/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-09-westcol-produccion-win-sports/ficha.md)
- **Fuente:** https://youtu.be/S5v1BWnXdaI?t=100 (WestCOL, minuto 1:40)
- **Oportunidad del Cazador:** `tema-stream-fighters-5`
- **Aprobar:** `/publicador aprobar 2026-11-09-westcol-produccion-win-sports`

#### TikTok

Envío: `datos/publicador/envios/2026-11-09-westcol-produccion-win-sports__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-09-westcol-produccion-win-sports:tiktok`

```text
Westcol dice que Stream Fighters 5 tendrá la producción de Win Sports 🎥

¿Qué le cambiarías al evento del año pasado?

Crédito: canal WestCOL, «Stream Fighters 5 va a ser HISTÓRICO (Mis expectativas) | WESTCOL». Momento original desde el minuto 1:40: https://youtu.be/S5v1BWnXdaI?t=100

#StreamFighters5 #Westcol #WinSports #Kick
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-09-westcol-produccion-win-sports__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-09-westcol-produccion-win-sports:instagram`

```text
"La producción de Win Sports": así dice Westcol que se arma Stream Fighters 5 🎥

Un equipo que llega a las 4 de la mañana y que "puede ser tranquilamente de 500 personas".

¿Qué le cambiarías al evento del año pasado?

Crédito: canal WestCOL, «Stream Fighters 5 va a ser HISTÓRICO (Mis expectativas) | WESTCOL». Momento original desde el minuto 1:40: https://youtu.be/S5v1BWnXdaI?t=100

#StreamFighters5 #Westcol #WinSports #Kick
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-09-westcol-produccion-win-sports__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-09-westcol-produccion-win-sports:youtube`

**Título:** Westcol revela quién produce Stream Fighters 5

**Descripción:**

```text
Westcol cuenta que este año la producción de Stream Fighters es "la producción de Win Sports", con un equipo que "puede ser tranquilamente de 500 personas". Son datos que da él; no están verificados.

¿Qué le cambiarías al evento del año pasado?

Crédito: canal WestCOL, «Stream Fighters 5 va a ser HISTÓRICO (Mis expectativas) | WESTCOL». Momento original desde el minuto 1:40: https://youtu.be/S5v1BWnXdaI?t=100

#StreamFighters5 #Westcol #WinSports #Kick
```

**Etiquetas:** Stream Fighters 5, Westcol, Win Sports, producción, Kick, Colombia

### 50. 2026-11-02-toxico-intro-celos-aire

- **Gancho:** Lalo Ocampo estrena «Tóxico» · **Tipo:** `frase` · **Puntaje:** 68 · **Duración:** 19,6 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `autorizado`.
- **Video:** [clip.mp4](../clipero/clips/2026-11-02-toxico-intro-celos-aire/clip.mp4) (no está en esta copia) · **Ficha:** [ficha.md](../clipero/clips/2026-11-02-toxico-intro-celos-aire/ficha.md)
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

### 51. 2026-11-09-westcol-primer-stream-y-mustang

- **Gancho:** Aquí hizo su primer stream con Arcángel · **Tipo:** `revelacion` · **Puntaje:** 68 · **Duración:** 30,5 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-09-westcol-primer-stream-y-mustang/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-09-westcol-primer-stream-y-mustang/ficha.md)
- **Fuente:** https://youtu.be/O5LzrzMAbXM?t=4182 (WestCOL, minuto 1:09:42)
- **Aprobar:** `/publicador aprobar 2026-11-09-westcol-primer-stream-y-mustang`

#### TikTok

Envío: `datos/publicador/envios/2026-11-09-westcol-primer-stream-y-mustang__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-09-westcol-primer-stream-y-mustang:tiktok`

```text
Dónde hizo Westcol su primer stream con Arcángel (y cuál fue su primer carro) 🏎️

¿Cuál fue tu primer carro?

Crédito: canal WestCOL, «ENTRAMOS a los barrios más PELIGROSOS de Medellín con SAMULX | WESTCOL». Momento original desde el minuto 1:09:42: https://youtu.be/O5LzrzMAbXM?t=4182

#Westcol #Samulx #Arcángel #Medellín #IRL
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-09-westcol-primer-stream-y-mustang__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-09-westcol-primer-stream-y-mustang:instagram`

```text
De andar en bus al Mustang 🚌➡️🏎️

Pasando por el barrio donde vivió, Westcol le señala a Samulx la casa del primer stream que hizo con Arcángel. ¿Su primer carro? "El Mustang". ¿Y antes? "Bus, puro bus".

¿Cuál fue tu primer carro?

Crédito: canal WestCOL, «ENTRAMOS a los barrios más PELIGROSOS de Medellín con SAMULX | WESTCOL». Momento original desde el minuto 1:09:42: https://youtu.be/O5LzrzMAbXM?t=4182

#Westcol #Samulx #Arcángel #Medellín #IRL
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-09-westcol-primer-stream-y-mustang__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-09-westcol-primer-stream-y-mustang:youtube`

**Título:** Westcol: "el primer stream que hice con Arcángel fue aquí"

**Descripción:**

```text
Westcol le muestra a Samulx dónde hizo su primer stream con Arcángel y cuenta cuál fue su primer carro: "El Mustang". ¿Y antes? "Bus, puro bus".

¿Cuál fue tu primer carro?

Crédito: canal WestCOL, «ENTRAMOS a los barrios más PELIGROSOS de Medellín con SAMULX | WESTCOL». Momento original desde el minuto 1:09:42: https://youtu.be/O5LzrzMAbXM?t=4182

#Westcol #Samulx #Arcángel #Medellín
```

**Etiquetas:** Westcol, Samulx, Arcángel, Mustang, Medellín, primer stream

### 52. 2026-11-09-westcol-confianza-en-medellin

- **Gancho:** Samulx quería escoltas. Westcol dijo que no · **Tipo:** `frase` · **Puntaje:** 68 · **Duración:** 28,5 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-09-westcol-confianza-en-medellin/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-09-westcol-confianza-en-medellin/ficha.md)
- **Fuente:** https://youtu.be/O5LzrzMAbXM?t=44 (WestCOL, minuto 0:44)
- **Aprobar:** `/publicador aprobar 2026-11-09-westcol-confianza-en-medellin`

#### TikTok

Envío: `datos/publicador/envios/2026-11-09-westcol-confianza-en-medellin__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-09-westcol-confianza-en-medellin:tiktok`

```text
Westcol a Samulx: "Yo quiero que usted le tenga confianza a Medellín" 🇨🇴

¿Tú confiarías?

Crédito: canal WestCOL, «ENTRAMOS a los barrios más PELIGROSOS de Medellín con SAMULX | WESTCOL». Momento original desde el minuto 0:44: https://youtu.be/O5LzrzMAbXM?t=44

#Westcol #Samulx #Medellín #IRL #Kick
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-09-westcol-confianza-en-medellin__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-09-westcol-confianza-en-medellin:instagram`

```text
Samulx dudaba por la seguridad. Westcol: "Eso no va a pasar" 🇨🇴

"Yo quiero que usted le tenga confianza a Medellín… yo ando todos los días así, tranquilo". Samulx: "Voy a confiar en ti".

¿Tú confiarías?

Crédito: canal WestCOL, «ENTRAMOS a los barrios más PELIGROSOS de Medellín con SAMULX | WESTCOL». Momento original desde el minuto 0:44: https://youtu.be/O5LzrzMAbXM?t=44

#Westcol #Samulx #Medellín #IRL #Kick
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-09-westcol-confianza-en-medellin__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-09-westcol-confianza-en-medellin:youtube`

**Título:** Westcol convence a Samulx de confiar en Medellín

**Descripción:**

```text
Antes de salir, Samulx duda por la seguridad. Westcol: "Yo quiero que usted le tenga confianza a Medellín… yo ando todos los días así, tranquilo". Samulx: "Voy a confiar en ti".

¿Tú confiarías?

Crédito: canal WestCOL, «ENTRAMOS a los barrios más PELIGROSOS de Medellín con SAMULX | WESTCOL». Momento original desde el minuto 0:44: https://youtu.be/O5LzrzMAbXM?t=44

#Westcol #Samulx #Medellín #IRL
```

**Etiquetas:** Westcol, Samulx, Medellín, seguridad, IRL, Kick

### 53. 2026-11-09-westcol-no-tentar-al-ladron

- **Gancho:** Westcol: 'no es justificar al ladrón, pero…' · **Tipo:** `consejo` · **Puntaje:** 67 · **Duración:** 24,3 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-09-westcol-no-tentar-al-ladron/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-09-westcol-no-tentar-al-ladron/ficha.md)
- **Fuente:** https://youtu.be/O5LzrzMAbXM?t=1987 (WestCOL, minuto 33:07)
- **Aprobar:** `/publicador aprobar 2026-11-09-westcol-no-tentar-al-ladron`

#### TikTok

Envío: `datos/publicador/envios/2026-11-09-westcol-no-tentar-al-ladron__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-09-westcol-no-tentar-al-ladron:tiktok`

```text
Westcol: "No es justificar al ladrón, pero tampoco tentarlo"

¿Estás de acuerdo?

Crédito: canal WestCOL, «ENTRAMOS a los barrios más PELIGROSOS de Medellín con SAMULX | WESTCOL». Momento original desde el minuto 33:07: https://youtu.be/O5LzrzMAbXM?t=1987

#Westcol #Medellín #Consejo #IRL
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-09-westcol-no-tentar-al-ladron__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-09-westcol-no-tentar-al-ladron:instagram`

```text
El consejo de Westcol para andar por Medellín

"Usted no puede jugar con la necesidad de la gente. No es justificar al ladrón, pero tampoco tentarlo".

¿Estás de acuerdo?

Crédito: canal WestCOL, «ENTRAMOS a los barrios más PELIGROSOS de Medellín con SAMULX | WESTCOL». Momento original desde el minuto 33:07: https://youtu.be/O5LzrzMAbXM?t=1987

#Westcol #Medellín #Consejo #IRL
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-09-westcol-no-tentar-al-ladron__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-09-westcol-no-tentar-al-ladron:youtube`

**Título:** Westcol: "usted no puede jugar con la necesidad de la gente"

**Descripción:**

```text
Recorriendo Medellín, Westcol da su consejo: "Yo me vengo por acá y parcho tranquilo… pero usted no puede jugar con la necesidad de la gente. No es justificar al ladrón, pero tampoco tentarlo".

¿Estás de acuerdo?

Crédito: canal WestCOL, «ENTRAMOS a los barrios más PELIGROSOS de Medellín con SAMULX | WESTCOL». Momento original desde el minuto 33:07: https://youtu.be/O5LzrzMAbXM?t=1987

#Westcol #Medellín #Consejo #IRL
```

**Etiquetas:** Westcol, Medellín, consejo, seguridad, IRL, Samulx

### 54. 2026-11-09-westcol-por-que-uso-reloj

- **Gancho:** ¿Por qué Westcol usa relojes caros? · **Tipo:** `frase` · **Puntaje:** 74 · **Duración:** 38,4 s · **Ventana hasta:** 2026-11-15
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-09-westcol-por-que-uso-reloj/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-09-westcol-por-que-uso-reloj/ficha.md)
- **Fuente:** https://youtu.be/ybjXHgxGBMo?t=777 (WestCOL, minuto 12:57)
- **Aprobar:** `/publicador aprobar 2026-11-09-westcol-por-que-uso-reloj`

#### TikTok

Envío: `datos/publicador/envios/2026-11-09-westcol-por-que-uso-reloj__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-09-westcol-por-que-uso-reloj:tiktok`

```text
Westcol explica por qué usa relojes caros (y confiesa que tuvo fake) ⌚

¿Reloj caro o reloj fake? Opina.

Crédito: canal WestCOL, «Me GASTÉ $100.000 DÓLARES en un RICHARD MILLE (Valió la pena?) | WESTCOL». Momento original desde el minuto 12:57: https://youtu.be/ybjXHgxGBMo?t=777

#Westcol #Relojes #RichardMille #Lujo #Kick
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-09-westcol-por-que-uso-reloj__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-09-westcol-por-que-uso-reloj:instagram`

```text
Westcol y sus relojes: por qué los usa y los fake que tuvo antes ⌚

"Es como cuando me echo una buena loción… uno sale con más confianza". Cuenta que tuvo relojes falsos cuando los estaba "proyectando" y que ahora no tiene "necesidad de hacer esa película".

¿Reloj caro o reloj fake? Opina.

Crédito: canal WestCOL, «Me GASTÉ $100.000 DÓLARES en un RICHARD MILLE (Valió la pena?) | WESTCOL». Momento original desde el minuto 12:57: https://youtu.be/ybjXHgxGBMo?t=777

#Westcol #Relojes #RichardMille #Lujo #Kick
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-09-westcol-por-que-uso-reloj__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-09-westcol-por-que-uso-reloj:youtube`

**Título:** ¿Por qué Westcol usa relojes de lujo?

**Descripción:**

```text
"Es como cuando me echo una buena loción… uno sale con más confianza". Westcol cuenta por qué usa relojes y que antes tuvo relojes falsos.

¿Reloj caro o reloj fake? Opina.

Crédito: canal WestCOL, «Me GASTÉ $100.000 DÓLARES en un RICHARD MILLE (Valió la pena?) | WESTCOL». Momento original desde el minuto 12:57: https://youtu.be/ybjXHgxGBMo?t=777

#Westcol #Relojes #RichardMille #Lujo
```

**Etiquetas:** Westcol, relojes, Richard Mille, lujo, reloj fake, Kick

### 55. 2026-11-09-westcol-patek-inversion

- **Gancho:** Westcol: los relojes son inversión · **Tipo:** `consejo` · **Puntaje:** 72 · **Duración:** 23,1 s · **Ventana hasta:** 2026-11-15
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-09-westcol-patek-inversion/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-09-westcol-patek-inversion/ficha.md)
- **Fuente:** https://youtu.be/ybjXHgxGBMo?t=362 (WestCOL, minuto 6:02)
- **Aprobar:** `/publicador aprobar 2026-11-09-westcol-patek-inversion`

#### TikTok

Envío: `datos/publicador/envios/2026-11-09-westcol-patek-inversion__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-09-westcol-patek-inversion:tiktok`

```text
Westcol dice que su Patek subió "como 25.000" en un mes ⌚📈

¿Un reloj es inversión o gasto?

Crédito: canal WestCOL, «Me GASTÉ $100.000 DÓLARES en un RICHARD MILLE (Valió la pena?) | WESTCOL». Momento original desde el minuto 6:02: https://youtu.be/ybjXHgxGBMo?t=362

#Westcol #Patek #Relojes #Inversión #Lujo
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-09-westcol-patek-inversion__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-09-westcol-patek-inversion:instagram`

```text
"Eso es inversión": Westcol y su Patek ⌚📈

Cuenta que el Patek que le compró a Alto Rango subió de precio: "como 25.000 le gané… un mesecito después". ¿Venderlo? "No, no, yo no lo vendo".

¿Un reloj es inversión o gasto?

Crédito: canal WestCOL, «Me GASTÉ $100.000 DÓLARES en un RICHARD MILLE (Valió la pena?) | WESTCOL». Momento original desde el minuto 6:02: https://youtu.be/ybjXHgxGBMo?t=362

#Westcol #Patek #Relojes #Inversión #Lujo
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-09-westcol-patek-inversion__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-09-westcol-patek-inversion:youtube`

**Título:** ¿Un reloj de lujo es inversión? Westcol responde

**Descripción:**

```text
Westcol cuenta que el Patek que le compró a Alto Rango subió de precio un mes después ("como 25.000 le gané") y que no lo vende. Cifras que da él; no es un consejo de inversión.

¿Un reloj es inversión o gasto?

Crédito: canal WestCOL, «Me GASTÉ $100.000 DÓLARES en un RICHARD MILLE (Valió la pena?) | WESTCOL». Momento original desde el minuto 6:02: https://youtu.be/ybjXHgxGBMo?t=362

#Westcol #Patek #Relojes #Inversión
```

**Etiquetas:** Westcol, Patek Philippe, relojes, inversión, lujo, Alto Rango

### 56. 2026-11-09-westcol-richard-y-patek-por-carro

- **Gancho:** No le trajeron el carro y compró esto · **Tipo:** `historia` · **Puntaje:** 69 · **Duración:** 32,6 s · **Ventana hasta:** 2026-11-15
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-09-westcol-richard-y-patek-por-carro/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-09-westcol-richard-y-patek-por-carro/ficha.md)
- **Fuente:** https://youtu.be/ybjXHgxGBMo?t=1045 (WestCOL, minuto 17:25)
- **Aprobar:** `/publicador aprobar 2026-11-09-westcol-richard-y-patek-por-carro`

#### TikTok

Envío: `datos/publicador/envios/2026-11-09-westcol-richard-y-patek-por-carro__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-09-westcol-richard-y-patek-por-carro:tiktok`

```text
No le trajeron el carro… y Westcol se compró un Richard y un Patek ⌚

¿Carro o relojes?

Crédito: canal WestCOL, «Me GASTÉ $100.000 DÓLARES en un RICHARD MILLE (Valió la pena?) | WESTCOL». Momento original desde el minuto 17:25: https://youtu.be/ybjXHgxGBMo?t=1045

#Westcol #RichardMille #Patek #Relojes #Lujo
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-09-westcol-richard-y-patek-por-carro__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-09-westcol-richard-y-patek-por-carro:instagram`

```text
Así empezó Westcol con los relojes caros ⌚

El carro que esperaba no llegó: "Lo voy a gastar en un Richard y un Patek… al otro día aparecí con el Richard y el Patek Philippe". Y se prometió no comprar más diamantes.

¿Carro o relojes?

Crédito: canal WestCOL, «Me GASTÉ $100.000 DÓLARES en un RICHARD MILLE (Valió la pena?) | WESTCOL». Momento original desde el minuto 17:25: https://youtu.be/ybjXHgxGBMo?t=1045

#Westcol #RichardMille #Patek #Relojes #Lujo
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-09-westcol-richard-y-patek-por-carro__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-09-westcol-richard-y-patek-por-carro:youtube`

**Título:** Westcol: "al otro día aparecí con el Richard y el Patek"

**Descripción:**

```text
Westcol cuenta que no era de relojes tan caros hasta que el carro que esperaba no llegó: "Lo voy a gastar en un Richard y un Patek".

¿Carro o relojes?

Crédito: canal WestCOL, «Me GASTÉ $100.000 DÓLARES en un RICHARD MILLE (Valió la pena?) | WESTCOL». Momento original desde el minuto 17:25: https://youtu.be/ybjXHgxGBMo?t=1045

#Westcol #RichardMille #Patek #Relojes
```

**Etiquetas:** Westcol, Richard Mille, Patek Philippe, relojes, carros, lujo

### 57. 2026-11-05-parceritos-lokillo-balsamo

- **Gancho:** Lokillo, el día que perdió a su abuelo · **Tipo:** `emotivo` · **Puntaje:** 67 · **Duración:** 30,2 s · **Ventana hasta:** 2026-11-16
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-parceritos-lokillo-balsamo/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-parceritos-lokillo-balsamo/ficha.md)
- **Fuente:** https://youtu.be/o1uyVvIu4xc?t=2295 (Los Parceritos, minuto 38:15)
- **Aprobar:** `/publicador aprobar 2026-11-05-parceritos-lokillo-balsamo`

#### TikTok

Envío: `datos/publicador/envios/2026-11-05-parceritos-lokillo-balsamo__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-05-parceritos-lokillo-balsamo:tiktok`

```text
Lokillo, sobre salir al escenario el día que perdió a su abuelo

¿Cuál es tu bálsamo?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 15: EL CHISPUS». Momento original desde el minuto 38:15: https://youtu.be/o1uyVvIu4xc?t=2295

#Lokillo #LosParceritos #StandUp #Comedia #Colombia
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-05-parceritos-lokillo-balsamo__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-05-parceritos-lokillo-balsamo:instagram`

```text
"Fue como un bálsamo": Lokillo sobre salir al escenario en medio del dolor

"Por estas dos horitas no estoy pensando en eso, sino en hacer reír a la gente".

¿Cuál es tu bálsamo?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 15: EL CHISPUS». Momento original desde el minuto 38:15: https://youtu.be/o1uyVvIu4xc?t=2295

#Lokillo #LosParceritos #StandUp #Comedia #Colombia
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-05-parceritos-lokillo-balsamo__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-05-parceritos-lokillo-balsamo:youtube`

**Título:** Lokillo: "fue como un bálsamo, como un respiro"

**Descripción:**

```text
En Los Parceritos, Lokillo cuenta que el día de lo de su abuelo estuvo muy triste y que salir al escenario "fue como un bálsamo, como un respiro".

¿Cuál es tu bálsamo?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 15: EL CHISPUS». Momento original desde el minuto 38:15: https://youtu.be/o1uyVvIu4xc?t=2295

#Lokillo #LosParceritos #StandUp #Comedia
```

**Etiquetas:** Lokillo, Los Parceritos, stand up, comedia, Erika Zapata, Colombia

### 58. 2026-11-05-parceritos-primer-beso-28

- **Gancho:** Su primer beso fue a los 28 · **Tipo:** `historia` · **Puntaje:** 67 · **Duración:** 72,2 s · **Ventana hasta:** 2026-11-16
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-parceritos-primer-beso-28/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-parceritos-primer-beso-28/ficha.md)
- **Fuente:** https://youtu.be/o1uyVvIu4xc?t=258 (Los Parceritos, minuto 4:18)
- **Aprobar:** `/publicador aprobar 2026-11-05-parceritos-primer-beso-28`

#### TikTok

Envío: `datos/publicador/envios/2026-11-05-parceritos-primer-beso-28__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-05-parceritos-primer-beso-28:tiktok`

```text
Erika Zapata dio su primer beso a los 28… y aprendió con tutoriales de YouTube 😂

¿A qué edad diste tu primer beso?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 15: EL CHISPUS». Momento original desde el minuto 4:18: https://youtu.be/o1uyVvIu4xc?t=258

#LosParceritos #Lokillo #ErikaZapata #Humor #Colombia
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-05-parceritos-primer-beso-28__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-05-parceritos-primer-beso-28:instagram`

```text
"Tutoriales de YouTube": el primer beso de Erika Zapata en Los Parceritos 😂

No dio su primer beso hasta los 28: se puso un plazo hasta la Feria de las Flores para conseguir novio, buscó tutoriales… y la dejaron después.

¿A qué edad diste tu primer beso?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 15: EL CHISPUS». Momento original desde el minuto 4:18: https://youtu.be/o1uyVvIu4xc?t=258

#LosParceritos #Lokillo #ErikaZapata #Humor #Colombia
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-05-parceritos-primer-beso-28__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-05-parceritos-primer-beso-28:youtube`

**Título:** Erika Zapata: "hasta los 28 años nunca había dado mi primer beso"

**Descripción:**

```text
Erika Zapata cuenta en Los Parceritos que no dio su primer beso hasta los 28, que se puso un plazo hasta la Feria de las Flores para conseguir novio y que buscó "tutoriales de YouTube".

¿A qué edad diste tu primer beso?

Crédito: canal Los Parceritos, «LOS PARCERITOS - CAP. 15: EL CHISPUS». Momento original desde el minuto 4:18: https://youtu.be/o1uyVvIu4xc?t=258

#LosParceritos #Lokillo #ErikaZapata #Humor
```

**Etiquetas:** Los Parceritos, Erika Zapata, Lokillo, primer beso, humor, Colombia

### 59. 2026-11-04-parceritos-decimas-abuelo

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

### 60. 2026-11-04-parceritos-filosofo-o-reggaetonero

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

### 61. 2026-11-04-parceritos-poeta-corre-feo

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

### 62. 2026-11-04-parceritos-billete-diomedes

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

### 63. 2026-11-04-parceritos-flor-abeja

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

### 64. 2026-11-04-parceritos-billete-popo

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

### 65. 2026-11-04-parceritos-borracho-ensayo

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

### 66. 2026-11-04-parceritos-profesor-sobra

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

### 67. 2026-11-04-parceritos-novela-mas-corta

- **Gancho:** La novela más corta del mundo · **Tipo:** `humor` · **Puntaje:** 70 · **Duración:** 31 s · **Ventana hasta:** 2026-11-19
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

### 68. 2026-11-04-parceritos-el-paseo

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

### 69. 2026-11-04-parceritos-poesia-protesta

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

### 70. 2026-11-04-parceritos-vomitar-premios

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

### 71. 2026-11-04-parceritos-poema-cuarto-oscuro

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

### 72. 2026-11-04-parceritos-fracaso-objetividad

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

### 73. 2026-11-06-kris-r-musica-cambia-vida

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

### 74. 2026-11-01-kris-r-musica-cada-semana

- **Gancho:**  · **Tipo:** `` · **Puntaje:** 72 · **Duración:**  s · **Ventana hasta:** 2026-11-20
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-01-kris-r-musica-cada-semana/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-01-kris-r-musica-cada-semana/ficha.md)
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

### 75. 2026-11-01-kris-r-primer-estadio

- **Gancho:**  · **Tipo:** `` · **Puntaje:** 71 · **Duración:**  s · **Ventana hasta:** 2026-11-20
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-01-kris-r-primer-estadio/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-01-kris-r-primer-estadio/ficha.md)
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
- Aprobar una sola plataforma: `/publicador aprobar <clip-id>:<plataforma>` (por ejemplo, `/publicador aprobar 2026-11-05-westcol-batisenal-w:tiktok`)
- Aprobar todo lo pendiente: `/publicador aprobar todo`
- Rechazar: `/publicador rechazar <clip-id> <motivo>`
- Cambiar un texto: por ejemplo, `/publicador cambia el título de YouTube de <clip-id> por ...`
