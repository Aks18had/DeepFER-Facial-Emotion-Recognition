# DeepFER: Facial Emotion Recognition Using Deep Learning

A deep learning-based **Facial Emotion Recognition (FER)** system that classifies facial expressions into **7 emotions** using a custom CNN and MobileNetV2 transfer learning.

## 🎯 Objective

Classify facial expressions into **Angry, Disgust, Fear, Happy, Neutral, Sad, and Surprise** using deep learning.

## 📊 Dataset

- **35,887** facial images
- **7 emotion classes**
- **48×48 grayscale** images
- Train: **25,942** | Validation: **2,879** | Test: **7,066**

## ⚙️ Approach

**Preprocessing:** Normalization, one-hot encoding, data augmentation, class weighting

**Models:** Custom CNN + MobileNetV2 transfer learning

**Optimization:** Adam, Dropout, Batch Normalization, Early Stopping, ReduceLROnPlateau, Model Checkpointing

**Evaluation:** Accuracy, Precision, Recall, F1-score, Confusion Matrix, Error Analysis

## 📈 Results

| Model | Test Accuracy | Macro F1 |
|---|---:|---:|
| **Custom CNN** | **50.38%** | **42.99%** |
| MobileNetV2 (Frozen) | 40.70% | 34.45% |

**Custom CNN performed better** on this dataset.

## 🔍 Key Findings

- **Happy** was recognized most effectively.
- **Angry, Disgust, Fear, and Sad** showed higher confusion.
- Low-resolution images and class imbalance affected performance.

## 🎥 Application

**Camera → Face Detection → Preprocessing → CNN → Emotion Prediction**

The pipeline can be extended for real-time emotion-aware applications.

## 🛠️ Tech Stack

**Python · TensorFlow/Keras · CNN · MobileNetV2 · OpenCV · NumPy · Matplotlib · Scikit-learn · Google Colab**

## 🚀 How to Run
- Open the notebook in Google Colab.
- Mount Google Drive.
- Place the dataset in the required folder.
- Run the notebook cells sequentially.

## 🔮 Future Improvements
- Higher-resolution images
- Fine-tuned pretrained models
- Improved class balancing
- Stronger CNN architectures
- Real-time deployment


## 👨‍💻 Author

**Akshad Goyanka**
