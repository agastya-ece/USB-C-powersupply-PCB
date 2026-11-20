# 🔌 USB-C 5V Power Supply PCB

My first custom PCB design, built using **EasyEDA**!

A compact USB-C powered 5V supply board designed to explore USB Type-C power input, CC configuration, decoupling and PCB layout.

## ⚡ Features

- 🔌 USB Type-C power input
- 🔋 5V power rail
- ⚙️ CC1 and CC2 pull-down configuration (5.1kΩ)
- 🔆 Green LED power indicator
- 🔧 2-pin screw terminal output
- 🧩 Input and output decoupling capacitors

## 🛠️ Circuit Overview

The circuit uses a USB Type-C connector configured as a 5V power sink.

**Power Input**
- USB Type-C receptacle
- 5.1kΩ pull-down resistors on CC1 and CC2

**Power Conditioning**
- Two 100nF capacitors on the input rail
- One 100nF capacitor on the output rail

**Power Indication**
- Green LED with a 1kΩ current-limiting resistor

**Power Output**
- 2-pin terminal block providing 5V and GND

## 🧰 Tools & Components

| Category | Component |
|---|---|
| EDA Software | EasyEDA |
| Input | USB Type-C |
| Resistors | 5.1kΩ × 2, 1kΩ × 1 |
| Capacitors | 100nF × 3 |
| Indicator | Green LED |
| Output | 2-pin terminal block |

## 📂 Repository Structure

```text
USB-C-powersupply-PCB/
│
├── schematic/
│   ├── schematic.pdf
│   └── schematic.png
│
├── pcb/
│   ├── pcb-layout.png
│   └── pcb-3d-view.png
│
├── documentation/
│   └── BOM.csv
│
├── source/
│   └── easyeda-project
│
└── README.md
```

## 🧠 What I Learned

- USB Type-C power input configuration
- CC1 and CC2 pin functionality
- Pull-down resistor selection
- Power rail decoupling
- Schematic capture and PCB layout
- Component footprint selection and routing
- Design Rule Checks (DRC)

## 📍 Project Status

🟡 **Design Completed — Fabrication Pending**

- [x] Circuit schematic
- [x] Component selection
- [x] PCB layout design
