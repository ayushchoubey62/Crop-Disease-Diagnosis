# 🌿 Crop Disease Diagnosis App

An AI-powered desktop application to detect **plant leaf diseases** using deep learning and provide treatment suggestions — all through a user-friendly **Tkinter interface**.

---

## 🚀 Features

- 🧠 **Deep Learning-Based Prediction**
  - Uses a fine-tuned CNN model trained on 38 crop disease classes
  - Accurate identification with class-wise confidence scores

- 🖼️ **Tkinter GUI**
  - Sleek, responsive desktop interface
  - Dark mode / Light mode toggle 🌗

- 📸 **Image Upload & Live Camera Capture**
  - Diagnose from local images or real-time webcam feed

- 🛠️ **Image Tools**
  - Zoom, crop, filters, pan, enhancement

- 🧪 **Smart Prediction**
  - Non-crop image detection using heuristics or ML
  - Displays detailed disease description & symptoms
  - Offers treatment suggestions for each diagnosis

- 📊 **Diagnosis History**
  - View past predictions with timestamps and export support

- 🗂️ **Persistent Data**
  - Saves recent images, diagnosis results, and theme preference

- 📄 **Export to PDF**
  - One-click PDF report generation for farmer use

---

## 🧰 Technologies Used

| Component         | Details                                 |
|------------------|------------------------------------------|
| UI Framework      | Python Tkinter + ttk                    |
| Deep Learning     | TensorFlow / Keras (MobileNetV2 / CNN) |
| Image Processing  | OpenCV, PIL                             |
| PDF Export        | FPDF                                    |
| Data Persistence  | JSON (App state, history)               |

---

## 🧪 Model Details

- Input size: `150x150x3`
- Output: `38 classes`
- Trained with `ImageDataGenerator` & data augmentation
- Loss: `categorical_crossentropy`, Optimizer: `adam`

---

🔮 Future Improvements
Firebase login & cloud sync

Batch folder diagnosis

Real-time mobile version (Kivy / Flutter)

Graph-based analytics dashboard

Disease severity classification

🧑‍💻 Author
Ayush Choubey
🔗 https://www.linkedin.com/in/ayush-choubey-b2a366281
📬 ayushchoubey800@gmail.com


⚠️ Disclaimer
This tool is for educational and early-stage diagnostic purposes only. For commercial or clinical use, consult an expert or validate against field trials.

