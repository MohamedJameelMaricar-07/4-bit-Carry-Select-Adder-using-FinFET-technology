# 4-bit Carry Select Adder using FinFET Technology

This project explores the design and analysis of a 4-bit Carry Select Adder (CSA) using **FinFET technology** in **Cadence Virtuoso**. It focuses on optimizing **power consumption**, **delay**, and **transistor count** compared to conventional CMOS design.

---

## 📌 Objectives

- Design a 4-bit CSA using FinFET technology
- Analyze power, delay, and area
- Reduce transistor count using Gate Diffusion Input (GDI) logic
- Simulate using Cadence Virtuoso with 7nm FinFET models

---

## 🛠️ Tools Used

- **Cadence Virtuoso**
- **GPDK 90 & 7nm FinFET PDK**
- **LTSpice / Analog simulation tools**
- **MS Word (for documentation)**

---

## 📊 Results

| Metric       | Existing CSA | Proposed FinFET CSA |
|--------------|--------------|---------------------|
| Power (µW)   | 563 µW       | 448 µW              |
| Delay (ps)   | 1250 ps      | 108.5 ps            |

---

## 🧠 Key Concepts

- FinFET vs MOSFET
- Gate Diffusion Input (GDI)
- Full adder and multiplexer design
- Transistor-level schematic design
- Digital circuit optimization for VLSI

---

## 📁 Files

- `Final_Report_FinFET_CSA.docx`: Full documentation
- `schematics/`: Transistor-level diagrams
- `waveforms/`: Simulation output (fall time, rise time, power)

---

## 📚 References

- Venkatesan et al., ICACCS 2019 – Analysis of 1-bit Full Adder
- Mathurendra Singh et al., DELCON 2022 – FinFET in Adders
- Ramkumar & Kittur – Low-Power CSA Design, IEEE VLSI
- Naseri & Timarchi – Low-Power XOR/XNOR Gates

---

## 🔮 Future Scope

- Apply ML/AI for layout and performance optimization
- Explore Gate-All-Around (GAA) and Approximate Computing architectures


