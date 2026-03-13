# Human Scream Detection for Crime Control

AI-powered audio classification system designed to detect **human scream sounds** from audio recordings using deep learning.

This project explores how **audio signal processing and neural networks** can support **automated emergency detection and smart city safety systems**.

---

# Project Overview

Human screams often indicate **distress, danger, or emergency situations**. Detecting these sounds automatically can enable faster responses in environments such as:

- Public surveillance systems  
- Smart city monitoring  
- Emergency detection platforms  

This project builds an **AI-based audio classification system** capable of distinguishing between different types of audio signals related to human screams.

The system converts audio signals into **Mel Spectrogram representations**, extracts spatial features using **MobileNetV2**, and learns temporal patterns using a **Bidirectional LSTM network** to perform classification.

---

# Key Features

- Audio preprocessing and noise reduction  
- Mel Spectrogram feature extraction from audio signals  
- Deep learning classification using **MobileNetV2 + Bidirectional LSTM**  
- Multi-class audio classification  
- Model performance evaluation using standard metrics  

---

# System Pipeline
## System Pipeline

```
Audio Input (.wav)
      │
      ▼
Audio Preprocessing
(Noise Reduction)
      │
      ▼
Mel Spectrogram Generation
      │
      ▼
Spectrogram → Image Representation
      │
      ▼
MobileNetV2 (CNN Feature Extraction)
      │
      ▼
Bidirectional LSTM
      │
      ▼
Dense Softmax Layer
      │
      ▼
Audio Classification
```
---

# Classes Predicted

The model classifies audio signals into the following categories:

- Child Scream  
- Women Scream  
- Normal Audio  

---

# Technologies Used

## Programming

- Python  
- NumPy  
- Librosa  
- OpenCV  

## Machine Learning & Deep Learning

- TensorFlow  
- Keras  
- MobileNetV2  
- Bidirectional LSTM  

## Data Analysis & Visualization

- Scikit-learn  
- Matplotlib  
- Seaborn  

---

# Dataset

The dataset contains labeled audio samples organized into three categories.
## Dataset Structure

```
dataset/
├── train/
│   ├── child/
│   ├── women/
│   └── normal/
└── test/
    ├── child/
    ├── women/
    └── normal/
```

Each audio file is converted into **Mel Spectrogram images**, which are used as input to the deep learning model.

---

# Audio Preprocessing

The audio processing pipeline includes:

- Loading audio signals using **Librosa**  
- Standardizing the sample rate  
- Applying **noise gating** to reduce background noise  
- Generating **Mel Spectrogram features**  
- Converting spectrograms into image format suitable for CNN input  

## Model Architecture

The deep learning architecture combines **convolutional neural networks (CNNs)** with **recurrent neural networks (RNNs)** to capture both spatial and temporal audio patterns.

### Architecture Overview

- **Input:** Mel Spectrogram Image (224 × 224)  
- **MobileNetV2:** Pretrained CNN for feature extraction  
- **Bidirectional LSTM:** Temporal pattern learning  
- **Dense Layer**  
- **Softmax Output Layer**

This hybrid architecture improves the model’s ability to detect **complex scream patterns in audio signals**.

---

## Model Training

Training configuration used in this project:

- **Optimizer:** Adam  
- **Loss Function:** Categorical Crossentropy  
- **Batch Size:** 32  
- **Epochs:** 30  

The dataset is divided into **training and testing sets** to evaluate model performance.

---

## Model Evaluation

Model performance is evaluated using several metrics:

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

The notebook also generates:

- Training vs Validation Accuracy plots  
- Loss curves  
- Classification reports  
- Confusion matrix visualizations  

These metrics help analyze how effectively the model distinguishes between **scream and non-scream audio signals**.

---

## Applications

Potential real-world applications of this system include:

- Smart city surveillance systems  
- Automated emergency detection platforms  
- Public safety monitoring systems  
- Crime prevention infrastructure  
- Intelligent urban monitoring systems  

Such systems can help **detect distress signals automatically and trigger faster emergency responses**.

---

## Future Improvements

Possible extensions of this project include:

- Real-time scream detection using microphone input  
- Integration with **IoT-based smart city monitoring systems**  
- Deployment using **Flask or FastAPI APIs**  
- Training on larger and more diverse audio datasets  
- Exploring **transformer-based audio models**

---

## Author

**Sakina Bohra**

Aspiring **Generative AI and Machine Learning Engineer** interested in building intelligent systems using:

- Artificial Intelligence  
- Deep Learning  
- Large Language Models  
- Smart City AI Systems
