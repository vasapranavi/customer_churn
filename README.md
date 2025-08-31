# 📊 Customer Churn Prediction & GenAI-Powered Retention

This repository contains the code and resources for a case assignment focused on building a predictive application to analyze customer behavior and develop a proactive customer retention program for a telecommunication client.  

The project is divided into two key parts:  
1. **Machine Learning Model for Churn Prediction**  
2. **Generative AI-based Retention Email Messaging**  

---

## 📁 Project Structure

```
customer_churn/
│
├── data/                              # Dataset used for model training & evaluation
│
├── part_1_churn_prediction            # Jupyter Notebook for training & evaluation
│
├── part_2_genai_email_generation      # GenAI-powered retention system
│
└── README.md                          # Main documentation
```

---

## 🎯 Part I: Customer Churn Prediction

### Objective
Build a machine learning model to classify which customers are most likely to churn.

### Methodology
- **Data Exploration & Preprocessing**:  
  - Handle missing values  
  - Encode categorical features  
  - Scale numerical data  

- **Model Training & Evaluation**:  
  Trained multiple classifiers:  
  - Logistic Regression  
  - Random Forest  
  - Gradient Boosting  

- **Feature Importance**:  
  Identified the most influential factors driving churn.  

### Key Findings
- **Model Performance**:  
  - Logistic Regression delivered the best results.  

- **Influencing Factors**:  
  - pricing pressure  
  - lack of commitment
  - absence of support/security services 

These insights form the foundation for targeted retention strategies.  

---

## 📩 Part II: GenAI-Powered Email Messaging

This component demonstrates how Large Language Models (LLMs) can be leveraged to generate **personalized, brand-consistent retention emails** for customers predicted to churn.

### Brand Adherence
- Detailed Prompting
- Guardrails 
- Human-in-the-Loop
- Fine-tuning / Style Guides

### Scalability
- Modular Prompt Design
- Segmentation  
- High-Value Customers
- Price-Sensitive Customers
- Dynamic Content Generation

---

## 🚀 How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/vasapranavi/customer_churn.git
cd customer_churn
```

### 2. Install Dependencies
It is recommended to use a virtual environment.  
```bash
pip install pandas scikit-learn openai matplotlib
```

### 3. Set up LLM API
- Generate an API key (e.g., OpenAI, Gemini).  
- Store it securely in an environment variable.  
- Required by `genai_script.py`.  

### 4. Run the Code
- **Part I (Churn Prediction)**  
  Open Jupyter Notebook:  
  ```bash
  jupyter notebook part_1_churn_prediction/model_training.ipynb
  ```  

- **Part II (GenAI Email Generation)**  
  Run script:  
  ```bash
  python part_2_genai_email_generation/genai_script.py
  ```

- **View Prompts**:  
  ```bash
  cat part_2_genai_email_generation/genai_prompts.md
  ```

---

## 🤝 Deliverables

- 📂 **Churn Prediction ML Model** → `part_1_churn_prediction/`  
- 📂 **GenAI Email Generation Code & Prompts** → `part_2_genai_email_generation/`  
- 🎤 **Client Presentation** (CMO & CTO) prepared from insights and findings.  

---

## 📌 Future Improvements
- Add deep learning models for churn prediction.  
- Automate API integration with CRM/CDP systems.  
- Expand multilingual email support.  

---


---
