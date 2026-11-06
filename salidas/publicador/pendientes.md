# Pendientes de aprobación del Publicador

Actualizado: 2026-11-06 00:40 (-05:00) · ciclo 3 · modo `aprobacion`

Hay **40 clips y 119 envíos pendientes de aprobación** (TikTok, Instagram y YouTube). Van ordenados por ventana, de la que cierra antes a la que cierra después, y, si la ventana es la misma, por puntaje. El modo es `aprobacion`, así que no se publica nada hasta que lo apruebes.

## Antes de aprobar

- **Ninguna plataforma tiene credenciales en esta PC.** El script devuelve `sin_credenciales` en las cuatro. TikTok sigue activa en `config.json`, pero en esta copia del proyecto hay que volver a autorizarla. Hazlo en tu propia ventana de PowerShell, desde la carpeta del proyecto:
  `powershell -NoProfile -ExecutionPolicy Bypass -File legion/03-publicador/publicar.ps1 autorizar -Plataforma tiktok`
  YouTube e Instagram tampoco tienen credenciales ni están activas (`plataformas.md` §3 y §5). Puedes aprobar por adelantado: lo aprobado se sube cuando la plataforma esté lista, si la ventana sigue abierta.
- **Faltan videos.** Los clips del 2026-11-01 al 2026-11-03 no tienen `clip.mp4` en esta copia. Se pueden aprobar, pero para subirlos hay que volver a generarlos o copiarlos. Los del 2026-11-04 y el 2026-11-05 sí tienen el video.
- **Cinco ventanas cierran hoy, 6-nov:** `lonche-seis-cifras`, `westcol-cuerpo-35-anos`, `lonche-sueno-americano`, `westcol-w-sound-700mil` y `westcol-w-sound-espana`. A ninguno le queda video en esta copia.
- **Derechos:** salvo los 4 de «Tóxico» (`autorizado`), todo es `sin_verificar`. Solo se publica si lo apruebas expresamente, y siempre lleva el crédito a la fuente con el minuto.
- **TikTok, en modo borrador:** el video llega a tu bandeja y el texto se pega en la app. Como mucho caben 5 borradores pendientes por API cada 24 h, así que publica o descarta los que ya tengas antes de aprobar más.
- **Vencidos este ciclo (83 entradas):** son los envíos de Instagram y YouTube de los clips de Blessd del 29-oct y los clips nuevos cuya ventana ya había pasado (Awooween, varios de Westcol del 2-nov, el jet de Blessd, The Chanty, el fotógrafo). Siguen en `datos/publicador/envios/`. Una aprobación expresa los vuelve a activar.

## Clips

### 1. 2026-11-02-lonche-seis-cifras

- **Gancho:** Lonche: «seis cifras a la semana» · **Tipo:** `revelacion` · **Puntaje:** 72 · **Duración:** 52,0 s · **Ventana hasta:** 2026-11-06
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** clip.mp4: el archivo no está en esta copia del proyecto (no es un error: la entrada se puede aprobar igual, pero para subirlo hace falta el video) · **Ficha:** [ficha.md](../clipero/clips/2026-11-02-lonche-seis-cifras/ficha.md)
- **Fuente:** https://youtu.be/XMLQv5JNuK0?t=429 (Clipskick04, minuto 7:09)
- **Aprobar:** `/publicador aprobar 2026-11-02-lonche-seis-cifras`

#### TikTok

Envío: `datos/publicador/envios/2026-11-02-lonche-seis-cifras__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-02-lonche-seis-cifras:tiktok`

```text
Lonche: "solamente hay un número uno y es el que gana más"

¿Para ustedes el número uno es el que más gana o el que más gente mueve?

Crédito: directo de Lonche en Kick (lonchedehuevito), vía canal Clipskick04, «LONCHE REACCIONANDO A VÍCTOR MENDIVIL Y OMAR CAMACHO». Momento original desde el minuto 7:09: https://youtu.be/XMLQv5JNuK0?t=429

#Lonche #Kick #Streamer #LaFES #México
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-02-lonche-seis-cifras__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-02-lonche-seis-cifras:instagram`

