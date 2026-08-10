# Shotlist — "Rodri just told Real Madrid no."

**Formato:** short vertical 9:16 · **Líneas:** 25 (27 clips tras dividir 2 líneas)
**Duración calculada:** 181 palabras ÷ 2.5 p/s ≈ **72 s** (objetivo del canal: 60 s — ver Paso 0.2)

---

## LÍMITE DE ESTA ENTREGA — LÉELO ANTES QUE NADA

La FASE 4 que pediste (descargar, extraer frames, analizar el segmento) **no la he podido
ejecutar**, y no voy a fingir que sí:

- No hay `yt-dlp` ni `ffmpeg` en este entorno.
- YouTube bloquea la apertura de páginas de vídeo desde aquí (redirige a captcha de Google).
  No lo esquivo: me pediste no evadir sistemas de protección.

**Consecuencia directa:** no puedo darte timestamps verificados ni análisis de expresión
frame a frame. Hacerlo sería inventar exactamente lo que las reglas del canal prohíben
("nunca inventes detalles de un clip que no hayas comprobado").

Lo que **sí** es real en este documento:

| Campo | Estatus |
|---|---|
| Hechos del guion | ✅ Verificados en ESPN, Sky Sports, FIFA, Man City, FC Barcelona, NPR, CNN |
| Vídeos fuente (título + canal + URL) | ✅ Existen: devueltos por búsqueda indexada |
| Interpretación, hipótesis, scoring, curva | ✅ Trabajo completo |
| `ANCLA` (dónde mirar dentro del vídeo) | ⚠️ **Deducida de hechos verificados, NO vista.** Confírmala en reproducción |
| Duración del vídeo, capítulos, expresión concreta | ❌ No comprobables desde aquí |

Los `ANCLA` no son adivinanzas: se apoyan en hechos verificados (gol de Ferran Torres en la
prórroga, orden del protocolo FIFA, fecha del partido de la lesión). Pero son **puntos de
entrada, no timestamps confirmados.** Ábrelos y ajusta.

---

## PASO 0 — VERIFICACIÓN FACTUAL

Todas las premisas del guion **se sostienen**:

| Premisa | Veredicto | Fuente |
|---|---|---|
| España gana el Mundial 2026 (1-0 a Argentina, gol de Ferran Torres en prórroga, MetLife, 19 jul) | ✅ | NPR, CNN |
| Rodri gana el Balón de Oro del torneo (Messi 2.º, Mbappé 3.º) | ✅ | FIFA, ESPN, Sky |
| **Rodri fue CAPITÁN y levantó él la Copa** | ✅ | ESPN, Sky |
| De Jong se rompe el LCM (rodilla derecha) | ✅ | FC Barcelona, ESPN, beIN |
| Barcelona cierra a Rodri, ~50 M€ | ✅ | Goal, Sky, Forbes |
| Llega a Barcelona el 12 de agosto, mismo día que el resto de internacionales | ✅ | Goal |
| Real Madrid en conversaciones con City desde la semana previa, ~50 M£ | ✅ | Sky |
| Rodri: un año de contrato, sin renovar | ✅ | Sky, ESPN |
| Cirugía de espalda, recuperación corta | ✅ | Man City oficial, Sky |
| Maresca es el técnico del City (sustituye a Guardiola, junio 2026) | ✅ | Man City oficial, Al Jazeera |
| Rotura de LCA en septiembre de 2024 (vs Arsenal) | ✅ | Conocido y confirmado |
| Tiene 30 años (n. 22/06/1996) | ✅ | — |

**Ninguna línea necesita reformularse por falsedad.** El guion es publicable tal cual en lo factual.

### Pero hay UN ERROR FACTUAL EN UNA VISUAL (no en el guion)

**Línea 8, tu visual: "De Jong lesionado o siendo atendido" [con el Barça].**

De Jong **no se lesionó jugando con el Barcelona.** Se lesionó **con Países Bajos en el
Mundial**, jugó el torneo con la rodilla fuertemente vendada, y el Barça confirmó la rotura
**al volver él de vacaciones** (23-24 julio). Países Bajos cayó en dieciseisavos ante Marruecos
en penaltis.

Un clip de De Jong tirado en el césped con camiseta del Barça **sería un error factual visual**
— rechazo automático nº 3. Corregido abajo.

> Nota: esto también corrige el **Ejemplo 6** de `references/ejemplos.md`, que describe
> "camiseta del Barça identificable". Ese ejemplo se escribió sobre una lesión anterior y
> **no aplica a este caso.** Conviene actualizarlo.

---

## PASO 0.2 — AUDITORÍA DE ESCRITURA

**1. Duración.** 181 palabras ≈ **72 s**. El objetivo del canal son 60 s exactos. Estás
~30 palabras por encima. Para TikTok, 72 s sigue estando por encima del umbral de
monetización, así que **no es un fallo** — pero si quieres los 60 s clavados, los candidatos
naturales a caer son las líneas 7, 13 y 24 (las tres son refuerzo, no información nueva).

**2. Dos líneas llevan dos ideas y necesitan dos clips cada una** (regla: >8 palabras):

- **L5** *"Real Madrid were first. They'd been in talks with Manchester City since last week."*
  → 14 palabras. **L5a** = "Real Madrid were first" · **L5b** = "in talks since last week".
- **L17** *"City wanted him to sign a new deal and lead the team under Maresca."*
  → 14 palabras. **L17a** = renovación · **L17b** = "under Maresca".

Estirar un clip sobre 14 palabras es uno de los errores históricos listados en `guion.md`.

**3. No hay frases de transición prohibidas.** El guion es acumulativo y seco, exactamente
el patrón correcto. El remate sentencia sin explicar. **Bien escrito.**

---

## PASO 0.3 — EL PROBLEMA ESTRUCTURAL GRAVE: EL LOOP ESTÁ ROTO

Tu plan usa el **Balón de Oro dos veces**: línea 3 (recepción) y línea 25 (cierre).

Eso rompe dos reglas a la vez:

- **Rechazo automático nº 11** — clip ya usado en el mismo vídeo.
- **Regla del loop** (`retencion.md` / Ejemplo 11) — el clip final debe reconectar con el
  **primer frame**, no con el tercero. Si el cierre remite a la línea 3, el autoloop de TikTok
  no encaja y el replay involuntario se pierde.

Y hay un segundo problema encadenado: **líneas 2 y 3 gastan tus dos mejores activos
(levantamiento de Copa + Balón de Oro) en los segundos 3-8**, dejando el payoff (75-85 %,
líneas 19-21) sin munición. Eso contradice frontalmente *"guarda tus dos mejores clips para
hook y payoff"*.

### Solución propuesta (la aplico en esta shotlist)

Aprovecho que la ceremonia del Balón de Oro da **dos momentos distintos en el mismo
escenario**:

- **L1 / hook** → Rodri en la ceremonia, **cara compuesta, seria, sin celebrar**, sosteniendo
  o recibiendo el trofeo. Emoción: frío. Encaja con *"told Real Madrid no"*.
- **L25 / cierre** → Rodri **levantando** el Balón de Oro. Mismo escenario, misma ropa, misma
  luz → **rima visual perfecta** con el frame 1, pero **momento distinto**: no es repetición,
  es cierre de círculo. El loop funciona y tú conservas el Balón de Oro en el cierre, que es
  lo que querías.

