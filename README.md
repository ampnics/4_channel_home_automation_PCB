4-Channel Home Automation with ESP32 PCB
This project is a 4-channel home automation system based on the ESP32, designed to control electrical appliances via Wi-Fi, 
MQTT, or a mobile app. The custom PCB integrates relays, optoisolated inputs, and an efficient power supply for reliable operation.

Features
✔ ESP32-based Wi-Fi control (supports web server & MQTT).
✔ 4-Channel relay output for appliance control.
✔ Optoisolated inputs for safe external switch connections.
✔ Onboard buck converter (AC/DC to 5V) for efficient power.
✔ Compact PCB design for easy enclosure integration.

Hardware Overview
1️⃣ Components Used:
ESP32-WROOM-32 (Wi-Fi + Bluetooth MCU)
4 x Relays (5V or 12V, SPDT)
Optocouplers for switch inputs
AC to DC Buck Converter (HLK-PM03 or equivalent)
Screw terminals for easy wiring
Status LEDs for each relay & power indicator
2️⃣ PCB Design Details:
Designed in KiCad
2-layer PCB for cost efficiency
Proper relay isolation from low-voltage ESP32
Wide power traces for relay switching
It is open source design by Md Ammar Maniyar for @ampnics