```text
"Con mis seis cifras a la semana estoy bien": Lonche

Para Lonche no hay discusión sobre quién es el número uno: "el que gana más". Reta a los demás a enseñar cuánto les paga Kick y dice que lo suyo son "seis cifras a la semana… cuando chambeo". Es lo que él afirma; no está comprobado.

¿Para ustedes el número uno es el que más gana o el que más gente mueve?

Crédito: directo de Lonche en Kick (lonchedehuevito), vía canal Clipskick04, «LONCHE REACCIONANDO A VÍCTOR MENDIVIL Y OMAR CAMACHO». Momento original desde el minuto 7:09: https://youtu.be/XMLQv5JNuK0?t=429

#Lonche #Kick #Streamer #LaFES #México
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-02-lonche-seis-cifras__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-02-lonche-seis-cifras:youtube`

**Título:** Lonche habla de cuánto gana en Kick: "seis cifras a la semana"

**Descripción:**

```text
Para Lonche no hay discusión sobre quién es el número uno: "el que gana más". Reta a los demás a enseñar cuánto les paga Kick y dice que lo suyo son "seis cifras a la semana… cuando chambeo". Es lo que él afirma; no está comprobado.

¿Para ustedes el número uno es el que más gana o el que más gente mueve?

Crédito: directo de Lonche en Kick (lonchedehuevito), vía canal Clipskick04, «LONCHE REACCIONANDO A VÍCTOR MENDIVIL Y OMAR CAMACHO». Momento original desde el minuto 7:09: https://youtu.be/XMLQv5JNuK0?t=429

#Lonche #Kick #Streamer #LaFES
```

**Etiquetas:** Lonche, Lonche Kick, streamer, La FES, Kick, México

### 2. 2026-11-02-westcol-cuerpo-35-anos

- **Gancho:** Westcol: «Mi cuerpo tiene 35 años» · **Tipo:** `humor` · **Puntaje:** 71 · **Duración:** 44,8 s · **Ventana hasta:** 2026-11-06
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** clip.mp4: el archivo no está en esta copia del proyecto (no es un error: la entrada se puede aprobar igual, pero para subirlo hace falta el video) · **Ficha:** [ficha.md](../clipero/clips/2026-11-02-westcol-cuerpo-35-anos/ficha.md)
- **Fuente:** https://youtu.be/MBotzCroy1Q?t=1405 (juan diego mm, minuto 23:25)
- **Aprobar:** `/publicador aprobar 2026-11-02-westcol-cuerpo-35-anos`

#### TikTok

Envío: `datos/publicador/envios/2026-11-02-westcol-cuerpo-35-anos__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-02-westcol-cuerpo-35-anos:tiktok`

```text
Westcol, 25 años: "mi cuerpo realmente tiene 35" 😂

¿Cuántos años tiene su cuerpo de verdad?

Crédito: directo "IM BACK" de Westcol en Kick (2-nov-2026), vía canal juan diego mm, «WESTCOL HABLANDO DE TODO Y HABLA DEL DISFRAZ QUE QUERÍA USAR». Momento original desde el minuto 23:25: https://youtu.be/MBotzCroy1Q?t=1405

#Westcol #Humor #Streamer #Kick #Colombia
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-02-westcol-cuerpo-35-anos__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-02-westcol-cuerpo-35-anos:instagram`

```text
"No tengo hombro, no tengo rodilla y no tengo muela": Westcol

Tanta tecnología y nadie inventa lo que Westcol quiere: una pastillita que te quite un año. Con 25 años, bromea con que su cuerpo "realmente tiene 35": "no tengo hombro, no tengo rodilla y en este momento no tengo muela".

¿Cuántos años tiene su cuerpo de verdad?

Crédito: directo "IM BACK" de Westcol en Kick (2-nov-2026), vía canal juan diego mm, «WESTCOL HABLANDO DE TODO Y HABLA DEL DISFRAZ QUE QUERÍA USAR». Momento original desde el minuto 23:25: https://youtu.be/MBotzCroy1Q?t=1405

#Westcol #Humor #Streamer #Kick #Colombia
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-02-westcol-cuerpo-35-anos__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-02-westcol-cuerpo-35-anos:youtube`

**Título:** Westcol quiere una pastilla para quitarse un año 😂

**Descripción:**

```text
Tanta tecnología y nadie inventa lo que Westcol quiere: una pastillita que te quite un año. Con 25 años, bromea con que su cuerpo "realmente tiene 35": "no tengo hombro, no tengo rodilla y en este momento no tengo muela".

¿Cuántos años tiene su cuerpo de verdad?

Crédito: directo "IM BACK" de Westcol en Kick (2-nov-2026), vía canal juan diego mm, «WESTCOL HABLANDO DE TODO Y HABLA DEL DISFRAZ QUE QUERÍA USAR». Momento original desde el minuto 23:25: https://youtu.be/MBotzCroy1Q?t=1405

#Westcol #Humor #Streamer #Kick
```

