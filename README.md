# Protegiendo el Ñembi Guasu

Juego de navegador en pixel art (vista cenital 3/4) sobre un día de trabajo de un guardaparque en el bosque seco: patrullar, detener la tala ilegal y prevenir y combatir incendios forestales.

**▶ Jugar:** https://nativamlopez.github.io/protegiendo-el-nembi-guasu/

## Cómo se juega

Una jornada va de las 06:00 a las 20:00 y dura unos 4 minutos reales. Empieza con un informe de la mañana (viento, sequía y puntos de calor) y termina con un resumen: bosque salvado, incendios controlados, denuncias presentadas y confianza de la comunidad.

- **Patrulla:** sigue el humo, el sonido de las motosierras y los avisos de radio.
- **Tala ilegal:** encuentra el claro talado, documéntalo con la cámara y presenta la denuncia en el campamento base **Ñembi Misi**.
- **Incendios:** el fuego avanza con el viento. Apágalo con agua (cargas limitadas) o abre un cortafuego.
- **Comunidad:** conversa con los vecinos. Con más confianza, te avisan de las talas.

## Controles

| Teclado | Pantalla táctil | Acción |
|---|---|---|
| WASD / Flechas | Joystick | Caminar |
| E | Botón E | Usar herramienta, hablar, recargar |
| Mantener E | Mantener botón E | Documentar tala o abrir cortafuego |
| 1 · 2 · 3 | Botones 1 · 2 · 3 | Cámara · Agua · Rastrillo |
| M | Sonido | Silenciar |
| P / Esc | Pausa | Pausa |

En computadora, haz clic sobre el juego si el teclado no responde. En celular se juega mejor en horizontal.

## Detalles técnicos

Todo el juego está en un solo archivo, `index.html`: HTML y JavaScript sin bibliotecas ni imágenes externas. El pixel art se dibuja con código en un `<canvas>` y los sonidos se generan con la Web Audio API.
