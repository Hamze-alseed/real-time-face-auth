# Real-Time Face Recognition System

## 🔍 Overview
A real-time face recognition system using InsightFace (ArcFace embeddings)
with face enrollment and verification.

## 🚀 Features
- Face enrollment
- Face verification using cosine similarity
- Runs in real-time
- Google Colab compatible

## 🔐 Liveness Detection
To prevent spoofing attacks (photos or videos), a blink-based liveness
detection mechanism is implemented using MediaPipe Face Mesh.
Authentication is only allowed after detecting a real eye blink.

## 🧠 Tech Stack
- Python
- OpenCV
- InsightFace
- ONNX Runtime
- Scikit-learn

## ⚙️ How to Run
1. Open the notebook in Google Colab
2. Run the install cell
3. Enroll your face
4. Test verification

## 📈 Future Improvements
- Multi-user support
- Web interface