**Etiquetas:** Westcol, humor, streamer, Kick, Colombia, Westcol directo

### 3. 2026-11-02-lonche-sueno-americano

- **Gancho:** Lonche y su «sueño americano» · **Tipo:** `frase` · **Puntaje:** 71 · **Duración:** 43,2 s · **Ventana hasta:** 2026-11-06
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** clip.mp4: el archivo no está en esta copia del proyecto (no es un error: la entrada se puede aprobar igual, pero para subirlo hace falta el video) · **Ficha:** [ficha.md](../clipero/clips/2026-11-02-lonche-sueno-americano/ficha.md)
- **Fuente:** https://youtu.be/TGZYr7VNzio?t=2568 (Lonche PRIME, minuto 42:48)
- **Aprobar:** `/publicador aprobar 2026-11-02-lonche-sueno-americano`

#### TikTok

Envío: `datos/publicador/envios/2026-11-02-lonche-sueno-americano__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-02-lonche-sueno-americano:tiktok`

```text
Lonche: "el día que mi comunidad se sienta feliz por un chisme, ese día me retiro"

¿Qué es para ustedes el sueño americano?

Crédito: directo IRL de Lonche en Kick, vía canal Lonche PRIME, «ASÍ es VIVIR un DÍA de CHILL en LOS ANGELES | Lonche». Momento original desde el minuto 42:48: https://youtu.be/TGZYr7VNzio?t=2568

#Lonche #SueñoAmericano #LaFES #Kick #México
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-02-lonche-sueno-americano__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-02-lonche-sueno-americano:instagram`

```text
"Soy un mexicano más cumpliendo el verdadero sueño americano": Lonche

Lonche le habla a su comunidad, la FES: "el día que se sienta feliz por yo haber creado un chisme, ese día me retiro". Lo que sí tienen que presumir: los carros, ser reconocidos y ser "buenas personas". "Soy un mexicano más como ustedes que se le está cumpliendo el verdadero sueño americano".

¿Qué es para ustedes el sueño americano?

Crédito: directo IRL de Lonche en Kick, vía canal Lonche PRIME, «ASÍ es VIVIR un DÍA de CHILL en LOS ANGELES | Lonche». Momento original desde el minuto 42:48: https://youtu.be/TGZYr7VNzio?t=2568

#Lonche #SueñoAmericano #LaFES #Kick #México
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-02-lonche-sueno-americano__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-02-lonche-sueno-americano:youtube`

**Título:** Lonche a la FES: de qué sí deben sentirse orgullosos

**Descripción:**

```text
Lonche le habla a su comunidad, la FES: "el día que se sienta feliz por yo haber creado un chisme, ese día me retiro". Lo que sí tienen que presumir: los carros, ser reconocidos y ser "buenas personas". "Soy un mexicano más como ustedes que se le está cumpliendo el verdadero sueño americano".

¿Qué es para ustedes el sueño americano?

Crédito: directo IRL de Lonche en Kick, vía canal Lonche PRIME, «ASÍ es VIVIR un DÍA de CHILL en LOS ANGELES | Lonche». Momento original desde el minuto 42:48: https://youtu.be/TGZYr7VNzio?t=2568

#Lonche #SueñoAmericano #LaFES #Kick
```

**Etiquetas:** Lonche, sueño americano, La FES, Kick, streamer, México

### 4. 2026-11-02-westcol-w-sound-700mil

- **Gancho:** Westcol presume los números de la W · **Tipo:** `revelacion` · **Puntaje:** 68 · **Duración:** 61,0 s · **Ventana hasta:** 2026-11-06
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** clip.mp4: el archivo no está en esta copia del proyecto (no es un error: la entrada se puede aprobar igual, pero para subirlo hace falta el video) · **Ficha:** [ficha.md](../clipero/clips/2026-11-02-westcol-w-sound-700mil/ficha.md)
- **Fuente:** https://youtu.be/8L8CP3xe3Qo?t=96 (WestcolClips, minuto 1:36)
- **Aprobar:** `/publicador aprobar 2026-11-02-westcol-w-sound-700mil`

