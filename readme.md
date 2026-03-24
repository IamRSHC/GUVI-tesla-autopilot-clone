# 🚗 Tesla Autopilot Clone – Object Detection using YOLOv8

## 📌 Overview

This project implements a real-time **object detection system** inspired by Tesla’s Autopilot using a pre-trained YOLOv8 model.

The system detects and visualizes multiple objects in road scenes such as vehicles, pedestrians, and traffic signals from input images.

---

## 🎯 Key Features

* 🔍 Multi-object detection using YOLOv8
* 🖼️ Side-by-side comparison (Original vs Detected)
* 📊 Console-based object count analytics
* ⚡ Fast inference using pre-trained model
* 🎯 Confidence threshold filtering

---

## 🧠 Methodology

### 1. Model

* Used **YOLOv8 (Ultralytics)** pre-trained on the COCO dataset
* Selected lightweight yet efficient variant for faster inference

### 2. Processing Pipeline

1. Load input images from dataset folder
2. Perform object detection using YOLOv8
3. Draw bounding boxes with class labels
4. Display results alongside original images
5. Print detected object counts in console

---

## 📂 Dataset

* Custom dataset of real-world traffic scenes
* Includes:

  * Cars 🚗
  * Buses 🚌
  * Trucks 🚚
  * Motorcycles 🏍️
  * Pedestrians 🚶
  * Traffic lights 🚦

---

## 🛠️ Tech Stack

* Python
* Ultralytics YOLOv8
* OpenCV
* NumPy
* Matplotlib

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/IamRSHC/GUVI-tesla-autopilot-clone.git
cd tesla-autopilot-clone
```

### 2. Install dependencies

```bash
pip install ultralytics opencv-python matplotlib
```

### 3. Run the notebook

Open the Jupyter notebook and run all cells sequentially.

---

## 📊 Sample Output

* Displays **Original vs Detected images**
* Bounding boxes with class labels and confidence
* Console output showing object counts per image

---

## ⚠️ Limitations

* Uses pre-trained model (no custom training)
* May miss small or occluded objects
* Performance depends on image quality

---

## 🚀 Future Improvements

* Train on custom dataset for higher accuracy
* Add real-time video processing
* Deploy as a web application
* Optimize for edge devices

---

## 🧾 Conclusion

This project demonstrates how deep learning models like YOLOv8 can be used to build efficient and practical object detection systems for autonomous driving scenarios.

---

## 👨‍💻 Author

R S HAREECHARAN

---
