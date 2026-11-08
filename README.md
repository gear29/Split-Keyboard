# Split-Keyboard
This is a key board  but 2


 Wireless Split Keyboard

A custom wireless split mechanical keyboard powered by two Seeed Studio XIAO nRF52840 controllers and ZMK firmware.

Project Overview

Wireless Split Keyboard is a custom split keyboard designed around two independently powered wireless halves. Each half uses a Seeed Studio XIAO nRF52840 microcontroller and communicates using ZMK's split keyboard functionality.

The goal of this project is to create a fully custom keyboard, including its PCB, firmware, and mechanical design.

Features

Wireless split keyboard design

Two Seeed Studio XIAO nRF52840 controllers

ZMK firmware

Custom 5×5 matrix per half

42 total keys

Mechanical keyboard switches

Custom PCB design

Configurable keymap and layers


Repository Structure

wireless-split-keyboard/
├── README.md
├── bom.csv
├── PCB/
│   ├── schematic.kicad_sch
│   ├── pcb.kicad_pcb
│   └── gerbers/
├── CAD/
│   └── source-files/
└── Firmware/
    └── ZMK firmware repository


Building

Manufacture the custom PCB.

Assemble the keyboard electronics.

Flash the left and right ZMK firmware.

Configure and test the keyboard.



<img width="1903" height="1012" alt="image" src="https://github.com/user-attachments/assets/d2b58d95-d243-42a3-9f07-f32aa7837554" />


<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/f580587f-f28c-4ba2-8ec1-996511a94c14" />
