🫀 Atrial Fibrillation Detection using CNN-BiLSTM

This project implements an end-to-end deep learning pipeline for detecting Atrial Fibrillation (AFib) from raw ECG signals using a CNN + BiLSTM hybrid architecture. The model is trained and evaluated on the MIT-BIH Atrial Fibrillation Database (PhysioNet) and achieves high classification performance on real clinical ECG data.

🔍 Key Features

📊 Dataset: MIT-BIH Atrial Fibrillation Database (PhysioNet)

⏱️ ECG segmentation (7.5-second windows, 50% overlap)

🧠 Hybrid CNN + BiLSTM architecture

⚖️ Class imbalance handling using class weights

📈 Comprehensive evaluation:

Accuracy

Precision, Recall, F1-Score

ROC-AUC

Confusion Matrix

💾 Trained model export (.h5)

🧠 Model Architecture

1D Convolutional layers for local ECG feature extraction

Bidirectional LSTM layers for temporal dependency modeling

Fully connected layers for binary classification (Normal vs AFib)

🏆 Results
Metric	Value
Test Accuracy	99.09%
AFib Recall	98.95%
AFib Precision	96.31%
ROC-AUC	High (see ROC curve)
📂 Project Structure
├── main.py / notebook.ipynb
├── afib_cnn_bilstm_final.h5
├── confusion_matrix.png
├── roc_curve.png
├── training_history.png
├── README.md

🛠️ Tech Stack

Python

NumPy, Pandas

TensorFlow / Keras

Scikit-learn

WFDB (PhysioNet)

Matplotlib, Seaborn

📎 Dataset Source

MIT-BIH Atrial Fibrillation Database – PhysioNet

🚀 Future Work

Patient-wise cross-validation

Real-time AFib detection

<img width="931" height="621" alt="image" src="https://github.com/user-attachments/assets/13ef0925-6d00-4935-af19-b9e2ca6b1c4b" />
<img width="484" height="367" alt="image" src="https://github.com/user-attachments/assets/38a5d72a-fe9e-44f9-a6d2-500870451108" />
<img width="496" height="369" alt="image" src="https://github.com/user-attachments/assets/d0725837-4d9b-4fbb-861e-e1aa252192ef" />
<img width="933" height="743" alt="image" src="https://github.com/user-attachments/assets/2c9acf65-fce8-4e55-a256-04aa96ca7bfc" />



Transformer-based ECG modeling

Deployment using TensorFlow Lite
