<div align="center">

# AeroAcoustix

### InnovAero Competition 2026 — Lufthansa Technik

**A Frequency-Targeted Passive–Active Design for a VIP Compartment**
**Beside a Wing-Mounted Turbofan**

_From engine source to passenger ear in a CFRP wide-body at cruise, with independent 3-D validation_

[![CAD Model](https://img.shields.io/badge/CAD-Fusion%20360-orange)](https://a360.co/44GbDCQ)

</div>

---

## Overview

Long-haul VIP cabins are sold on the premium quality of their acoustic environment — yet they sit inside the same
pressurised fuselage that carries punishing engine noise. This project designs a **highly optimized, mass-efficient
acoustic treatment** for a **3.0 × 2.0 × 2.3 m VIP compartment** in a carbon-fibre wide-body aircraft, positioned
beside a **wing-mounted turbofan at cruise** — acoustically the most demanding location on the aircraft.

A single, traceable calculation chain is built from **engine sound power → free-field propagation → oblique-incidence
transmission through the sidewall → passenger ear**, using transfer-matrix modelling, damped-plate theory, and an
energy-based receiver model for both **seated** and **reclined** positions. The design combines skin damping, a
full-depth absorptive cavity, a tuned resonator barrier leaf, and **headrest active noise control (ANC)** to close
the low-frequency gap that passive mass alone cannot solve.

Every prediction is cross-checked against an **independent 3-D wave solution**, a **finite-element model**, and a
**Monte-Carlo uncertainty analysis** — and validated with a full **flight-test plan** and **installation concept**.

---

## 🎯 Key Results

| Configuration                          | Seated (dBA) | Reclined (dBA) | Added Mass |
| -------------------------------------- | :----------: | :------------: | :--------: |
| Bare CFRP shell                        |     90.8     |      90.7      |     –      |
| T1 — Conventional insulation           |     75.8     |      80.8      |   174 kg   |
| **T2 — Proposed passive build-up**     |   **67.3**   |    **70.6**    |   238 kg   |
| **T2 + Headrest Active Noise Control** |   **60.2**   |    **62.7**    |   238 kg   |

> 🎧 The final hybrid design is **~8.4× quieter** than the untreated cabin at the seated position, with the
> blade-passage tone rendered fully inaudible.

**Design targets:** 55 dBA seated (business-jet benchmark) · 45 dBA reclined (WHO night-noise guidance + 5 dB margin)

---

## Repository Structure

```text
AeroAcoustix-InnovAero-2026/
│
├── assets/
│   ├── CAD_Screenshots_Fusion/
│   │   ├── images/
│   │   └── README.md
│   │
│   ├── Engineering_Drawings/
│   │   ├── AERO_acoustix_Drawings.pdf
│   │   └── README.md
│   │
│   └── Render_Photos_Deck/
│       ├── images/
│       └── README.md
│
├── README.md


Each subfolder contains its own detailed `README.md` describing individual files, view angles, and technical context.

---

## CAD Model & Live 3D View

The compartment was modelled in **Autodesk Fusion 360** inside an A350-type fuselage section — including the
layered sidewall build-up, floor deck, partitions, sliding door, furniture, and the Smart Cabin Management System UI.

🔗 **Interactive 3D Model (A360):** `[ https://a360.co/44GbDCQ]`

---

## Source Code & Calculation Model

All acoustic results in the report are produced by a single, open-source Python model (`model.py`) — the
same tool used for sensitivity analysis, Monte-Carlo uncertainty propagation, and the on-site recalculation exercise.

🔗 **GitHub Source Code:** [tusharr-mishra/AeroAcoustix-InnovAero-2026](https://github.com/tusharr-mishra/AeroAcoustix-InnovAero-2026)

---

## 👥 Team

| Name | Institution | Programme | Principal Contribution |
|---|---|---|---|
| **Tushar Mishra** *(Head)* | Amity University, Noida | B.Tech CSE | Acoustic Modelling, Numerical Cross-Checks, Report Production |
| **Mohnish Murugan** | IIT Madras | B.Tech Aerospace | Acoustic Model, Calculation Chain, Verification |
| **Yash Bhake** | IIT Bombay | B.Tech Mechanical | Materials, Certification Basis, In-Service Anchoring |
| **Tushar Kumar** | Delhi Technological University | B.Des Industrial Design | CAD Model & Integration Concept (Fusion 360) |

📧 Contact: tusharmishra0710@gmail.com · mp.mohnish@gmail.com · yashbhake1@gmail.com · tusharkr561@gmail.com

---

## 📌 Status

> This repository is under active development as part of an ongoing competition submission.
> Assets, models, and documentation will continue to be refined.

---

<div align="center">

**Lufthansa Technik InnovAero Competition 2026**

</div>
```
