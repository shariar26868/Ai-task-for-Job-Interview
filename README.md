# Ai-task-for-Job-Interview
# Duplicate Question Detection Using Machine Learning  

This project focuses on detecting duplicate questions using **Natural Language Processing (NLP)** and **Machine Learning (ML)**. It applies **text preprocessing, feature extraction, and classification models** to determine whether two questions have the same meaning.  

## 🚀 Project Overview  
- **Data Preprocessing:**  
  - Cleaned and normalized text (removed special characters, expanded contractions).  
  - Tokenized and vectorized text using **TF-IDF**.  
- **Handling Class Imbalance:**  
  - Applied **Random Undersampling** to balance the dataset.  
- **Model Development:**  
  - Implemented a **deep learning model (ANN)** using TensorFlow/Keras.  
  - Used **Logistic Regression** for comparison.  
- **Evaluation:**  
  - Measured performance using **accuracy, confusion matrix, and ROC curve**.  

## 📂 Dataset  
- The dataset contains pairs of questions labeled as duplicate (`1`) or not duplicate (`0`).  
- Loaded and processed 10,000 samples for model training.  
