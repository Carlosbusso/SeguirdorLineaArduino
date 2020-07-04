# Seguidor de Línea con Arduino UNO

Este repositorio contiene los códigos en Arduino para la programación de un móvil seguidor de línea con Arduino UNO realizado por Carlos Evangeliste en el canal de YouTube EmicTron.

El link del video sobre el tutorial de desarrollo e implementación de este móvil es: 
https://www.youtube.com/watch?v=g83Z-Ymjf7w&t=2s

## Carpeta Codigo_Lectura_CNY70

Contiene el código de programación de prueba de la lectura de sensores.

NOTA: Existe una mala referencia en el video con respecto a la conexión de los sensores.

el único problema es la referencia para hacer la conexión de los sensores, todo lo demás está bien, en el vídeo tomo como referencia para conectar los sensores el color de sus leds, pero eso solo es válido para esa marca que yo usé.  

En general se debe tomar como referencia el datasheet del sensor para hacer la correcta conexión del sensor, para cualquier marca de CNY70 se debe hacer la conexión como te envió en las fotos adjuntas donde se tiene que poner la marca al lado derecho, conectado de esta forma debe funcionar bien los sensores. 

Guíate con el color de los cables conectados al sensor. Primero haz la conexión de esta manera y luego tus sensores ya deben marcar 1 y 0 con eso puedes continuar con el armado del carro.
Saludos.

### *Te dejo el siguiente vídeo para que lo puedas revisar y tener una mejor referencia sobre la conexión:
https://www.youtube.com/watch?v=A7AVA0E4U4Q

## Carpeta Codigo_Seguidor_de_Linea

Contiene el código final de programación del seguidor de línea. Este debe realizarse una vez los sensores estén probados y funcionando correctamente.
