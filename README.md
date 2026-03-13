# Human Scream Detection for Crime Control
### AI-powered Acoustic Analysis for Emergency Detection

An intelligent **audio classification system** designed to detect human screams using machine learning and deep learning techniques.  
This project explores how **AI-driven acoustic monitoring systems** can support **crime prevention, emergency detection, and smart city safety infrastructure**.


## Project Overview

Public safety systems often rely on manual monitoring or delayed reporting during emergencies.  
This project investigates how **machine learning models can automatically detect distress signals such as human screams** from audio recordings.

By analyzing acoustic patterns using **MFCC and Mel Spectrogram features**, the system learns to classify audio signals into **scream vs non-scream categories**, enabling the possibility of **automated alert systems in high-risk environments**.

Potential applications include:

- Smart city surveillance systems
- Emergency detection in public spaces
- Security monitoring in transportation hubs
- Automated crime prevention systems

## Key Features

-  Processing of **6000+ real-world audio samples**
-  Audio preprocessing and noise reduction
-  Feature extraction using **MFCC (Mel Frequency Cepstral Coefficients)**
-  Spectral analysis through **Mel Spectrograms**
-  Deep learning classification using **Convolutional Neural Networks (CNN)**
-  Model evaluation using **Accuracy, Precision, Recall, F1-score, and Confusion Matrix**
-  End-to-end **machine learning pipeline**

## System Pipeline

Raw Audio Data
      ↓
Audio Preprocessing & Noise Reduction
      ↓
Feature Extraction (MFCC + Mel Spectrogram)
      ↓
Dataset Preparation
      ↓
CNN Model Training
      ↓
Model Evaluation
      ↓
Scream vs Non-Scream Prediction

## Technologies Used

**Programming**
- Python

**Libraries & Frameworks**
- NumPy
- Pandas
- Librosa
- Scikit-learn
- TensorFlow / Keras
- Matplotlib

**Development Environment**
- Jupyter Notebook
- Google Colab

## Dataset

The project uses an audio dataset containing **6000+ labeled sound samples**, categorized into:

- Child scream
- Women scream
- Normal background audio

Each audio file undergoes preprocessing and feature extraction before being used for model training.

## Model Evaluation Metrics

The model performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

These metrics help determine the effectiveness of the model in detecting distress signals while minimizing false alarms.

## Future Improvements

This project can be expanded into a real-world AI safety system through:

- Real-time audio stream processing
- Edge AI deployment for smart surveillance devices
- Integration with IoT security systems
- Multi-class emotion or distress detection
- Mobile or web-based emergency alert system

## Real-World Impact

AI-based acoustic monitoring can significantly enhance **public safety infrastructure** by enabling faster response to distress situations.

Potential impact areas include:

- Smart cities
- Public transportation hubs
- Campus safety systems
- Emergency response automation

## Author

Sakina Bohra

Final Year Computer Science Student  
Specializing in Artificial Intelligence & Machine Learning

📧 sakina.bohra2004@gmail.com  
🔗 LinkedIn: https://linkedin.com/in/sakina-bohra1007  

---

## Acknowledgment

This project was developed as part of academic research exploring how **AI-driven audio analysis can support crime detection and emergency response systems**.
