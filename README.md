# ✈️ British Airways Data Science Job Simulation

 This repository contains my completed work for the British Airways Data Science Job Simulation hosted on Forage. The project involved web scraping, data analysis, feature   engineering, model training, and presentation of findings—designed to simulate a real-world data science task at British Airways. kindly check my notebook for detailed explanation


  https://github.com/PATRICK079/British_Airways/blob/main/British%20Airways%20-2.ipynb
---

## 🔍 Project Overview

British Airways is seeking insights to improve customer satisfaction and predict booking behavior using data science techniques. The simulation is divided into two main tasks:

---

## 📌 Task 1: Web Scraping and Review Analysis

- **Objective:** Scrape customer reviews for British Airways from [AirlineQuality.com](https://www.airlinequality.com/airline-reviews/british-airways).
- **Tools Used:** `BeautifulSoup`, `requests`, `pandas`
- **Process:**
  - Scraped multiple pages of customer reviews.
  - Cleaned and saved the data into a CSV file.
  - Performed text preprocessing and exploratory data analysis (EDA).
  - Applied **topic modeling** to uncover common themes using `LDA`.
  - Performed Sentiment Analysis with a pretrained model from hugging face
  - Applied Word cloud Techniques 
  - Built a **RAG (Retrieval-Augmented Generation)** system using HuggingFace embeddings and Gemini Flash to enable contextual Q&A on the reviews.

---

## 📌 Task 2: Predictive Modeling

- **Objective:** Predict whether a customer would make a booking based on various flight-related features.
- **Steps Involved:**
  - Data preprocessing and cleaning.
  - Applied **SMOTE** to handle class imbalance.
  - Trained and compared multiple classification models:
    - Logistic Regression  
    - Decision Tree  
    - Random Forest  
    - Gradient Boosting  
    - AdaBoost  
    - K-Nearest Neighbors    
  - Evaluated models using:
    - Accuracy, Precision, Recall, F1 Score  
    - Cross-Validation (CV)  
  - Identified **Random Forest** as the best performer with a CV accuracy of **88%**.
  - Visualized feature importance to interpret model predictions.

---

## 📊 Summary of Findings

- The dataset was highly imbalanced, which affected initial model performance.
- After applying SMOTE, models performed better, especially Random Forest.
- Top predictive features included:
  - `length_of_stay`
  - `flight_duration`
  - `purchase_lead`
  - `flight_hour`
  - `num_passengers`
- A one-slide PowerPoint summary was prepared for stakeholders.

---


---

## 🛠️ Tools & Technologies

- Python
- langchain
- BeautifulSoup
- Pandas, NumPy
- scikit-learn
- imbalanced-learn (SMOTE)
- HuggingFace Transformers
- Gemini flash (via API)
- Matplotlib, Seaborn
- PowerPoint

# 🧠 Topic Modeling & Word cloud Visuals

 Below are key visual insights from the text data analysis:

## 📌 Word Cloud

This word cloud highlights the most frequent terms in customer reviews.

<img width="502" alt="Screenshot 2025-05-21 at 18 21 17" src="https://github.com/user-attachments/assets/b33837ad-665f-4243-a79b-5ce8245af5eb" />

## 📌 LDA Topic Modeling

Visual representation of the main topics extracted from customer reviews using LDA.

<img width="1192" alt="Screenshot 2025-05-21 at 17 43 48" src="https://github.com/user-attachments/assets/0ed9fdc9-fe65-441f-9d35-e85e96d430e3" />


## 📄 License

This project is for educational purposes as part of the British Airways job simulation on [Forage](https://www.theforage.com/).

---

# 📬 Contact
Patrick Edosoma

Machine Learning Engineer

[Linkedlin](https://www.linkedin.com/in/patrickedosoma/)

# ⭐️ Star This Repo
If you found this project helpful, please star ⭐️ it to show support!

