---

# **Face Mask Detection using NVIDIA Jetson Nano**

## 📌 Overview

This project focuses on **real-time face mask detection** using **Deep Learning** and deployment on the **NVIDIA Jetson Nano**. The system detects whether a person is wearing a mask or not from live video streams or images. It leverages **TensorFlow, OpenCV, and EfficientNetB0** for accurate classification and real-time inference.

---

## 🎯 Objectives

* Detect faces with and without masks in real-time.
* Build an **affordable and portable solution** using the Jetson Nano.
* Use **transfer learning** with EfficientNetB0 for faster training and better accuracy.
* Deploy the trained model on an **edge device** (Jetson Nano) for practical applications.

---

## 🛠️ Tech Stack

* **Programming Language**: Python
* **Deep Learning Framework**: TensorFlow / Keras
* **Model**: EfficientNetB0 (Transfer Learning)
* **Computer Vision**: OpenCV
* **Hardware**: NVIDIA Jetson Nano, USB Camera / ESP32-CAM
* **Dataset**: Face Mask Detection Dataset (with images of people wearing and not wearing masks)

---

## 📂 Project Structure

```bash
├── data/                    # Dataset (with_mask / without_mask)
├── models/                  # Saved trained models
├── notebooks/               # Jupyter notebooks for training & testing
├── scripts/                 # Python scripts for preprocessing & detection
│   ├── train.py             # Model training script
│   ├── detect_mask_video.py # Real-time detection using webcam
│   └── preprocess.py        # Image resizing & preprocessing
├── results/                 # Graphs, accuracy/loss plots, test outputs
├── requirements.txt         # Dependencies
├── README.md                # Project documentation
└── LICENSE                  # License file
```

---

## 🚀 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/face-mask-detection-jetson-nano.git
cd face-mask-detection-jetson-nano
```

### 2. Create virtual environment (optional)

```bash
python -m venv venv
source venv/bin/activate  # Linux / Mac
venv\Scripts\activate     # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run training

```bash
python scripts/train.py
```

### 5. Run real-time detection

```bash
python scripts/detect_mask_video.py
```

---

## 📊 Results

* **Accuracy**: \~95% on test dataset
* **Real-time performance**: \~20 FPS on Jetson Nano
* Works in **different lighting conditions** and with multiple faces.

---

## 📸 Sample Outputs

|                ✅ With Mask               |                ❌ Without Mask               |
| :--------------------------------------: | :-----------------------------------------: |
| <img src="results/mask.png" width="250"> | <img src="results/no_mask.png" width="250"> |

---

## 🔮 Future Enhancements

* Support for **mobile deployment (TensorFlow Lite)**.
* Extend detection to **mask type classification** (cloth, surgical, N95).
* Integration with **IoT systems** for alerts & monitoring.

---

## 📜 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Contributors

* * Addaginta .Karthik ** – Project Lead & Developer
* **Dr.MGR University, Chennai** – Guidance & Support

---
