# Estación Meteorológica WiFi v1.0 

![N|Solid](https://raw.githubusercontent.com/electgpl/WeatherStationWemos/master/Images/1537318485855.png)

Esta es una estación Meteorológica Inalámbrica mediante WiFi, basada en el SoC ESP8266 para la comunicación y los sensores: BMP085/180, DHT11 y LDR.
Para una mejor precisión de medición, la temperatura se extrae del sensor Bosch en lugar del sensor DHT11, quedando así el DHT11 solo para indicar la humedad relativa.
El firmware cuenta con la biblioteca WiFiManager para aumentar la facilidad de autenticación para el usuario y los datos son enviados directamente a ThingSpeak.
Estos datos son enviados cada 5 minutos para mantener las buenas costumbres de frecuencia de datos en el servidor ThingSpeak, en el caso de parámetros meteorológicos no es necesaria la actualización constante de los datos, estos cambian de forma lenta.

## Controles - v1.0

  - Core - **ESP8266 - WEMOS D1 Mini**
  - Sensor de Presión y Temperatura - **BMP085 - BMP180**
  - Sensor de Humedad y Temperatura - **DHT11**
  - Sensor de Luminosidad - **LDR**
  - Botón de configuración para restablecer datos de fabrica
  - Servidor - **ThingSpeak**
  - Control WiFi - **WiFiManager**

## Alimentación

> Diseñado para ser alimentado con fuente de alimentación de 100 a 240Vac 3W

### Diseño

> Diseñado con EAGLE, en solo dos capas con componentes THT para facilitar
> la integración al alumno, el desarrollo del PCB en el hogar y mantener
> el menor costo posible.

### Medición OnLine en Tiempo Real ThingSpeak Channel 128756
https://thingspeak.com/channels/128756


Patrocinado
----
¿Dónde fabricamos nuestros PCBs?
Nuestros PCBs los fabricamos con la empresa PCBWay, esta empresa nos permite realizar pequeñas cantidades como prototipos rápidos para nuestros desarrollos a medida.
También nos permite realizar grandes producciones para realizar proyectos comerciales.
Servicio de prototipo de PCB por tan solo $5 las 10 unidades.
Cada nuevo miembro recibirá un bono de $5, más servicio express de 24Hs o 48Hs.
Servicio de ensamblado de PCB por $88 más envió gratis en todo el mundo, más esténcil, más componentes.
Un servicio de calidad!
https://www.pcbway.es/

[![N|Solid](https://github.com/electgpl/Banners/blob/master/PCBWay_600x160.gif)](https://www.pcbway.es/)


License
----

MIT