**Coste:** la línea 3 pierde su visual original. La resuelvo con el **plano de reacción del
estadio/banquillo español** durante el anuncio, que además rompe la cadena de tres planos de
trofeo seguidos. Ver L3.

**Si prefieres tu versión original**, dímelo: es defendible, pero entonces el vídeo no tiene
loop y hay que asumirlo conscientemente.

---

## PASO 0.4 — MAPA DE FUNCIONES

| # | Línea | Función | Energía |
|---|---|---|---|
| 1 | Rodri told Madrid no | **HOOK** | BAJA-tensión |
| 2 | Won the World Cup | Escalada | **ALTA** |
| 3 | Golden Ball | Escalada | MEDIA |
| 4 | Picked Barcelona | **GIRO** | MEDIA |
| 5a/b | Madrid were first / in talks | Contexto | BAJA / MEDIA |
| 6 | £50m | Evidencia | MEDIA |
| 7 | Personal terms never the problem | Contexto | BAJA |
| 8 | De Jong MCL | **GIRO** | ALTA |
| 9 | Barcelona needed a midfielder | Evidencia | MEDIA |
| 10 | Called Rodri's camp | Escalada | BAJA |
| 11 | Agreed in days | Evidencia | BAJA *(pattern interrupt)* |
| 12 | Four year deal | Evidencia | MEDIA |
| 13 | Same money at City | Evidencia | MEDIA |
| 14 | Didn't leave for money | **GIRO** | BAJA |
| 15 | Madrid found out from press | **GIRO** | BAJA |
| 16 | One year left | Contexto | MEDIA |
| 17a/b | New deal / under Maresca | Contexto | MEDIA / BAJA |
| 18 | He's 30 | Escalada | BAJA |
| 19 | ACL Sept 2024 | **PAYOFF 1** | ALTA |
| 20 | Back surgery | **PAYOFF 2** | BAJA |
| 21 | Paying 50m anyway | **PAYOFF 3** | ALTA |
| 22 | Lands August 12th | Cierre | BAJA |
| 23 | Same day as Spain internationals | Cierre | ALTA |
| 24 | Madrid still trying | Cierre | BAJA |
| 25 | Would you have taken the risk? | **LOOP** | MEDIA |

**Payoff real = líneas 19-21** (30 años + LCA + espalda + pagan 50 M igual). Ahí está la tesis
del vídeo. Es donde va el mejor material, no en la línea 2.

---

# SHOTLIST

---

### L1 — HOOK

**SCRIPT:** *"Rodri just told Real Madrid no."*

**VISUAL INTENTION:** Decisión fría, no fútbol. Rodri como **persona que rechaza**, no como
jugador. La frase aporta el impacto; la imagen aporta el temple. Ambigüedad = muerte.

**INTERPRETACIÓN — sujeto:** Rodri · **emoción:** frialdad determinada · **energía:** baja con
tensión · **plano:** primer plano / medio corto, cara 30-50 % del cuadro · **corporal:**
mandíbula firme, mirada fuera de cuadro, **sin sonrisa** · **contexto:** España, ceremonia
post-final, nocturno con focos.

**NO DEBE APARECER:** sonrisa, celebración, confeti en primer plano, compañeros abrazándole,
camiseta del City (aquí es "el hombre", no "el jugador del City").

**BEST CLIP:** `youtube.com/watch?v=woU8Jt1NMnU` — *"🏆 FIFA World Cup 2026 Final Award
Ceremony | Full Video | Trophy Presentation"*

**ANCLA:** durante la entrega individual de premios, **antes** del levantamiento de copa. El
protocolo FIFA sitúa los premios individuales (Balón de Oro / Guante de Oro / Joven) **antes**
de la entrega del trofeo — ahí es donde vive la cara compuesta. ⚠️ Confirmar en reproducción.

**DURACIÓN:** 2.0 s · **SCORE (proyectado):** 92/100 — A 37 / B 24 / C 14 / D 10 / E 7

**WHY IT WINS:** Es la única ventana reciente donde Rodri aparece **serio y quieto**: todo el
resto del material post-Mundial es euforia, que contradice la frase. Ceremonia = luz
controlada, cara centrada, recorte 9:16 trivial.

**BACKUP 1:** `youtube.com/watch?v=DK2UTrhiTww` — *"Rodri vs Argentina | WC 2026 final FULL
PERFORMANCE | 1080i"* — ancla: intervalos muertos del partido (saques, faltas), donde el
player-cam aísla su cara. **88/100.** Riesgo: compilación de terceros, verificar watermark.

**BACKUP 2:** `youtube.com/shorts/Zpnu-6cR7Kg` — *"What a moment for Spanish captain Rodri…"*
— ya vertical. **80/100.** Riesgo alto de subtítulos quemados (rechazo nº 7): **verificar antes**.

**RECHAZADOS:**
- `UrvD25jvaz8` *"Rodri Reacts to Winning the World Cup"* → emoción alegre, **contradice la
  frase**. Rechazo nº 2. Es el error clásico: clip bueno, emoción incorrecta.
- `PSpFmsGf3Ig` *"Trump PUSHED Off Stage… AWKWARD Trophy Moment With Rodri"* → viral y raro,
  pero la emoción es incomodidad/circo, no determinación. **A ≤ 25 → regla anti-espectáculo.**
  Tentador y equivocado.
- Cualquier highlight de acción de Rodri → describe fútbol, no una decisión.

**CROP NOTES:** cara al tercio superior-central. Dejar aire sobre la cabeza; ojos ~38 % de
altura. Esquina inferior derecha libre para UI.

**EDIT NOTES:** velocidad normal. Zoom digital lentísimo hacia dentro (~103 % → 107 %) para que
no lea como foto fija. **Entra 0.5-1 s de audio de ambiente ANTES de la voz** — pico de audio
en el segundo 0 (`guion.md`).

---

### L2

**SCRIPT:** *"Three weeks ago he won the World Cup."*

**VISUAL INTENTION:** Catarsis, y **él dentro de ella**. La frase es sobre él aunque el logro
sea colectivo (Ejemplo 8).

**MEJORA SOBRE TU SUGERENCIA:** pediste *"España levantando la Copa"*. **Rodri era el capitán
y levantó él el trofeo** — de manos de Trump, en MetLife. Tu versión diluye al protagonista en
el grupo; ésta lo pone en el centro. Es objetivamente mejor y es factual.

**BEST CLIP:** `youtube.com/watch?v=6HaHNYjnghE` — *"Highlights | Spain 1-0 Argentina | FIFA
World Cup 2026™ FINAL"* (canal oficial FIFA — fuente tier 2)

**ANCLA:** bloque final del vídeo, tras el gol de Ferran Torres en la prórroga. Los highlights
oficiales cierran con levantamiento de copa. ⚠️ Confirmar.

**DURACIÓN:** 2.2 s · **SCORE:** 94/100 — A 38 / B 24 / C 13 / D 12 / E 7

**WHY IT WINS:** Protagonista + trofeo + confeti + nocturno en un solo frame, desde fuente
oficial sin watermark. Cumple el requisito de Ejemplo 8: sujeto identificable en el primer
tercio del clip.

