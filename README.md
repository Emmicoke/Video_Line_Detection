# Line Detection with OpenCV

## 📖 Description
This repository demonstrates a basic **real-time line detection system** using a webcam feed.  
The project applies **color masking**, **Canny edge detection**, and **Hough Line Transform** to detect and draw straight lines on the captured frames.  

It uses **OpenCV**, **NumPy**, and can optionally be extended with **Stereolabs ZED SDK (pyzed.sl)** if depth sensing or stereo vision is required.  

---

## ✨ Features
- 🎥 Real-time video capture from webcam  
- 🎨 HSV-based masking to filter specific colors (currently set to detect white)  
- 🖼️ Canny edge detection to highlight strong edges  
- 📏 Hough Line Transform to detect and draw lines on the video feed  
- ⌨️ Press **ESC (27 key)** to exit  

---

## ⚙️ Requirements
- Python **3.8+**  
- Webcam (internal or external)  
- Libraries:
  - `opencv-python`
  - `numpy`
  - `pyzed` (optional, only needed if you plan to use ZED camera features)

Install dependencies with:
```bash
pip install opencv-python numpy
