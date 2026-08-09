---
name: visual-selection
description: Selecciona footage de archivo para un guion de football commentary faceless (shorts verticales 9:16, documental largo o edits sin narración). Úsala siempre que haya que decidir qué imagen va sobre cada línea de un guion, armar una shotlist, revisar una selección visual ya hecha, o cuando el usuario pegue un guion y pida visuales, clips, b-roll, footage o "qué pongo aquí". Cubre análisis narrativo de cada frase, hipótesis visuales, búsqueda y comparación de candidatos, scoring 0-100, reglas de rechazo y curva de retención.
---

# Selección visual — football commentary

Antes de nada lee `CLAUDE.md` en la raíz del proyecto: rol, canal, formatos, prohibiciones
y principio rector. Este documento es el **procedimiento**; los detalles viven en
`references/`.

---

## Procedimiento

### Paso 0 — Verificar el guion antes de tocar imagen

1. **Verificación factual** de toda premisa (fichaje, resultado, declaración). Fuentes
   fiables: ESPN, Sky Sports, The Athletic, Fabrizio Romano, medios oficiales. Si no se
   verifica: dilo y propón reformular como pregunta abierta.
2. **Auditoría de escritura.** Marca las líneas que van a producir visuales débiles por
   construcción, antes de buscar nada:
   - Frases de transición (*"but here's the part nobody's talking about"*, *"now here's
     why that matters"*) → **prohibidas**. Son de formato largo; en vertical son puntos de
     fuga. Señálalas y propón cortarlas.
   - Líneas con más de una idea → deben partirse.
   - Líneas de más de ~8 palabras → probablemente necesitan 2 clips, no uno estirado.

   Referencia de ritmo: ~2.5 palabras/segundo. Un short de 60 s ≈ 150-180 palabras ≈
   22-26 líneas ≈ **22-26 clips**. 60 segundos exactos es el objetivo (umbral de monetización).

3. **Mapa de funciones.** Antes de buscar, etiqueta cada línea: hook / evidencia /
   escalada / giro / payoff / loop / contexto. Decide ya dónde van tus dos mejores clips:
   **el segundo mejor en el hook, el mejor en el payoff (75-85 % del video)**. Nunca los
   gastes en frases intermedias.

### Paso 1 — Leer la frase en 13 dimensiones

No busques nada todavía. Analiza internamente: significado literal, emoción dominante,
tensión, intención narrativa, contexto futbolístico, personaje protagonista, reacción vs
acción, anticipación, payoff, simbolismo, continuidad, energía y función psicológica.

→ Desarrollo completo en `references/dimensiones.md`, incluida la decisión
**literal vs no literal** (cuándo cada uno).

### Paso 2 — Formular hipótesis visuales por escrito

Para cada línea, **escribe 2-3 hipótesis antes de buscar**:

- una **literal** (lo que la frase menciona),
- una de **reacción** (la consecuencia o la cara de quien lo recibe),
- una **simbólica** (estadio, túnel, camiseta, luces, ausencia).

Prohibido buscar antes de tener la hipótesis escrita. Buscar primero contamina el criterio
con lo que el algoritmo te sirva.

### Paso 3 — Buscar candidatos

Mínimo **4-6 candidatos reales por frase**, repartidos entre hipótesis. Nunca busques solo
por nombre de jugador: busca por **partido + competición + año**, por **incidente**, por
**momento** (`tunnel`, `full time reaction`, `press conference`, `trophy lift`).

→ Jerarquía de fuentes y queries prácticas en `references/fuentes.md`.

Regla dura: si una visual no es encontrable en **menos de 3 minutos**, no es una visual
válida. Cámbiala o marca la línea para reformular.

### Paso 4 — Filtrar y puntuar

1. Aplica los **eliminatorios de Nivel 1** y las **18 reglas de rechazo automático**. Lo que
   falle se descarta **sin puntuar**.
2. Puntúa los supervivientes 0-100 (A 40 / B 25 / C 15 / D 12 / E 8).
3. **Regla anti-espectáculo:** un clip con **A ≤ 25/40 no puede seleccionarse aunque su
   total supere 85.** La calidad técnica no compra alineación narrativa.
4. Compara frame a frame los dos finalistas antes de cerrar.

→ Criterios jerarquizados en `references/criterios.md`; scoring, tramos y rechazos en
`references/scoring.md`.

Umbrales: objetivo **90-94** en frases importantes; **80-89** aceptable en evidencia y
escalada; **70-79** máximo 3 clips por video y solo en contexto/transición; **<70** se
rechaza y se sigue buscando.

### Paso 5 — Validar la secuencia completa

Un clip correcto en aislamiento puede ser un error en la línea de montaje. Antes de
entregar, revisa la lista entera:

- **Curva de energía:** nunca tres clips de la misma energía seguidos. Patrón sano
  ALTA – MEDIA – ALTA – BAJA – ALTA – MEDIA…
- **Escala de plano:** nunca dos primeros planos ni dos planos generales consecutivos.
- **Continuidad:** sin saltos día→noche→día sin motivo, sin paleta repetida sin motivo.
- **Pattern interrupt** cada 4-6 clips.
- **Ningún clip repetido**, salvo el loop final o refuerzo deliberado de la evidencia central.
- **Ningún clip que queme el payoff antes de tiempo.**
- **El último clip reconecta con el primer frame** (loop).

→ Sistema completo en `references/retencion.md`.

### Paso 6 — Entregar

Formato exacto por línea:

```
LÍNEA: "[texto exacto del guion]"
FUNCIÓN: [hook / evidencia / escalada / giro / payoff / loop / contexto]
EMOCIÓN: [una palabra]
HIPÓTESIS ELEGIDA: [literal / reacción / simbólica]
VISUAL: [descripción concreta: quién, qué hace, escala de plano, contexto]
DÓNDE BUSCARLO: [query exacta + plataforma]
DURACIÓN: [segundos]
SCORE ESTIMADO: [n/100]
RECHAZADOS: [qué descartaste y por qué]
```

Cierra la entrega con:

- **Curva de energía** de la secuencia (una línea: `A M A B A M A B…`).
- **Riesgos de footage:** líneas cuya visual quizá no exista, para ajustar guion antes de producir.
- **Líneas por debajo de 80** y qué propones para cada una.

Plantilla lista para copiar: `templates/shotlist.md`.

---

## Qué NO hacer

- Escoger el primer resultado de una búsqueda.
- Conformarte con un clip "aceptable" sin haber agotado la búsqueda.
- Asumir que alta resolución equivale a buen clip.
- Buscar únicamente por nombre de jugador.
- Decidir sin haber comparado al menos 4 candidatos reales.
- Afirmar que has encontrado o analizado un clip que no has verificado.
- Inventar detalles de un clip (ángulo, expresión, minuto) que no hayas comprobado.
- Proponer una visual que no exista o que exija más de 3 minutos de búsqueda.
- Proponer reacciones secundarias imposibles de encontrar (*"el entrenador rival negando
  con la cabeza"*, *"los jugadores del banquillo protestando"*): bloquean la producción.
- Estirar un clip para rellenar tiempo, o cubrir una frase de 20 palabras con una sola visual.

---

## Referencias

| Archivo | Contenido |
|---|---|
| `references/dimensiones.md` | Las 13 dimensiones; literal vs no literal |
| `references/criterios.md` | Jerarquía de criterios Nivel 1-5; resolución de conflictos |
| `references/scoring.md` | Scoring 0-100, tramos, anti-espectáculo, 18 rechazos automáticos |
| `references/ejemplos.md` | 11 ejemplos de razonamiento — el estándar exigido |
| `references/retencion.md` | Ritmo, curva de energía, pattern interrupts, tipos de footage |
| `references/fuentes.md` | Jerarquía de 9 fuentes y cómo buscar en cada una |
| `references/guion.md` | Escritura de guion, audio, miniaturas, errores históricos |
| `templates/shotlist.md` | Plantilla de entrega |

Antes de tu primera selección en una sesión, lee `references/ejemplos.md`: fija el nivel
de razonamiento esperado mejor que cualquier instrucción abstracta.
