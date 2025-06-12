# 👤 Gender and Age Detection System
This project uses deep learning and computer vision to detect faces in images or webcam feeds and accurately predict the **gender** and **age group** of each person. It supports real-time processing and works under varying lighting and pose conditions.

## 🔍 Features
- Detects faces from images and live webcam input  
- Predicts **Gender**: Male or Female  
- Predicts **Age Groups**:  
  `(0–2)`, `(4–6)`, `(8–12)`, `(15–20)`, `(25–32)`, `(38–43)`, `(48–53)`, `(60–100)`  
- Real-time prediction with confidence scores  
- Annotates results directly on the image/video stream  
- Handles cases where no face is detected

## 🧠 Technologies Used
- Python  
- OpenCV  
- TensorFlow  
- Caffe  
- NumPy  
- argparse

🚀 How to Run
For image input:-
python detect.py --image path/to/image.jpg

For webcam input:-
python detect.py
