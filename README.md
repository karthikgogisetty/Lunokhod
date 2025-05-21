# RCAAI Conference Repository 📡🤖

This repository contains supporting files, code, simulations, and documentation for the RCAAI (Recent Challenges in Artificial Intelligence) conference presentation and the associated paper published by Springer:  
📖 [Springer Link – Lunokhod: A Compact Multi-Terrain Fire Detection and Extinguishing Rover](https://link.springer.com/chapter/10.1007/978-981-99-4634-1_5)

---

## 🗂️ Repository Structure

### 1. `approach/`
This directory contains the official project report submitted under MIT Manipal’s ISA-FIEPER initiative. It outlines the core idea, mission planning, and system design behind the Lunokhod rover, capable of terrain-aware fire detection and extinguishing.

- `MIT_Manipal_Team_Lunokhod_-_ISA_FIEPER_Project_Report.docx` – Full project report.
- `LICENSE` – Project licensing details.

### 2. `conference/`
This is the working directory that supports the conference publication, we took ahead this novel idea to present it in RCAAI 2022. It includes:
- 🔬 **Model Simulations**
  - `buck_converter_end_effector.slx` – Simulink model for energy-efficient end-effector design.
  - `Script for End Effector.mat` – Related MATLAB script.
- 📓 **Jupyter Notebooks**
  - `RCAII.ipynb` – Main notebook with experiments and visualizations.
  - `fireDetectionMdl.ipynb` – Fire detection ML model.
- 📊 **Data & Visuals**
  - `SampleRCAIIdashboard.csv` – Dataset used in dashboard visualization.
  - `B vs I.png`, `F vs I.png`, `H vs I.png` – Graphical data plots.
  - `Graphs.docx` – Analytical graphs with interpretations.
- 🖼️ **Publication Files**
  - `Lunokhod (1).pdf` – Final published manuscript.
  - `Lunokhod (1).docm` – Source manuscript file.
- 🖥️ **Dashboard**
  - `dash.py` – A lightweight Python dashboard using Plotly/Dash.
- 📝 `README.md` – (Redundant now, merged into this main README)

---

## 🔍 Research Overview

### 🔥 Problem Statement
Fire outbreaks in industrial, forested, and remote terrains pose a major threat to life and property. Existing robotic solutions either lack adaptability to multiple terrains or fail to incorporate autonomous fire detection.

### 🤖 Lunokhod Rover
The rover combines:
- Terrain-adaptive locomotion
- Real-time fire detection using sensor fusion and ML
- Power-efficient end-effector simulation for fire suppression
- Autonomous dashboard for monitoring environmental stats

---

## 📌 Citation

If you use this work in your research, please cite the publication:

```bibtex
@InProceedings{LunokhodRCAAI2024,
  author    = {Karthik G and Team Lunokhod},
  title     = {Lunokhod: A Compact Multi-Terrain Fire Detection and Extinguishing Rover},
  booktitle = {Recent Challenges in Artificial Intelligence},
  year      = {2024},
  publisher = {Springer},
  doi       = {10.1007/978-981-99-4634-1_5}
}
```

**Note:** This is done by 4 people led by me, for contact information of my team refer to the conference paper or the draft.