**BACKUP 1:** `youtube.com/watch?v=YWg9FEfjl_k` — *"Trump Presents FIFA World Cup 2026 Trophy
to Rodri Hernández"* — **91/100.** Momento raro y Tier-1 (EE.UU.), pero la presencia política
puede desviar el foco de la historia deportiva.

**BACKUP 2:** `youtube.com/watch?v=7YeSZeP_5wM` — *"Spain v Argentina — 30-Minute EXTENDED
HIGHLIGHTS"* (ITV Sport) — **89/100.** Más metraje donde elegir; logo ITV aceptable (nivel 16).

**RECHAZADOS:** plano general de celebración sin Rodri (rechazo nº 1, sujeto <8 %); clips donde
tarda >1 s en aparecer (nº 14); vídeos de "fans reaction" (`nJ66JzRMa04`) — el valor aquí es él,
no la grada.

**CROP NOTES:** trofeo y cara **en el mismo eje vertical**. Si el plano es horizontal amplio,
recortar cerrando sobre él y aceptar perder el confeti lateral.

**EDIT NOTES:** velocidad normal, **corte duro**. No ralentizar: el slow motion se reserva para
el payoff (líneas 19-21), y `retencion.md` limita a 2 usos por vídeo.

---

### L3

**SCRIPT:** *"He won the Golden Ball. Best player of the tournament."*

**VISUAL INTENTION:** Consagración individual. **Reasignada** para no gastar aquí el activo del
cierre (ver Paso 0.3) y para no encadenar tres planos de trofeo.

**HIPÓTESIS ELEGIDA:** reacción (en vez de literal).

**BEST CLIP:** `youtube.com/watch?v=Jpm-FVOKhxY` — *"FIFA World Cup 2026 Awards: Mbappe Wins
Golden Boot, Rodri Golden Ball"*

**ANCLA:** momento del anuncio del Balón de Oro — buscar el **plano de reacción** (banquillo
español, compañeros, grada) en lugar del trofeo en alto, que queda reservado para L25.

**DURACIÓN:** 2.5 s · **SCORE:** 86/100 — A 34 / B 21 / C 13 / D 11 / E 7

**WHY IT WINS:** Sostiene la línea sin quemar el cierre, e inserta cara humana entre dos planos
de trofeo. Si el plano de reacción no existe en este vídeo, usar el propio Balón de Oro **en
mano, a la altura del pecho** (no en alto) — el gesto en alto es exclusivo de L25.

**BACKUP 1:** `youtube.com/shorts/15uKZ50UE7w` — *"Spain captain Rodri wins the Golden Ball
award"* — ya vertical. **84/100.** Verificar subtítulos quemados.

**BACKUP 2:** `youtube.com/shorts/C6BKXNb1NjE` — *"Rodri Wins Golden Ball, Unai Simón Golden
Glove, Pau Cubarsí Young Player"* — **78/100.** Riesgo: formato lista, puede cortar demasiado pronto.

**RECHAZADOS:** `VSBNSCPjirk` (ESPN FC, *"Should Rodri have won over Messi?"*) y `aAMPJbvcyVE`
→ **talking heads de estudio**: rechazo nº 12, escena genérica que no comunica esta frase.

**CROP NOTES:** si es reacción de banquillo, encuadrar 2-3 cuerpos, no uno.
**EDIT NOTES:** corte directo. Sin zoom (L1 ya lleva zoom; alternar tratamiento).

---

### L4 — GIRO

**SCRIPT:** *"Then he picked Barcelona."*

**VISUAL INTENTION:** El pivote del vídeo. Debe **aterrizar seco**. Institución, no persona.

**ATENCIÓN A LA CONTINUIDAD:** tu plan pone Camp Nou aquí y Bernabéu en L5 → **dos planos
generales de estadio consecutivos**, prohibido (`retencion.md`). Lo resuelvo bajando la escala
aquí: **detalle**, no plano general.

**BEST CLIP:** escudo del Barça / rótulo "Spotify Camp Nou" en **plano cerrado o contrapicado
corto**, con movimiento de cámara.

**DÓNDE BUSCARLO:** YouTube → `Spotify Camp Nou reopening 2026 tour` · `FC Barcelona stadium
detail crest` · canal oficial **FC Barcelona** (fuente tier 3).

**DURACIÓN:** 1.8 s · **SCORE:** 82/100 (concepto)

**WHY IT WINS:** El detalle golpea más seco que el plano general y salva la alternancia de
escala con L5.

**BACKUP 1:** exterior del Camp Nou a ras de suelo, travelling lateral. **80/100.**
**BACKUP 2:** camiseta del Barça colgada en vestuario — símbolo de pertenencia (`dimensiones.md`). **78/100.**

**RECHAZADOS:** plano general aéreo del Camp Nou → se reserva para **L21** (donde el estadio
lleno sí es el argumento) y evita repetición.

**CROP NOTES:** escudo descentrado al tercio superior; espacio inferior para el subtítulo.
**EDIT NOTES:** corte seco al inicio de "Then". Sin transición.

⚠️ **Riesgo de footage:** el Camp Nou ha estado en obras. Verificar que el material sea del
estado actual del estadio y no de archivo antiguo (rechazo nº 3, época incorrecta).

---

### L5a

**SCRIPT:** *"Real Madrid were first."*

**VISUAL INTENTION:** Institución que llega antes… y pierde. Anticipa la humillación de L15.

**BEST CLIP:** Santiago Bernabéu, **plano general**, exterior, luz fría, movimiento lento (drone
o travelling).

**DÓNDE BUSCARLO:** YouTube → `Santiago Bernabeu drone exterior 2026` · `Bernabeu aerial night` ·
canal oficial **Real Madrid**.

**DURACIÓN:** 1.5 s · **SCORE:** 84/100 (concepto)

**WHY IT WINS:** Tras el detalle de L4, el general aquí crea el contraste de escala correcto y
presenta al perdedor de la historia.

**BACKUP 1:** fachada del Bernabéu iluminada, contrapicado. **82/100.**
**BACKUP 2:** escudo del Madrid en la fachada. **76/100** — pero **choca con L7**, que ya usa el
escudo. No usar ambos.

**RECHAZADOS:** Bernabéu **lleno y ruidoso** → contradice el tono de institución superada
(Ejemplo 2). Jugadores del Madrid celebrando → contradicción total.

**CROP NOTES:** vertical favorece la fachada; buscar toma con eje vertical dominante.
**EDIT NOTES:** velocidad normal, movimiento de cámara continuo.

---

### L5b

**SCRIPT:** *"They'd been in talks with Manchester City since last week."*

**VISUAL INTENTION:** La otra parte de la negociación. Cambia de institución: Madrid → City.

**BEST CLIP:** Etihad Stadium exterior, o el escudo del City sobre la valla publicitaria.

**DÓNDE BUSCARLO:** YouTube → `Etihad Stadium exterior 2026` · canal oficial **Man City**.

**DURACIÓN:** 1.6 s · **SCORE:** 80/100 (concepto)

**WHY IT WINS:** Traduce "conversaciones" en dos edificios en vez de en un gráfico. Nunca
ilustres una negociación con flechas o escudos animados (prohibición absoluta).

**BACKUP 1:** Etihad de noche con focos. **82/100.**
**BACKUP 2:** — si vas justo de tiempo, **esta es la primera línea a fusionar con L5a.**

