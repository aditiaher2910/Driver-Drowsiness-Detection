# 🚗 Driver Drowsiness Detection Alert System

## 📌 Overview

The Driver Drowsiness Detection Alert System is a real-time computer vision-based application designed to detect driver fatigue and prevent road accidents. The system monitors the driver's eye movements and triggers an alert when signs of drowsiness are detected.

---

## 🎯 Features

* 👁️ Real-time eye tracking using webcam
* 😴 Detects drowsiness based on eye closure (EAR - Eye Aspect Ratio)
* 🔔 Audio alert system when drowsiness is detected
* ⚡ Fast and efficient processing using OpenCV
* 🧠 Machine Learning / Deep Learning integration (optional)

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Libraries & Tools:** OpenCV, NumPy, Dlib / Mediapipe
* **Concepts Used:** Computer Vision, Facial Landmark Detection

---

## ⚙️ How It Works

1. Captures live video using webcam
2. Detects face and eyes using facial landmarks
3. Calculates Eye Aspect Ratio (EAR)
4. If EAR falls below a threshold for a certain time, system detects drowsiness
5. Triggers an alert sound to wake the driver

---

## 📁 Project Structure

```
driver-drowsiness-detection/
│
├── dataset/
├── models/
├── app.py
├── requirements.txt
├── alarm.wav
└── README.md
```

---

## ▶️ Installation & Usage

### 1. Clone the repository

```
git clone https://github.com/your-username/driver-drowsiness-detection.git
```

### 2. Navigate to the folder

```
cd driver-drowsiness-detection
```

### 3. Install dependencies

```
pip install -r requirements.txt
```

### 4. Run the project

```
python app.py
```

---

## 📸 Applications

* 🚘 Road safety systems
* 🚛 Commercial vehicle monitoring
* 🏢 Smart transportation systems

---

## ✅ Advantages

* Helps reduce accidents caused by fatigue
* Low-cost and real-time solution
* Easy to implement

---

## ⚠️ Limitations

* Performance depends on lighting conditions
* Requires camera access
* May vary with facial features or obstructions

---

## 🔮 Future Scope

* Mobile app integration
* Integration with IoT and smart vehicles
* Improved accuracy using deep learning models

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 🙌 Acknowledgements

* OpenCV community
* Dlib / Mediapipe contributors
