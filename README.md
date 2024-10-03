# Egg-Foul-Detection-System

### Tagline
Checking the quality of eggs using an ultrasonic sensor, liquid level sensor, and LCD display.

---

## Introduction

### What is this project?
The **Egg Quality Checker** uses an ultrasonic sensor and liquid level sensor to determine the quality of an egg based on distance measurements. The result is displayed on an LCD screen, indicating whether the egg is good, bad, or absent.

### Why was this project created?
This project was developed to provide a simple, cost-effective solution for checking the quality of eggs without breaking them. It can be useful in kitchens, food quality testing, and poultry farms.

---

## Key Features
- **Ultrasonic Distance Measurement**: Measures the distance between the egg and the sensor to determine its quality.
- **Liquid Level Sensor**: Detects the water level for calibration.
- **LCD Display Output**: Displays the distance measured and the quality of the egg (good, bad, or no egg).
- **Button Control**: Toggles the LCD display on and off to conserve power.

---


## Getting Started

### Prerequisites
- Arduino Board
- Ultrasonic Sensor (HC-SR04)
- Liquid Level Sensor
- LCD Display (16x2)
- Push Button
- Breadboard and jumper wires for connections

---

## Connections

### 1. Ultrasonic Sensor (HC-SR04) to Arduino:
| **HC-SR04 Pin** | **Arduino Pin** |
|-----------------|-----------------|
| VCC             | 5V              |
| GND             | GND             |
| TRIG            | Pin 8           |
| ECHO            | Pin 9           |

### 2. Liquid Level Sensor to Arduino:
| **Sensor Pin**  | **Arduino Pin** |
|-----------------|-----------------|
| VCC             | 5V              |
| GND             | GND             |
| Analog Output   | A0              |

### 3. LCD Display to Arduino:
| **LCD Pin** | **Arduino Pin** |
|-------------|-----------------|
| RS          | Pin 2           |
| EN          | Pin 3           |
| D4          | Pin 4           |
| D5          | Pin 5           |
| D6          | Pin 6           |
| D7          | Pin 7           |
| VCC         | 5V              |
| GND         | GND             |

### 4. Push Button to Arduino:
| **Button Pin** | **Arduino Pin** |
|----------------|-----------------|
| Pin 1          | Pin 13          |
| Pin 2          | GND             |

### 5. Breadboard and Jumper Wires:
- Use jumper wires to connect all components to the breadboard and Arduino for proper grounding and power distribution.

---

## Screenshots
- **Circuit Diagram**
  (https://github.com/user-attachments/assets/083887c8-c267-46fc-96fa-7553baffdce1)

- **LCD Display Output**
  (https://github.com/user-attachments/assets/68b4a5bf-dc25-4aed-bfcc-1d72d112385b)


---

## Installation

1. Connect the ultrasonic sensor, liquid level sensor, LCD display, and push button to the Arduino board as described above.
2. Upload the provided code to the Arduino board using the Arduino IDE.

---

## Usage

1. Press the button to toggle the LCD display on or off.
2. The ultrasonic sensor will measure the distance to the egg, and based on this value, the egg's quality will be determined.
3. The result (good, bad, or no egg) will be displayed on the LCD screen.

---
