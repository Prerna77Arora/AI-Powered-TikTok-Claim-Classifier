# CaseStudy--Tiktok_Claim_Classifie
# AI-Powered TikTok Claim Classifier 🎬

This project is the **Course 6 End-of-Course Portfolio Project** from the **Google Advanced Data Analytics Certificate**.  
The goal is to **build, evaluate, and summarize** a machine learning model that classifies TikTok videos as either **claims** or **opinions**, helping the moderation team prioritize user reports efficiently.

---

# CaseStudy--Tiktok_Claim_Classifier
# 🎬 AI-Powered TikTok Claim Classifier  

This project is the **Course 6 End-of-Course Portfolio Project** from the **Google Advanced Data Analytics Certificate**.  
The goal is to **build, evaluate, and summarize** a machine learning model that classifies TikTok videos as either **claims** or **opinions**, helping the moderation team prioritize user reports efficiently.

---

## 📖 Project Overview

TikTok receives thousands of **user reports** on videos that may contain **claims** or **opinions** daily.  
Currently, **human moderators** review all these reports, which is **time-consuming** and can lead to **delays**.  

By leveraging **machine learning**, we aim to:  
- Automatically classify content as **claims** or **opinions**  
- Prioritize critical claim-related videos for faster moderation  
- Improve **efficiency** in the content review pipeline  

---

## 🏢 Background

**Client:** TikTok Content Moderation Team  
- Handles millions of video uploads daily  
- Faces challenges in **scaling human moderation**  

**Business Need:**  
Classify videos to **speed up moderation** and **reduce backlog**.

**Original Request:**  
Predict whether a video contains a **claim** or an **opinion**.  

**Value Delivered:**  
- Automated claim detection reduces manual workload  
- High recall ensures **claims are not missed**  
- Supports moderation **without impacting user experience**  

---

## 🎯 Project Goals

1. **Data Preprocessing & Feature Engineering**  
   - Clean and explore the dataset  
   - Convert video transcriptions to numerical features (TF-IDF)  
   - Encode categorical variables  

2. **Model Building & Training**  
   - Implement tree-based classifiers (Random Forest, XGBoost)  
   - Tune hyperparameters using **RandomizedSearchCV** with cross-validation  

3. **Model Evaluation**  
   - Use **accuracy, precision, recall, and F1-score** to evaluate performance  
   - Focus on **recall** to minimize missing claim videos  

4. **Reporting & Communication**  
   - Provide an **executive summary** for non-technical teams  
   - Deliver insights and recommendations to TikTok stakeholders  

---

## 📂 Project Structure

```plaintext
├── data/
│   └── tiktok_claims_dataset.csv       # Dataset used for model training (if applicable)
├── notebooks/
│   └── Tiktok_Claim_Classifier.ipynb   # Full ML workflow & analysis
├── reports/
│   └── executive_summary.pdf           # Non-technical summary for stakeholders
├── PACE_strategy.pdf                   # Planning and strategy document
└── README.md                           # Project overview (this file)

---

## 🧰 Tools & Libraries

This project is implemented using **Python** and the following libraries:

- **Pandas** – Data manipulation  
- **NumPy** – Numerical computations  
- **Matplotlib / Seaborn** – Data visualization  
- **Scikit-learn** – Machine learning model building & evaluation  
- **XGBoost / RandomForest** – Classification algorithms  
- **Jupyter Notebook** – Analysis environment  
```
---

## 📊 Machine Learning Workflow

1. **Data Preprocessing**
   - Clean and explore the claims classification dataset
   - Handle missing values and convert text into numerical features (TF-IDF)
   
2. **Feature Engineering**
   - Create features from `video_transcription_text`
   - Combine with numeric and categorical features

3. **Model Development**
   - Train classification models using:
     - **RandomForestClassifier**
     - **XGBoostClassifier**
   - Optimize using **RandomizedSearchCV** with cross-validation

4. **Model Evaluation**
   - Evaluate using:
     - Accuracy
     - Precision
     - Recall
     - F1-score
   - Select the model with the **best recall score** (prioritizing claims detection)

5. **Results & Insights**
   - Present model results in the Jupyter notebook
   - Create an **executive summary** for stakeholders

---

## 👥 TikTok Team Structure

**Data Team:**  
- Willow Jaffey – Data Science Lead  
- Rosie Mae Bradshaw – Data Science Manager  
- Orion Rainier – Data Scientist  

**Cross-Functional Stakeholders:**  
- Mary Joanna Rodgers – Project Management Officer  
- Margery Adebowale – Finance Lead, Americas  
- Maika Abadi – Operations Lead  

---

## 📑 Deliverables

1. **PACE Strategy Document** (planning, action, communication, execution)  
2. **Jupyter Notebook** with:
   - Data analysis
   - Model training & evaluation  
3. **Executive Summary** for non-technical stakeholders  

---

## 🔑 Key Takeaways

- Practiced **end-to-end machine learning model development**  
- Learned to **communicate results** to both technical and non-technical teams  
- Gained a **portfolio-ready project** showcasing skills in data analytics and ML  

---

## ⚠️ Disclaimer

This is a **fictional project** created for learning purposes as part of the **Google Advanced Data Analytics Certificate**.  
All names, data, and incidents are **fictitious** and are not related to the real TikTok.