#### TikTok

Envío: `datos/publicador/envios/2026-11-02-westcol-w-sound-700mil__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-02-westcol-w-sound-700mil:tiktok`

```text
Westcol: la nueva W Sound hizo 700.000 streams en un día "y apenas está empezando"

¿Ya la escucharon? ¿Se va más lejos que la otra?

Crédito: directo "IM BACK" de Westcol en Kick (2-nov-2026), vía canal WestcolClips, «ESTOY DE REGRESO - HABLANDO DEL ACCIDENTE AÉREO EN FLORIDA Y DEL ÉXITO DE LA W SOUND CON HADES66». Momento original desde el minuto 1:36: https://youtu.be/8L8CP3xe3Qo?t=96

#Westcol #WSound #Hades66 #Spotify #MúsicaUrbana
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-02-westcol-w-sound-700mil__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-02-westcol-w-sound-700mil:instagram`

```text
La W Sound con Hades66 y sus números, según Westcol

Westcol saca la calculadora: según él, un éxito colombiano tuvo su mejor día en Spotify con 487.000 streams y la W Sound con Hades66 hizo 700.000 "ayer, creo", y "apenas está empezando". Son cifras que él dice, sin comprobar.

¿Ya la escucharon? ¿Se va más lejos que la otra?

Crédito: directo "IM BACK" de Westcol en Kick (2-nov-2026), vía canal WestcolClips, «ESTOY DE REGRESO - HABLANDO DEL ACCIDENTE AÉREO EN FLORIDA Y DEL ÉXITO DE LA W SOUND CON HADES66». Momento original desde el minuto 1:36: https://youtu.be/8L8CP3xe3Qo?t=96

#Westcol #WSound #Hades66 #Spotify #MúsicaUrbana
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-02-westcol-w-sound-700mil__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-02-westcol-w-sound-700mil:youtube`

**Título:** Westcol presume los números de la W Sound con Hades66

**Descripción:**

```text
Westcol saca la calculadora: según él, un éxito colombiano tuvo su mejor día en Spotify con 487.000 streams y la W Sound con Hades66 hizo 700.000 "ayer, creo", y "apenas está empezando". Son cifras que él dice, sin comprobar.

¿Ya la escucharon? ¿Se va más lejos que la otra?

Crédito: directo "IM BACK" de Westcol en Kick (2-nov-2026), vía canal WestcolClips, «ESTOY DE REGRESO - HABLANDO DEL ACCIDENTE AÉREO EN FLORIDA Y DEL ÉXITO DE LA W SOUND CON HADES66». Momento original desde el minuto 1:36: https://youtu.be/8L8CP3xe3Qo?t=96

#Westcol #WSound #Hades66 #Spotify
```

**Etiquetas:** Westcol, W Sound, Hades66, Westcol Hades66, Spotify, música urbana

### 5. 2026-11-02-westcol-w-sound-espana

- **Gancho:** Westcol: ¿por qué la W pegó en España? · **Tipo:** `humor` · **Puntaje:** 67 · **Duración:** 63,6 s · **Ventana hasta:** 2026-11-06
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** clip.mp4: el archivo no está en esta copia del proyecto (no es un error: la entrada se puede aprobar igual, pero para subirlo hace falta el video) · **Ficha:** [ficha.md](../clipero/clips/2026-11-02-westcol-w-sound-espana/ficha.md)
- **Fuente:** https://youtu.be/8L8CP3xe3Qo?t=672 (WestcolClips, minuto 11:12)
- **Aprobar:** `/publicador aprobar 2026-11-02-westcol-w-sound-espana`

#### TikTok

Envío: `datos/publicador/envios/2026-11-02-westcol-w-sound-espana__tiktok.json` · TikTok está en modo borrador: el video llega a tu bandeja y este texto se pega en la app. · `/publicador aprobar 2026-11-02-westcol-w-sound-espana:tiktok`

```text
Westcol tiene una teoría de por qué la W Sound pegó en España 😂

España, ¿es verdad lo que dice?

Crédito: directo "IM BACK" de Westcol en Kick (2-nov-2026), vía canal WestcolClips, «ESTOY DE REGRESO - HABLANDO DEL ACCIDENTE AÉREO EN FLORIDA Y DEL ÉXITO DE LA W SOUND CON HADES66». Momento original desde el minuto 11:12: https://youtu.be/8L8CP3xe3Qo?t=672

#Westcol #WSound #Hades66 #España #MúsicaUrbana
```

