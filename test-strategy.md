1. Error en la generacion numero aleatorio
Error: El numero estaba siendo limitado a 9. Ademas, no estaba redondeado a entero por lo que se generaban numeros decimales
Solucion: se corrigo utilizando  Math.floor(Math.random() * 101) para generar un numero del 0 al 100 y se redondeo el resultado

2. Error en la cantidad de intentos
Error:El numero de intentos estaba siendo lmitado a 5 pero la descripcion del problema indicaba que eran 10
Solucion: Se actualizo la constante ATTEMS a 10

3. Error en la seleccion de elementos
Error: Al seleccionar el elemento guessSubmit faltaba un punto lo que causaba error en la seleccion
Solucion: Se agrego el punto antes de guessSubmit

4. erro en la comparacion de tipos de datos
Error: La comparcion userGuess === randomNumber comparaba un string contra un int
Solucion utilizada: Se convirtio la entrada del usuario a un numero entero. 
Posible solucion: Cambiar a userGuess == randomNumber para que compare el dato puro sin incluir tipos

5. Errores en los mensajes y colores
Error: Los mensajes y los colores en los mensajes no coincidian con la logica del juego. Se mostraba un mensaje de perdida cuando el usuario adivinaba el numero
Solucion: SE ajustaron los mensajes para que coincidan con la logica del juego. Se cambio a verde para el mensaje de vicotoria

6. Error en el evento addEventListener
Error: En la configuracion del evento click para el botón de reinicio, la sintaxis de addEventListener estaba incorrecta
Solucion: Se corrigio la sintaxis de addEventListener para el boton de reinicio

7. Error en la generación del nuevo número aleatorio al reiniciar
Error: La generacion del nuevo numero aleatorio al reiniciar el juego era incorrecta
Solución: se corrigo utilizando  Math.floor(Math.random() * 101) para generar un numero del 0 al 100 y se redondeo el resultado