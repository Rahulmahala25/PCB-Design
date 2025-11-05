# 5V to 3.3V Voltage Regulator (Altium Designer)

This project implements a compact **5V to 3.3V linear voltage regulator module**, designed in **Altium Designer**.  
It accepts a 5 V input and outputs a regulated 3.3 V supply suitable for powering low-power digital electronics, MCUs, and sensors.

---

## ✅ Features

- Input Voltage: **+5 V**
- Output Voltage: **+3.3 V**
- Low-noise linear regulation
- Compact 2-connector interface (J1 → input, J2 → output)
- Decoupling capacitors placed at input (C1) and output (C2)
- Optimized copper routing & ground reference for improved stability
- 3D mechanical visualization included

---

## 🧩 Components

| Reference | Component | Description |
|-----------|-----------|-------------|
| U1 | MIC5317-3.3YM5-TR | 3.3 V Low-Dropout Regulator (LDO) |
| C1 | 1 µF capacitor | Input decoupling |
| C2 | 1 µF capacitor | Output decoupling |
| J1 | Connector | 5 V / GND input |
| J2 | Connector | 3.3 V / GND output |

---

## 📐 Schematic

![Schematic]<img width="1445" height="562" alt="image" src="https://github.com/user-attachments/assets/8315570d-6132-4323-8241-eec52e65c2d4" />


> Shows the full circuit: input connector → decoupling capacitor → MIC5317 regulator → output capacitor → output connector.

---

## 🖼 PCB Layout

### ✅ Top View (2D)

![PCB Layout 2D]<img width="1088" height="502" alt="image" src="https://github.com/user-attachments/assets/62882303-6fd9-4988-8a43-5f6329c633f4" />


> Components arranged linearly for minimal trace length. Short ground + input paths ensure improved noise performance.

---

### ✅ 3D View

![PCB Layout 3D](./pcb_3d.png)

> 3D rendering for mechanical checks, connector placement clarity, and production visualization.

---

## 🛠 Tools Used

- **Altium Designer**
- Git / GitHub

---

## 📄 Manufacturing Outputs

This folder includes:
- ✅ Gerber files
- ✅ Drill files
- ✅ BOM (Bill of Materials)

These files can be used directly for PCB fabrication and assembly.

---

## 🚀 Design Notes

- The MIC5317 LDO provides low-noise regulation suitable for digital/analog circuits.
- Input/Output decoupling capacitors placed near U1 improve transient response.
- Component placement is symmetric to minimize routing complexity.
- Ground plane improves power integrity and noise reduction.

---

## 📦 Applications

- Low-power microcontrollers
- Sensors
- IoT development boards
- Logic-level conversion modules

---

## 🔧 Future Improvements

- Add power LED indicator
- Include reverse-polarity protection
- Add mounting holes for enclosure
- Add bulk capacitor for high-transient loads

---

## 📜 License

Open-source — free to learn and modify.

---

## ✨ Author

**Rahul Mahala**