**EDIT NOTES:** corte directo. ⚠️ Cuidado: L5b (Etihad) y L13 (Etihad) **no pueden ser el mismo
plano** — rechazo nº 11.

---

### L6

**SCRIPT:** *"They offered fifty million pounds."*

**VISUAL INTENTION:** **Regla de cifras de dinero** (`dimensiones.md`): la cifra la dicen voz y
subtítulo. La imagen muestra **al activo que vale ese dinero**, en acción.

**BEST CLIP:** Rodri con el City **en acción de partido**, plano medio, ganando un balón o
girando con él.

**DÓNDE BUSCARLO:** YouTube → `Rodri Manchester City 2025/26 highlights` · `Rodri best moments
City Premier League`.

**DURACIÓN:** 2.0 s · **SCORE:** 83/100 (concepto)

**WHY IT WINS:** Demuestra el precio en lugar de repetirlo.

**BACKUP 1:** Rodri dirigiendo/señalando a compañeros — lenguaje corporal de líder. **85/100.**
**BACKUP 2:** Rodri en el túnel del Etihad. **79/100.**

**RECHAZADOS:** **cualquier** imagen de billetes, bolsas de dinero o gráficos → cliché fatal,
prohibición absoluta del canal.

⚠️ **AVISO DE REPETICIÓN:** L6, L12 y L16 son los tres "Rodri con el City". **Deben ser tres
partidos distintos y tres escalas distintas.** Asignación: **L6 = plano medio, acción** ·
**L12 = plano medio, celebración/liderazgo** · **L16 = plano general de juego, otro partido.**

**EDIT NOTES:** corte al beat de "fifty".

---

### L7

**SCRIPT:** *"Personal terms were never the problem for Madrid."*

**VISUAL INTENTION:** Frase de tesis, sin footage posible. Función **rítmica y de continuidad**
(Ejemplo 10): sostener sin restar.

**BEST CLIP:** escudo del Real Madrid en el estadio, plano cerrado con movimiento.

**DÓNDE BUSCARLO:** YouTube → `Real Madrid crest stadium detail` · canal oficial Real Madrid.

**DURACIÓN:** 1.8 s · **SCORE:** 76/100 (concepto)

**WHY IT WINS:** Cumple su función sin mentir. **Es de los tres clips más débiles del vídeo, y
lo asumo conscientemente** — está en el tramo 70-79, permitido solo en líneas contextuales, y
esta lo es.

**BACKUP 1:** palco/gradas vacías del Bernabéu. **74/100.**
**BACKUP 2:** — **candidata nº 1 a eliminarse si recortas a 60 s.** No aporta información nueva.

**EDIT NOTES:** zoom lento. Es un respiro deliberado antes del giro de L8.

---

### L8 — GIRO

**SCRIPT:** *"Then Frenkie de Jong tore his MCL."*

🔴 **TU VISUAL ERA FACTUALMENTE INCORRECTA.** De Jong se lesionó **con Países Bajos en el
Mundial**, no con el Barça, y jugó el torneo con la rodilla vendada. Un clip suyo caído con
camiseta azulgrana = rechazo automático nº 3.

**VISUAL INTENTION:** Ruptura súbita: el interruptor que enciende toda la historia. Sin esta
lesión no hay fichaje.

**BEST CLIP (corregido):** De Jong con **Países Bajos**, rodilla derecha **visiblemente
vendada**, gesto de dolor o molestia — o su salida del campo ante Marruecos.

**DÓNDE BUSCARLO:** YouTube → `Netherlands Morocco World Cup 2026 round of 32 highlights` ·
`Frenkie de Jong knee strapping World Cup 2026` · `de Jong injury Netherlands 2026`.

**DURACIÓN:** 2.2 s · **SCORE:** 79/100 (concepto) — **por debajo del umbral, lo señalo**

**WHY IT WINS:** Es lo único factualmente correcto disponible.

⚠️ **RIESGO DE FOOTAGE ALTO — LEE ESTO ANTES DE PRODUCIR.** Puede que **no exista** un momento
limpio de rotura: no hubo camilla ni caída dramática, la lesión se confirmó **después** del
torneo. Opciones, en orden:

1. **Mejor alternativa real:** eliminación de Países Bajos ante Marruecos en penaltis →
   De Jong cabizbajo. Emoción de pérdida, factualmente correcta, y **sí existe**. **83/100.**
2. **Alternativa simbólica:** primer plano de rodilla vendada en juego. **80/100** si se encuentra.
3. **Reformular la línea:** *"Then Barcelona lost Frenkie de Jong for months."* → permite usar
   el comunicado del club o a De Jong fuera del campo, y elimina la dependencia de un clip que
   quizá no exista. **Es mi recomendación si la búsqueda supera 3 minutos.**

**RECHAZADOS:** De Jong con el Barça lesionado (falso); imágenes médicas o quirúrgicas
(rechazo nº 18); De Jong en rueda de prensa (mata la energía del giro).

**EDIT NOTES:** corte duro de entrada. Sin ralentizar.

---

### L9

**SCRIPT:** *"Barcelona needed a holding midfielder overnight."*

**VISUAL INTENTION:** Urgencia y hueco. El pivote es el puesto vacío.

**BEST CLIP:** mediocampo del Barça en acción **desbordado** — rival progresando por el centro,
o Barça recuperando bajo presión.

**DÓNDE BUSCARLO:** YouTube → `Barcelona midfield 2025/26` · `Barcelona pre-season 2026
highlights` · canal oficial FC Barcelona.

**DURACIÓN:** 2.0 s · **SCORE:** 77/100 (concepto)

**WHY IT WINS:** Traduce "necesitaban" en una carencia visible.

**BACKUP 1:** entrenamiento del Barça, plano medio de trabajo de centro del campo. **75/100.**
**BACKUP 2:** Flick en la banda observando. **79/100** — cara humana, sube retención.

**RECHAZADOS:** *"dos jugadores corriendo por el centro del campo"* → rechazo nº 12, escena
genérica. **Este es el riesgo real de esta línea:** es fácil acabar con relleno intercambiable.
**Segunda candidata a recorte** si vas a 60 s.

**EDIT NOTES:** corte directo, velocidad normal.

---

### L10

**SCRIPT:** *"They called Rodri's camp."*

**VISUAL INTENTION:** Anticipación. Algo se mueve fuera de cuadro. **No ilustres la llamada.**

**BEST CLIP:** Rodri **caminando solo**, saliendo del campo o por el túnel, de espaldas o de
perfil. Tipo de footage infrautilizado y muy valioso (`retencion.md`).

**DÓNDE BUSCARLO:** YouTube → `Rodri tunnel walk Manchester City` · `Rodri substituted walking
off` · `Man City players arrive Etihad`.

**DURACIÓN:** 1.8 s · **SCORE:** 85/100 (concepto)

**WHY IT WINS:** Soledad + dirección de movimiento = expectativa. El sujeto mira o va hacia algo
que no vemos: exactamente el criterio nº 20 (generar curiosidad).

**BACKUP 1:** Rodri en el banquillo, aislado en el cuadro. **81/100.**
**BACKUP 2:** llegada al estadio, traje, bajando del autobús. **83/100.**

**RECHAZADOS:** teléfonos, oficinas, imágenes de "llamada" → literalidad barata.

**CROP NOTES:** dejar **aire delante** de su dirección de marcha; el vacío delante es el mensaje.
**EDIT NOTES:** velocidad normal. Corte antes de que llegue a destino — no resuelvas el movimiento.

