# TID
Ramo Taller de Investigación Dirigida de la Universidad Adolfo Ibáñez, realizado en conjunto con el profesor Andrés Peters Rivas sobre programación de microcontroladores ESP32-S3
con dispositivos de interfaz humana.  
Integrantes:
- Gabriel Chomalí
- Gabriel Basualto
  
## Objetivo general
Desarrollar código y pruebas para configurar la comunicación entre un dispositivo microcontrolador ESP32-S3 y dispositivos HID como mouse, joystick o teclado.

## Objetivos específicos
- Revisar estado del arte sobre programación de microcontroladores para interacción con dispositivos HID
- Aprender programación de ESP32-S3 en ESP-IDF
- Crear códigos para la interacción entre dispositivo HID y placa de desarrollo basada en un ESP32-S3.
- Realizar pruebas de funcionamiento.

### Bitacora
Martes 19 de Marzo:
Primera reunion con el profesor donde organizamos los objetivos del TID y el paso a paso que deberiamos completar durante el desarrollo de este.

Jueves 18 de Abril:
Tercera reunion con el profesor para soldar los microcontroladores S3 para poder realizar pruebas con estos en el futuro.

Sabado 11 de Mayo:
Se creo el repositorio de Github, para poder trabajar en conjunto y tener un lugar para guardar los codigos junto con una bitacora para tener la informacion organizada de los pasos que se fueron desarrollando durante el TID.

Martes 14 de Mayo:
Durante la mañana se uso el metodo de integración de Arduino en Espresiff para comprobar los codigos creados por el grupo anterior, comprobar si estos se adaptan bien o requieren modificación.
Se inicia un proceso de ajuste del editor de código utilizado para ejecutar los archivos (Visual Studio Code), en donde, utilizamos la extensión del ide del fabricante de los chips (ESP-IDF). 
Así, se podrían ejecutar los códigos sin ningún tipo de manipulación en el nuevo entorno.

Viernes 17 de Mayo:
Luego de reiterados intentos por ejecutar los códigos en el nuevo entorno sin éxito debido a problemas de instalación del PATH de la extensión en Visual Studio, se realizó una reunión entre los participantes
para replantearse objetivos relacionados a la instalación del entorno de Espressif. Luego, se llegó a la conclusión de que utilizando este método de migración, iba a resultar imposible añadir nuevas
características al prototipo, ya que el código seguiría estando bajo el ecosistema Arduino y no serían aprovechadas las nuevas características que ofrece ESP-IDF.

Sábado 18 de Mayo:
Se define que se comenzará a utilizar la APP del fabricante directamente instalada en el sistema operativo para realizar una migración manual, trasladando arquitectura y librerías utilizadas en el código.

Lunes 20 de Mayo:
Se realiza instalación de ESP-IDF en el OS y paralelamente la transcripción de los primeros códigos.

Miércoles 29 de Mayo:
Revisión de avances y discusión junto al profesor. Definición de pasos a seguir para cuando se termine la migración del código. Fijación de fecha para probar nuevo código en el proyecto físico.





