# smart-water-system
Prototype for an automated water level management system

## Overview

The Smart Water Level Management System is a project aimed at automating the refilling process of a water tank based on its water level. This system detects the water level in the tank and initiates the refill operation when the water level falls below a certain threshold. It offers two distinct methods for refilling the tank from a water source, ensuring efficient water management without requiring manual intervention. Additionally, the system alerts the user when the water level in the tank is low, providing timely notification for maintenance or action.

## Features

- Automatic detection of water level in the tank.
- Automatic refilling of the tank from the water source.
- Two refill methods based on the water level in the source.
- User option to manually deactivate the refill process.
- Optional integration of a temperature sensor for monitoring water temperature.
- User alert when the water level in the tank is low.

## Components

- 555 Timer Chip: Used to detect water levels in the tank.
- Aquarium Pump: Responsible for refilling the tank from the water source.
- NPN Transistor: Controls the on/off stages of the pump.
- Seven Segment LED Display: Displays the current water level in the tank.
- JK Flip Flop: Connects the level detection and refilling process for seamless operation.
- NTC Thermistor: Detects the temperature of the water in the source.
- Buzzer: Alerts the user when necessary, when the water level is low.

## Operation

1. **Water Level Detection**: The system continuously monitors the water level in the tank and the source.
2. **Refill Activation**: When the water level in the tank falls below a predefined threshold, the refill process is activated.
3. **Refill Methods**:
   - If the water level in the source is less than half its capacity, the refill process stops when the tank reaches a certain level.
   - If the water level in the source exceeds half its capacity, the refill process stops after filling the tank to its maximum level.
4. **Manual Control**: Users can manually deactivate the refill process if necessary.
5. **Optional Temperature Monitoring**: The system can optionally incorporate a temperature sensor circuit to monitor water temperature in the source.

[Watch the demo video](https://drive.google.com/file/d/1sLQjN3sKWsUDiInLERMFxNUoDE2apIY-/view?usp=sharing)