---

### L11 — PATTERN INTERRUPT

**SCRIPT:** *"He agreed personal terms in days."*

**VISUAL INTENTION:** Credibilidad documental. Uno de los pocos casos donde una **captura
estática supera a un clip** (Ejemplo 7), porque el valor es textual y verificable.

**BEST CLIP:** captura del titular real. Fuentes verificadas y utilizables:
- **Sky Sports** — *"Rodri transfer news: Barcelona target Man City and Spain star wanted by
  Real Madrid"*
- **Goal** — *"Confirming his arrival date: Barcelona seal Rodri deal"*
- **Forbes** — *"FC Barcelona's Expected Rodri Transfer Triggers Two Midfield Exits"*

**DURACIÓN:** 1.6 s · **SCORE:** 88/100

**WHY IT WINS:** Prueba verificable con logo de medio visible, y **rompe el patrón visual** en
la posición correcta (clip nº 11, dentro de la ventana de 4-6).

**BACKUP 1:** captura de Fabrizio Romano. **87/100** — verificar que sea su cuenta oficial.
**BACKUP 2:** captura del comunicado oficial del FC Barcelona. **85/100.**

**RECHAZADOS:** capturas ilegibles a tamaño móvil; cuentas de rumores sin verificar (rechazo
nº 17); capturas sin logo de medio visible.

**CROP NOTES:** **recortar sobre el titular, no sobre el cuerpo del texto.** El titular debe
leerse a tamaño móvil sin esfuerzo. Logo del medio dentro de cuadro — es lo que da credibilidad.

**EDIT NOTES:** **zoom lento obligatorio** (rechazo nº 15: nada estático total). Ideal: entrar
con 0.3 s de negro antes — refuerza el pattern interrupt.

---

### L12

**SCRIPT:** *"Four year deal. Over ten million euros net per season."*

**VISUAL INTENTION:** Otra vez cifras → **no ilustrar dinero**. Mostrar el estatus que justifica
ese contrato.

**BEST CLIP:** Rodri con el City, **plano medio, celebrando o dirigiendo** — registro distinto
al de L6 (ver aviso de repetición).

**DÓNDE BUSCARLO:** YouTube → `Rodri Manchester City celebration 2025/26` · `Rodri captain
armband City`.

**DURACIÓN:** 2.4 s · **SCORE:** 81/100 (concepto)

**BACKUP 1:** Rodri levantando un título con el City. **84/100.**
**BACKUP 2:** Rodri aplaudiendo a la grada del Etihad. **78/100.**

**RECHAZADOS:** gráficos de contrato, tablas salariales, imágenes de dinero → prohibición absoluta.

**EDIT NOTES:** línea larga (10 palabras ≈ 4 s). **Si supera 4 s, pártela en dos micro-clips**
("Four year deal" / "Over ten million euros net") — nunca estires un clip (`guion.md`).

---

### L13

**SCRIPT:** *"The same money he already earns at City."*

**VISUAL INTENTION:** Equivalencia → prepara la negación de L14. Debe mantener energía **MEDIA**:
L14 y L15 ya son bajas, y tres bajas seguidas matan.

**BEST CLIP:** Etihad **lleno, de noche**, con movimiento — o Rodri en el campo con la grada al fondo.

**DÓNDE BUSCARLO:** YouTube → `Etihad Stadium full night Premier League 2026` · canal oficial Man City.

**DURACIÓN:** 2.0 s · **SCORE:** 78/100 (concepto)

**WHY IT WINS:** Sostiene el ritmo y evita el bache de energía. ⚠️ **No repetir el plano de L5b.**

**BACKUP 1:** grada del City cantando. **77/100.**
**BACKUP 2:** Rodri calentando en el Etihad. **80/100.**

**RECHAZADOS:** cualquier gráfico comparativo de salarios. **Tercera candidata a recorte** si
vas a 60 s.

**EDIT NOTES:** velocidad normal, movimiento de cámara.

---

### L14 — GIRO

**SCRIPT:** *"He didn't leave for money."*

**VISUAL INTENTION:** **Regla de negaciones** — tu instinto era correcto. Nunca muestres dinero
bajo una negación de dinero. La contradicción entre lo que se dice y lo que se ve **genera peso**.

**BEST CLIP:** primer plano de Rodri, **expresión neutra**, quieto, mirada baja o fuera de cuadro.

**DÓNDE BUSCARLO:** YouTube → `Rodri press conference 2026` · `Rodri interview Spain` ·
`kkNIWDJpw6A` (*"Rodri Exclusive: Battling An ACL Injury & Ballon d'Or Beef"* — entrevista, buen
banco de primeros planos serenos).

**DURACIÓN:** 2.0 s · **SCORE:** 89/100 (concepto)

**WHY IT WINS:** Cara + calma + silencio bajo una frase de negación. Es el clip más "documental"
del vídeo y el que mejor vende la tesis sin argumentarla.

**BACKUP 1:** Rodri en rueda de prensa, plano fijo. **85/100** — aplicar zoom lento obligatorio.
**BACKUP 2:** Rodri sentado en el banquillo, pensativo. **83/100.**

**RECHAZADOS:** dinero, contratos, cualquier símbolo económico; Rodri sonriendo (rompe la
gravedad de la frase).

**CROP NOTES:** cara centrada, **más cerrado que L1** — L1 y L14 son ambos primeros planos y no
pueden parecer el mismo plano. Distinto contexto (ceremonia vs entrevista) y distinta escala.

**EDIT NOTES:** velocidad normal. Considera **0.3 s de silencio** antes de la frase: el silencio
bajo un primer plano quieto es el pattern interrupt más barato y efectivo.

---

### L15 — GIRO

**SCRIPT:** *"Madrid found out from the press."*

**VISUAL INTENTION:** Humillación institucional. Emoción: **vacío**. No hay individuo
protagonista (Ejemplo 2 — este caso está literalmente en el manual).

**BEST CLIP:** Santiago Bernabéu **vacío o semivacío**, atardecer o noche, luz fría, cámara con
movimiento lento.

**DÓNDE BUSCARLO:** YouTube → `Santiago Bernabeu empty stadium drone` · `Bernabeu interior empty
2026` · canal oficial Real Madrid.

**DURACIÓN:** 2.2 s · **SCORE:** 90/100 (concepto)

**WHY IT WINS:** La ausencia dice "les dejaron fuera" mejor que cualquier imagen de periodistas.
Mostrar prensa sería literal y débil.

**BACKUP 1:** gradas vacías desde el césped, contrapicado. **88/100.**
**BACKUP 2:** Bernabéu vacío con los focos encendiéndose. **86/100.**

**RECHAZADOS:** periodistas, cámaras, micrófonos, periódicos → literalidad barata, el error
exacto que el manual señala. Bernabéu lleno → contradice la emoción de vacío. Fotos fijas sin
movimiento (rechazo nº 15).

⚠️ **No puede ser el mismo plano que L5a ni que L24** — son tres Bernabéus. Asignación:
**L5a = exterior/fachada** · **L15 = interior vacío** · **L24 = exterior nocturno iluminado.**

**EDIT NOTES:** movimiento lento continuo. **No cortar antes de 2 s:** esta línea necesita
respirar, es el clímax emocional del bloque medio.

