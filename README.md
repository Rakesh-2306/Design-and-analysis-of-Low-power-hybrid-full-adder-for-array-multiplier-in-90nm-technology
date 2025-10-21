# ⚡ Low Power Hybrid Full Adder for Array Multiplier (90nm CMOS)

## 📘 Overview
This project presents a **hybrid full adder (FA)** combining **Transmission Gate (TG)** and **Pass Transistor Logic (PTL)** to achieve **low power, reduced delay, and optimized area**.  
The FA is integrated into **4-bit and 8-bit array multipliers**, designed and verified in **Cadence Virtuoso (90nm CMOS technology)**.

---

## ⚙️ Key Highlights
- **Technology:** 90nm CMOS (GPDK)
- **Tool:** Cadence Virtuoso  
- **Verification:** DRC, LVS, Parasitic Extraction  
- **Transistor Count:** 20 (1-bit FA)  
- **Supply Voltage:** 2V  

| Design | Delay | Power | PDP |
|---------|--------|--------|------|
| 1-bit FA | 19.92 ps | 5.42 µW | 108.04 aJ |
| 4-bit Multiplier | 0.0196 ns | 1.25 mW | 0.0245 pJ |
| 8-bit Multiplier | 19.65 ns | 5.37 mW | 105.52 pJ |

---

## 🧩 Features
- Low Power and High Speed Hybrid FA  
- Optimized XOR–XNOR, SUM, and CARRY modules  
- Integrated into 4-bit and 8-bit array multipliers  
- Verified with post-layout parasitic extraction  

---
