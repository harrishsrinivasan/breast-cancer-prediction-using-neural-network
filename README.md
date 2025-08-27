#  Breast Cancer Prediction using Neural Networks

This project predicts whether a breast tumor is **malignant** (cancerous) or **benign** (non-cancerous) using a **Neural Network** model.  
The implementation is done in **Python** using **TensorFlow/Keras**, along with standard ML preprocessing and evaluation techniques.

---

##  Project Overview
- Load and preprocess the Breast Cancer dataset  
- Normalize features using `StandardScaler`  
- Build and train a Neural Network (Dense layers with activation functions)  
- Evaluate the model using accuracy, loss, confusion matrix, and classification report  
- Predict tumor type for new/unseen samples  

---

##  Repository Structure
breast-cancer-prediction/
│──data.csv # Dataset
│── breast_cancer_prediction.ipynb # Jupyter Notebook (EDA + Neural Network)
│── requirements.txt # Python dependencies
│── README.md # Project documentation

---

## ⚙️ Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/harrishsrinivasan/breast-cancer-prediction-using-neural-network.git
   cd breast-cancer-prediction
    ```

---

## Neural Network Model

- Input layer: number of neurons = number of features
- Hidden layers: Dense layers with ReLU activation
- Output layer: Single neuron with sigmoid activation (binary classification)
- Loss function: Binary Crossentropy
- Optimizer: Adam
- Metrics: Accuracy

---

## Results (example – update with your actual numbers)

- Training Accuracy: 91.69%
- Testing Accuracy: 85.46%
- Loss curve & accuracy curve plotted to track training progress



