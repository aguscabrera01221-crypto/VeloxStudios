# VeloxStudios

Sistema de selección visual para un canal faceless de football commentary en inglés
(TikTok / YouTube Shorts / Instagram Reels).

Convierte una intención narrativa en una **shotlist**: qué imagen va sobre cada línea del guion,
dónde encontrarla, cuánto dura y por qué gana a los candidatos descartados.

## Uso

Abre Claude Code en la raíz del repo, pega el guion y pide las visuales. `CLAUDE.md` se carga
solo; la skill `visual-selection` se activa cuando la petición trata de footage, clips, b-roll
o shotlists. Para forzarla: `/visual-selection`.

## Estructura

```
CLAUDE.md                                  Contexto permanente: rol, canal, formatos,
                                           principio rector, prohibiciones
.claude/skills/visual-selection/
  SKILL.md                                 Procedimiento en 6 pasos
  references/
    dimensiones.md                         13 dimensiones; literal vs no literal
    criterios.md                           Jerarquía Nivel 1-5; resolución de conflictos
    scoring.md                             Scoring 0-100 + 18 rechazos automáticos
    ejemplos.md                            11 ejemplos — el estándar de razonamiento
    retencion.md                           Ritmo, curva de energía, tipos de footage
    fuentes.md                             Jerarquía de 9 fuentes y cómo buscar
    guion.md                               Guion, audio, miniaturas, errores históricos
  templates/
    shotlist.md                            Plantilla de entrega
```

## Reglas que no se negocian

- **El guion dice el dato. La imagen dice la emoción.** Nunca lo mismo dos veces.
- Nunca sacrificar coincidencia narrativa por estética.
- Mínimo 4-6 candidatos comparados por frase.
- Una visual que no se encuentra en menos de 3 minutos no es una visual válida.
- Sin gráficos, sin tarjetas de datos, sin marcadores estáticos, sin intro, sin footage de IA
  que simule un evento real.
- Verificación factual de toda premisa antes de producir.
