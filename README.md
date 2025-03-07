


# 🚀 Design and Implementation of Intelligent Safety Services for Personal Mobility Devices
**AI-powered safety enhancement for personal mobility**  

---

## 📌 Project Overview  
This project is an AI-based system designed to improve personal mobility safety through real-time hazard detection and notification, indoor parking return confirmation, and driving habit analysis.
This project integrates **computer vision (YOLOv5, NetVLAD)**, **sensor-based driving habit analysis**, and **web/app interfaces** to create a comprehensive smart mobility solution.  

📖 **Paper Published**:  
[IEEE MetaCom 2023 - Design and Implementation of Intelligent Safety Services for Personal Mobility Devices](https://ieeexplore.ieee.org/abstract/document/10271873) 

🗓 **Conference Date**: *26-28 June 2023*  

📅 **Publication Date (IEEE Xplore)**: *06 October 2023*  

📍 **Conference**: *2023 IEEE International Conference on Metaverse Computing, Networking and Applications (MetaCom)*
---

## 🔥 Features  
✔ **Real-time hazard detection** (School zones, speed bumps, sudden stops)  
✔ **AI-based pothole & speed bump recognition** (YOLOv5)  
✔ **Visual localization-based parking validation** (NetVLAD)  
✔ **IoT integration with Raspberry Pi for GPS, gyro, and camera uploads**  
✔ **Web-based admin dashboard & mobile app**  

---

## 🛠️ Project Structure  

### 1️⃣ Risk Detection Modules  

#### 🚦 Hazard Detection  
```
python School_zone_detect.py
python Speed_bump_detect.py
python Sudden_stop_detect.py
python Analysis_rating.py

# Activate environment
conda activate <your_env>

# Pothole detection
cd yolov5_pothole/get_image_Folder
python integrated.py

# Speed bump detection
cd yolov5_speedbump/get_image_Folder
python integrated.py
```
---

### 2️⃣ Web Interface 🌐

```
execute web/src/admin.html
```

---

### 3️⃣ IoT Device Integration (Raspberry Pi) 🖥️
Handles real-time data uploads from sensors and cameras.
```
# Activate Conda environment
conda activate <your_env>

# Upload camera and sensor data
python Upload_cam.py
python upload_gps.py
python upload_gyro.py
```

---
### 4️⃣ Mobile App 📱
```
# Download all files in the 'app' folder
```


---
### 5️⃣ Parking Validation via Visual Localization 📍
Ensures proper kickboard parking using AI-based visual localization (NetVLAD).
```
# Activate environment
conda activate <your_env>

# Run visual localization
python Visual_localization.py
```

---
🎥 Experiment Results & Hardware Specifications
For detailed experiment results, hardware specifications, and implementation details, visit the project page below:

🔗 
[Hackster.io Project Page]
(https://ieeexplore.ieee.org/abstract/document/10271873](https://www.hackster.io/490781/multiple-safety-service-for-electric-scooter-7d3def) 

This page includes:
✅ Real-world test videos showcasing system performance
✅ Hardware specifications and sensor details
✅ Implementation insights on AI-based safety services

Check it out to explore how our intelligent safety system enhances personal mobility! 🚀

