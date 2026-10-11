# 🤖 Entrená tu IA en 30 segundos

Juego de piedra, papel o tijera contra una IA que entrenás vos con la cámara.
La mano se detecta con [MediaPipe Hand Landmarker](https://ai.google.dev/edge/mediapipe/solutions/vision/hand_landmarker)
y los gestos se clasifican con k vecinos más cercanos (KNN), todo en el navegador.

**Probalo:** https://ramirohualpa.github.io/entrena-tu-ia/

## Cómo se usa

1. Permití el acceso a la cámara.
2. Mantené apretado ✊ Piedra, ✋ Papel o ✌️ Tijera mientras mostrás el gesto (mínimo 15 ejemplos de cada uno).
3. Apretá **¡Jugar!** y mostrá tu gesto cuando aparezca "¡Tijera!".

En computadora también funcionan las teclas `1`, `2`, `3` (grabar), `espacio` (jugar), `R` (nuevo jugador) y `C` (ver el código).

La cámara necesita https, por eso hay que abrirla desde GitHub Pages (o `localhost`) y no como archivo local.