---

### L16

**SCRIPT:** *"Rodri has one year left on his contract."*

**VISUAL INTENTION:** Dato duro de contexto. Función: reactivar energía tras dos bajas.

**BEST CLIP:** Rodri en acción de Premier League — **plano general de juego**, tercer partido
distinto (ver aviso L6).

**DÓNDE BUSCARLO:** YouTube → `Rodri Premier League 2025/26 highlights` · `Manchester City
extended highlights 2026`.

**DURACIÓN:** 2.0 s · **SCORE:** 79/100 (concepto)

**BACKUP 1:** Rodri saliendo del túnel del Etihad con el equipo. **83/100.**
**BACKUP 2:** Rodri en el círculo central antes del saque. **80/100** — símbolo de tiempo detenido.

**RECHAZADOS:** gráficos de contrato o líneas de tiempo → prohibición absoluta.
**EDIT NOTES:** corte directo. Ancla Premier = valor Tier-1 (criterio nº 21).

---

### L17a

**SCRIPT:** *"City wanted him to sign a new deal…"*

**BEST CLIP:** dirigentes/staff del City, o Rodri con el escudo del City en primer término.

**DÓNDE BUSCARLO:** YouTube → canal oficial Man City, `Man City contract announcement 2026`.

**DURACIÓN:** 1.8 s · **SCORE:** 76/100 (concepto)

**BACKUP 1:** Rodri firmando/posando con la camiseta del City (archivo). **74/100** — ojo,
"jugador firmando contrato" es visualmente muerto (`dimensiones.md`).
**BACKUP 2:** Etihad con el escudo dominante. **75/100.**

---

### L17b

**SCRIPT:** *"…and lead the team under Maresca."*

**VISUAL INTENTION:** Presentar al técnico nuevo. Debe leerse **quién es** en 2 segundos.

**BEST CLIP:** `youtube.com/watch?v=xyWktje3xxM` — *"Enzo Maresca Cam! | City 1-1 Inter | Asia
Tour 2026"* (canal oficial Man City)

**ANCLA:** vídeo dedicado íntegramente a Maresca en banda → **cualquier tramo sirve**; elegir un
gesto de instrucción amplio. ⚠️ Confirmar en reproducción.

**DURACIÓN:** 1.8 s · **SCORE:** 87/100

**WHY IT WINS:** Es literalmente una cámara fija sobre Maresca desde fuente oficial: material
limpio, sin watermark, y **resuelve un footage escaso** (lleva semanas en el cargo).

**BACKUP 1:** `youtube.com/watch?v=lryDTVzPNQ8` — *"MARESCA: 'WE WERE PRESSING IN THE WRONG
WAY!'"* — rueda de prensa. **80/100**, estático: exige zoom lento.
**BACKUP 2:** `youtube.com/watch?v=a7vodVqRUpI` — *"Enzo Maresca's FIRST Manchester City press
conference!"* — **78/100.**

**RECHAZADOS:** cualquier imagen de Maresca **con el Chelsea** → rechazo nº 3, contexto
incorrecto. **Es el error más probable de esta línea:** la mayor parte de su footage indexado es
del Chelsea. **Verifica el color de la ropa y el fondo antes de descargar.**

**CROP NOTES:** Maresca gesticulando en el tercio superior; banquillo/campo como fondo.
**EDIT NOTES:** velocidad normal.

---

### L18

**SCRIPT:** *"He's 30 years old."*

**VISUAL INTENTION:** Aquí arranca el payoff. La edad no es un dato: es **la primera pieza de la
acusación**. Debe verse un rostro que ya no es joven.

**BEST CLIP:** primer plano de Rodri, quieto, **preferiblemente cansado o sudado** tras esfuerzo.

**DÓNDE BUSCARLO:** YouTube → `Rodri full time reaction` · `DK2UTrhiTww` (player-cam del final,
buscar tramos de fatiga en la prórroga).

**DURACIÓN:** 1.5 s · **SCORE:** 86/100 (concepto)

**WHY IT WINS:** Sudor y respiración cuentan "30 años" sin decirlo. Y **la prórroga de la final
existe** — el partido se decidió en el tiempo extra, así que hay metraje real de agotamiento.

**BACKUP 1:** Rodri con las manos en las rodillas. **88/100** si se encuentra.
**BACKUP 2:** Rodri bebiendo agua / recuperando en pausa. **82/100.**

**RECHAZADOS:** gráficos de edad; Rodri joven en el Atlético (rechazo nº 3, época incorrecta).

**CROP NOTES:** más cerrado aún que L14. Los tres primeros planos del vídeo (L1, L14, L18)
**escalan progresivamente hacia dentro** — es una decisión deliberada: el vídeo se va cerrando
sobre él a medida que la acusación se acumula.

**EDIT NOTES:** corte seco y corto. 1.5 s, no más: es un golpe, no un plano.

---

### L19 — PAYOFF 1

**SCRIPT:** *"He tore his ACL in September 2024."*

**VISUAL INTENTION:** Evidencia central de la tesis de riesgo. Aquí **la literalidad total es
obligatoria**. Si el espectador duda de lo que vio, el vídeo pierde.

**BEST CLIP:** `youtube.com/watch?v=HgrqAWPBSTk` — *"Rodri Injury against Arsenal"*

**ANCLA:** Man City 2-2 Arsenal, **22 de septiembre de 2024**, primera parte. Vídeo dedicado al
incidente → el momento está en los primeros segundos. ⚠️ Confirmar.

**DURACIÓN:** 2.5 s · **SCORE:** 91/100 — A 38 / B 22 / C 13 / D 11 / E 7

**WHY IT WINS:** Es **el** momento, aislado, sin tener que recorrer un partido entero. Rodilla y
cara en el mismo encuadre = la evidencia se ve, no se deduce.

**BACKUP 1:** `youtube.com/watch?v=37TygKpva4o` — *"Manchester City confirm Rodri suffered
ligament injury to right…"* — **87/100.** Cobertura informativa, algo más contextual.
**BACKUP 2:** `youtube.com/watch?v=zLCEsX-fyPU` — *"Pep Guardiola confirms Rodri is out for
season with ACL injury"* — **80/100.** Rueda de prensa: credibilidad alta, energía baja. **Ojo:
sale Guardiola, que ya no es el técnico** — puede confundir tras L17b. Usar solo si no hay otra.

**RECHAZADOS:**
- `UIgT0V350Ec` *"Arsenal Fans CELEBRATE Rodri ACL injury"* → emoción invertida (celebración
  bajo frase de daño). Rechazo nº 2.
- `l9zibwaqc_s` → **es Rodrygo, no Rodri.** Rechazo nº 3. Trampa real de búsqueda: verifica el
  jugador antes de descargar.
- `z26lwGfXeyY` *"Rodri in tears… Painful Ankle Injury"* → **tobillo, no LCA.** Título
  contradictorio con el hecho verificado. Rechazo nº 17, fuente no fiable.

**CROP NOTES:** rodilla y cara en cuadro. Si el plano es muy abierto, priorizar **la cara** — la
reacción de dolor comunica más que la mecánica de la lesión.

**EDIT NOTES:** **aquí sí, cámara lenta** — es uno de los dos usos permitidos por vídeo. Speed
ramp: entrar a velocidad normal y frenar en el instante del impacto. Sin contenido gráfico
explícito (rechazo nº 18): cortar antes de planos largos de sufrimiento.

