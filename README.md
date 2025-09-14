# ✋ Hand Gesture Volume Control

A simple **computer vision project** that allows you to control your system volume using hand gestures (thumb & index finger distance).  
Built with **OpenCV** and **MediaPipe**.

## 🎥 How It Works
- Opens webcam and tracks your hand in real-time  
- Detects **index fingertip (id=8)** and **thumb tip (id=4)**  
- Measures distance between them:
  - **Far apart → Volume Up**
  - **Close together → Volume Down**

## 🛠️ Tech Stack
- **OpenCV** – Image capture and drawing  
- **MediaPipe** – Hand landmark detection  
- **PyAutoGUI** – Sending volume key presses  

## 📂 Usage (Run Locally)

1. **Clone the repository**
   ```bash
   git clone https://github.com/vnguyen243/gesture_volume_control.git
   cd gesture_volume_control
2. **Create virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
3. **Install dependencies**
   ```bash
   pip install -r requirements.tx
4. **Run the scripts**
   ```bash
   python volume_control.py
5. **Exit**
   Pres **Esc** to close the program
