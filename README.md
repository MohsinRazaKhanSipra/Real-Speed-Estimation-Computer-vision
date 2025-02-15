# 🚗 Vehicle Speed Estimation Using AI & Computer Vision

## 📌 Overview
This project demonstrates how to estimate vehicle speed from video footage using **YOLOv8**, **ByteTrack**, and **Supervision**. The system detects vehicles, tracks them across frames, and computes their speed using **perspective transformation** for real-world measurements.

## 🔧 Features
✅ **Vehicle Detection** – YOLOv8 for real-time object detection  
✅ **Multi-Object Tracking** – ByteTrack for consistent tracking  
✅ **Perspective Transformation** – Converts pixel distances to real-world measurements  
✅ **Speed Calculation** – Computes speed in km/h from movement data  
✅ **Real-time Processing** – Efficiently handles video frame-by-frame  

## 💂 Installation & Setup
Ensure you have Python installed, then install dependencies:
```bash
pip install ultralytics supervision opencv-python numpy
```

## 📺 Usage
1. **Upload a Video**: Place your video file in the project folder.
2. **Run the Script**:
   ```bash
   python speed_estimation.py
   ```
3. **View Results**: The script will display vehicle detection, tracking, and estimated speeds.

## 🏃️‍♂️ Code Structure
```
📂 Vehicle-Speed-Estimation
├── 📋 speed_estimation.py   # Main script for speed calculation
├── 📂 videos                # Folder for input videos
├── 📋 requirements.txt      # Dependencies list
├── 📋 README.md             # Project documentation
```

## ⚡ Speed Calculation Formula
```python
Speed (km/h) = (Distance traveled in pixels / Time in seconds) * 3.6
```

## 🔥 Demo
[![Vehicle Speed Estimation](https://your-image-or-demo-link.com)](https://www.youtube.com/watch?v=2QkXjGXGNFE)

## 📖 Medium Article
For a detailed step-by-step guide, check out my article:  
[How to Estimate Vehicle Speed Using Object Detection and Tracking](https://medium.com/@mohsinrazasepra/how-to-estimate-vehicle-speed-using-object-detection-and-tracking-e68e5404450d)

## 🎯 Applications
- 🚦 **Traffic monitoring & analytics**
- 🚔 **Law enforcement & speed tracking**
- 🤖 **Autonomous vehicle development**

## 🛠️ Contributions
Feel free to open an issue or submit a pull request to enhance the project!

## 📌 Connect with Me
🔗 **Portfolio:** [mohsinrazaofficial.netlify.app](https://mohsinrazaofficial.netlify.app/)  
📧 **Email:** mohsinrazasepra@gmail.com  
🌟 **Medium:** [@mohsinrazasepra](https://medium.com/@mohsinrazasepra)