#### Instagram Reels

Envío: `datos/publicador/envios/2026-11-02-westcol-w-sound-espana__instagram.json` · cuando Instagram esté activa, se publica al momento y en público. · `/publicador aprobar 2026-11-02-westcol-w-sound-espana:instagram`

```text
"Los españoles son personas con muchos modales": Westcol no entiende el éxito de la W en España

La W Sound con Hades66 está más pegada en España que en cualquier otro lugar, dice Westcol, y no se lo explica: "los españoles que conozco son personas con muchos modales". Su teoría, en broma, tiene muchos pitidos. Y el remate: a un colombiano no le extraña, "ya acostumbrados a Kris R".

España, ¿es verdad lo que dice?

Crédito: directo "IM BACK" de Westcol en Kick (2-nov-2026), vía canal WestcolClips, «ESTOY DE REGRESO - HABLANDO DEL ACCIDENTE AÉREO EN FLORIDA Y DEL ÉXITO DE LA W SOUND CON HADES66». Momento original desde el minuto 11:12: https://youtu.be/8L8CP3xe3Qo?t=672

#Westcol #WSound #Hades66 #España #MúsicaUrbana
```

#### YouTube Shorts

Envío: `datos/publicador/envios/2026-11-02-westcol-w-sound-espana__youtube.json` · privacidad `private` · `/publicador aprobar 2026-11-02-westcol-w-sound-espana:youtube`

**Título:** ¿Por qué la W Sound pegó en España? La teoría de Westcol

**Descripción:**

```text
La W Sound con Hades66 está más pegada en España que en cualquier otro lugar, dice Westcol, y no se lo explica: "los españoles que conozco son personas con muchos modales". Su teoría, en broma, tiene muchos pitidos. Y el remate: a un colombiano no le extraña, "ya acostumbrados a Kris R".

España, ¿es verdad lo que dice?

Crédito: directo "IM BACK" de Westcol en Kick (2-nov-2026), vía canal WestcolClips, «ESTOY DE REGRESO - HABLANDO DEL ACCIDENTE AÉREO EN FLORIDA Y DEL ÉXITO DE LA W SOUND CON HADES66». Momento original desde el minuto 11:12: https://youtu.be/8L8CP3xe3Qo?t=672

#Westcol #WSound #Hades66 #España
```

**Etiquetas:** Westcol, W Sound, Hades66, España, música urbana, humor

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

### 13. 2026-11-05-westcol-dinero-parqueado

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

### 14. 2026-11-05-westcol-regateo-revuelto

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

### 15. 2026-11-05-revuelto-beneficio-tributario

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

### 16. 2026-11-05-westcol-precio-lambo-bajara

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

### 17. 2026-11-05-westcol-negocio-blessd-discoteca

- **Gancho:** Westcol cuenta el negocio que hizo con Blessd · **Tipo:** `historia` · **Puntaje:** 83 · **Duración:** 54,3 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-westcol-negocio-blessd-discoteca/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-westcol-negocio-blessd-discoteca/ficha.md)
- **Fuente:** https://youtu.be/LgnQHaFVvyo?t=994 (WestCOL, minuto 16:34)
- **Revisa:** La ficha pide escuchar antes de publicar la palabra "Tahoe" (la camioneta) en los subtítulos. Blessd no sale en el clip: lo cuenta Westcol.
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

### 18. 2026-11-05-westcol-robot-sin-seguridad

- **Gancho:** Westcol le quitará la seguridad al robot · **Tipo:** `revelacion` · **Puntaje:** 83 · **Duración:** 60,4 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-westcol-robot-sin-seguridad/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-westcol-robot-sin-seguridad/ficha.md)
- **Fuente:** https://youtu.be/Xrwm98iaWY8?t=40 (WestCOL, minuto 0:40)
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

### 19. 2026-11-05-westcol-robot-ascensor

- **Gancho:** La primera vez del robot en un ascensor · **Tipo:** `humor` · **Puntaje:** 80 · **Duración:** 38,4 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-westcol-robot-ascensor/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-westcol-robot-ascensor/ficha.md)
- **Fuente:** https://youtu.be/Xrwm98iaWY8?t=968 (WestCOL, minuto 16:08)
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

### 20. 2026-11-02-toxico-celos-completo

