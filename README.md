# 🫁 Tuberculosis Detection Using Deep Learning

A Deep Learning-based project that aims to detect Tuberculosis (TB) from chest X-ray images using image classification techniques.

The project explores the application of Convolutional Neural Networks (CNNs) and image preprocessing techniques to classify chest X-ray images and assist in identifying potential signs of Tuberculosis.

---

## 📌 Project Overview

Tuberculosis is an infectious disease that primarily affects the lungs. Early identification plays an important role in diagnosis and treatment.

This project uses Deep Learning and Computer Vision techniques to analyze chest X-ray images and predict whether an image belongs to a **Normal** or **Tuberculosis** category.

The model is developed and trained using Python and TensorFlow/Keras.

## ✨ Features

- Chest X-ray image classification.
- Image preprocessing and normalization.
- Data augmentation to improve model generalization.
- Deep Learning model training and evaluation.
- Prediction on input X-ray images.
- Model experimentation using a Jupyter Notebook.

## 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Deep Learning | TensorFlow, Keras |
| Image Processing | OpenCV |
| Data Processing | NumPy, Pandas |
| Visualization | Matplotlib |
| Development | Jupyter Notebook, VS Code |
| Version Control | Git, GitHub |

## 📂 Project Structure

```text
tb-detection/
│
├── app/
│   └──              # Application-related files
│
├── dataset/
│   └──              # Chest X-ray dataset
│
├── model/
│   └──              # Saved model files
│
├── notebooks/
│   └── Tuberculosis_Fin.ipynb
│
├── main.py           # Main application entry point
│
├── requirements.txt  # Project dependencies
│
├── .gitignore
│
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/tuberculosis-detection.git
```

### 2. Navigate to the Project Directory

```bash
cd tuberculosis-detection
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

Activate it:

**Windows:**
```bash
venv\Scripts\activate
```

**Linux / macOS:**
```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the Project

```bash
python main.py
```

For model training and experimentation, open the Jupyter Notebook:

```bash
jupyter notebook notebooks/Tuberculosis_Fin.ipynb
```

## 🧠 Methodology

The project follows a Deep Learning workflow:

1. **Data Collection:** Obtain chest X-ray images belonging to the required classification categories.
2. **Data Preprocessing:** Resize images, normalize pixel values and prepare data for model training.
3. **Data Augmentation:** Apply transformations such as rotation, horizontal flipping and zooming to increase training data diversity.
4. **Model Development:** Build and train a Deep Learning classification model.
5. **Model Evaluation:** Evaluate the model using appropriate classification metrics.
6. **Prediction:** Use the trained model to generate predictions for input chest X-ray images.

## 📊 Evaluation Metrics

The following metrics can be used to evaluate model performance:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## 🚀 Future Improvements

- Improve model performance using larger and more diverse datasets.
- Experiment with transfer learning architectures.
- Add Grad-CAM visualization for model interpretability.
- Develop a more user-friendly prediction interface.
- Improve model generalization through further experimentation.

## ⚠️ Disclaimer

This project is developed for educational and research purposes only. It is not intended to replace professional medical diagnosis or clinical evaluation. Predictions should not be used as the sole basis for medical decisions.

## 👩‍💻 Author

**Your Name**

Computer Science Engineering Student

[GitHub](https://github.com/YOUR-USERNAME) | [LinkedIn](https://www.linkedin.com/)

---

⭐ If you find this project interesting, consider giving the repository a star!
