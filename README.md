# Turbine Casing – Thermal Analysis (Methane vs Hydrogen)

This project presents a steady-state thermal analysis of a turbine casing operated under **methane** and **hydrogen** combustion conditions.  
The goal is to evaluate how different fuels influence temperature distribution, hotspot formation, and the resulting thermal load on the component.

## 🔧 Tools & Software
- **Siemens NX** – geometry preparation  
- **ANSYS Fluent** – thermal simulation  
- **Material:** AISI 310S stainless steel  

## 🔥 Overview
Two operating scenarios were compared:

### **Methane Case**
- Lower peak temperature  
- More uniform wall heating  
- Temperatures within the expected capability of AISI 310S  

### **Hydrogen Case**
- Higher overall temperature field  
- Stronger thermal gradients  
- Local hotspots exceeding the safe range for AISI 310S  

The results highlight how hydrogen combustion, although cleaner, imposes significantly higher thermal stress on turbine components.

## 📈 Key Results
- Hydrogen increases maximum temperature by several hundred degrees  
- Thermal gradients correlate with potential stress concentration zones  
- Methane operation shows more manageable thermal behavior  

## ➡️ Next Step
A **thermo-structural analysis** will be performed by mapping the thermal field onto the structural model to evaluate:

- deformation  
- thermal strain  
- equivalent von Mises stress  
- material safety margins  

## 📂 Repository Contents
- `/presentation` – PDF summary of the thermal analysis  
- `/images` – contour plots  
- `/models` – geometry files  
- This `README.md`  

## 📬 Contact
Project created for personal learning and engineering portfolio purposes.  
Open to feedback and discussion.