- **Gancho:** Celos hasta del aire · **Tipo:** `frase` · **Puntaje:** 78 · **Duración:** 21,2 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `autorizado`: confirmaste que tienes permiso del artista.
- **Video:** clip.mp4: el archivo no está en esta copia del proyecto (no es un error: la entrada se puede aprobar igual, pero para subirlo hace falta el video) · **Ficha:** [ficha.md](../clipero/clips/2026-11-02-toxico-celos-completo/ficha.md)
- **Fuente:** https://youtu.be/bip8ttg-VeE?t=126 (Lalo Ocampo, minuto 2:06)
- **Revisa:** Música: en TikTok conviene usar el sonido oficial de «Tóxico» si existe en la app (se elige al terminar el borrador en la app). Escuchar el audio del clip: la entrada llega a +0,51 dBTP. Repite dos líneas de intro-celos-aire: publicarlos separados.
- **Revisa:** Música: en Instagram conviene usar el sonido oficial de «Tóxico» si existe en la app. La API publica al momento con el audio del clip y no permite elegir sonido: para usarlo hay que publicar a mano desde la app. Escuchar el audio del clip: la entrada llega a +0,51 dBTP. Repite dos líneas de intro-celos-aire: publicarlos separados.
- **Revisa:** Escuchar el audio del clip: la entrada llega a +0,51 dBTP. Repite dos líneas de intro-celos-aire: publicarlos separados.
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

### 21. 2026-11-02-toxico-coro-eres-mia

- **Gancho:** El coro más tóxico · **Tipo:** `frase` · **Puntaje:** 76 · **Duración:** 21,7 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `autorizado`: confirmaste que tienes permiso del artista.
- **Video:** clip.mp4: el archivo no está en esta copia del proyecto (no es un error: la entrada se puede aprobar igual, pero para subirlo hace falta el video) · **Ficha:** [ficha.md](../clipero/clips/2026-11-02-toxico-coro-eres-mia/ficha.md)
- **Fuente:** https://youtu.be/bip8ttg-VeE?t=84 (Lalo Ocampo, minuto 1:24)
- **Revisa:** Música: en TikTok conviene usar el sonido oficial de «Tóxico» si existe en la app (se elige al terminar el borrador en la app). Escuchar el audio del clip: la entrada llega a +1,83 dBTP (posible distorsión). La letra dice 'pobre cabrón' en los subtítulos: puede limitar el alcance.
- **Revisa:** Música: en Instagram conviene usar el sonido oficial de «Tóxico» si existe en la app. La API publica al momento con el audio del clip y no permite elegir sonido: para usarlo hay que publicar a mano desde la app. Escuchar el audio del clip: la entrada llega a +1,83 dBTP (posible distorsión). La letra dice 'pobre cabrón' en los subtítulos: puede limitar el alcance.
- **Revisa:** Escuchar el audio del clip: la entrada llega a +1,83 dBTP (posible distorsión). La letra dice 'pobre cabrón' en los subtítulos: puede limitar el alcance.
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

### 22. 2026-11-05-westcol-robot-piquete

- **Gancho:** Westcol: su robot tiene más piquete · **Tipo:** `humor` · **Puntaje:** 75 · **Duración:** 26,6 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `sin_verificar`: contenido de terceros sin permiso confirmado. Solo se publica con tu aprobación expresa y siempre con crédito a la fuente. Riesgos: reclamaciones de Content ID (los ingresos pasan al titular), bloqueo del video o avisos por derechos de autor que pueden llevar al cierre de la cuenta.
- **Video:** [clip.mp4](../clipero/clips/2026-11-05-westcol-robot-piquete/clip.mp4) · **Ficha:** [ficha.md](../clipero/clips/2026-11-05-westcol-robot-piquete/ficha.md)
- **Fuente:** https://youtu.be/Xrwm98iaWY8?t=2643 (WestCOL, minuto 44:03)
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

### 23. 2026-11-02-toxico-verso-mando-la-ubi

