# sesión 12 - 19 de mayo SONIDO

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
