# 🤖 Entrená tu IA en 30 segundos

Juego de piedra, papel o tijera contra una IA que entrenás vos con la cámara.
La mano se detecta con [MediaPipe Hand Landmarker](https://ai.google.dev/edge/mediapipe/solutions/vision/hand_landmarker)
y los gestos se clasifican con k vecinos más cercanos (KNN), todo en el navegador.

**Probalo:** https://ramirohualpa.github.io/entrena-tu-ia/

## Cómo se usa

1. Permití el acceso a la cámara desde el cartel inicial (después aparece un tutorial corto; se vuelve a ver con **❓ Ayuda**).
2. Mantené apretado ✊ Piedra, ✋ Papel o ✌️ Tijera mientras mostrás el gesto (mínimo 15 y hasta 500 ejemplos de cada uno).
3. Apretá **¡Jugar!** y mostrá tu gesto cuando aparezca "¡Tijera!".
4. Si la IA quedó mal entrenada, **🧹 Reiniciar entrenamiento** borra los ejemplos sin tocar el puntaje.

La cámara se apaga sola al cambiar de pestaña o de app y se vuelve a prender al regresar.

En computadora también funcionan las teclas `1`, `2`, `3` (grabar), `espacio` (jugar), `B` (reiniciar entrenamiento), `R` (nuevo jugador) y `C` (ver el código).

La cámara necesita https, por eso hay que abrirla desde GitHub Pages (o `localhost`) y no como archivo local.

![QR para abrirla en el teléfono](qr-entrena-tu-ia.png)
