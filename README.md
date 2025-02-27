# Performance Evaluation of ML Algorithms for Efficient Resume-Job Matching

## 📌 Project Overview

This project aims to explore different approaches to **matching job descriptions with resumes** by gradually transitioning from **rule-based methods** to **machine learning (ML), deep learning, and generative AI**.

## 🫠 Methodology

We follow a structured approach:

1. **Rule-Based Matching**: Implemented exact keyword and skill matching between job descriptions and resumes.
2. **Machine Learning (ML) Algorithms**: Trained multiple models including Logistic Regression, Random Forest, Support Vector Machine, Decision Tree, Gradient Boosting, and XGBoost to improve matching accuracy.
3. **Deep Learning**: Planning to implement advanced NLP models like transformers (BERT, GPT) for better semantic understanding of job descriptions and resumes.
4. **Generative AI**: Future enhancements will focus on improving dataset augmentation and refining job-resume matching using LLMs.

## 💂️ Models Used

We have trained and evaluated multiple ML models:

- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)
- Decision Tree Classifier
- Gradient Boosting Classifier
- XGBoost Classifier

Each model has been evaluated based on accuracy and classification reports.

## 📂 Dataset

We are using an **Updated Resume Dataset**, which contains:

1. **Resume Text**: Raw resume content.
2. **Job Titles**: The corresponding job categories for classification.

### **Data Preprocessing Steps:**

- Removed stopwords and lemmatized words using NLTK.
- Used TF-IDF vectorization to convert resume text into numerical features.
- Encoded job titles as numeric labels for model compatibility.

## 🚀 Installation & Usage

### **1️⃣ Clone the Repository**

```bash
git clone https://github.com/your-repo-name.git
cd your-repo-name
```

### **2️⃣ Install Dependencies**

```bash
pip install -r requirements.txt
```

### **3️⃣ Train and Save Models**

```bash
python train_models.py   # Train and save all ML models
```

### **4️⃣ Run Model Evaluation & UI**

```bash
python evaluate_models.py   # Evaluate trained models and plot accuracy
python run_ui.py            # Launch the UI for resume-job matching
```

## 🎯 Model Evaluation & Visualization

We have plotted accuracy scores for all models to compare performance. Additionally, a UI (built with Gradio or Streamlit) allows users to input their resumes (PDF/Text) and select a model for prediction.




