# CUSTOM_ROBOT_PCB_WITH_ESP32
A custom-designed PCB for robotics applications, featuring the ESP32-C3-WROOM-2 microcontroller with WiFi & Bluetooth connectivity, motor control via the L298P H-bridge, efficient power management, and USB isolation for safe programming.


<img src="https://github.com/bejaouihamza/CUSTOM_ROBOT_PCB_WITH_ESP32/blob/main/Capture%20d'%C3%A9cran%202025-07-20%20135718.png" width="800"/>


Key Features
🚀 Core Components
ESP32-C3-WROOM-2 – RISC-V-based MCU with WiFi 4 & Bluetooth 5 (BLE)

L298P Motor Driver – Dual H-bridge for controlling two DC motors or one stepper motor

CH340C USB-UART – Reliable serial communication for programming and debugging

USB Battery Isolation – Prevents backpowering issues during programming

12V Battery Input – Supports LiPo/Li-ion batteries with proper protection

⚡ Power Management
Buck Converter (12V → 5V/3.3V) – Efficient voltage regulation for MCU & peripherals

Battery Monitoring – Optional voltage divider for battery level sensing

🔌 Connectivity & I/O
USB-C Port – For programming & serial communication

Bluetooth/WiFi Control – Remote operation via smartphone or PC

GPIO Breakout – Access to unused ESP32 pins for sensors & expansions

🛠️ Applications
Autonomous Robots (Line-following, obstacle avoidance)

RC Vehicles (WiFi/Bluetooth-controlled)

IoT-Enabled Robotics (Telemetry, remote control)

📌 Schematic & Design Files
Designed in KiCad (schematics & PCB layout included)

Gerber files ready for manufacturing
<img src="https://github.com/bejaouihamza/CUSTOM_ROBOT_PCB_WITH_ESP32/blob/main/Capture%20d'%C3%A9cran%202025-07-20%20135809.png" width="800"/>

🔧 Getting Started
Flash the ESP32-C3 via USB-C .

Power via 12V battery – The buck converter supplies stable 5V/3.3V to the system.

Control motors via the L298P using PWM signals from the ESP32.

Use WiFi/BLE for wireless communication (Arduino/ESP-IDF supported).
