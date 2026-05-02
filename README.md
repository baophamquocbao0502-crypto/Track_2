# 🚗 NVIDIA End-to-End Self-Driving Car

Train an NVIDIA CNN to autonomously drive a car by cloning 
human driving behaviour — camera image as input, 
steering angle as output.
## 📁 Project Structure
nvidia-end2end-self-driving/
├── drive.py          # Real-time deployment
├── README.md         # Documentation
└── requirements.txt  # Dependencies
## 🛠 Tech Stack
- Python 3.11
- TensorFlow 2.20
- Keras
- Flask + Socket.IO
- OpenCV
- Udacity Self-Driving Car Simulator
## 🚀 How to Run
# 1. Install dependencies
pip install -r requirements.txt
# 2. Run server
python drive.py
# 3. Open Udacity Simulator → Autonomous Mode
## 📦 Model Download
Download trained model: model_04.h5
## 📊 Results
✅ Track 1: Completed full lap
✅ Track 2: Generalized to never-seen-before track
