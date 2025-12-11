# Deep Learning I – Final Project (AASD 4010)

This repository contains the complete implementation and documentation for the Deep Learning I Final Project. It includes exploratory data analysis, preprocessing, model development, hyperparameter tuning, evaluation, and a final report.

---

## 📌 Project Overview
This project demonstrates a full end-to-end deep learning workflow:

- Data preprocessing  
- Exploratory Data Analysis (EDA)  
- Deep learning model development  
- Hyperparameter tuning  
- Evaluation using metrics and visualizations  
- Final conclusions and insights  

---

## 📁 Repository Structure

```
project/
│── code/
│   ├── model_training.ipynb
│   ├── preprocessing.ipynb
│   ├── evaluation.ipynb
│   └── utils.py
│
│── data/
│   └── sample_dataset.csv
│
│── report/
│   └── AASD4010_FinalReport.docx
│
│── slides/
│   └── presentation.pdf
│
└── README.md
```

---

## 📊 Dataset (Sample Included)

A small subset of the dataset used in this project is included for reproducibility.

### **sample_dataset.csv**
```
id,text,label
1,"The product was delivered late and the quality was disappointing.",negative
2,"Amazing experience! I would definitely recommend this to my friends.",positive
3,"The service was okay, not too bad but not great either.",neutral
4,"Terrible support. They never responded to my emails.",negative
5,"Absolutely loved it! Exceeded my expectations.",positive
6,"The packaging was damaged but the product was fine.",neutral
7,"I am extremely satisfied with the results.",positive
8,"Not worth the price. I regret buying this.",negative
9,"It works well, but the setup process was confusing.",neutral
10,"Fantastic quality and fast delivery!",positive
```

---

## 🧠 Methodology

### **1. Data Analysis**
- Class balance  
- Distribution of labels  
- Text length analysis  
- Cleaning steps (removing noise, tokenization, etc.)  

### **2. Model Development**
- Deep learning model (RNN / GRU / LSTM / Transformer — whichever you used)  
- Embeddings  
- Loss function & optimizer  
- Training loop / epochs  

### **3. Evaluation**
- Accuracy  
- Loss curves  
- Confusion matrix  
- Prediction samples  

---

## 🚀 How to Run the Project

### **Install dependencies**
```
pip install -r requirements.txt
```

### **Run Jupyter/Colab Notebooks**
1. Open the `.ipynb` files  
2. Update dataset path if required  
3. Run all cells top-to-bottom  

### **Run Python scripts**
```
python train.py
python evaluate.py
```

---

## 📈 Results Summary

This section includes:

- Train vs validation accuracy  
- Train vs validation loss  
- Confusion matrix  
- Sample predictions  
- Hyperparameter tuning results  

*(Replace with your actual values in the report if needed.)*

---

## 📝 Final Report
The report follows the required academic structure:

- Background  
- Problem statement  
- Dataset analysis  
- Methodology  
- Model training  
- Results  
- Tuning  
- Conclusions  

---

## 🧩 Project Requirements Checklist
This project includes:

- A deep learning model  
- EDA and preprocessing  
- Visual metrics and evaluation  
- Code + report + slides  
- A reproducible dataset sample  

---

## 📬 Contact
For questions or clarifications, feel free to reach out through GitHub or email.
