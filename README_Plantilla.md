Sensor de Ambiente Inteligente

`Tecnología de los Sistemas de Información - Seminario Avanzado`  
`Ciclo Lectivo 2025`

## **`Integrante/s`**

- Sebastian Angel Warman
- Joaquin Sanchez Laffont

## **`Objetivo`**

Nosotros queremos desarrollar un sistema de iluminación inteligente que detecte los niveles de luz ambiente mediante un sensor LDR y que active automáticamente un LED cuando hay oscuridad. Además, nuestro sistema permite cambiar el modo de funcionamiento con un botón (modo fijo, parpadeo o alarma) y ajustar la intensidad lumínica utilizando un potenciómetro.
## **`Descripción del Proyecto`**
El proyecto consiste en un circuito controlado por un Arduino UNO que utiliza una fotorresistencia (LDR) para medir la iluminación del ambiente. Si el nivel de luz baja de un umbral determinado, el Arduino enciende un LED simulando una lámpara automática.

## **`Componentes`**
Arduino UNO
LDR (sensor de luz)
Potenciómetro
Botón pulsador
LED 
Buzzer
Resistencia de 10 kΩ 
Resistencia de 220 Ω 
Protoboard
Cables de conexión
## **`Requisitos`**

Software necesario:
Arduino IDE
Tinkercad 
Librerías:
No requiere librerías adicionales
Hardware adicional:
Ninguno 
`Completar una vez definido el proyecto.`

## **`Etapas del proyecto`**
### Etapa 1:
Conectar la LDR en divisor de tensión con resistencia de 10 kΩ
Conectar un LED al pin digital 8 con resistencia de 220 Ω
Simular el circuito 

### Etapa 2:
Ajustar correctamente el umbral de luz
Aplicar antirrebote al botón para que no se pulse muchas veces
Corregir el funcionamiento 
realizar pruebas
## **`Extras`**
Mostrar los valores del sensor en el Monitor Serial.
Agregar un LED aparte que se prenda cuando el sistema detecta que está “en modo alarma”.
Probar cuánto tarda en reaccionar el sistema y ver si conviene agregar un delay() para que no sea tan brusco el cambio.
