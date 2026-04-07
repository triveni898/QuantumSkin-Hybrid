# 🧬 QuantumSkin-Hybrid: Hybrid Quantum-Classical Skin Disease Diagnosis

## 🚀 Overview

QuantumSkin-Hybrid is an advanced hybrid deep learning framework that combines classical Convolutional Neural Networks (CNNs) with Variational Quantum Circuits (VQCs) for intelligent skin disease diagnosis.

The system leverages both classical and quantum computing to improve classification performance, especially in complex and imbalanced medical datasets.

---

## 🎯 Problem Statement

Skin cancer diagnosis is challenging due to:

* High similarity between disease classes
* Limited and imbalanced datasets
* Lack of interpretability in AI models

This project addresses these challenges using a hybrid quantum-classical approach.

---

## 🧠 Key Innovation

* Hybrid CNN + Quantum Model
* Variational Quantum Circuits (VQC) for feature refinement
* Improved performance on imbalanced datasets
* Reliable predictions with calibration (ECE = 0.03)
* Explainability using Grad-CAM

---

## 🏗 System Architecture

Pipeline:

1. Image preprocessing (resizing, normalization)
2. CNN feature extraction (EfficientNet / ResNet)
3. Feature compression
4. Mapping features to quantum states
5. Variational Quantum Circuit processing
6. Final classification with confidence scores

---

## ⚙️ Tech Stack

### Classical

* Python
* TensorFlow / PyTorch
* EfficientNet-B0 / ResNet50
* NumPy, Pandas

### Quantum

* PennyLane
* Qiskit
* Variational Quantum Circuits

### Visualization

* Matplotlib
* Captum (Grad-CAM)



## 📂 Dataset

* HAM10000 Dataset
* Multi-class skin disease classification

---

## ▶️ How to Run

```bash
git clone https://github.com/triveni898/QuantumSkin-Hybrid.git
cd QuantumSkin-Hybrid
pip install -r requirements.txt
```

### Run Project

* Open `notebooks/QuantumSkin_Hybrid_Model.ipynb`
* Run all cells in Google Colab or Jupyter Notebook

---

## 📁 Project Structure

```
QuantumSkin-Hybrid/
│
├── notebooks/              # Colab notebook
├── src/
│   ├── classical/          # CNN model
│   ├── quantum/            # VQC implementation
│   ├── hybrid/             # Combined model
│   └── training/           # Training scripts
│
├── results/                # Graphs & outputs
├── docs/                   # Project report
├── README.md
├── requirements.txt
└── LICENSE
```

---

## 🤝 Contributors

* Setty Triveni
* G. Charitha
* P. Bhargavi
* M.V. Mahalakshmi

### 👨‍🏫 Mentor

* Dr. T. Manikumar

---

## 💡 Key Highlights

* Real-world application of Quantum Machine Learning in healthcare
* Hybrid architecture combining CNN and quantum circuits
* Designed for scalability and future quantum hardware

---

## 🔮 Future Scope

* Deployment using real quantum hardware
* Integration with healthcare systems
* Real-time diagnosis application

---

## ⚠️ Note

This project uses quantum simulators (PennyLane/Qiskit) due to limited availability of real quantum hardware.

---

## ⭐ Conclusion

QuantumSkin-Hybrid demonstrates how hybrid quantum-classical models can improve accuracy, reliability, and interpretability in medical image classification.
