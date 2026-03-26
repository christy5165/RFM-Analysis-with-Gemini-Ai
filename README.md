# RFM-Analysis-with-Gemini-Ai
# AI-Powered Customer Segmentation & Marketing Strategy

## 📌 Project Overview
This project combines **Data Analytics** and **Generative AI** to transform raw sales data into actionable business strategies. Using an **RFM (Recency, Frequency, Monetary)** model, I categorized customers into behavioral segments and then used the **Google Gemini 1.5 Flash API** to automatically generate tailored marketing goals and email campaigns for each group.

## 🛠️ Tech Stack
* **Python:** Data processing and API integration.
* **Pandas:** Data cleaning and RFM calculation.
* **Matplotlib & Seaborn:** Visualizing customer distributions.
* **Google Gemini API:** Generative AI for marketing strategy automation.
* **Google Colab:** Development environment using Secrets for secure API key management.

## 🚀 Key Features
* **Data Cleaning:** Handled missing values and filtered out cancellations.
* **RFM Modeling:** Calculated scores to identify "Champions," "At Risk," and "Loyal" customers.
* **AI Integration:** Built a custom function to send segment data to Gemini and receive professional marketing copy in seconds.

## 🛠️ Troubleshooting: API Version Management
During development, I encountered a `404 NotFound` error when trying to connect to the Gemini model. 

**The Challenge:**
Initially, the code used a specific version tag for the model (`gemini-1.5-flash`), which resulted in a broken connection as Google updated their API endpoints.

**The Solution:**
I updated the initialization to use the `gemini-1.5-flash-latest` alias. This ensures the application always points to the most current, stable version of the model, making the code more robust and future-proof.  

## 📊 Results
Instead of manually writing emails for thousands of customers, this system provides:
1.  A clear visualization of customer health.
2.  Instant, personalized marketing goals.
3.  Catchy, AI-generated email subject lines ready for use.
