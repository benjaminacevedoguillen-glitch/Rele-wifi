# Placa Relay-WiFi

Placa de control con dos relés y conectividad WiFi para encender y apagar cargas de 220 V de forma remota. Es una alternativa económica de domótica para iluminación y pequeños electrodomésticos.

Proyecto de la materia **Montajes de Proyectos Electrónicos** (2.º cuatrimestre 2026).
Escuela de Educación Secundaria Técnica N° 5 "2 de Abril" – Temperley, Buenos Aires.

## Características

- 2 relés de 5 V con contactos NA, común y NC.
- Microcontrolador ESP32-C3 Super Mini con WiFi.
- Etapa de potencia aislada con optoacopladores.
- 2 entradas para sensores de proximidad (radar de aproximadamente 7 m).
- Conector UART reservado para ampliaciones.
- Alimentación de 12 V con regulador a 5 V.
- Diseñada en KiCad.

## Aplicaciones

- Iluminación de interiores y exteriores con encendido y apagado remoto.
- Iluminación programada por rango horario.
- Encendido automático por sensor de proximidad.
- Encendido remoto de electrodomésticos.

## Estructura del repositorio

- `Diseño 3D/`: gabinete y piezas 3D.
- `Hardware/`: proyecto de KiCad, esquemático y PCB.
- `Software/`: firmware del ESP32-C3.

## Advertencia de seguridad

Este proyecto maneja 220 V de corriente alterna, que pueden causar descargas graves. Desconectá la red antes de conectar o modificar cualquier carga y alojá la placa en un gabinete aislado.

## Autor

Benjamín Acevedo Guillen

Profesor: Ing. Martín Leguizamón
