# Algoritmos y Diagramas de Flujo

## Algoritmos

### ¿Qué es un Algoritmo?

Son una serie de pasos bien definidos que siguen un orden secuencial con el objetivo de resolver un problema o planteamiento de una manera eficiente y lo mas corta posible.  
Estos algoritmos se van optimizando con el análisis.

### ¿Cómo construir un algoritmo?

Ejemplo:  
"Quiero encender la luz de la habitación donde estoy en este momento"

Debemos identificar cual es objetivo y cuales son los recurso con los que cuento, para lograr esto se requiere de un proceso de análisis.

Se tiene que leer la situación varias veces cuanto sea posible

No siempre vamos a tener un nivel de detalle lo suficientemente claro para que todos los recursos estén dados en un requerimiento, se tendrá que asumir en algunos casos o agregar las condiciones para que todo pueda darse según el resultado que queremos obtener.

Aquí se dividió el problema en partes mas pequeñas

Hay una luz la cual se puede encender

La luz debe estar apagada, validad si esta encendida
si esta encendida terminar el proceso
si esta apagada presionar el boton
si la luz se enciende terminar el proceso 
si no se enciende revisar el boton
si el boton esta bien revisar la corriente electrica
si no hay corriente electrica llamar al servicio de suminstro de energia
si no esta bien reparar boton y presionar de nuevo el boton
si la luz enciende terminar el proceso 


## Diagramas de flujo

Conjunto de simbolos y de elementos que nos permiten represetnar los pasos de un proceso.

Simbolos mas utilizados:

Óvalo horizontal: Inicio de un flujo nos indica tambien el fin

Rombo: La decision que se toma ante una sentencia o condicion

Rectangulo: nos permite identificar una operacion, algoritmo, proceso o mensaje

Flecha: conexion entre elementos, muestran el direccionamiento del proceso


# Reto 1: ¿Hay dinero en el cajero electrónico?

Inicio  
Estoy en el cajero?  
si = solicitar cantidad de dinero y pasar a linea 7  
no = ir al cajero y regresar a linea 4  
Hay dinero en el cajero?  
si = nos da el dinero  
no = volver a solicitar regresa a linea 5  
fin  

![diagrama-de-flujo](imagenes/Untitled%201.webp)

<br>
<br>

Optimizar este proceso.

![optimizado](imagenes/cajero.webp)
