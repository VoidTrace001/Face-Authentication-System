# 🔐 Face Authentication System

A full **Face Authentication System** built in Python for recognizing and verifying faces using webcam or image input.
This project demonstrates a high-quality folder and module structure, making it easy to understand, use, and extend!

---

## 🧠 Overview

This system allows you to:

- 🎥 Detect and recognize faces in real-time from your webcam.
- ✅ Authenticate known users against stored face data.
- 🏫 Easily extend for attendance, security access, or login systems.

---

## 📁 Project Structure

```
Face-Authentication-System/
├── database/           # Stored face images or face encodings
├── modules/            # Core logic and face processing scripts
├── config.py           # Configuration file
├── main.py             # Main execution script
├── requirements.txt    # Python dependencies
├── .gitignore          # Git ignore rules
├── LICENSE             # MIT License
└── README.md           # Project documentation
```

---

## 🚀 Features

- ✔ Real-time face detection and recognition
- ✔ Modular and clean Python codebase
- ✔ Easy setup and run instructions
- ✔ Works with webcam or image datasets
- ✔ Configurable via `config.py`

---

## 🛠️ Installation

### 1. Clone the repository:

```bash
git clone https://github.com/VoidTrace001/Face-Authentication-System.git
cd Face-Authentication-System
```

### 2. Create & activate a virtual environment (recommended):

```bash
python3 -m venv venv
# macOS / Linux
source venv/bin/activate
# Windows
venv\Scripts\activate
```

### 3. Install dependencies:

```bash
pip install -r requirements.txt
```

> ⚠️ **Note:** `dlib` and `face-recognition` may require additional system dependencies.
> - On **Windows**: Install [CMake](https://cmake.org/) and Visual Studio Build Tools.
> - On **Linux/macOS**: Run `sudo apt-get install build-essential cmake` (Linux) or `brew install cmake` (macOS).

---

## ▶️ How to Run

Simply run the main script:

```bash
python main.py
```

You should see a live webcam window detecting and recognizing faces.

> Make sure your webcam is connected and allowed access.

---

## 👤 Adding New Users

1. Capture or add face images of the new user into the `database/` folder.
2. Create a sub-folder with the user's name (e.g., `database/John/`).
3. Add at least 3–5 clear images of their face for better accuracy.
4. Re-run `main.py` — the system will automatically encode and register the new user.

---

## 📦 Dependencies

All required libraries are listed in `requirements.txt`. Key ones include:

| Library | Purpose |
|---|---|
| `opencv-python` | Webcam capture and video processing |
| `face-recognition` | Face detection and recognition |
| `dlib` | Underlying ML engine for face-recognition |
| `numpy` | Array and matrix operations |

Install them all via:

```bash
pip install -r requirements.txt
```

---

## ⚙️ Configuration

You can modify `config.py` to adjust:

- Camera index (default webcam = `0`)
- Recognition tolerance/threshold
- Database path
- Frame resize settings for performance

---

## 💡 Usage Tips

- Add more images per person (5–10) for better recognition accuracy.
- Make sure lighting is sufficient during face capture.
- Use a consistent background when adding user images to the database.
- Lower the tolerance value in `config.py` for stricter matching.

---

## 📌 Use Case Ideas

This project can be extended for:

| Use Case | Description |
|---|---|
| 🏫 Attendance System | Auto-mark attendance using face recognition |
| 🚪 Door Access Control | Unlock doors for registered faces |
| 🔐 Secure Login | Replace password login with face verification |

---

## 🤝 Contributing

Contributions are welcome! Please check out [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

Feel free to:
- ⭐ Star the repo
- 🐛 Report issues
- 💬 Suggest enhancements
- 📤 Submit pull requests

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 🙌 Acknowledgements

- [face-recognition](https://github.com/ageitgey/face_recognition) by Adam Geitgey
- [OpenCV](https://opencv.org/) community
- [dlib](http://dlib.net/) by Davis King

---

Thanks for checking out the Face Authentication System!  
Happy coding! 🚀
