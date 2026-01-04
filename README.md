# ESP32-S3 Test Board

A custom-designed development board for the ESP32-S3, designed in KiCad. This project was created for learning and prototyping purposes, featuring USB-C connectivity and a compact form factor.

<p align="center">
  <img src="/esp32-s3-testboard/esp32-s3-testboard.png" alt="3D Front View" width="45%">
  <img src="/esp32-s3-testboard/esp32-s3-testboard-back.png" alt="3D Back View" width="45%">
</p>

## About The Project

This PCB is a breakout and test board for the **ESP32-S3** microcontroller. It breaks out the necessary pins for prototyping and includes essential circuitry for power management and programming.

The design is based on the [High Speed PCB Design tutorial by Made by Morten](https://www.youtube.com/watch?v=QoU0WWNgO2g).

### Key Features
* **Microcontroller:** ESP32-S3 (WROOM Module)
* **Connectivity:** USB Type-C (Native USB)
* **Power:** Onboard 3.3V LDO Regulator
* **User Interface:** Reset & Boot buttons, Status LEDs
* **Layer Stack:** 4-Layer PCB design for better signal integrity and power distribution

## EDA Tool & Libraries

* **Designed in:** [KiCad EDA](https://www.kicad.org/)
* **Custom Library:** This project utilizes specific footprints and symbols from my personal library:
    * [Oddibits - KiCad Library](https://github.com/ktauchathuranga/oddibits)

## Getting Started

To view or modify the design:

1.  Clone this repository:
    ```bash
    git clone [https://github.com/ktauchathuranga/esp32-s3-testboard.git](https://github.com/ktauchathuranga/esp32-s3-testboard.git)
    ```
2.  Clone the dependency library (Oddibits) alongside it or add it to your KiCad Global Libraries table:
    ```bash
    git clone [https://github.com/ktauchathuranga/oddibits.git](https://github.com/ktauchathuranga/oddibits.git)
    ```
3.  Open the `.kicad_pro` file in KiCad 7.0 or later.

## Fabrication

This board is designed to be manufactured by standard PCB fabrication houses (e.g., JLCPCB, PCBWay).
* **Layers:** 4
* **Minimum Trace/Space:** Check Design Rules (usually 0.2mm or similar standard capabilities)
* **Via Size:** Standard

## Credits & References

* **Original Guide:** [Made by Morten - ESP32-S3 PCB Design](https://www.youtube.com/watch?v=QoU0WWNgO2g)
* **Espressif Systems:** For the ESP32-S3 Datasheets and Hardware Design Guidelines.

## License

This project is open-source. Please see the [LICENSE](LICENSE) file for more details.