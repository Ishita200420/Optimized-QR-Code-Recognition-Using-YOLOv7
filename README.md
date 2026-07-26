# Optimized QR Code Recognition in Retail Stores Using YOLOv7 and Cuckoo Search Algorithm
![Python](https://img.shields.io/badge/Python-3.10-blue)
![YOLOv7](https://img.shields.io/badge/YOLOv7-Object%20Detection-success)
![License](https://img.shields.io/badge/License-MIT-green)

## Project Overview
This project focuses on enhancing **QR code recognition in retail environments** by integrating **YOLOv7** (a state-of-the-art object detection model) with the **Cuckoo Search Optimization algorithm** for improved detection and efficiency. The solution aims to optimize recognition speed and accuracy, making it suitable for real-time applications in retail and inventory management.

---

## 🔄 Workflow

```text
Input Image
      │
      ▼
Image Pre-processing
(Perspective Correction + Super Resolution)
      │
      ▼
YOLOv7 QR Detection
      │
      ▼
Cuckoo Search Optimization
      │
      ▼
Multi-engine QR Decoding
(Pyzbar + ZXing + OpenCV)
      │
      ▼
Decoded QR Output
```

---

## Tech Stack
- **Language**: Python 3.x
- **Libraries**: 
  - YOLOv7
  - OpenCV (`cv2`)
  - NumPy, Pandas
  - Matplotlib, Seaborn
  - Pillow
  - Pyzbar
  - Weights & Biases (for experiment tracking)
- **Algorithms**:
  - YOLOv7 Object Detection
  - Cuckoo Search Algorithm for optimization

---

## Project Structure
```
├── optimized-qr-code-recognition-in-retail-stores.ipynb  # Main Kaggle notebook
├── requirements.txt                                       # Dependencies
├── README.md                                              # Project documentation
└── results/                                               # Detection results & visualizations
```

---

## Installation & Setup
1. **Clone the repository**
   ```bash
   git clone https://github.com/Ishita200420/qr-code-recognition-yolov7-cuckoo.git
   cd qr-code-recognition-yolov7-cuckoo
   ```

2. **Create a virtual environment (optional but recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate    # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

---

## How to Run
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook optimized-qr-code-recognition-in-retail-stores.ipynb
   ```
2. Follow the steps in the notebook to:
   - Load the dataset or your own dataset
   - Run YOLOv7 detection
   - Apply Cuckoo Search Optimization
   - View performance metrics and visualizations

---

## Results

| Metric | Result |
|--------|--------|
| Training Images | 1,169 |
| Testing Images | 145 |
| Training Epochs | 110 |
| Detection Model | YOLOv7 |
| Optimization Algorithm | Cuckoo Search Algorithm |
| Detection Accuracy | 95% |
| Decoding Accuracy | 98% |
| F1 Score (QR Images) | 99% |
| F1 Score (Negative Images) | 90% |
| Processing Pipeline | YOLOv7 + CSA + Pyzbar + ZXing + OpenCV |
| Deployment | Real-time Retail QR Recognition |

<img width="829" height="330" alt="image" src="https://github.com/user-attachments/assets/bda4aed4-f813-47b8-af41-8ea635d53f39" />

<img width="462" height="208" alt="image" src="https://github.com/user-attachments/assets/73596d53-b2ad-41a8-a704-f47d3aa5083e" />

<img width="1041" height="437" alt="image" src="https://github.com/user-attachments/assets/47b35bfb-2660-42e1-afd2-cab27b2dacb8" />

### Key Achievements

- Robust detection under blur, occlusion and illumination changes
- Automatic hyperparameter optimization using Cuckoo Search
- Multi-engine QR decoding for improved robustness
- Real-time inference suitable for retail applications

---

## Future Enhancements
- Integrate with a real-time retail POS system.
- Extend optimization to multi-object scenarios.
- Deploy as a web-based or mobile application.

---

## Dataset & References
- Kaggle Notebook: https://www.kaggle.com/code/ishita200420/optimized-qr-code-recognition-in-retail-stores
- [YOLOv7 Official GitHub](https://github.com/WongKinYiu/yolov7)
- Research on **Cuckoo Search Algorithm**

---

## Authors
- **Ishita Rana:**
  www.linkedin.com/in/ishita-rana-03651b305
- **Leena:**
  www.linkedin.com/in/leenabansal1108
