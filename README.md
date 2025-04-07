# Client Satisfaction Score Predictor 🎯

This project predicts client satisfaction scores (0–10) based on key service-related features using synthetic data and machine learning. It includes a full **Streamlit web app**, synthetic dataset generation, and a trained **Random Forest Regressor** model.

---

## 🚀 Features

- ✅ Synthetic dataset with realistic business logic
- 🤖 Machine learning model (Random Forest) for regression
- 📊 Streamlit UI for real-time prediction
- 📁 Exportable Excel dataset for analysis or model training
- 🔮 Predict satisfaction score from:
  - Response time
  - Service and product quality
  - Issue resolution
  - Customer loyalty
  - Support interactions

---

## 🧠 Model Inputs

| Feature | Description |
|--------|-------------|
| `Response_Time_Minutes` | Average customer service response time |
| `Service_Quality` | Rating (1-5) of service provided |
| `Product_Quality` | Rating (1-5) of product quality |
| `Issue_Resolved` | Whether the client's issue was resolved (1 = Yes, 0 = No) |
| `Customer_Loyalty_Years` | Years of customer loyalty |
| `Support_Interactions` | Number of support interactions |

---

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/client-satisfaction-score-predictor.git
   cd client-satisfaction-score-predictor

    Install dependencies

pip install -r requirements.txt

Run the app

    streamlit run app.py

📂 Files

    app.py – Streamlit web app

    client_satisfaction_data.xlsx – Generated synthetic dataset

    model_training.py (optional) – Logic for generating data and training model

    README.md – Project documentation

📈 Sample Prediction Output

Response Time: 12 mins  
Service Quality: 4  
Product Quality: 5  
Issue Resolved: Yes  
Loyalty: 3 years  
Support Interactions: 4  

🔮 Predicted Satisfaction Score: 8.34 / 10

🤝 Contributing

Contributions are welcome! Please:

    Fork the repo

    Create a feature branch

    Commit your changes

    Open a pull request

📃 License

This project is licensed under the MIT License.
👨‍💻 Author

[Your Name] – [your.email@example.com]
GitHub: @yourusername
🌐 Demo (Optional)

Deploy the app on Streamlit Cloud or locally with:

streamlit run app.py


---

Let me know your GitHub username and email if you'd like me to personalize this for you, or generate a `requirements.txt` file too!

