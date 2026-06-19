# 🌦️ ReWeather: Reviviendo Estaciones Meteorológicas

Sistema de monitoreo meteorológico basado en IoT desarrollado para la adquisición, transmisión y visualización remota de variables ambientales en tiempo real utilizando ESP32, comunicación LoRa, Firebase y una plataforma web de monitoreo.

## 🚀 Descripción del Proyecto

La recolección de datos meteorológicos en zonas rurales suele verse afectada por los altos costos de infraestructura, la baja disponibilidad de conectividad y las limitaciones de las tecnologías de comunicación convencionales.

ReWeather surge como una solución de bajo costo y arquitectura abierta que permite monitorear variables ambientales a larga distancia sin depender de redes celulares o infraestructura de internet en el punto de medición.

El sistema integra sensores meteorológicos, procesamiento embebido mediante ESP32, comunicación inalámbrica LoRa, almacenamiento de datos en la nube mediante Firebase y una plataforma web para la visualización de información en tiempo real.

---

## 🎯 Problema

La recolección de datos meteorológicos en zonas rurales se ve limitada por altos costos, baja conectividad y tecnologías de corto alcance, dificultando el monitoreo ambiental en tiempo real y la toma de decisiones basada en datos.

---

## 🎯 Objetivo General

Diseñar e implementar una estación meteorológica basada en ESP32 y tecnología LoRa para la adquisición y transmisión remota de variables ambientales en tiempo real.

---

## 🏗️ Arquitectura del Sistema

El sistema está compuesto por los siguientes módulos:

### 📡 Nodo Transmisor

Encargado de capturar las variables meteorológicas mediante sensores ambientales conectados a un ESP32.

### 📶 Comunicación LoRa

Responsable de transmitir los datos a larga distancia con bajo consumo energético y sin necesidad de infraestructura de red.

### 📥 Nodo Receptor

Recibe los datos enviados por el nodo transmisor y los procesa para su almacenamiento.

### ☁️ Firebase

Almacena la información meteorológica y permite la sincronización con la plataforma web.

### 🌐 Panel Meteorológico USB

Interfaz web desarrollada para visualizar las variables ambientales en tiempo real y consultar registros históricos.

🔗 Plataforma Web:

https://estacion-meteorologica-d167d.web.app/

---

## 🌡️ Variables Meteorológicas Monitoreadas

### Temperatura y Humedad

* Temperatura (°C)
* Humedad Relativa (%)

### Viento

* Velocidad del viento (m/s)
* Dirección del viento (grados y puntos cardinales)

### Precipitación

* Cantidad de lluvia acumulada (mm)

### Radiación Solar

* Radiación solar (W/m²)

### Radiación Ultravioleta

* Índice UV

---

## 🔌 Hardware Utilizado

### Microcontrolador

* ESP32

### Comunicación

* Módulos LoRa

### Sensores Ambientales

* Sensor de temperatura y humedad
* Sensor de velocidad del viento
* Sensor de dirección del viento
* Sensor de precipitación
* Sensor de radiación solar
* Sensor UV

---

## 💻 Desarrollo de Firmware

Se desarrolló firmware personalizado para el ESP32 encargado de:

* Adquisición de datos de sensores.
* Procesamiento y validación de mediciones.
* Empaquetado de información.
* Transmisión mediante LoRa.
* Manejo de errores y reconexión.

### Tecnologías

* C++
* Arduino IDE
* ESP32

---

## 🖥️ Plataforma Web

Se desarrolló una plataforma web para el monitoreo remoto de variables ambientales.

### Funcionalidades

* Visualización de datos en tiempo real.
* Visualización de graficas y comportamiento de los datos.
* Consulta de variables meteorológicas.
* Actualización automática de información.
* Interfaz accesible desde cualquier navegador.
* Descarga de los datos.

### Tecnologías

* HTML
* CSS
* JavaScript
* Firebase

### Capturas de Pantalla

*(Agregar imágenes de la plataforma aquí)*

---

## ☁️ Gestión y Almacenamiento de Datos

Firebase fue utilizado como plataforma de almacenamiento y sincronización de datos.

### Funciones Implementadas

* Almacenamiento de registros meteorológicos.
* Actualización en tiempo real.
* Gestión centralizada de información.
* Integración con la interfaz web.

---

## 🔧 Diseño Electrónico y PCB

Como parte del desarrollo del proyecto se diseñó una PCB personalizada para integrar los diferentes módulos electrónicos del sistema.

### Actividades Realizadas

* Diseño del esquemático electrónico.
* Selección de componentes.
* Diseño y enrutamiento de PCB.
* Verificación eléctrica.
* Generación de archivos de fabricación.

### Herramienta Utilizada

* KiCad

### Aporte Personal

El diseño completo de la PCB fue desarrollado de forma individual como parte del proyecto.

### Evidencias

* Esquemático electrónico.
<img width="658" height="853" alt="image" src="https://github.com/user-attachments/assets/b65fe41d-f548-41e4-a8db-dadb454135be" />

---

* Diseño PCB.
<img width="503" height="800" alt="image" src="https://github.com/user-attachments/assets/45d96857-3f17-4176-9202-bf4386f045bb" />

---

* Renderizado 3D de la tarjeta.
<img width="1324" height="866" alt="image" src="https://github.com/user-attachments/assets/e61801cb-9719-454a-97c3-4a56f9c55822" />

---

## 📊 Resultados Obtenidos

* Adquisición exitosa de variables meteorológicas en tiempo real.
* Comunicación estable entre nodos mediante LoRa.
* Almacenamiento seguro de datos en Firebase.
* Visualización remota de información mediante plataforma web.
* Validación del sistema como alternativa de bajo costo para monitoreo ambiental.
* Arquitectura escalable para futuras expansiones y nuevos sensores.

---

## 🛠️ Tecnologías Utilizadas

`ESP32` `LoRa` `C++` `Arduino IDE` `Firebase` `HTML` `CSS` `JavaScript` `KiCad` `GitHub`

---

