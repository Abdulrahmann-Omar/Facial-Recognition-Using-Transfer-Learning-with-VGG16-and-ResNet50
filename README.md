# Facial-Recognition-Using-Transfer-Learning-with-VGG16-and-ResNet50
This project uses transfer learning with VGG16 and ResNet50 to classify facial images. A facial recognition dataset is preprocessed and split for training, validation, and testing. Model performance is evaluated and compared based on accuracy and loss across epochs.
-----------
# Facial Recognition with Transfer Learning (VGG16 & ResNet50)

This project applies transfer learning using pre-trained VGG16 and ResNet50 models to classify facial images from a public dataset. It demonstrates the effectiveness of using deep CNN architectures for facial recognition tasks.

## 📁 Dataset
- **Source:** [Kaggle Facial Recognition Dataset](https://www.kaggle.com/datasets/apollo2506/facial-recognition-dataset)
- Images are organized into labeled folders for supervised classification.
- Split into training (70%), validation (20%), and test (10%).

## 🧠 Models Used
### VGG16
- Pre-trained on ImageNet
- Top layers removed and replaced with custom classification layers
- Base layers frozen for feature reuse

### ResNet50
- Pre-trained on ImageNet
- Global Average Pooling + Dense softmax layer added
- Base layers frozen

## 🛠️ Workflow
1. **Dataset Loading and Preprocessing**
2. **Normalization** (Pixel values scaled to [0,1])
3. **Model Definition** (VGG16 and ResNet50)
4. **Training & Validation**
5. **Model Evaluation**
6. **Performance Visualization** (Accuracy and loss curves)

## 📊 Evaluation Metrics
- Accuracy
- Loss
- Visualizations of performance over epochs

## ✅ Results
Both models were evaluated on unseen test data. Metrics showed strong classification performance, with comparative plots to visualize learning progress.

## 📦 Dependencies
- TensorFlow / Keras
- Matplotlib
- KaggleHub
- NumPy

Install required libraries using:
```bash
pip install tensorflow matplotlib kagglehub numpy
