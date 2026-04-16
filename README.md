# 🧬 Elite Cycling Lab | ECAM

**A decision layer for high-performance bike fitting.**

ECAM (Elite Cycling Analysis Model) sits on top of motion capture data and rider input to answer a simple question:

*What is actually limiting this rider, how much is it costing them, and what should we fix first?*

**Project Status:** Pilot Phase (Costa Blanca, Spain)  
**Lead:** Erin NS (DPT)  
**Data Source:** Bike Fast Fit (BFF)  
**Environment:** WorldTour / high-performance training region  

---

## 🛰️ OVERVIEW

Elite Cycling Lab is a field-based project focused on bridging the gap between kinematic data and real-world performance.

* **BFF** captures high-quality movement data  
* **ECAM** turns it into actionable decisions  

Instead of reviewing angles and pressure maps in isolation, the system produces:
* A ranked set of performance limiters  
* A clear explanation of what’s driving each one  
* An estimate of performance impact (watts)  
* A practical order of intervention  

**All within a single session.**

---

## 🧠 WHAT ECAM DOES

ECAM combines:
* Movement data from capture systems (joint angles, patterns)  
* Rider feedback under load (fatigue, pressure, stability)  

It aligns these inputs to identify the patterns that actually limit performance in real riding conditions.

**The output is not more data. It’s a decision.**

---

## 🚀 EXAMPLE OUTPUT

* **Primary Limiter Identified:** (e.g., Thoracic compression)  
* **Secondary Compensations:** (e.g., Cervical overextension)  
* **Estimated Performance Cost:** (e.g., 15–25W)  
* **Clear Intervention Priority:** Immediate mechanical adjustment + targeted off-bike work  

This allows immediate changes on the bike and more focused follow-up work off it.

---

## 📂 REPOSITORY CONTENT

* [**Case Study 001: The Endurance Focus**](./Cases/Case_001_Audit.md) – Addressing hip compression and pelvic drift.
* [**Case Study 002: The Aero-Respiratory Conflict**](./Cases/Case_002_Audit.md) – Balancing aerodynamics with breathing mechanics.
* [**Case Study 003: The Sprint Stability Audit**](./Cases/Case_003_Audit.md) – Isolating torque leaks and pelvic instability.

**Note:** Core engine logic and implementation parameters are proprietary and are not included in this public overview.

---

## ⚠️ DISCLAIMER

These outputs are performance-focused hypotheses intended to guide optimization. Medical conditions require evaluation by a licensed professional.

---

*Built and tested in a real training environment with high-level riders. If you work with BFF data, the workflow should feel immediately familiar.*
