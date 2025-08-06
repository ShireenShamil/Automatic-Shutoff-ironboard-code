# Automatic Shutoff Ironboard C++ Code

## 🚀 Overview

This repository contains the C++ code for an automatic shutoff ironboard safety system. The project's purpose is to enhance safety by automatically powering off a connected iron when a prolonged period of inactivity is detected. This prevents potential fire hazards and saves energy. The code is designed to be easily implemented on a microcontroller and integrated with the necessary hardware.

## ✨ Features

  * **Inactivity Detection:** The system uses a sensor to detect a lack of motion or activity, triggering a safety timer.
  * **Customizable Timer:** The duration of inactivity before the shutoff is triggered can be easily configured within the code.
  * **Safe Power Cutoff:** Once the timer expires, the code sends a signal to a relay or similar mechanism to safely cut power to the iron.
  * **Status Indicators:** The code supports visual indicators (e.g., LEDs) to show the current state of the system (active, timer counting down, and off).

## 💻 Technologies Used

  * **C++:** The core programming language for the microcontroller.
  * **[Microcontroller/Platform]:** e.g., Arduino, ESP32, etc.
  * **[Sensor(s)]:** e.g., MPU-6050 Accelerometer for motion detection, or a simple IR sensor.
  * **[Actuator]:** e.g., A Relay Module to control the power supply.

## 🛠 Getting Started

These instructions will help you set up the hardware and software to get the project running.

### Prerequisites

  * A microcontroller compatible with C++ programming (e.g., Arduino Uno).
  * A sensor for detecting inactivity (e.g., an accelerometer).
  * A relay module to control the power outlet.
  * The appropriate IDE for your microcontroller (e.g., Arduino IDE).
  * Jumper wires, breadboard, and other basic electronic components.

### Installation

1.  Clone this repository to your local machine:
    ```bash
    git clone https://github.com/ShireenShamil/Automatic-Shutoff-ironboard-code.git
    ```
2.  Open the project file (`.ino` for Arduino) in your IDE.
3.  Ensure you have all necessary libraries for your sensors installed via the IDE's Library Manager.

### Code Structure

The code is typically structured with two main functions:

  * `setup()`: Initializes the microcontroller pins, sensors, and communication protocols.
  * `loop()`: Contains the main program logic, continuously checking for activity and managing the timer and power state.

## 🔌 Circuit Diagram

To correctly assemble the hardware, you will need a circuit diagram. Please refer to the [link to the circuit diagram or image file] provided in the repository. The diagram will show how to connect the microcontroller, sensor, and relay.

## 🤝 Contributing

Contributions are welcome\! If you have a suggestion for a feature or an improvement, please feel free to open an issue or submit a pull request.
## ✍️ Author

  * **Shireen Shamil**
