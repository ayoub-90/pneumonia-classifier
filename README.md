# Pneumonia Detection Using CNN and LSTM

This project explores the detection of pneumonia using two deep learning architectures: **Convolutional Neural Networks (CNN)** and **Long Short-Term Memory (LSTM)** networks. The objective is to compare the performance of these models in classifying chest X-ray images.

---

## **Table of Contents**
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Model Architectures](#model-architectures)
  - [CNN](#cnn)
  - [LSTM](#lstm)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)

---

## **Project Overview**
Pneumonia is a serious respiratory condition that requires accurate and timely diagnosis. This project aims to leverage deep learning to classify chest X-ray images into two categories: **Pneumonia** and **Normal**. A comparative study between CNN and LSTM is performed to understand their suitability for this task.

---

## **Dataset**
- **Source**: Chest X-ray dataset from [Kaggle](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia).
- **Structure**:
  - Images labeled as `Pneumonia` or `Normal`.
  - Preprocessed by resizing to 150x150 pixels and normalizing pixel values.

---

## **Model Architectures**

### **CNN**
- **Purpose**: Extracts spatial features from images.
- **Architecture**:
  - Convolutional layers with ReLU activation.
  - MaxPooling layers for dimensionality reduction.
  - Fully connected layers for classification.

### **LSTM**
- **Purpose**: Processes sequentially reshaped image data.
- **Architecture**:
  - LSTM layers for sequential pattern recognition.
  - Dense layers for classification.

---

## **Results**
| Metric               | CNN                  | LSTM                 |
|----------------------|----------------------|----------------------|
| Training Accuracy    | ~95%                | ~85%                |
| Validation Accuracy  | ~92%                | ~80%                |
| Training Time        | Short (~10 mins)    | Long (~30 mins)     |

---

## **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/ayoub-90/pneumonia-classifie.git
   ```
2. Navigate to the project directory:
   ```bash
   cd pneumonia-detection
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## **Usage**
1. Open the notebook:
   ```bash
   jupyter notebook
   ```
2. Run the notebook `pneumonia_detection.ipynb` to train and evaluate the models.
3. Visualize results and compare performance metrics.

---

## **Contributors**
- **Elharem Ayoub**
- **Adam Elouarga**

---

## **License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to contribute by submitting issues or pull requests!
