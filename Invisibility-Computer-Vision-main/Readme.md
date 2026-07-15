# 👻 Ghost Invisibility Mode using Computer Vision

A real-time Computer Vision project that creates an **invisibility cloak (ghost mode)** effect using **Python, OpenCV, MediaPipe, and NumPy**. The application captures the background, detects the user using AI-based segmentation, and replaces the user's body with the stored background. Hand gestures are used to toggle between **Visible** and **Invisible** modes.

---

## 📌 Features

- 🎥 Real-time webcam processing
- 🧠 AI-powered human segmentation using MediaPipe
- ✋ Hand gesture recognition
- 👻 Ghost / Invisibility effect
- 🔄 Toggle visibility using pinch gesture
- 📸 Save screenshots
- 🔁 Recalibrate background anytime
- ⚡ Fast real-time performance

---

## 🛠️ Technologies Used

- Python 3.12
- OpenCV
- MediaPipe
- NumPy

---

## 📂 Project Structure

```
Ghost-Invisibility-Mode/
│
├── main.py              # Main application
├── engine.py            # Segmentation and invisibility engine
├── requirements.txt     # Project dependencies
├── README.md
├── LICENSE
└── screenshots/         # Demo images (optional)
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/bilagimitali-sys/Ghost-Invisibility-Mode.git
cd Ghost-Invisibility-Mode
```

### 2. Create a virtual environment (Optional)

```bash
python -m venv venv
```

Activate it

Windows

```bash
venv\Scripts\activate
```

Linux / macOS

```bash
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
python main.py
```

---

## 🎮 Controls

| Key | Action |
|------|---------|
| **Q** | Quit application |
| **R** | Recalibrate background |
| **S** | Save screenshot |

---

## ✋ Gesture Controls

1. Stand still for **3 seconds** to capture the background.
2. Show **both hands**.
3. Spread both hands until the yellow box appears.
4. Pinch your **thumb and index finger** together.
5. The invisibility effect is activated.
6. Pinch again to return to normal.

---

## 🧠 How It Works

1. Webcam captures live video.
2. Background image is stored.
3. MediaPipe Selfie Segmentation detects the person.
4. A segmentation mask is generated.
5. The human region is replaced with the stored background.
6. MediaPipe Hands detects 21 hand landmarks.
7. Pinch gesture toggles invisibility mode.

---

## 📸 Demo

Add your screenshots inside the **screenshots/** folder.

Example

```
screenshots/
├── demo1.png
├── demo2.png
└── demo3.png
```

You can also add a GIF demonstrating the project.

---

## 🚀 Future Improvements

- Multiple gesture controls
- Better background replacement
- Object detection integration
- Custom virtual backgrounds
- GPU acceleration
- Performance optimization

---

## 📖 Applications

- Computer Vision Learning
- Augmented Reality
- AI Demonstrations
- Virtual Meetings
- Entertainment
- Human Segmentation Research

---

## 📋 Requirements

- Python 3.12
- Webcam
- Windows / Linux / macOS

---

## 📦 Dependencies

```
opencv-python
mediapipe==0.10.14
numpy
```

---

## ⚠️ Notes

- Works best with a static background.
- Ensure good lighting for better segmentation.
- Python **3.12** is recommended for MediaPipe compatibility.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

## 📄 License

This project is licensed under the Apache 2.0 License.

---

## 👩‍💻 Author

**Mitali Bilagi**

GitHub: https://github.com/bilagimitali-sys

---

⭐ If you found this project useful, don't forget to **Star** the repository!