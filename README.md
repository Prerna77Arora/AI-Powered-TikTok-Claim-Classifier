# CaseStudy--Tiktok_Claim_Classifie
# AI-Powered TikTok Claim Classifier 🎬

This project is the **Course 6 End-of-Course Portfolio Project** from the **Google Advanced Data Analytics Certificate**.  
The goal is to **build, evaluate, and summarize** a machine learning model that classifies TikTok videos as either **claims** or **opinions**, helping the moderation team prioritize user reports efficiently.

---

## 📌 Project Overview

TikTok receives a large number of **user reports** on videos that may contain **claims** or **opinions**.  
Currently, human moderators review these reports, which can lead to delays.  

By creating a **predictive machine learning model**, TikTok can:  
- Reduce the backlog of reports  
- Prioritize critical content for review  
- Improve the efficiency of content moderation  

---

## 📂 Project Files

- **`Tiktok.ipynb`** – Jupyter Notebook containing the full analysis, model development, and evaluation  
- **`README.md`** – Project overview and documentation  
- *(Optional)* **`data/`** – Directory for any CSV or JSON files used in the project  

---

## 🎯 Objectives

1. Perform **feature engineering** on the claims classification dataset  
2. **Build and train** a machine learning model to classify videos  
3. **Evaluate** model performance using metrics like accuracy, precision, recall, and F1-score  
4. **Summarize findings** for technical and non-technical stakeholders  
5. Deliver an **executive summary** for cross-functional TikTok teams  

---

## 🧰 Tools & Libraries

This project is implemented using **Python** and the following libraries:

- **Pandas** – Data manipulation  
- **NumPy** – Numerical computations  
- **Matplotlib / Seaborn** – Data visualization  
- **Scikit-learn** – Machine learning model building & evaluation  
- **XGBoost / RandomForest** – Classification algorithms  
- **Jupyter Notebook** – Analysis environment  

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
