# Proyecto IoT – Bodega de vinos de Rueda

## 1. Empresa seleccionada

Hemos elegido una bodega de vinos de Rueda (Castilla y León), dedicada a la elaboración y conservación del vino.

El proyecto consiste en desarrollar un sistema de monitorización ambiental para controlar la temperatura y la luminosidad de la bodega mediante una placa BBC Micro:bit v2.

## 2. Clasificación IT/OT

| Elemento | Clasificación | Función |
|---|---|---|
| Cubas de fermentación | OT | Elaboración del vino. |
| Sensor de temperatura | OT | Medición de temperatura. |
| Sensor de luz | OT | Medición de luminosidad. |
| Micro:bit v2 | OT | Procesamiento de datos y alertas. |
| Matriz LED y altavoz | OT | Avisos visuales y sonoros. |
| Ordenador | IT | Programación y consulta de datos. |

## 3. Funcionamiento del programa

La Micro:bit v2 controla dos variables:

- **Temperatura:** si es inferior a 10 °C o superior a 15 °C, emite un pitido y muestra una cruz.
- **Luminosidad:** si está entre 100 y 150 unidades, emite un pitido y muestra una cruz.

## 4. Indicadores KPI

| KPI | Objetivo |
|---|---|
| Latencia | Menos de 2 segundos en la captura y procesamiento. |
| Precisión | Detectar los valores que cumplen las condiciones de alarma. |
| Estabilidad | Transmitir correctamente los datos durante las pruebas. |

## 5. Diseño 3D

Hemos diseñado en Tinkercad una carcasa para proteger la Micro:bit v2.

Incluye:
- Espacio para colocar la placa.
- Abertura para visualizar los LED.
- Ranura para el cable USB.
- Rejillas de ventilación.

## 6. Conclusión

Con este proyecto hemos aplicado la tecnología IoT al sector vitivinícola de Rueda. Hemos desarrollado un programa que controla la temperatura y la luminosidad, genera alertas automáticas y cuenta con un diseño 3D para proteger la placa.

De esta manera, combinamos la tradición del vino con la innovación tecnológica.