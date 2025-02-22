# Performance Evaluation of ML Algorithms for Efficient Resume-Job Matching

## 📌 Project Overview
This project aims to explore different approaches to **matching job descriptions with resumes** by gradually transitioning from **rule-based methods** to **machine learning (ML), deep learning, and generative AI**. 

## 🛠️ Methodology
We will follow a structured approach:
1. **Rule-Based Matching**: Exact keyword and skill matching between job descriptions and resumes.
2. **Machine Learning (ML) Algorithms**: Using classical ML techniques (e.g., decision trees, logistic regression) to improve matching.
3. **Deep Learning**: Implementing advanced NLP models like transformers (BERT, GPT) for better understanding of job descriptions and resumes.
4. **Generative AI**: Enhancing data generation and refining job-resume matching using LLMs.

## 📂 Dataset
We are merging two datasets:
1. **Resume Dataset**: Contains job titles and skills extracted from resumes.
2. **Job Description Dataset**: Includes job titles and their descriptions.

### **Pre-Merging Analysis**
Before merging, we will:
- Identify **common and unique job titles** in both datasets.
- Analyze **possible title variations** (e.g., "Software Engineer" vs. "Software Developer").
- Decide whether to introduce **manual job title mapping** before merging.

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

### **3️⃣ Run the Analysis & Merging Script**
```bash
python analyze_titles.py   # Pre-merge job title analysis
python merge_datasets.py   # Merge job descriptions with resumes
```

## 📌 Next Steps
✅ **Merge datasets with logical correctness**  
✅ **Evaluate rule-based methods before moving to ML**  
🔜 **Train ML models and explore deep learning approaches**  
🔜 **Enhance dataset using Generative AI**  

## 🤝 Contributing
Feel free to contribute! Open issues and submit PRs to improve job-resume matching techniques.

## 📜 License
This project is licensed under the [MIT License](LICENSE).

---

Let me know if you’d like to add anything! 🚀


