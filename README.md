# Plant Disease Prediction System 🌱

### **Project Overview**
The Plant Disease Prediction System is a machine learning-based solution designed to predict diseases in plants using image data and advanced deep learning techniques. This project aims to assist farmers and agricultural professionals in diagnosing plant diseases quickly and accurately, enabling timely treatment and prevention.

---

## **Features**

### 🌟 **Advanced Machine Learning**
- **Convolutional Neural Networks (CNNs)** for image classification.
- Pre-trained deep learning models like **ResNet**, **VGG**, or custom-built models.

### 🎨 **Interactive Web Interface**
- **Streamlit** integration for user-friendly, interactive predictions.
- Upload images and get real-time insights on plant health.

### 📊 **Data Visualization**
- Visualize results using **matplotlib** and **seaborn**.
- Model performance metrics such as accuracy, precision, recall, and loss curves.

### ⚙️ **Extensibility**
- Modular code design for easy enhancement and deployment.
- Support for additional datasets and custom models.

---

## **Project Workflow**

1. **Data Preprocessing:**
   - Collect plant leaf image datasets.
   - Preprocess images (resizing, normalization, augmentation).

2. **Model Training:**
   - Train a CNN model on the processed dataset.
   - Fine-tune hyperparameters for improved performance.

3. **Prediction Pipeline:**
   - Deploy the model for predictions on new image inputs.
   - Display results in an interactive Streamlit interface.

4. **Visualization:**
   - Generate graphs for model evaluation.
   - Provide insights through heatmaps and performance metrics.

---

## **Tech Stack**

### **Languages & Tools**
- **Python**: Core language.
- **Streamlit**: Web interface for predictions.
- **TensorFlow / PyTorch**: Deep learning frameworks.
- **OpenCV**: Image processing.
- **NumPy, Pandas**: Data manipulation and preprocessing.
- **Matplotlib, Seaborn**: Visualization.

---

## **Setup Instructions**

### 1️⃣ **Clone the Repository**

git clone https://github.com/RudraanshGupta/Plant-Disease-Prediction-System.git
cd Plant-Disease-Prediction-System

### 2️⃣ **Install Dependencies**

pip install -r requirements.txt

### 3️⃣ **Run the Application**

streamlit run Test_plant_diseases.ipynb
