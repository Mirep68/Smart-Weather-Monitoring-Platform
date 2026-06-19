# ESP32 LoRa32 (LILYGO T3 LoRa32)

## Descripción General

El ESP32 LoRa32 fue el componente principal utilizado en el proyecto **ReWeather: Reviviendo Estaciones Meteorológicas**. Este módulo integra un microcontrolador ESP32 de alto rendimiento junto con un transceptor LoRa, permitiendo tanto el procesamiento local de datos como la comunicación inalámbrica de largo alcance.

Gracias a esta integración, fue posible desarrollar una solución de monitoreo meteorológico capaz de capturar variables ambientales y transmitirlas de manera remota sin depender de redes celulares o infraestructura de internet en el punto de medición.

## Función Dentro del Proyecto

Dentro de la arquitectura de ReWeather, el ESP32 LoRa32 cumplió funciones críticas tanto en el nodo transmisor como en el nodo receptor.

### Nodo Transmisor

- Lectura de sensores meteorológicos.
- Procesamiento de datos ambientales.
- Validación de mediciones.
- Empaquetado de información.
- Transmisión inalámbrica mediante LoRa.

### Nodo Receptor

- Recepción de paquetes de datos.
- Verificación de integridad de la información.
- Procesamiento de datos recibidos.
- Envío de información hacia Firebase.
- Comunicación con la plataforma web.

## Importancia en el Proyecto

La selección del ESP32 LoRa32 permitió:

- Reducir costos de implementación.
- Simplificar la arquitectura electrónica.
- Disponer de conectividad Wi-Fi y LoRa en un solo dispositivo.
- Implementar comunicaciones de largo alcance.
- Facilitar el desarrollo del firmware.
- Mejorar la escalabilidad del sistema.

Este componente fue fundamental para lograr una comunicación estable entre estaciones meteorológicas ubicadas en zonas con baja conectividad y la plataforma de monitoreo remoto.

## Características Principales

- Microcontrolador ESP32 de doble núcleo.
- Comunicación LoRa integrada.
- Conectividad Wi-Fi.
- Conectividad Bluetooth.
- Bajo consumo energético.
- Múltiples interfaces de comunicación (UART, SPI, I2C).
- Amplia capacidad de procesamiento para aplicaciones IoT.
- Compatible con Arduino IDE y ESP-IDF.

## Aplicaciones

- Internet de las Cosas (IoT).
- Telemetría.
- Monitoreo ambiental.
- Agricultura inteligente.
- Redes de sensores inalámbricos.
- Sistemas de monitoreo remoto.

## Recursos Oficiales

### Página Oficial del Producto

https://lilygo.cc/products/lora3 

### Documentación y Datasheet

La documentación técnica, especificaciones completas y recursos de desarrollo pueden consultarse en la página oficial del fabricante.

## Evidencia en el Proyecto

<img width="1000" height="850" alt="image" src="https://github.com/user-attachments/assets/ceb4f898-084a-45cc-9e53-1523d19a94bd" />

---

<img width="600" height="450" alt="image" src="https://github.com/user-attachments/assets/2e0b4f73-eb68-4956-92d8-ddc91f594008" />


## Tecnologías Relacionadas

- ESP32
- LoRa
- C++
- Arduino IDE
- Firebase
- IoT
- Telemetría
- Sistemas Embebidos
