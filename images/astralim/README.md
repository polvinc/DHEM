# AstrAlim board
## Open-source project
[link to the pcb design: ](https://oshwlab.com/pololamag/nafa-astralim)

Designed for amateur astronomers and built in conjunction with the hardware solution [NAFA-Hardware](https://github.com/dragonlost/NAFABox-hardware) (Nomad Astronomy For All), **AstrAlim** is a purpose-built add-on for the Raspberry Pi 5 or 4 mini-computer, specifically crafted to handle the electrical aspects of astrophotography sessions. This all-in-one HAT (Hardware Attached on Top) delivers the following features:
- **A single 12V DC, 15A input** in XT30 format streamlines power supply for the entire photo session, reducing complications and friction during telescope movement. It includes polarity protection.
- **A 5V, 5A power supply** to energize the Raspberry Pi.
- **Three controllable (ON/OFF) 12V DC outputs**, up to 36W, in DC Jack 2.1x5.5mm format for cameras, focusers, and filter wheels. One of these outputs allows selectable voltage between 12V, 9V, or 5V. Each output has current measurement via an INA219, and a self-resetting fuse secures the outgoing current up to 3A.
- **Two 12V PWM outputs**, up to 36W, in RCA/Cinch format to power up to two dew heaters, controllable to adjust their respective power levels. Current for each of these two outputs is also measured by an INA219, and a self-resetting fuse secures the outgoing current up to 3A.
- **Five red LEDs** provide visual feedback on the status of different outputs.
- **Two 1-wire outputs** and **two I2C outputs** for triggering and adjusting dew heaters based on the local dew point, by connecting temperature and humidity sensors, or other functions requiring these buses. ESD protection is included on these 4 outputs.
- **A 5-pin female header** for a NEO-6M Mini GPS module, with PPS (Pulse Per Second) output wired to the Raspberry Pi, providing precise time and positioning for nomadic astrophotography sessions, as well as the accuracy needed for occultation measurements.
- **A 32kbits EEPROM** ensures the Raspberry Pi recognizes AstrAlim at startup and initiates the necessary scripts for its proper functioning.
- **A 2x2p female direct-out connector** for future developments, allowing another stacked HAT to retrieve 12V voltage.

In summary, with the Raspberry Pi 5, **AstrAlim** offers a reliable, flexible, powerful, and energy-efficient solution, ideal for both fixed installations and nomadic use. This card also enables you to forgot conventional and costly proprietary systems, providing all the functions you might need to capture your most stunning pictures.

The software is currently being developed and fine-tuned.

A few statistics: 4 layers, 131 components, 1.7m track length, 97 vias, 446 pads, 48 resistors, 26 capacitors, 5 transistors, 5 MOSFETs, 5 polyfuses, 5 LEDs...

![AstrAlim_fcts.png](//image.easyeda.com/pullimage/ECG237k8oqopULxgYAXhKNfTiLsqNqy6pUzwKV6r.png)