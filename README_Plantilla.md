Sensor de luz (LDR o fotorresistencia)

`Tecnología de los Sistemas de Información - Seminario Avanzado`  
`Ciclo Lectivo 2025`

## **`Integrante/s`**

- Sebastian Angel Warman
- Joaquin Sanchez Laffont

## **`Objetivo`**

Nuestro objetivo es desarrollar un sistema automatico que detecte los niveles de iluminacion ambiental mediante un sensor de luz (LDR) y encienda una luz LED cuando hay oscuridad. Este proyecto busca simular el funcionamiento de una lampara inteligente que se activa al anochecer.
## **`Descripción del Proyecto`**

El proyecto consiste en un circuito controlado por Arduino UNO que utiliza una fotorresistencia (LDR) para medir la cantidad de luz en el ambiente.
Cuando el valor de luz baja de un umbral, el Arduino enciende un LED, simulando una luz automática de habitación.
Además, los valores de luz pueden visualizarse en el Monitor Serial, permitiendo ajustar el umbral de encendido según las condiciones de iluminación del entorno.

## **`Componentes`**

Arduino UNO
LDR (Sensor de luz)
Resistencia de 10 kΩ (para divisor de tensión)
Resistencia de 220 Ω (para el LED)
LED blanco o amarillo

Cables de conexión y protoboard
LED blanco o amarillo
LDR (Sensor de luz)
## **`Requisitos`**

Software necesario:
Arduino IDE
Tinkercad (para simulación virtual)
Librerías:
No requiere librerías adicionales (usa funciones nativas de Arduino).
Hardware adicional:
Ninguno 
`Completar una vez definido el proyecto.`

## **`Etapas del proyecto`**
### Etapa 1:
Conectar la LDR en divisor de tensión con resistencia de 10 kΩ.
Conectar un LED al pin digital 8 con resistencia de 220 Ω.
Simular el circuito en Tinkercad.

### Etapa 2:
Programar la lectura del sensor con (A0).
Establecer un umbral de luz (por ejemplo, 500).
Si el valor es menor al umbral → encender LED; si es mayor → apagar.
Probar diferentes condiciones de luz y registrar valores.
## **`Extras`**
Mostrar los valores del sensor en el Monitor Serial.
Agregar un potenciómetro para ajustar manualmente la sensibilidad.
Implementar un relé en el futuro para controlar una lámpara real en lugar de un LED.
