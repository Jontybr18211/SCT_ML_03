# 🐱🐶 Cats and Dogs Classification using SVM

This repository contains a simple yet effective image classification pipeline that distinguishes between cat and dog images using Support Vector Machine (SVM). The workflow includes hyperparameter tuning, model calibration, and saving the trained artifacts for future use.

## 📌 Project Highlights

- ✅ Feature extraction and preprocessing
- ✅ Hyperparameter tuning with `GridSearchCV`
- ✅ Model calibration using `CalibratedClassifierCV` for probability outputs
- ✅ Trained model and scaler saved using `joblib` for reuse

---

## 🛠️ Tech Stack

- Python
- Scikit-learn
- NumPy
- Jupyter Notebook

---

## 📂 File Structure

├── Cats_and_Dogs_classification.ipynb # Main training and calibration notebook
├── models/
│ ├── svm_cat_dog_calibrated.pkl # Calibrated SVM model
│ └── scaler.pkl # Scaler used for input features


---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/cats-dogs-svm-classifier.git
   cd cats-dogs-svm-classifier
