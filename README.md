# The-Doom: Portable Cyber Lab for Ethical Hacking and RF Interception

**The-Doom** is an open-source cyber research kit designed for education, training, and ethical testing. It combines low-cost hardware like Orange Pi and ESP32 with powerful tools for Wi-Fi auditing, SDR signal capture, and IoT device analysis.

---

## Hardware Components

- Orange Pi 5 (8GB) — or an old laptop (recycled for even lower cost)
- RTL-SDR V3 USB Dongle
- Alfa AWUS036ACH Wi-Fi Adapter
- MicroSD Card (64GB+)
- Arduino Nano or Uno (for hardware hacking)
- nRF24L01+ Module (2.4GHz transceiver)
- ESP8266 Module (ESP-01 for WiFi deauth attacks)
- Power Supply (5V/3.3V for microcontrollers)
- USB Hub and Adapter Cables
- Breadboard and Jumper Wires
- Portable Power Bank (USB-C)
- Optional: Portable Monitor

**Estimated Total Cost**: 30,000–40,000 ETB

---

## Key Features

- Wi-Fi monitor mode and packet injection (Aircrack-ng, Kismet, etc.)
- SDR scanning and decoding for FM, ADS-B, airband, and satellite signals
- Satellite signal interception (weather satellites, Inmarsat, NOAA APT decoding)
- ESP32 automation projects (IoT sniffers, sensors, jammers)
- Lightweight and portable with offline capability
- Modular design for easy expansion and customization
- Designed with educational and field training in mind

---

## Repository Structure

    The-Doom/
    ├── README.md
    ├── hardware/
    │ ├── parts_list.md
    │ ├── wiring_diagrams/
    │ └── setup_photos/
    ├── software/
    │ ├── install_guide.md
    │ ├── kali_on_orangepi.md
    │ ├── rf_tools.md
    │ ├── arduino_jammer_setup.md
    │ └── automation_scripts/
    │ ├── wifi_sniffer.py
    │ ├── rf_decoder.py
    │ └── arduino_jammer.ino
    ├── projects/
    │ ├── wifi_auditing.md
    │ ├── rtl_sdr_airband_monitor.md
    │ ├── satellite_weather_tracking.md
    │ └── arduino_rf_jammer_project.md
    ├── licenses/
    │ └── LICENSE
    └── images/
        └── the-doom-banner.png

---

## Legal Disclaimer

This project is for **educational purposes only**. All testing must be conducted **only** on devices and networks you **own** or have **explicit written permission** to assess. Any misuse is the responsibility of the user.🌚

---

## Contributing

Contributions are welcome. Submit pull requests for improvements or create issues for bugs, hardware additions(it must be cheap), or project suggestions.

---

## Notice

Project might be delayed due to shortage of money. I will be happy to accept any donation

 ---

## License

See the `licenses/` folder for licensing details.
