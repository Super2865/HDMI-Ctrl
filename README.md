# HDMI-Ctrl
The goal of the project is to create an HDMI CEC controller base on the ESP32-P4-C6, to control media devices by CEC or IR.  The architecture relies on a dual-MCU setup: an ESP32-P4 acting as the primary application processor (handling HDMI protocols and IO) and an ESP32-C6 serving as the wireless (Wi-Fi/BLE) network co-processor.
