# 🧠 Digit Recognizer — Kaggle Competition

A machine learning project built for the **Kaggle Digit Recognizer** competition.  
This project explores both traditional and deep learning approaches to handwritten digit classification using the MNIST dataset.

---

## 📘 Overview

The goal of the competition is to correctly identify digits (0–9) from grayscale images of handwritten digits.  
Two models were developed and submitted:

| Model | Technique | Public Score |
|--------|------------|--------------|
| Random Forest | Scikit-learn | **0.96257** |
| CNN (Keras) | Deep Learning | **0.98746** |


🧩 Models
---------

*   **Random Forest:** Simple baseline using pixel intensity features.
    
*   **CNN (Keras):** 3-layer convolutional neural network with ReLU activations and dropout regularization.
    

🏆 Results
----------

*   **Random Forest:** 96.257%
    
*   **CNN (Keras):** 98.746%Both models were successfully submitted via the Kaggle CLI.
