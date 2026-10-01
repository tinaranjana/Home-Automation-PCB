# Home Automation PCB

A 4-layer smart home PCB designed in KiCad, built around the ESP32-WROOM-32. It controls 3 appliances (Light, AC and Exhaust) through opto-isolated relay channels.

## Features
- ESP32-WROOM-32 main controller
- 3 relay channels with PC817 optocoupler isolation
- NPN transistor driver and 1N4007 flyback diode on each channel
- LDR and DHT11 sensor headers, I2C LCD header
- 4 push-button inputs and a UART header
- 12 V DC input with 5 V (L7805) and 3.3 V (AMS1117) regulation

## Design Details
- Tool: KiCad 10
- 4 copper layers: F.Cu, In1.Cu, In2.Cu, B.Cu
- 209 pads, 67 nets, 44 vias, 0 unrouted
- Antenna keep-out zone for the ESP32

## Files
- `Home_Automation_PCB.pdf`: schematic, PCB layers, 3D views and BOM
- `ibom.html`: interactive BOM

## Status
Learning project. Feedback and suggestions are welcome!

## Author
Ranjana Yadav
linkedin.com/in/ranjana-yadav-ece
