Chest X-Ray Pneumonia Detection using CNN

A deep learning-based medical imaging project that detects **Pneumonia** from Chest X-Ray images using a Convolutional Neural Network (CNN) built with TensorFlow and Keras.

🚀 Features
* Detects **Pneumonia** from Chest X-Ray images
* CNN model built using TensorFlow/Keras
* Data Augmentation for better accuracy
* Accuracy & Loss visualization graphs
* Confusion Matrix and Classification Report
* Automatic dataset folder detection
* Saves trained model (`.h5`)

🧠 Technologies Used
* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab

 📥 Dataset
This project uses the **Chest X-Ray Pneumonia Dataset**.

Dataset Structure:

```bash
train/
    NORMAL/
    PNEUMONIA/

test/
    NORMAL/
    PNEUMONIA/
```



⚙️ Installation

1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/Chest-Xray-Pneumonia-Detection.git
cd Chest-Xray-Pneumonia-Detection
```

2️⃣ Install Requirements

bash
pip install -r requirements.txt


▶️ Run Project

bash
python chest_xray_cnn.py


📊 Model Architecture

The CNN model contains:

* Conv2D Layers
* MaxPooling Layers
* Dense Layers
* Dropout Layer
* Sigmoid Output Layer

Used for Binary Classification:
* NORMAL
* PNEUMONIA


📈 Output
The project generates:
* Training Accuracy Graph
* Validation Accuracy Graph
* Training Loss Graph
* Validation Loss Graph
* Confusion Matrix
* Classification Report


💾 Model Saving

The trained model is automatically saved as:

chest_xray_model.h5


📸 Sample Results
Example outputs:
* High classification accuracy
* Pneumonia prediction detection
* Visual training performance graphs



🔮 Future Improvements
* Add Streamlit Web App
* Deploy Online using Streamlit Cloud
* Use Transfer Learning (VGG16 / ResNet50)
* Add PDF Medical Report Generation
* Add Real-Time X-Ray Upload Prediction

👨‍💻 Author
Muhammad Hayyan

⭐ Support
If you like this project:
* Star this repository ⭐
* Fork this project 🍴
* Share with others 🚀

📜 License
This project is for educational and learning purposes.
