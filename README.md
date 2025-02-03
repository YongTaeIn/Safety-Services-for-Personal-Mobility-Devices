# KICK_OFF _킥보드 프로젝트 관련 코드.

### 1. detect 
1) python School_zone_detect.py
2) python Speed_bump_detect.py
3) python Sudden_stop_detect.py
4) python Analysis_rating.py

### 2. WEB
1) execute web/src/admin.html

 
###  3. Device (Raspberry pi)
1) activate conda environment
2) python Upload_cam.py
3) python upload_gps.py
4) python upload_gyro.py

###  4. APP
1) download all file in app folder

###  5. Risk Detection (YOLOv5) 
1) activate conda environment
2_1) cd yolov5_pothole/get_image_Folder
2_2) python integrated.py
3_1) cd yolov5_speedbump/get_image_Folder
3_2) python integrated.py

###  6. Parking Check (Visual localization) 
1) activate conda environment
2) python Visual_localization.py


### 7. Paper
link : https://ieeexplore.ieee.org/abstract/document/10271873



# 🚀 KICK_OFF: Design and Implementation of Intelligent Safety Services for Personal Mobility Devices
**AI-powered safety enhancement for personal mobility**  

![Kickboard Safety](https://user-images.githubusercontent.com/your-image-url.png)  

---

## 📌 Project Overview  
KICK_OFF is an AI-driven system designed to enhance kickboard safety by detecting risks, managing GPS tracking, and enabling real-time visual localization.  
This project integrates **computer vision (YOLOv5)**, **sensor-based risk detection**, and **web/app interfaces** to create a comprehensive smart mobility solution.  

📖 **Paper Reference**:  
[IEEE MetaCom 2023 - Smart Kickboard Risk Detection](https://ieeexplore.ieee.org/abstract/document/10271873)  

---

## 🔥 Features  
✔ **Real-time hazard detection** (School zones, speed bumps, sudden stops)  
✔ **AI-based pothole & speed bump recognition** (YOLOv5)  
✔ **Visual localization-based parking validation**  
✔ **IoT integration with Raspberry Pi for GPS, gyro, and camera uploads**  
✔ **Web-based admin dashboard & mobile app**  

---

## 🛠️ Project Structure  

### 1️⃣ Risk Detection Modules  

#### 🚦 Hazard Detection  
```sh
python School_zone_detect.py
python Speed_bump_detect.py
python Sudden_stop_detect.py
python Analysis_rating.py
