# Deepfake Detection System

A web-based Deepfake Detection System built using Flask, TensorFlow, OpenCV, and FFT (Fast Fourier Transform) analysis.

This project detects whether an uploaded image or video is REAL or AI-generated / manipulated.

---

# Features

- Detects deepfake images
- Supports video analysis
- FFT-based frequency domain analysis
- Deep learning model integration
- Modern responsive frontend
- Confidence score prediction
- Flask web application

---

# Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Flask
- HTML
- CSS

---

# Project Structure

```bash
FFT_Deepfake_Detector/

│── app.py
│── requirements.txt
│── README.md
│
├── model/
│   └── FFT_SAVEDMODEL/
│
├── static/
│   ├── uploads/
│   └── fft_outputs/
│
├── templates/
│   └── index.html
```

---

# How It Works

1. User uploads image or video
2. FFT transformation is applied
3. Frequency-domain patterns are extracted
4. Deep learning model predicts:
   - REAL
   - FAKE
5. Result displayed with confidence score

---

# Dataset

The model is trained using:
- Real human face datasets
- AI-generated photorealistic face datasets
- FFT-transformed frequency-domain images

---

# Future Improvements

- Hybrid RGB + FFT architecture
- Mobile application support

---

# License

This project is for educational and research purposes.
