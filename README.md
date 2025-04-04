
https://github.com/maridilo/ExamenRedes2.git

# Examen de Redes II – En Busca de la Red Perdida

## Parte I: Conceptos y Teoría

### 1. El Mural de las Siete Capas
Te adentras en la sala principal del templo y descubres un gran mural compuesto por siete franjas horizontales superpuestas, decoradas con símbolos y jeroglíficos. Cada franja representa un nivel diferente en un ritual de comunicación. Los sabios de esta civilización entendían que un mensaje debía pasar por varias etapas desde su origen hasta su destino, refinándose o traduciendo su forma en cada nivel de la pirámide comunicativa. 
#### Pregunta: 
¿Qué representa el mural de las siete capas en términos de las redes de comunicación modernas? Identifica brevemente cada capa y explica cómo se relaciona este antiguo “modelo” con el proceso de comunicación de datos actual.


El mural de las siete capas en términos de las redes de comunicación modernas representa el modelo OSI (Open Systems Interconnection), que describe como los datos viajan desde un dispositivo emisor hasta un receptor en una red de comunicaciones. Cada capa del modelo OSI realiza funciones específicas que ayudan a encapsular, transportar, interpretar o entregar correctamente la información.
Este modelo divide el proceso de comunicación en siete capas jerárquicas, desde el software mas cercano al usuario hasta el hardware físico de transmisión.
Estas capas son:
![DIAGRAMA](./imagen_2025-04-04_161130137.png)

---

   
### 2. Los Dos Pergaminos del Mensajero
En una cámara oculta encuentras dos pergaminos polvorientos. El primero describe el Ritual del Mensajero Confiable: antes de entregar un mensaje, el mensajero realiza un saludo de tres pasos con el receptor para asegurarse de que ambos estén listos, luego entrega el mensaje y espera una confirmación de recibido. Si la confirmación no llega, reintenta el envío.
 El segundo pergamino narra el Ritual del Mensajero Veloz: un mensajero que sale disparado a entregar mensajes sucesivos sin aviso previo ni asegurarse de la recepción, cubriendo la mayor distancia en el menor tiempo, aunque a veces los mensajes se pierdan en el camino.
#### Pregunta:
Interpreta los dos rituales descritos. ¿A qué protocolos de comunicación actuales equivalen el mensajero confiable y el mensajero veloz? Compara sus características, explicando las ventajas y desventajas de cada enfoque en redes modernas.


Estos dos rituales descritos se tratan de dos protocolos de comunicación actuales: el TCP (Transmission Control Protocol) y UDP (User Datagram Protocol).

El que equivale al mensajero confiable es el protocolo TCP. Este ritual descrito se trata del funcionamiento del TCP, orientado a la conexión fiable. El saludo de tres pasos corresponde al proceso de establecimiento de conexión conocido como “three-way handshake”, que asegura que tanto el emisor como el receptor estén listos para la comunicación. Además, garantiza la entrega: si no se recibe una confirmación (ACK) del mensaje, lo retransmite.

#### Características:
-	Conexión Orientada: requiere establecer una conexión antes de enviar los datos.
-	Entrega garantizada: los datos llegan completos, en orden y sin duplicados.
-	Control de flujo: ajusta la transmisión para no saturar la red.
-	Recursos: más pesado por su mayor uso del CPU y ancho de banda.
  
#### Ventajas:
-	Fiabilidad: ideal para aplicaciones donde perder datos no es viable (ejemplo: navegación web, correo electrónico, transferencia de archivos).
-	Orden y control: mantiene una secuencia correcta de los paquetes.
  
#### Desventajas:
-	Mayor latencia: al establecer la conexión y las confirmaciones.
-	Sobrecarga de red: por el control de errores, ACKs y retransmisiones.

El mensajero veloz equivale al protocolo UDP, que no es orientado a conexión. El mensajero envía los datos sin establecer ningún contacto previo, ni esperar confirmación. Su objetivo es la velocidad y eficiencia, aun a costa de que algunos mensajes puedan perderse en el camino.

#### Características:
-	No necesita conexión: se envía sin verificar que el receptor esté disponible.
-	No garantiza la entrega ni el orden: los datos pueden perderse en el camino o llegar desordenados.
-	Bajo consumo de recursos: porque no tiene mecanismos de corrección o confirmación.
  
#### Ventajas:
-	Rápido y con baja latencia: perfecto para transmisiones en tiempo real.
-	Menos sobrecarga: útil en redes con limitaciones en el ancho de banda.
  
#### Desventajas:
-	No es fiable: si un paquete se pierde, no se recupera automáticamente.
-	Sin control de flujo: posibilidad de saturar el receptor si hay demasiada información.


---
   
### 5. El Enigma de las Subredes

---
   
### 7. La Encrucijada de las Rutas

---
   
### 9. El Guardián de la Máscara Única

---

## Parte II: Práctica con Cisco Packet Tracer
### Ejercicio 1 – La Ruta Perdida entre Dos Reinos

- Descripción
  
- Topología
  
- Direccionamiento IP
  
- Comandos configurados
  
- Capturas de configuración
  
- Pruebas de conectividad
  

### Ejercicio 2 – La Ciudad de las Redes Aisladas
- Descripción
  
- Topología
  
- VLANs y subinterfaces
  
- Comandos configurados
  
- Capturas de configuración
  
- Pruebas de conectividad
  
