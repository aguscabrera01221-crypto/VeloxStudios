# MANIFEST — Rodri → Barcelona · FASE A (visual 1 de 25)

Pipeline: `apt ffmpeg` + `pip yt-dlp` → búsqueda multi-fuente → descarga → contact sheet →
inspección de frames → recorte. **Probado end-to-end sobre el hook.**

---

## 01 — HOOK

**SCRIPT LINE:** *"Rodri just told Real Madrid no."*
**INTENCIÓN:** decisión fría. Rodri como persona que rechaza, no como futbolista.
Sin celebración, sin sonrisa, mirada fuera de cuadro.

### SELECTED — BEST

| | |
|---|---|
| **ARCHIVO** | `01_hook/01_HOOK_Rodri_Profile_Serious_VERTICAL_BEST.mp4` |
| **FUENTE** | @FIFAWorldCup (X) · `x.com/FIFAWorldCup/status/2079011948750876976` |
| **EVENTO** | Ceremonia adidas Golden Ball, final Mundial 2026, MetLife Stadium, 19-jul-2026 |
| **VERIFICACIÓN** | ✅ **VERIFIED** — descargado e inspeccionado frame a frame |
| **TIMESTAMP ORIGEN** | 00:00.55 → 00:03.25 (de un original de 19.56 s) |
| **DURACIÓN LOCAL** | 2.72 s (frase necesita ~2.0 s → 0.7 s de handles) |
| **RESOLUCIÓN** | **1080×1920 — nativo 9:16, sin recorte, sin upscale** |
| **SCORE** | **93/100** · A 38 / B 24 / C 15 / D 10 / E 6 |

**QUÉ SE VE (verificado):** primer plano de perfil de Rodri, camiseta de España, cara ocupando
~30 % del encuadre vertical. Expresión seria, mandíbula firme, **sin sonreír en ningún frame**,
mirada fija fuera de cuadro. Deriva lenta de cámara + giro leve de cabeza = movimiento interno
real. Fondo de grada desenfocada. Diurno.

**WHY IT WINS:** es el único material localizado donde Rodri aparece **serio y quieto** — todo
el resto del footage post-Mundial es euforia, que contradice la frase. Y llega en 1080×1920
nativo: cero pérdida por recorte, que es donde este canal suele sangrar calidad.

**CROP 9:16:** ninguno. Úsalo tal cual. Ojos al ~30 % de altura, ya encuadrado.
Rótulo *"ADIDAS GOLDEN BALL WINNER"* en el **tercio superior** → no colisiona con subtítulos
quemados abajo. Si molesta: `crop=844:1500:118:420` + escala a 1080×1920 (upscale 1.28×).

**EDIT NOTES:** velocidad normal. Zoom lentísimo 103 %→107 %. Entra con 0.5-1 s de audio
ambiente **antes** de la voz (pico de audio en el segundo 0).

**⚠️ Nota editorial:** el rótulo nombra el Balón de Oro en la línea 1, adelantando la línea 3.
Son 6 segundos de adelanto y el premio no es el payoff del vídeo (que es L19-21), así que lo doy
por aceptable. Si prefieres cero adelanto → usa **ALT_01**, que está limpio de rótulo.

---

### ALT_01

| | |
|---|---|
| **ARCHIVO** | `01_hook/01_HOOK_Rodri_Walking_Trophy_Serious_NoBanner_ALT01.mp4` |
| **FUENTE** | @FOXSports (X) · `x.com/FOXSports/status/2078972248791097402` |
| **EVENTO** | Misma ceremonia, cobertura FOX/FS1 |
| **VERIFICACIÓN** | ✅ **VERIFIED** |
| **TIMESTAMP ORIGEN** | 00:23.20 → 00:27.20 (de 39.17 s) |
| **DURACIÓN LOCAL** | 4.00 s · **1280×720** |
| **SCORE** | **86/100** · A 37 / B 22 / C 10 / D 11 / E 6 |

**QUÉ SE VE:** Rodri caminando despacio con el Balón de Oro en la mano, **cabeza baja, mirando
el trofeo, completamente serio**. Ventana elegida a propósito: el rótulo inferior de FOX
("RODRI · GOLDEN BALL WINNER") **aparece a partir de ~29 s**, así que estos 4 s están limpios.
Solo logo FS1 pequeño arriba a la derecha (aceptable, aporta credibilidad broadcast).