---

### L20 — PAYOFF 2

**SCRIPT:** *"He had back surgery last week."*

**VISUAL INTENTION:** Acumulación. Segundo golpe de la acusación. Emoción: fragilidad reciente.

**BEST CLIP:** Rodri **caminando o en trabajo individual**, ritmo lento, sin explosividad.

**DÓNDE BUSCARLO:** canal oficial **Man City** → nota `mancity.com/news/mens/injury-update-202627-rodri`
suele venir acompañada de material; YouTube → `Rodri training return 2026` · `Man City training
Asia tour 2026`.

**DURACIÓN:** 2.0 s · **SCORE:** 80/100 (concepto)

**WHY IT WINS:** Baja la energía justo antes del remate de L21 — el contraste hace que L21 pegue
más fuerte.

⚠️ **RIESGO DE FOOTAGE MEDIO:** la cirugía fue hace días y la recuperación es corta; puede que
**aún no exista** material suyo entrenando post-operación. Alternativas: (a) Rodri **ausente**
del grupo — plano de entrenamiento del City sin él; (b) captura del comunicado oficial del club
(verificado, existe) — pero **ya usaste captura en L11**, así que repetir el recurso debilita el
pattern interrupt; (c) archivo de Rodri caminando, sin afirmar visualmente que es post-cirugía.

**EDIT NOTES:** velocidad normal, plano largo y quieto. Es la pausa antes del remate.

---

### L21 — PAYOFF 3 (EL MEJOR CLIP DEL VÍDEO)

**SCRIPT:** *"And Barcelona are paying fifty million anyway."*

**VISUAL INTENTION:** **Remate.** Sentencia, no explica. Toda la acumulación (30 años + LCA +
espalda) desemboca aquí. Debe ser el clip más espectacular del vídeo.

**BEST CLIP:** **Camp Nou lleno**, de noche, plano amplio con movimiento de cámara — o aéreo
descendiendo sobre el estadio en pleno partido.

**DÓNDE BUSCARLO:** YouTube → `Spotify Camp Nou full stadium 2026` · `Camp Nou aerial night
match` · canal oficial FC Barcelona · `Barcelona return to Camp Nou 2026`.

**DURACIÓN:** 3.0 s — **el clip más largo del vídeo, deliberadamente**

**SCORE:** 92/100 (concepto)

**WHY IT WINS:** La escala del estadio **es** el argumento: "pagan 50 millones igual" se entiende
viendo la magnitud de la institución que lo paga. Energía alta tras dos clips bajos = pico exacto
en el 80 % del vídeo.

**BACKUP 1:** afición del Barça celebrando en la grada. **88/100.**
**BACKUP 2:** aéreo diurno del Camp Nou. **84/100** — pierde el contraste nocturno (criterio nº 13).

**RECHAZADOS:** gráficos de la cifra; Camp Nou vacío (contradice la energía del remate);
**el mismo plano de L4** (rechazo nº 11 — por eso L4 es detalle y L21 es general).

**CROP NOTES:** el vertical favorece el aéreo descendente: el estadio llena el cuadro por sí solo.
**EDIT NOTES:** **segundo y último uso de cámara lenta permitido.** Aquí funciona un speed ramp
suave de entrada. Subir el audio ambiente de estadio por encima de la mezcla durante ~0.5 s.

---

### L22

**SCRIPT:** *"He lands in Barcelona on August 12th."*

**VISUAL INTENTION:** Concreción y cuenta atrás. Bajar energía tras el remate.

**BEST CLIP:** aéreo de la ciudad de Barcelona (Sagrada Familia / línea de costa), movimiento lento.

**DÓNDE BUSCARLO:** YouTube → `Barcelona city aerial drone 4K` — abundante y libre de derechos
en muchos casos. **Búsqueda de menos de 1 minuto.**

**DURACIÓN:** 1.8 s · **SCORE:** 82/100 (concepto)

**BACKUP 1:** aterrizaje/llegada al aeropuerto de El Prat. **85/100** — más literal y más fuerte
("lands").
**BACKUP 2:** exterior del Camp Nou de día. **76/100** — riesgo de repetir L4/L21.

**RECHAZADOS:** mapas, calendarios, gráficos de fecha → prohibición absoluta.
**EDIT NOTES:** movimiento continuo. Corte al beat de "12th".

---

### L23

**SCRIPT:** *"Same day the rest of the Spain internationals come back."*

**VISUAL INTENTION:** Contexto colectivo y anclaje emocional: vuelve al Mundial sin repetir
material. Energía alta antes del descenso final.

**BEST CLIP:** `youtube.com/watch?v=PSDbDQ0MbOc` — *"FULL ARRIVAL CEREMONY: Lamine Yamal, Rodri,
Torres & Spain Return Home With FIFA 2026 Trophy"*

**ANCLA:** llegada del grupo — buscar plano con **varios internacionales en cuadro**, no
individual. ⚠️ Confirmar.

**DURACIÓN:** 2.5 s · **SCORE:** 87/100

**WHY IT WINS:** Es literalmente "los internacionales españoles volviendo", con Yamal y Rodri en
el mismo material. Y **no repite** ningún clip anterior: es celebración en Madrid, no en MetLife.

**BACKUP 1:** `youtube.com/watch?v=207l7405BBw` — *"Yamal, Rodri & Spain's World Cup Heroes
Celebrate Wildly on Open-Top Bus Parade in Madrid"* — **86/100.**
**BACKUP 2:** `youtube.com/watch?v=Pz3V9ZmaFPU` — *"Spain: World Cup winners celebrate with a
victory parade in Madrid"* — **84/100**, probablemente el más limpio (agencia).

**RECHAZADOS:** `7c6nPpwV3Mo`, `gNM9JJcY868`, `kVKo_IUzbn0` → centrados **solo en Yamal**; la
frase habla del grupo. Además varios llevan watermark de cuenta (`AD1G`, `ZO1A`, `AD1N`) →
**rechazo nº 6, verificar antes de descargar.**

**CROP NOTES:** grupo, no individuo. Vertical favorece el autobús descubierto (eje vertical).
**EDIT NOTES:** velocidad normal, corte al beat.

---

### L24

**SCRIPT:** *"Real Madrid are still trying."*

**VISUAL INTENTION:** Tensión abierta que **no se resuelve**. Prepara la pregunta final.

**BEST CLIP:** Bernabéu de noche, **iluminado y en funcionamiento** — distinto del vacío de L15 y
de la fachada de L5a.

**DÓNDE BUSCARLO:** YouTube → `Santiago Bernabeu night exterior lights 2026` · canal oficial
Real Madrid.

**DURACIÓN:** 1.8 s · **SCORE:** 84/100 (concepto)

**WHY IT WINS:** El estadio encendido = la institución sigue despierta, sigue operando. Rima con
L15 (mismo lugar) pero **invierte el estado**: vacío → encendido. Esa rima invertida es lo que
convierte tres Bernabéus en una decisión editorial en vez de en repetición.

**BACKUP 1:** luces del Bernabéu encendiéndose — símbolo de anticipación (`dimensiones.md`). **86/100.**
**BACKUP 2:** interior con focos encendidos y campo vacío. **80/100** — riesgo de parecerse a L15.

