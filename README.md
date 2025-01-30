# Conscious Dating App Module - Behavioral Analysis & NLP

## 📌 Project Overview

This project aims to analyze user behaviors and preferences in a dating app using **Natural Language Processing (NLP), Machine Learning, and Behavioral Analytics**. The ultimate goal is to **provide data-driven insights** that enhance user experience and match-making accuracy.

## 🎯 Objectives

- **Understand user behaviors** through NLP and sentiment analysis.
- **Perform clustering** to identify user personas.
- **Build a chatbot** that provides insights on user profiles based on their attributes.



## 📊 Dataset Information

- **Source:** Datasets consist of user-generated responses and profile information from a dating platform and an independent survey.
- **Size:** \~60,000 user profiles.
- **Features:**
  - **Demographics:** Gender, age, height, education, income, smoking/drinking habits, etc.
  - **Behavioral Insights:** Ghosting experience, dating preferences, punctuality, etc.
  - **NLP Features:** User-written essays about self-summary, favorite activities, values, etc.

## 🔬 Methodology

### **1️⃣ Data Preprocessing**

- Combined all text-based fields into a unified "user\_profile" column.
- Cleaned and lemmatized text for NLP tasks.
- Handled missing values and categorical encodings.

### **2️⃣ NLP & Embeddings**

- Used **BERT transformer model to generate embeddings.**
- Applied **KMeans clustering** to group users based on their text similarity.

### **3️⃣ Behavioral Analysis & Classification**

- Extracted behavioral tendencies (respect, ethics, communication, growth) from text using **keyword-based and deep learning methods**.

### **4️⃣ Chatbot Implementation**

- The chatbot analyzes a user's profile and provides **insights & predictions**.
- Implemented using **OpenAI GPT API** for personalized recommendations.

## 🛠 Technologies Used

- **Python (Pandas, NumPy, Matplotlib, Seaborn)**

- **NLP Models: BERT, Sentence-Transformers**

- **Machine Learning: Scikit-Learn (KMeans)**

- **Chatbot: OpenAI GPT API**

## 📌 Future Improvements

- Implement **real-time** behavioral analysis in a dating app.
- Improve chatbot explanations by **integrating external behavioral psychology research**.
- Optimize NLP embeddings to **reduce processing time**.
- Apply **Deep Learning-based sentiment analysis** to refine emotional tendencies  further.
- Understand how to apply behavioral tendencies to the model.

##

---

For more details, contact **Selinsight** or open an issue in the repository!

