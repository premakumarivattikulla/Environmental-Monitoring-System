# Environmental Monitoring System

## Project Overview
The Environmental Monitoring System is an Arduino-based project designed to monitor environmental conditions such as temperature and light intensity.

It uses a TMP36 temperature sensor to measure temperature and an LDR (Light Dependent Resistor) to detect surrounding light levels. The readings are displayed on a 16x2 LCD.

## Components Used
- Arduino UNO
- TMP36 Temperature Sensor
- LDR (Light Dependent Resistor)
- 16x2 LCD Display
- 10kΩ Resistor
- Potentiometer
- Breadboard
- Jumper Wires

## Working Principle
1. The TMP36 sensor measures the surrounding temperature.
2. The LDR detects the intensity of ambient light.
3. Arduino reads the analog values from both sensors.
4. Temperature is calculated in Celsius.
5. Light conditions are classified as Bright or Dark.
6. Both readings are displayed on the LCD.

## Pin Connections

| Component | Arduino Pin |
|-----------|-------------|
| LCD RS | 8 |
| LCD E | 9 |
| LCD D4 | 10 |
| LCD D5 | 11 |
| LCD D6 | 12 |
| LCD D7 | 13 |
| TMP36 Output | A1 |
| LDR Output | A0 |

## Software Used
- Arduino IDE
- Tinkercad Circuits

## Features
- Real-time temperature monitoring
- Ambient light detection
- LCD-based output display
- Serial Monitor readings
- Simple and low-cost design

## Expected Output
The LCD displays:
- Temperature in Celsius
- Light status (Bright/Dark)

## Applications
- Environmental monitoring
- Smart home systems
- Indoor temperature monitoring
- Automatic lighting systems

## Future Improvements
- Add humidity monitoring.
- Add an air-quality sensor.
- Store sensor readings.
- Introduce IoT-based remote monitoring.

## Author
Premakumari Vattikulla

Department: EEE  
College: RGUKT Ongole
