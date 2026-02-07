# ✍️ Handwritten Character Recognition  
### CodeAlpha Internship – Task 3

## 📌 Project Overview

 **CodeAlpha Machine Learning Internship**.  
The goal of the project is to recognize handwritten characters (digits) using **image processing** and **deep learning techniques**.

A **Convolutional Neural Network (CNN)** is implemented to classify handwritten digits from the **MNIST dataset** with high accuracy.


## 🎯 Objective

The objective of this project is to:
- Identify handwritten digits from images
- Apply deep learning techniques for image classification
- Understand the working of CNNs on image data


## 📂 Dataset

- **Dataset Used:** MNIST Handwritten Digits  
- **Classes:** Digits (0–9)  
- **Image Size:** 28 × 28 grayscale images  
- **Source:** TensorFlow Keras built-in dataset  

📌 *Note:*  
The MNIST dataset is automatically loaded using TensorFlow, so no dataset files are stored in the `data/` folder.

## 🧠 Model Used

- **Model Type:** Convolutional Neural Network (CNN)
- **Layers Used:**
  - Convolutional Layers
  - MaxPooling Layers
  - Fully Connected (Dense) Layers
  - Softmax Output Layer

The trained model is saved for reuse.



## 🛠️ Tools & Technologies

- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Google Colab / Jupyter Notebook

  ## 📥 Clone the Repository

To get started, first clone the repository:

```bash
git clone https://github.com/ravikiranediga/CodeAlpha_Tasks.git
cd CodeAlpha_Tasks/CodeAlpha_Handwritten_Character_Recognition


## 🚀 How to Run the Project

### Option 1: Google Colab (Recommended)
1. Open Google Colab
2. Upload the notebook file
3. Run all cells

### Option 2: Local Machine
```bash
pip install -r requirements.txt
jupyter notebook handwritten_character_recognition.ipynb


