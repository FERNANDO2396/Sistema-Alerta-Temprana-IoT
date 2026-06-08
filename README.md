# Sistema-Alerta-Temprana-IoT
Sistema de monitoreo y alerta temprana para motores usando ESP32, MQTT y Node-RED.
# Sistema de Alerta Temprana para Motores usando IoT

## Descripción del Proyecto

Este proyecto implementa un sistema de monitoreo y alerta temprana para motores utilizando tecnologías IoT. El sistema emplea un ESP32 para adquirir datos de temperatura mediante un sensor DHT22. La información es enviada mediante MQTT hacia Node-RED para su visualización y procesamiento.

Cuando la temperatura supera los límites establecidos, el sistema activa indicadores visuales y sonoros para alertar sobre posibles condiciones de riesgo.

## Objetivos

* Monitorear la temperatura de un motor en tiempo real.
* Transmitir datos mediante MQTT.
* Visualizar la información en un Dashboard de Node-RED.
* Generar alertas automáticas cuando se detecten temperaturas elevadas.
* Aplicar conceptos de IoT e Industria 4.0.

## Tecnologías Utilizadas

* ESP32
* MQTT
* Mosquitto Broker
* Node-RED
* Dashboard Node-RED
* Wokwi

## Componentes Utilizados

* ESP32
* Sensor DHT22
* LED Verde
* LED Amarillo
* LED Rojo
* Buzzer
* Motor DC simulado

## Funcionamiento

1. El sensor DHT22 mide la temperatura.
2. El ESP32 envía los datos mediante MQTT.
3. Node-RED recibe y procesa la información.
4. El Dashboard muestra la temperatura en tiempo real.
5. Dependiendo del valor de temperatura se activan indicadores de estado y alertas.

## Archivos del Repositorio

* Código fuente del ESP32
* Flujo de Node-RED (flow.json)
* Simulación Wokwi
* Informe del proyecto (PDF)
* Presentación del proyecto

## Resultados

El sistema permite detectar de forma temprana condiciones anormales de temperatura, facilitando el monitoreo y la prevención de posibles fallas.

## Autor

Luis Fernando Llumiquinga
Colegio Alfonso del Hierro La Salle
Quito - Ecuador
