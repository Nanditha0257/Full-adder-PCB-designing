# Full Adder PCB Design using KiCad

## 📌 Overview
This project implements a 1-Bit Full Adder using TTL logic ICs and demonstrates the complete PCB design process in **KiCad**, including schematic capture, PCB layout, routing, and 3D visualization.

A Full Adder performs the addition of **three single-bit binary inputs (A, B, and Carry-In)** and produces **Sum** and **Carry-Out** outputs.

---

## 🛠️ Software Used

- KiCad 9
- Schematic Editor
- PCB Editor
- 3D Viewer

---

## 🔩 Components Used

- 74LS86 (Quad XOR Gate)
- 74LS08 (Quad AND Gate)
- 74LS32 (Quad OR Gate)
- 2-Pin Input Connectors
- 2-Pin Output Connectors
- +5V Power Supply
- GND

---

## ⚙️ Working Principle

A Full Adder adds three binary inputs.

### Boolean Expressions

Sum (S)

```
S = A ⊕ B ⊕ Cin
```

**Carry Out (Cout)**

```
Cout = (A · B) + (Cin · (A ⊕ B))
```

---

## 📊 Truth Table

| A | B | Cin | Sum | Cout |
|---|---|-----|-----|------|
| 0 | 0 |  0  |  0  |  0   |
| 0 | 0 |  1  |  1  |  0   |
| 0 | 1 |  0  |  1  |  0   |
| 0 | 1 |  1  |  0  |  1   |
| 1 | 0 |  0  |  1  |  0   |
| 1 | 0 |  1  |  0  |  1   |
| 1 | 1 |  0  |  0  |  1   |
| 1 | 1 |  1  |  1  |  1   |

---

## 📂 Project Structure

```
Full-Adder-KiCad/
│
├── Schematic/
│   └── fulladder.kicad_sch
│
├── PCB/
│   └── fulladder.kicad_pcb
│
├── Images/
│   ├── schematic.png
│   ├── pcb_layout.png
│   └── 3d_view.png
│
├── Gerber/
│
└── README.md
```

---

## 📷 Project Preview

### Schematic

> Add your schematic screenshot here.

### PCB Layout

> Add your PCB layout screenshot here.

### 3D View

> Add your 3D PCB render here.

---

## ✨ Features

- Complete Full Adder implementation
- Designed using standard TTL logic ICs
- Compact PCB layout
- Single-layer PCB routing
- 3D PCB visualization
- Beginner-friendly digital electronics project
- Suitable for PCB design practice and digital logic learning

---

## 🚀 Applications

- Arithmetic Logic Unit (ALU)
- Binary Adders
- Digital Arithmetic Circuits
- Computer Architecture
- Embedded Hardware Learning
- Digital Electronics Laboratory

---

## 📚 Future Improvements

- 4-Bit Ripple Carry Adder
- 4-Bit ALU
- Binary Multiplier
- LED Output Indicators
- DIP Switch Inputs
- Logic Simulation
- Two-layer PCB Design

---

## 👩‍💻 Author

Nanditha

Electronics and Communication Engineering (ECE)

Interested in:
- PCB Design
- Embedded Systems
- VLSI
- Digital Electronics
- IoT

---

## ⭐ Support

If you found this project helpful, consider giving the repository a ⭐ to support my work.
