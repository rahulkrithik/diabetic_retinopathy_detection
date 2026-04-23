<<<<<<< HEAD
# 🔬 Multi-Class Diabetic Retinopathy Detection

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-Deployed-red.svg)
![Accuracy](https://img.shields.io/badge/Accuracy-85%25-brightgreen.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

> An AI-powered web application that detects and grades Diabetic Retinopathy from retinal fundus images using deep learning.


## 📌 About The Project

Diabetic Retinopathy (DR) is the **leading cause of blindness** among working-age adults worldwide. Early detection is critical — but manual screening by ophthalmologists is slow and unavailable in rural areas.

This project uses **EfficientNet-B4** to automatically classify retinal images into 5 severity levels, enabling fast and accessible DR screening.

### Severity Classes Detected:
| Grade | Class | Description |
|-------|-------|-------------|
| 0 | No DR | No signs of retinopathy |
| 1 | Mild | Small microaneurysms only |
| 2 | Moderate | More than just microaneurysms |
| 3 | Severe | Severe NPDR, risk of progression |
| 4 | Proliferative DR | Advanced stage, high blindness risk |

---

## 🧠 Model Architecture

- **Base Model:** EfficientNet-B4 (pretrained on ImageNet)
- **Approach:** Transfer Learning + Fine-tuning
- **Input Size:** 380 × 380 pixels
- **Output:** Softmax over 5 classes

---

## 📊 Results

| Metric | Value |
|--------|-------|
| Training Accuracy | 85% |
| Validation Accuracy | 83% |
| Dataset | DDR Dataset or Aptos Dataset|
| No. of Classes | 5 |


## 🛠️ Tech Stack

- **Language:** Python 3.8+
- **Deep Learning:** TensorFlow 2.x / Keras
- **Model:** EfficientNet-B4
- **Web App:** Streamlit
- **Dataset:** [DDR Dataset](https://github.com/nkicsl/DDR-dataset) and APTOS Dataset

---

## 🚀 Getting Started

### Prerequisites
Make sure you have Python 3.8+ installed.

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/rahulkrithik/diabetic-retinopathy-detection.git

# 2. Navigate into the folder
cd diabetic-retinopathy-detection

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Streamlit app
streamlit run app.py
```

---

## 📁 Dataset

This project uses the **DDR Dataset** for Diabetic Retinopathy detection.

- 📥 Download from: [DDR Dataset GitHub](https://github.com/nkicsl/DDR-dataset)
- Place images inside the `/dataset` folder following this structure:

```
/dataset
  /train
    /0  /1  /2  /3  /4
  /test
    /0  /1  /2  /3  /4
```

> ⚠️ Dataset is not included in this repo due to size. Please download separately.

---

## 📦 Requirements

```
tensorflow>=2.8.0
streamlit>=1.10.0
numpy>=1.21.0
pandas>=1.3.0
matplotlib>=3.4.0
Pillow>=8.3.0
scikit-learn>=0.24.0
opencv-python>=4.5.0
```

---

## 🔮 Future Improvements

- [ ] Add Grad-CAM visualization to highlight affected regions
- [ ] Train on larger dataset (EyePACS) for better generalization
- [ ] Deploy on cloud (Hugging Face Spaces / Streamlit Cloud)
- [ ] Add patient report generation as PDF export
- [ ] Mobile-friendly UI

---

## ⭐ Support

If you found this project helpful, please consider giving it a **⭐ star** on GitHub!
It helps others discover the project and motivates me to keep building 🚀
=======
# diabetic_retinopathy_detection
Multi-class Diabetic Retinopathy detection using EfficientNet-B4 | 85% accuracy | Streamlit web app
>>>>>>> f0a207734d0e1fd0301a80560b025dba1151aeab
