<img width="3779" height="3779" alt="EM16_pin_define" src="https://github.com/user-attachments/assets/567efe6a-0592-436e-a48e-13ed558cf78b" />
<img width="778" height="396" alt="EM16" src="https://github.com/user-attachments/assets/aaab2748-0f61-4adf-bb4e-355812d75db2" />

HKL-EM16-S3 Example Code Repository
This repository contains a complete set of example firmware projects for the HKL-EM16-S3 ESP32-S3-based controller board. These sketches demonstrate how to use all the board’s peripherals and interfaces, serving as a practical reference for developers working on industrial IoT, automation, and embedded control applications.
📂 Example Code Function List
0.ESPHOME: Base example for integrating the board with ESPHome for home automation projects.
1.WIFI_SIGNAL: Demonstrates Wi-Fi connectivity and signal strength monitoring.
2_ANALOG_0_10V: 0-10V analog signal acquisition based on the ADS1115 high-precision ADC
3_DAC_OUTPUT: Analog voltage output control using the MCT4728 DAC module
4_PCF8574_Output: Controls digital outputs via the PCF8574 I/O expander.
5_PCF8574_Input: Reads digital inputs using the PCF8574 I/O expander.
6_HMI: Basic example for connecting and communicating with an HMI (Human-Machine Interface) screen.
7-SD_Write_code: File handling and data logging using an SD card module.
08_RS485_RE_SEND: Implements RS485 half-duplex communication (transmit/receive).
09_RS232_RS485_RE_SEND: Combined RS232/RS485 serial communication example.
10_SCT013_30A_1V_SENSOR: Reads AC current values using the SCT013 current transformer.
11_SSD1306_display_temperature: Displays temperature readings on an SSD1306 OLED screen.
11_W5500_WEB: Implements Ethernet connectivity using the W5500 chip to host a basic web server.
12_W5500_ETH_WEB_control_relay: Web-based relay control over Ethernet using the W5500 module.
13.NTP_UTC_time: Synchronizes the board’s clock with an NTP time server.
14_lora_code: Example for LoRa wireless communication.
15_RTC_DS1307: Reads and sets the real-time clock using the DS1307 module.
16_PSRAM_test_code: Tests the on-board PSRAM (pseudo-static RAM) for expanded memory usage.
17_NTC_B3950_code: Reads temperature using an NTC thermistor (B3950 curve).
18_Temperature_DS18B20: Reads temperature using the DS18B20 1-Wire digital sensor.
18-2_DHT11_DETECT: Reads humidity and temperature using the DHT11 sensor.
19_RS232_RE_SEND: Basic RS232 serial transmit/receive example.
The repository also includes the board’s schematic (SCH_HKL-EM16-S3_V1.0) and pinout diagram (EM16_pin_define) for hardware reference.