**WHY IT WINS:** cero texto que adelante nada, y el caminar aporta más movimiento que el BEST.
Pierde en C porque el recorte 16:9→9:16 obliga a ~2.6× de upscale.

**CROP 9:16:** `crop=405:720:330:0` (sujeto centrado-izquierda) → escalar a 1080×1920.
Verifica que no se corte el trofeo por la derecha.

---

### ALT_02

| | |
|---|---|
| **ARCHIVO** | `01_hook/01_HOOK_Rodri_Holding_GoldenBall_Composed_ALT02.mp4` |
| **FUENTE** | @FIFAWorldCup (X) — mismo original que BEST, momento distinto |
| **VERIFICACIÓN** | ✅ **VERIFIED** |
| **TIMESTAMP ORIGEN** | 00:04.40 → 00:07.40 |
| **DURACIÓN LOCAL** | 3.00 s · **1080×1920 nativo** |
| **SCORE** | **88/100** · A 36 / B 21 / C 15 / D 10 / E 6 |

**QUÉ SE VE:** plano medio, Rodri sujetando el Balón de Oro y **mirándolo hacia abajo**,
composición serena, sin celebrar. Rótulo *"ADIDAS GOLDEN BALL WINNER / RODRI"* en el **tercio
inferior** → aquí sí choca con los subtítulos quemados. Cara ~16 % del cuadro (más lejos que el BEST).

---

## BONUS — candidato adelantado para el cierre

`25_loop/25_LOOP_Rodri_Raises_GoldenBall_CANDIDATE.mp4` — FOX 33.0→36.5 s, 1280×720,
**VERIFIED**. Rodri **levantando el Balón de Oro en alto**. Es exactamente el material que la
shotlist reserva para **L25**, encontrado de paso. Guardado para no volver a buscarlo.

---

## RECHAZADOS EN ESTA FASE (todos inspeccionados, no descartados por título)

| Candidato | Motivo |
|---|---|
| Dailymotion ×8 (ceremonia, Trump, celebraciones) | **Máx. 512×288** servido a este cliente → por debajo de 720p. Rechazo nº 5 |
| @el_pais (X) 1920×1080 | Plano abiertísimo de la escalerilla del avión; sujeto <8 % del cuadro. **Rechazo nº 1** |
| @WorldCupDailyy / Full90 1168×674 | Reencode con viraje de color, tumulto sin plano de Rodri. **Rechazos nº 8 y 12** |
| ESPN (5 artículos) | Sólo embeben plató (Hislop, Laurens, Burley). **Rechazo nº 12** |
| FOX 31-38 s | Trofeo en alto = celebración → emoción contraria al hook. Reservado para L25 |
| @PFA, @brfootball, @ESPNUK, @espnW | Los posts no contienen vídeo (sólo foto/texto) |

---

## FUENTES BLOQUEADAS — sin sortear protecciones

| Fuente | Bloqueo | Sorteable |
|---|---|---|
| **YouTube** | *"Sign in to confirm you're not a bot"* | Requiere cookies de sesión → **es autenticación. No lo hago.** |
| **mancity.com** | Cloudflare anti-bot | Requiere impersonation de navegador → **no lo hago** |
| **FIFA.com /watch** | Sin extractor | — |
| **@SC_ESPN, @DAZN_ES (X)** | Metadata OK, media HTTP 403 | Bloqueo del CDN |
| **RTVE, Al Jazeera** | Búsqueda JS / URL no soportada | — |

**El bloqueo de YouTube es el límite estructural de este entorno.** No impidió completar el
hook: X (posts públicos de FIFA y FOX) entrega broadcast en 720p-1080p, y **FIFA publica en
vertical nativo 1080×1920**, que para este canal es mejor que cualquier fuente 16:9.

---

## ESTADO

**FASE A completada.** 3 clips reales, verificados e inspeccionados + 1 bonus para L25.
Visuales 02-25 pendientes de tu confirmación para escalar el mismo pipeline.

**MISSING FOOTAGE:** ninguno en esta fase.
