# CM5 MINIMA REV2

## Introduction

The **CM5 MINIMA REV2** is a compact carrier board for the latest Raspberry Pi computing module 5.
It is designed for embedded applications, DIY electronics, and low-power computing projects. Unlike traditional desktop computers, the CM5 is a small, efficient system that integrates essential computing hardware onto a single board. Whether you're a hobbyist, developer, or engineer, this module provides a versatile platform for various applications, including IoT, automation, and custom hardware development.

If you're not familiar with Raspberry Pi or single-board computers (SBCs), think of the CM5 as a miniaturized computer that can handle tasks like data processing, networking, and hardware control, all while fitting in the palm of your hand. 
https://www.raspberrypi.com/products/compute-module-5/?variant=cm5-104032

Get to know the story behind the MINIMA on Hackster.io:
https://www.hackster.io/piecol/tiny-open-source-media-streamer-with-lorawan-what-a98a93

![PCB_JLC](https://github.com/piecol/CM5_MINIMA_REV2/blob/main/PICS/img_0338.jpg)

## Designed with KiCad

MINIMA was developed using KiCad, a powerful open-source Electronic Design Automation (EDA) tool. KiCad enables designers to create high-quality PCB layouts and schematics while maintaining full control over their hardware designs. By leveraging open-source tools like KiCad, the CM5 MINIMA REV2 embraces accessibility, collaboration, and innovation in hardware development.
It is also certified by the Open Source Hardware Association: https://certification.oshwa.org/it000020.html

## Key Features

- **USB-C Power Delivery (PD):** Supports power negotiation for efficient energy use.
- **USB 2.0 Ports:** Connect peripherals such as keyboards, mice, and external storage.
- **Gigabit Ethernet:** High-speed wired networking with a low-profile cutout magjack.
- **HDMI Port:** Output video to external displays for media playback or interface applications.
- **M.2 M Key Slot:** Supports 2230 SSDs for fast storage expansion.
- **CSI/DSI Connector:** Attach camera modules or displays for vision-based applications.
- **SHTC3 Sensirion Sensor:** Built-in temperature and humidity monitoring.
- **I2C Connector (3.3V only):** Connect low-power sensors and communication modules.
- **SPI Connector:** Supports high-speed communication with other devices.
- **Fan Connector:** Optional cooling support for high-performance applications.
- **Status LEDs:** Visual indicators for power and system activity.
- **Compact Size:** Measuring only **5.4 × 5.7 cm**, ideal for space-constrained projects.

![PCB_JLC_BOTTOM](https://github.com/piecol/CM5_MINIMA_REV2/blob/main/PICS/img_0340.jpg)

## Schematics

[PDF SCHEMATICS](https://github.com/piecol/CM5_MINIMA_REV2/blob/main/CM5_MINIMA_2.pdf)

## Getting Started

To use the **CM5 MINIMA REV2**, you'll need:

- A **USB-C power adapter** that supports Power Delivery (PD).
- A **display (HDMI)** and **input devices (USB keyboard/mouse)** for setup.
- A **network connection** (Ethernet or Wi-Fi via an external adapter if needed).

## Flashing OS

To flash an operating system (OS) to the CM5, use the switch located on the bottom of the board to enable flashing mode. It is equivalent to the "Fit nRPI_BOOT to J2 (disable eMMC Boot) on the IO board jumper." on the CM5 IO board.
Please refere to the official guidelines for further instructions:
https://www.raspberrypi.com/documentation/computers/compute-module.html#set-up-the-io-board

![PCB_JLC_BOTTOM](https://github.com/piecol/CM5_MINIMA_REV2/blob/main/PICS/1739773194746.jpeg)

## Applications

- **IoT & Smart Devices:** Use sensors and network capabilities to create connected applications.
- **Home Automation:** Control and monitor home devices with minimal power consumption.
- **Embedded Systems:** Develop custom hardware solutions for industrial and consumer electronics.
- **Media Centers:** Play videos and manage digital content on an external display.
- **DIY Projects:** Ideal for makers and educators learning about electronics and programming.

## Conclusion

The **CM5 MINIMA REV2** is a powerful and flexible computing module that opens up endless possibilities for embedded computing and automation. Whether you're building a smart device, experimenting with sensors, or designing a networked system, this board provides the essential features you need in a compact, energy-efficient form factor.

![PCB](https://github.com/piecol/CM5_MINIMA_REV2/blob/main/PICS/PCB.png)


## **Stackup**:
6L (SIG:PWR | GND | SIG-PWR | PWR | GND | SIG:PWR) 

### If you would like to support me:

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/pierluigicj)


![F](https://github.com/piecol/CM5_MINIMA_REV2/blob/main/PICS/F.png)
![SIDE](https://github.com/piecol/CM5_MINIMA_REV2/blob/main/PICS/SIDE.png)
![B](https://github.com/piecol/CM5_MINIMA_REV2/blob/main/PICS/B.png)
