# -Comunicaci-n-LoRa-con-Arduino-MKR-1300-Visualizaci-n-OLED-y-Registro-en-SD
## Descripción General
Este proyecto amplía la funcionalidad de Arduino MKR 1300 para incluir la comunicación LoRa, visualización de datos en tiempo real mediante una pantalla OLED, y registro de datos en una tarjeta SD. Ideal para aplicaciones de IoT que requieren interactividad local y almacenamiento de datos junto con comunicación a larga distancia.

## Componentes y Tecnologías
- **Arduino MKR 1300**: Placa microcontroladora optimizada para comunicación LoRa.
- **Módulo LoRa**: Para comunicación de datos a larga distancia.
- **Pantalla OLED**: Para visualización de datos en tiempo real.
- **Tarjeta SD**: Utilizada para el registro de datos, como mediciones de temperatura y humedad.
- **Bibliotecas Arduino**: Incluyendo `MKRWAN_v2`, `SPI`, `SD`, y `U8g2lib`.

## Instalación y Uso
- Instala todas las bibliotecas necesarias utilizando el Administrador de Bibliotecas en el IDE de Arduino.
- Asegúrate de conectar correctamente todos los componentes hardware antes de proceder.
- Sube el código a tu Arduino MKR 1300 y verifica las conexiones si encuentras problemas durante la ejecución.

## Ejemplos de Uso
- **Visualización de datos**: La pantalla OLED puede mostrar datos como la temperatura, humedad y el estado de la red LoRa.
- **Registro de datos en SD**: Datos como la temperatura y la humedad son registrados en un archivo CSV en la tarjeta SD para análisis futuros.

## Contribuciones y Desarrollo Futuro
- **Contribuciones**: Invitación abierta a contribuir en el proyecto mejorando el código o añadiendo nuevas funcionalidades.
- **Desarrollo futuro**: Incorporar más sensores y optimizar el código para mejorar el rendimiento y la eficiencia energética.
"""