- **Gancho:** POV: tu novio es tóxico · **Tipo:** `frase` · **Puntaje:** 72 · **Duración:** 31,4 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `autorizado`: confirmaste que tienes permiso del artista.
- **Video:** clip.mp4: el archivo no está en esta copia del proyecto (no es un error: la entrada se puede aprobar igual, pero para subirlo hace falta el video) · **Ficha:** [ficha.md](../clipero/clips/2026-11-02-toxico-verso-mando-la-ubi/ficha.md)
- **Fuente:** https://youtu.be/bip8ttg-VeE?t=52 (Lalo Ocampo, minuto 0:52)
- **Revisa:** ESCUCHAR ANTES DE APROBAR: a los 19 s del clip (1:11 de la fuente) una palabra no se entiende (subtítulos: 'Nadie (…) mi amor') y falta confirmar 'Más que sea tóxico' o 'Más que ser tóxico'; los textos no citan esa línea. Entrada de audio a +1,3 dBTP. Música: en TikTok conviene usar el sonido oficial de «Tóxico» si existe en la app (se elige al terminar el borrador en la app).
- **Revisa:** ESCUCHAR ANTES DE APROBAR: a los 19 s del clip (1:11 de la fuente) una palabra no se entiende (subtítulos: 'Nadie (…) mi amor') y falta confirmar 'Más que sea tóxico' o 'Más que ser tóxico'; los textos no citan esa línea. Entrada de audio a +1,3 dBTP. Música: en Instagram conviene usar el sonido oficial de «Tóxico» si existe en la app; la API publica al momento con el audio del clip y no permite elegir sonido: para usarlo hay que publicar a mano desde la app.
- **Revisa:** ESCUCHAR ANTES DE APROBAR: a los 19 s del clip (1:11 de la fuente) una palabra no se entiende (subtítulos: 'Nadie (…) mi amor') y falta confirmar 'Más que sea tóxico' o 'Más que ser tóxico'; los textos no citan esa línea. Entrada de audio a +1,3 dBTP.
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

### 24. 2026-11-02-toxico-intro-celos-aire

- **Gancho:** Lalo Ocampo estrena «Tóxico» · **Tipo:** `frase` · **Puntaje:** 68 · **Duración:** 19,6 s · **Ventana hasta:** 2026-11-14
- **Derechos:** `autorizado`: confirmaste que tienes permiso del artista.
- **Video:** clip.mp4: el archivo no está en esta copia del proyecto (no es un error: la entrada se puede aprobar igual, pero para subirlo hace falta el video) · **Ficha:** [ficha.md](../clipero/clips/2026-11-02-toxico-intro-celos-aire/ficha.md)
- **Fuente:** https://youtu.be/bip8ttg-VeE?t=0 (Lalo Ocampo, minuto 0:00)
- **Revisa:** Música: en TikTok conviene usar el sonido oficial de «Tóxico» si existe en la app (se elige al terminar el borrador en la app). La voz entra a los 9,4 s.
- **Revisa:** Música: en Instagram conviene usar el sonido oficial de «Tóxico» si existe en la app. La API publica al momento con el audio del clip y no permite elegir sonido: para usarlo hay que publicar a mano desde la app.
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

### 25. 2026-11-04-parceritos-decimas-abuelo

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

### 26. 2026-11-04-parceritos-filosofo-o-reggaetonero

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

### 27. 2026-11-04-parceritos-billete-diomedes

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

### 28. 2026-11-04-parceritos-poeta-corre-feo

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

### 29. 2026-11-04-parceritos-flor-abeja

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

### 30. 2026-11-04-parceritos-billete-popo

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

### 31. 2026-11-04-parceritos-borracho-ensayo

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

### 32. 2026-11-04-parceritos-novela-mas-corta

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

### 33. 2026-11-04-parceritos-profesor-sobra

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

### 34. 2026-11-04-parceritos-el-paseo

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

### 35. 2026-11-04-parceritos-poesia-protesta

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

### 36. 2026-11-04-parceritos-vomitar-premios

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

### 37. 2026-11-04-parceritos-poema-cuarto-oscuro

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

### 38. 2026-11-04-parceritos-fracaso-objetividad

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

### 39. 2026-11-01-kris-r-musica-cada-semana

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

### 40. 2026-11-01-kris-r-primer-estadio

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
- Aprobar una sola plataforma: `/publicador aprobar <clip-id>:<plataforma>` (por ejemplo, `/publicador aprobar 2026-11-05-maluma-bebe-capo:tiktok`)
- Aprobar todo lo pendiente: `/publicador aprobar todo`
- Rechazar: `/publicador rechazar <clip-id> <motivo>`
- Cambiar un texto: por ejemplo, `/publicador cambia el título de YouTube de <clip-id> por ...`
