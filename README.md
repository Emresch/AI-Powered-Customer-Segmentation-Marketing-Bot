# 🛍️ AI-Powered Customer Segmentation & Marketing Agent

This project combines **Machine Learning (K-Means Clustering)** with **Generative AI (Google Gemini)** to automate personalized marketing strategies. It segments customers based on their spending behavior and generates tailored marketing SMS messages for each specific persona.

## 🚀 Features

* **Smart Segmentation:** Uses K-Means algorithm to group customers into 5 distinct psychological segments based on Income and Spending Score.
* **AI Content Generation:** Integrates **Google Gemini 2.5 Flash** to write hyper-personalized, persuasive marketing copy for each persona.
* **Dynamic Persona Mapping:** Automatically categorizes users into:
    * *VIPs* (High Income, High Spend)
    * *Potentials* (High Income, Low Spend)
    * *Impulsive* (Low Income, High Spend)
    * *Savers* (Low Income, Low Spend)
    * *Standard* (Average)
* **Secure Architecture:** Uses environment variables (`.env`) to keep API keys safe.

## 🛠️ Tech Stack

* **Python 3.x**
* **Google Generative AI** (LLM Integration)
* **Scikit-learn** (Machine Learning)
* **Pandas** (Data Manipulation)
* **Python-Dotenv** (Security)
