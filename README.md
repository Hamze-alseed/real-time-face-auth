# Face Recognition and Varification System

## 🔍 Overview
A real-time face recognition system using InsightFace (ArcFace embeddings)
with face enrollment and verification and liveness detection.

## 🚀 Features
- Face enrollment
- Face verification using cosine similarity
- Uses blink detection for liveness varification
- Google Colab compatible

## 🔐 Liveness Detection
To prevent spoofing attacks (photos or videos), a blink-based liveness
detection mechanism is implemented using MediaPipe Face Mesh.
Authentication is only allowed after detecting a real eye blink.

## System Pipeline

1. Enrollment
- Capture video of the user
- Detect face
- Extract embedding
- Store embedding vector
2. Verification
- Process test video frame-by-frame
- Detect eye blink (liveness)
- Compare embeddings using cosine similarity
- Grant or deny access


## 🧠 Tech Stack
- Python
- OpenCV
- InsightFace
- ONNX Runtime
- Scikit-learn

## ⚙️ How to Run
1. Open the notebook in Google Colab
2. Upload FaceID_System.ipynb
3. Run the install cell
4. Enroll your face
5. Test verification

## ⚠️ Security Note

Displayed frames are resized only for visualization
and do not affect recognition or liveness detection accuracy.


## 📈 Future Improvements
- Multi-user support
- Web interface

## 👤 Author
- Hamze Alsaeed 
- AI Engineer — Computer Vision & Deep Learning
