# Franzininho WiFi Developer Edition

The **Franzininho WiFi Developer Edition** is a development board designed to evaluate **ESP32-S2 modules** (WROOM and WROVER) and to support the development of the next generation of Franzininho boards.

The Franzininho project was created to help people develop skills in electronics and programming through *DIY* (Do-It-Yourself) activities, aligned with the *maker culture* in Brazil.

![front](img/1.jpeg)

As there are still few ESP32-S2-based boards available in the Brazilian market, the Franzininho WiFi was developed to serve as a development platform for this SoC, as well as to help evaluate and validate applications.

---

## Features

### ESP32-S2 Module (WROOM or WROVER)
- Xtensa® LX7 32-bit single-core microprocessor, up to 240 MHz  
- 128 KB ROM  
- 320 KB SRAM  
- 16 KB RTC SRAM  
- 2 MB (8 Mbit) PSRAM (WROVER module only)  
- Wi-Fi 802.11 b/g/n  

### Interfaces
- GPIO, SPI, LCD, UART, I2C, I2S  
- Camera interface  
- IR, pulse counter, LED PWM  
- TWAI (compatible with ISO 11898-1)  
- USB 1.1 OTG  
- ADC, DAC  
- Touch sensor  
- Temperature sensor  

### Hardware
- USB Type-A male connector  
- RGB LED (WS2812) (GPIO 18)  
- 40 pins broken out to 2x20 headers (2.54 mm pitch, 36 GPIOs) — breadboard-friendly  
- Reset and DFU (BOOT0) buttons to enter the ROM bootloader (USB serial, no external adapter required)  
- Serial debug pins (TX and RX) for hardware debug console  
- JTAG pads for advanced debugging access  
- 3.3 V power indicator LED  
- 3.3 V voltage regulator  

### Power Supply
- Micro USB port (default power source)  
- 5 V and GND header pins  
- 3V3 and GND header pins  

### Dimensions
- 72 mm x 30 mm  

### Compatibility
- Compatible with [ESP-IDF](https://docs.espressif.com/projects/esp-idf/en/latest/esp32s2/get-started/index.html)  
- Compatible with [CircuitPython](https://circuitpython.org/)  

![back](img/3.jpeg)

---

## License

This project is open-source hardware and is released under the **CERN Open Hardware License**.

The Franzininho WiFi board is certified by OSHWA:  
[UID BR000006](https://certification.oshwa.org/br000006.html)

![oshwa](license/OSHW_mark_BR000006.png)
