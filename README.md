# cognitive_analysis_tool-master

# 🧠 Cognitive Analysis Tool  

The **Cognitive Analysis Tool** is a research-driven project designed to analyze human cognitive responses using light, pupil detection, GPS data, and OpenCV-based computer vision. It enables automated logging, signal analysis, and visualization to study cognitive load and environmental conditions.  

---

## 🚀 Features  
- 📡 **Sensor Data Logging** – Collect and log lux (light intensity) and GPS data.  
- 👁️ **Pupil Analysis** – Detect, track, and analyze pupil responses using OpenCV.  
- 📊 **Signal Processing** – Tools for filtering, transforming, and analyzing cognitive signals.  
- 🌍 **Data Visualization** – Plot and visualize GPS, light, and pupil response data.  
- 💾 **Data Storage** – Automatic logging to SD card and CSV for later analysis.  
- 🔬 **Research Ready** – Built for academic and experimental environments.  

---

## 🛠️ Tech Stack  
- **Languages:** Python, Arduino (C++)  
- **Libraries:**  
  - Python: `OpenCV`, `NumPy`, `Matplotlib`  
  - Arduino: Light sensors, GPS modules  
- **Tools:** Git LFS for handling large media files (`*.mov`)  

---

## 📂 Project Structure  

```
cognitive_analysis_tool-master/
│
├── Lux Sensor/                  # Arduino-based lux (light) logging
│   ├── Adalogger FeatherWing/  
│   └── Arduino Nano/           
│
├── pupil_code/                  # Python scripts for pupil analysis
│   ├── gps_plot.py
│   ├── lum_analysis.py
│   ├── lux_log.py
│   ├── openCV_magic.py
│   ├── pupil_tools/             # Utility functions (signal, data, color tools)
│
├── Resources/                   # App resources (nib files, etc.)
│
├── analysisTool.py               # Main analysis script
├── setup.py                      # Setup instructions
├── LICENSE.md
└── ReadMe.txt
```

---

## ⚙️ Installation  

### 1. Clone the Repository  
```bash
git clone https://github.com/HellboyHero/cognitive_analysis_tool-master.git
cd cognitive_analysis_tool-master
```

### 2. Install Python Requirements  
```bash
pip install -r requirements.txt
```
*(If `requirements.txt` is missing, install manually: `opencv-python numpy matplotlib`)*

### 3. Set up Arduino Sensors  
- Upload the `Light_sd_log_direct.ino` code to your Arduino Nano or Adalogger.  
- Connect sensors (Lux + GPS) as per the circuit diagrams.  

---

## ▶️ Usage  

### Run Cognitive Analysis  
```bash
python analysisTool.py
```

### Run Pupil Analysis  
```bash
python pupil_code/openCV_magic.py
```

### Plot GPS Data  
```bash
python pupil_code/gps_plot.py
```

---

## 📊 Example Output  
- Real-time pupil tracking with OpenCV  
- Light intensity vs. time plots  
- GPS trajectory visualization  
- Signal processing (filters, transforms)  

---

## 🤝 Contribution  
Contributions are welcome!  

1. Fork the repository  
2. Create a feature branch (`git checkout -b feature-name`)  
3. Commit your changes (`git commit -m "Add feature"`)  
4. Push to your branch (`git push origin feature-name`)  
5. Open a Pull Request  

---

## 📜 License  
This project is licensed under the terms of the **MIT License**. See [LICENSE.md](LICENSE.md) for details.  

---

🔥 With this tool, researchers and developers can explore how **cognitive responses** are influenced by **light, environment, and visual processing**.  
