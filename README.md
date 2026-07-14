# Handwritten Character Recognition using CNN

## Horizon TechX Machine Learning Internship – Task 3

### 📌 Project Overview

This project was developed as part of the **Horizon TechX Machine Learning Internship**. The objective is to build a **Convolutional Neural Network (CNN)** that recognizes handwritten digits from images using the **MNIST dataset**.

The model learns patterns from thousands of handwritten digit images and predicts the correct digit with high accuracy.

---

## 🎯 Objective

Develop a deep learning model capable of recognizing handwritten digits (0–9) using image classification techniques.

---

## 🛠️ Technologies Used

- Python
- Google Colab
- TensorFlow
- Keras
- NumPy
- Matplotlib

---

## 📂 Dataset

**Dataset:** MNIST Handwritten Digits Dataset

The MNIST dataset contains:

- 60,000 training images
- 10,000 testing images
- 10 digit classes (0–9)
- Image size: **28 × 28 pixels**

The dataset is included with TensorFlow and downloads automatically when the notebook is executed.

---

## 🧠 Deep Learning Model

This project uses a **Convolutional Neural Network (CNN)** consisting of:

- Conv2D Layer
- MaxPooling2D Layer
- Conv2D Layer
- MaxPooling2D Layer
- Flatten Layer
- Dense Layer
- Dropout Layer
- Output Layer (Softmax)

---

## ⚙️ Project Workflow

1. Import required libraries.
2. Load the MNIST dataset.
3. Display sample handwritten images.
4. Normalize image pixel values.
5. Reshape images for CNN input.
6. Build the CNN model.
7. Compile the model.
8. Train the model.
9. Evaluate model performance.
10. Predict handwritten digits.
11. Visualize predictions.
12. Save the trained model.

---

## 📊 Model Evaluation

The model is evaluated using:

- Training Accuracy
- Validation Accuracy
- Test Accuracy
- Loss Function

Typical test accuracy is around **98%–99%**.

---

## 📁 Project Structure

```text
HorizonTechX_HandwrittenCharacterRecognition/
│
├── HorizonTechX_HandwrittenCharacterRecognition.ipynb
├── README.md
├── requirements.txt
├── HandwrittenCharacterRecognition.keras
└── screenshots/
    ├── sample_digits.png
    ├── accuracy_graph.png
    └── prediction_result.png
```

---

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/YourUsername/HorizonTechX_HandwrittenCharacterRecognition.git
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Open the Notebook

Open the notebook using **Google Colab** or **Jupyter Notebook**.

### 4. Run All Cells

The MNIST dataset will automatically download during execution.

### 5. Train the Model

Run all cells in sequence to train the CNN model and evaluate its performance.

---

## 📈 Results

- Successfully classified handwritten digits (0–9).
- Achieved high prediction accuracy on the test dataset.
- Demonstrated the effectiveness of CNNs for image classification tasks.

---

## 🚀 Future Enhancements

- Recognize handwritten alphabets using the EMNIST dataset.
- Build a complete OCR (Optical Character Recognition) system.
- Deploy the model using Streamlit or Flask.
- Train on custom handwritten character datasets.

---

## 📚 Learning Outcomes

Through this project, the following concepts were learned:

- Image preprocessing
- Computer Vision fundamentals
- Convolutional Neural Networks (CNN)
- Deep Learning with TensorFlow/Keras
- Model evaluation and prediction
- Image classification

---

## 👨‍💻 Author

**Thrishi**

Machine Learning Intern – Horizon TechX

---

## 📜 License

This project was developed for educational purposes as part of the **Horizon TechX Machine Learning Internship**.
