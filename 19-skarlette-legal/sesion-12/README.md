# sesión 12 - 19 de Junio SONIDO

+ Paso 1: agergar el archivo de sonido en mp3 o waw
+ Paso 2: Declarar y precargar el sonido,  let miSonido y fuction preload() { mi sonido= loadSound ("cancion") }
+ Paso 3: dar play al sonido

 ### ¿Como controlar el sonido?

**METODOS DE CONTROL:**
+ nombreVariable.play()
+ nombreVvariable.loop()
+ nombreVarible.stop()
+ nombreVariable.pause()
+ nombreVariable.setVolumen(valor) modifica el volumen 
+ nombreVariable.rate(valor)

**METODOS DE CONSULTA O ESTADOS DEL SONIDO** 
+ nombreVvariable.isPlaying(): devuelve true si esta activo el sonido y flase si no
+ nombreVvariable.isPaused(): devuelve true si el sonido fue congelado con pause()
+ nombreVvariable.isLooping(): devuelve true si el sonido se configura para repetir
+ nombreVariable.currentTime(): devuelve al segundo exacto en el que esta la reproduccion.
+ nombreVariable.duration() : Devuelve la duración total del archivo de audio en segundos (ej: 180.0).
+ nombreVariable.getVolume() : Devuelve el nivel de volumen actual del reproductor (un número entre 0.0
y 1.0).
+ nombreVariable.getRate() : Devuelve la velocidad de reproducción actual (ej: 1.0 para normal, 2.0 para el
doble).

## DESAFIÍO CLASE 

https://editor.p5js.org/Skarlettelegal/sketches/DejQpqi1W 

## Componentes de un sintetizador bascico

+ **El oscilador(p5.osci,,ktsor)** el motor que genera el sonido. puede tener distintas formas  de onda que cambia los sonidos:
    + 'sine' (onda senoidal ó sinusoidal: un sonido suave, como una flauta).
    + 'triangle' (onda triangular: sonido intermedio).
    + 'sawtooth' (onda de diente de sierra: un sonido brillante y rasposo, como de sintetizador de los 80).
    + 'square' (onda cuadrada: sonido retro, tipo videojuego de 8 bits).
 
+ **La Frecuencia (Frequence):** Controla qué tan rápido vibra la onda. Matemáticamente, a mayor
frecuencia, el sonido es más agudo; a menor frecuencia, es más grave. Se mide en Hertz (Hz).
+ **La Amplitud (Amplitude):** Controla la altura de la onda, lo que nosotros percibimos como el
volumen. Va de 0.0 (silencio) a 1.0 (máximo).

+ referentes en la ppt
