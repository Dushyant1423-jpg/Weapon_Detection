# 🔍 Weapon Detection System (Computer Vision + MQTT)

This project is a **Weapon Detection System** built using **YOLOv7** and **Computer Vision** with **MQTT integration**.
It detects weapons such as guns and knives from images or video streams and sends real-time data to an MQTT dashboard.

---

## 🚀 Features

* 🔫 Weapon detection (guns, knives, etc.)
* 👁️ Powered by YOLOv7 (real-time object detection)
* 📡 Real-time data transmission using MQTT
* 📊 Live monitoring on MQTT dashboard
* 🌐 Basic web interface using HTML
* ⚡ Fast and efficient processing

---

## 🛠️ Technologies Used

### Core:

* Python
* YOLOv7
* OpenCV

### Libraries:

* pytz
* requests
* sympy
* tqdm
* tensorboard
* flask
* flask-cors
* paho-mqtt (1.6.1)

### Dataset:

* COCO Dataset

### Frontend:

* HTML

---

## 📁 Project Structure

```id="4g7n2m"
weapon-detection/
│── main.py
│── get_coco.sh
│── model/
│── images/
│── utils/
│── templates/
│── mqtt/
```

---

## ⚙️ How to Run

1. Open the project folder

2. Install dependencies:

```bash id="9v2k8p"
pip install pytz requests sympy tqdm tensorboard flask flask-cors paho-mqtt==1.6.1 opencv-python
```

3. Download COCO dataset:

```bash id="7k3d1x"
bash get_coco.sh
```

4. Run the project:

```bash id="5q8z2r"
python main.py
```

---

## 💡 Future Improvements

* Improve detection accuracy
* Enhance real-time performance
* Add alert/notification system
* Improve frontend UI

---

## ⚠️ Disclaimer

This project is for educational purposes only.

---

## 🙌 Author

**Dushyant Singh**
