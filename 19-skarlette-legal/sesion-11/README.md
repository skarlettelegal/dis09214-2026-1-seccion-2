# sesión 11 - 12 de junio Diseño Responsivo

+ Paso 1, crear un lienzo con dimensiones dinamicas, **CreateCanvas(windowWhidth, windowHeight)**
+ Paso 2, crear un evento, function windowResized()
+ redimensiona el canvas
+ Paso 3, usar valores relativos
+ Paso 4, incluir un factor de referencia
  referencia: min(width,height)
  observa el ancho y el alto del canvas
+ Paso 5 usar translate - push y pop.
  Consejo para proyectos complejos, en ligar de hacer matematicas complejas en cada rect() o ellipse() usamos translate()
  para mover el origen del mundo
  ocupar el translate() para trasladar la posicion de la figura, 

  ### Referencias
  Para variar el tamaño en el lienz, que va al minimo entre height y el whidth

  ## Desafio
  Hacer la bandera chilena en p5

  https://editor.p5js.org/Skarlettelegal/sketches/SIqUL
https://editor.p5js.org/Skarlettelegal/sketches/SIqULjkiS

  # SUBIR IMAGENES
+ Paso 1, subir la imagen a p5
    agregar archicos, poner nombres, hacer carpetas para que sea mas ordenado
+ Paso 2, Declarar y precargar la imagen
  ***fuction preload()**
  creamos una variable de la imagen **let miImagen**
+Paso 3 Dibujar y dimensionar en el draw
https://editor.p5js.org/Skarlettelegal/sketches/XPDiMU48U

# Modificar pixeles

+ get (x,y) -  "el ojo"
+ set(x,y,nuevoColor) - "el pincel"
+ updatePixeles() - "Actualización"

  
