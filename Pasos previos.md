# Reto 1: Encendido alternativo de dos diodos led.

Esta practica se dedica a conseguir que dos diodos led se enciendan alternativamente, uno encendido y otro apagado, y despues de un tiempo asignado estos dos hagan lo opuesto, y asi sucesivamente.

[Pincha aquí para ver la prueba en tinkercad](https://www.tinkercad.com/things/jdIYAWvcs1k-grand-elzing-migelo/editel?returnTo=https%3A%2F%2Fwww.tinkercad.com%2Fdashboard)


Prueba en tinkercad:
<p align="center">
<img src="Imágenes/Placa.PNG" width="400" height="400" />
</p>


Explicación del Código:
<p align="center">
<img src="Imágenes/Codigo.PNG" width="400" height="400" />
</p>


El void setup es donde se declaran las variables. Los pines 2 y 3 están marcados como output.

El void loop es donde se ejecuta el código se repite de forma infinita.

El pin 3 se enciende (HIGH) mientras que el 2 se apaga (LOW).

El delay hace una espera antes de seguir, en este caso la espera es de 400 milisegundos,

El pin 3 ahora se apaga (LOW), mientras que el 2 ahora es el encendido (HIGH)

Otro delay de 400 milisegundos, y el loop se repite.
