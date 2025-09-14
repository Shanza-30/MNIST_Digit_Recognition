# 🔢 MNIST Digit Recognition

This project recognizes handwritten digits (0–9) from the MNIST dataset using machine learning models.  
It includes data preprocessing, model training with Logistic Regression and CNN, evaluation using accuracy and confusion matrix, and comparison of results.

## 🚀 Project Workflow

1. **Data Preprocessing**
   - Loaded MNIST dataset  
   - Normalized pixel values (0–255 → 0–1)  
   - One-hot encoded the target labels  

2. **Model Building**
   - **Logistic Regression:** Baseline model for quick evaluation  
   - **Convolutional Neural Network (CNN):** Deep learning model for higher accuracy  

3. **Evaluation**
   - Accuracy, confusion matrix, classification report  
   - Visualization of training/validation accuracy and loss curves  

4. **Results Comparison**
   - Compared Logistic Regression vs CNN performance  
   - CNN achieved **~98–99% accuracy** on test set  

## 📊 Results
| Model               | Test Accuracy |
|--------------------|--------------|
| Logistic Regression | ~92–93% |
| CNN (Deep Learning) | ~98–99% |

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:** NumPy, Matplotlib, Seaborn, scikit-learn, TensorFlow/Keras  
