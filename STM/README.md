
# Scanning Tunneling Microscope (STM) Design

This repository contains the design files for Mechanical Scanning Tunneling Microscope (STM), including Fusion360 CAD files, PCB engineering files, C++ firmware, and the Python software used to control the STM.

![HOPG](./Images/image_adc_1691722949755.jpg "Image of Carbon Atoms on Graphite Surface Captured by STM")
_Image of carbon atoms on the surface of graphite, showing the hexagonal structure of carbon atoms, captured by STM._

## Project Overview

The STM can achieve atomic-level resolution, allowing it to image individual atoms.


The overall design and inspiration for this project were primarily based on Dan Berard's home-built STM project, which you can find here:  
[**[Dan Berard's Home-Built STM]**](https://dberard.com/home-built-stm/)

![CAD](./Images/stm_cad.png "CAD Files of the STM")
_CAD files of the STM, including the STM body and vibration isolation platform._

## Repository Contents

- **Fusion360 CAD Files**: Full 3D models of the STM, including the main STM body and the vibration isolation system.
- **PCB Engineering Files**: PCB designs for the pre-amplifier and control circuit used in the STM.
- **C++ Firmware**: Microcontroller firmware for real-time control of the STM.
- **Python Control Software**: Python software for interfacing with the STM, including GUI control and data processing.

## How It Works

This STM uses a 3D-printed unimorph disk scanner, based on piezoelectric ceramics, for sub-nanometer movement. The sharp tungsten tip moves laterally across the sample's surface while measuring tunneling current to map atomic structures. A Teensy 4.1 microcontroller controls the scanner and collects scan data, while a Python program processes the data to produce high-resolution images of atomic structures.



## Acknowledgments

This project would not have been possible without the work and inspiration from Dan Berard's STM project. A huge thank you for sharing detailed reference materials that helped shape this design.

## Future Work

- **Add BOM List**: A Bill of Materials (BOM) for all the parts needed to build this STM will be added soon.

## Disclaimer

This project is experimental and requires a strong understanding of STM technology, electronics, and 3D printing. Building an STM can be challenging, but if you love pushing the boundaries of what hobbyists can achieve, this project is for you.