**RECHAZADOS:** dirigentes del Madrid en el palco (difícil de encontrar y de identificar);
cualquier plano ya usado.

**EDIT NOTES:** movimiento lento. **Bajar la música** aquí para preparar el silencio del cierre.

---

### L25 — LOOP

**SCRIPT:** *"Would you have taken the risk?"*

**VISUAL INTENTION:** Cerrar el círculo y **provocar el replay involuntario**. Debe rimar con el
frame 1.

**BEST CLIP:** Rodri **levantando el Balón de Oro** — mismo escenario, misma luz y misma ropa que
L1, pero **momento distinto** (L1 = compuesto, quieto; L25 = trofeo en alto).

**FUENTE:** `youtube.com/watch?v=woU8Jt1NMnU` (misma ceremonia que L1) o
`youtube.com/watch?v=Jpm-FVOKhxY`.

**DURACIÓN:** 2.5 s · **SCORE:** 90/100

**WHY IT WINS:** Conserva el Balón de Oro en el cierre — que era tu intención — **y** repara el
loop: el espectador vuelve al segundo 0 y encuentra la misma cara, mismo sitio, otra emoción.
Eso es lo que dispara el replay.

**BACKUP 1:** repetición exacta del frame de L1, congelado 0.5 s. **88/100** — loop perfecto,
pero renuncia al Balón de Oro.
**BACKUP 2:** corte a negro con el audio de la línea 1 por debajo. **85/100** — la opción más
seca, muy efectiva si el remate es de pregunta.

**RECHAZADOS:** **cualquier material nuevo que no haya aparecido antes** (Ejemplo 11); end cards;
logos del canal.

**CROP NOTES:** encuadre lo más parecido posible al de L1 — la rima visual depende de eso.
**EDIT NOTES:** corte directo, **sin música al final**. Dejar 0.3 s de negro antes del bucle para
que TikTok reinicie limpio.

---

# FASE 8 — COHERENCIA GLOBAL

## Curva de energía

```
L1  L2  L3  L4  L5a L5b L6  L7  L8  L9  L10 L11 L12 L13 L14
B   A   M   M   B   M   M   B   A   M   B   B   M   M   B

L15 L16 L17a L17b L18 L19 L20 L21 L22 L23 L24 L25
B   M   M    B    B   A   B   A   B   A   B   M
```

**Auditoría:** ninguna secuencia de tres energías iguales. Los dos puntos frágiles eran
**L13-L14-L15** (tres bajas) y **L4-L5a** (dos generales seguidos); ambos corregidos subiendo L13
a MEDIA y bajando L4 a plano de detalle.

## Alternancia de escala

Los tres primeros planos (**L1, L14, L18**) están separados por 12 y 3 clips, y **escalan
progresivamente hacia dentro**. Los tres planos generales de estadio (**L5a, L15, L21**) están
separados y son lugares distintos.

## Auditoría de repetición — LOS TRES RIESGOS REALES

| Riesgo | Líneas | Resolución |
|---|---|---|
| **Rodri con el City** ×3 | L6, L12, L16 | Tres partidos distintos + tres escalas distintas (medio-acción / medio-celebración / general) |
| **Bernabéu** ×3 | L5a, L15, L24 | Fachada / interior vacío / exterior nocturno encendido. La rima L15↔L24 es deliberada (vacío → encendido) |
| **Camp Nou** ×2 | L4, L21 | Detalle cerrado / general lleno nocturno |
| **Etihad** ×2 | L5b, L13 | Exterior día / interior lleno noche |

## Pattern interrupts

- **L11** — captura de titular + 0.3 s de negro *(clip 11 — dentro de la ventana 4-6 desde L6)*
- **L14** — 0.3 s de silencio bajo primer plano quieto *(clip 15)*
- **L19** — speed ramp a cámara lenta *(clip 20)*
- **L21** — speed ramp + subida de audio ambiente *(clip 22)*

## Reparto de fuentes

Oficial FIFA/Man City/FC Barcelona/Real Madrid ≈ 45 % · Broadcast (ITV, FOX, ESPN) ≈ 20 % ·
Prensa verificada (capturas) ≈ 5 % · Aéreos y recurso ≈ 30 %.
**Ninguna compilación de terceros en posición crítica** — solo `DK2UTrhiTww` como backup del hook,
marcado para verificar watermark.

## Cámara lenta

Exactamente **2 usos** (L19, L21), el máximo permitido, y ambos en el payoff.

---

# RESUMEN DE DECISIONES CONTRA TU PLAN ORIGINAL

| # | Tu visual | Qué hice | Por qué |
|---|---|---|---|
| 2 | España levanta la Copa | **Rodri** levanta la Copa | Era capitán y la levantó él. Ejemplo 8: el protagonista dentro de la euforia |
| 3 | Rodri recibe el Balón de Oro | Reacción del anuncio | Libera el Balón de Oro para el cierre y evita 3 planos de trofeo seguidos |
| 4 | Camp Nou | Camp Nou **en detalle** | Evita dos planos generales seguidos con L5 |
| 5 | Bernabéu (1 clip) | **Dividida en 2 clips** | 14 palabras: estirar un clip es error histórico |
| 8 | De Jong lesionado (Barça) | De Jong con **Países Bajos** | 🔴 Error factual: se lesionó en el Mundial |
| 13 | Etihad | Etihad **lleno, energía media** | Evitaba tres clips de energía baja seguidos |
| 17 | Maresca (1 clip) | **Dividida en 2 clips** | 14 palabras |
| 25 | Rodri levanta el Balón de Oro | **Igual, pero con L1 reconstruido para que rime** | Repara el loop sin perder tu intención |

---

# LO QUE NO LLEGA AL ESTÁNDAR

**Por debajo de 80 (4 líneas):**

| Línea | Score | Propuesta |
|---|---|---|
| **L8** De Jong MCL | 79 | Usar la eliminación ante Marruecos (**83**) o **reformular** a *"Barcelona lost Frenkie de Jong for months."* |
| **L9** Barcelona needed a midfielder | 77 | Cambiar a Flick observando desde la banda (**79**) — cara humana. O recortar la línea |
| **L7** Personal terms | 76 | Aceptable como contextual, pero es **la primera a eliminar** si vas a 60 s |
| **L17a** City wanted a new deal | 76 | Fusionar con L17b si el material de dirigentes no aparece rápido |

El manual permite **máximo 3 clips en el tramo 70-79**. Estoy en **4**. La salida limpia es
**recortar L7** (no aporta información nueva), lo que además te acerca a los 60 s. Si la
mantienes, el vídeo sigue siendo publicable, pero estarías una línea por encima del estándar
propio del canal — lo digo para que sea una decisión tuya y no un descuido mío.

**Riesgos de footage a resolver ANTES de grabar la voz:**

1. 🔴 **L8** — puede no existir un momento limpio de la lesión de De Jong. **Comprueba esto
   primero**: si no aparece en 3 minutos, reformula la línea.
2. 🟠 **L20** — puede no existir material post-cirugía de Rodri (fue hace días).
3. 🟠 **L4 / L21** — verificar que el material del Camp Nou corresponde al estado actual del
   estadio y no a archivo previo a las obras.
4. 🟠 **L17b** — la mayoría del footage de Maresca es **del Chelsea**. Verificar escudo y fondo.
