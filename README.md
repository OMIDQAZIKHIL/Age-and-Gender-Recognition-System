# 👤 Age and Gender Recognition System

A **real-time Age and Gender Recognition System** developed using **Python** and **OpenCV Deep Learning**. This system detects human faces in images, videos, or live webcam feeds and predicts both **age group** and **gender**. It is designed for learning, research, and demonstrating computer vision and deep learning skills.

---

## 📌 Project Overview

The Age and Gender Recognition System automates the task of identifying a person’s age range and gender using deep learning models. It utilizes OpenCV’s **DNN (Deep Neural Network)** module along with **pre-trained Caffe models** to detect faces and classify age and gender in real time.

The system supports **image input**, **video files**, and **live webcam feed**, making it flexible and practical for real-world applications. This project is suitable for **academic projects**, **research**, and **portfolio demonstrations**.

---

## 🛠️ Technologies Used

* **Python** – Core logic & deep learning inference  
* **C++** – Optional implementation  
* **Other / Scripts** – Supporting files  

Additional tools and libraries:

* OpenCV (Computer Vision & DNN)
* Caffe (Pre-trained deep learning models)
* NumPy

---

## ✨ Key Features

* 🧑‍🤝‍🧑 Real-time face detection  
* 👶👦🧑👵 Age group prediction  
* 🚹🚺 Gender classification  
* 🎥 Works with images, videos, and webcam  
* 🖥️ Displays annotated output frames  
* 💾 Option to save processed output  
* ⚙️ Supports CPU and GPU execution  

---

## 🗂️ System Modules

* **Face Detection Module** – Detects human faces using deep neural networks  
* **Age Prediction Module** – Classifies detected faces into predefined age groups  
* **Gender Prediction Module** – Predicts gender using a trained classification model  
* **Output & Visualization Module** – Displays and saves annotated results  

---

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/OMIDQAZIKHIL/Age-and-Gender-Recognition-System.git
cd Age-and-Gender-Recognition-System
```

### 2. Install Required Dependencies
```bash
pip install opencv-python numpy
```

**Optional:** For GPU acceleration, OpenCV must be built with CUDA support.

---

## 🏃 Run Instructions

### ▶️ Python Implementation
```bash
python AgeGender.py --input <image_or_video_file> --camera --output <optional_output_path> --device cpu
```

**Notes:**
* Leave `<image_or_video_file>` empty to use the live webcam  
* Use `--device gpu` to enable GPU acceleration  

### ▶️ C++ Implementation (Optional)
```bash
cmake .
make
./AgeGender <input_file>
```

* Leave `<input_file>` empty to use the live webcam  

---

## 🎯 Use Case

* Academic mini and final year projects  
* Learning computer vision and deep learning  
* Research and experimentation  
* Portfolio demonstration of Python & OpenCV skills  

---

## 🔒 Security & Best Practices

* Local processing of data and models  
* No external data transmission  
* Efficient computation using optional GPU support  
* Modular code structure for easy customization  

---

## 👨‍💻 Author

**Omid Qazikhil**  
Python Developer | Computer Vision Enthusiast | Cybersecurity Student  

GitHub: https://github.com/OMIDQAZIKHIL  
Email: omid.qazikhil2020@gmail.com  

---

## 📜 License

This project is intended for **educational purposes**.  
You are free to use, modify, and distribute it with proper credit to the author.

---

⭐ If you like this project, don’t forget to **star the repository**!
