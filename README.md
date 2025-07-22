# 📊 Customer Churn Prediction – Project Update 🚀

I'm excited to share my latest machine learning project focused on predicting telecom customer churn — a key step toward improving customer retention and business growth.

---

## 📌 Problem Statement

Customer churn — when users stop using a service — is a major concern for telecom companies. By identifying which customers are likely to churn, companies can proactively offer personalized plans or support to retain them.

---

## 🎯 Goal

Build a machine learning model that predicts whether a customer is likely to churn based on just **4 key features**:
- Gender
- Tenure (months with the company)
- Contract Type (e.g., month-to-month)
- Monthly Charges

---

## 🧠 Model

- **Algorithm**: Logistic Regression  
- **Framework**: scikit-learn  
- **Preprocessing**: Label Encoding & Feature Scaling (for charges)  
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score  

---

## 🛠️ Tools & Technologies

- Python 🐍  
- pandas, numpy, scikit-learn  
- Streamlit (for deployment)  
- GitHub & Streamlit Cloud

---

## 📈 Dataset Features Used

| Feature | Description |
|--------|-------------|
| `gender` | Male/Female |
| `tenure` | Number of months with the company |
| `Contract` | Type of contract (Month-to-month, One year, Two year) |
| `MonthlyCharges` | Amount charged monthly to the customer |

---

## 🚀 Streamlit Web App

The app allows users to input customer details and instantly predicts whether they are likely to churn.

🖥️ **Web UI Includes**:
- Dropdowns and sliders for input
- One-click prediction
- Color-coded result:  
  - 🟢 **Customer is likely to stay**  
  - 🟡 **Customer is likely to churn**

---

## 📂 Files

- `train_model.py`: Preprocess, train and save the model
- `app.py`: Streamlit app for interactive predictions
- `logistic_model.pkl`: Saved trained model
- `scaler.pkl`: Saved scaler for monthly charges
- `requirements.txt`: Python dependencies
- `README.md`: Project documentation

---

## 📦 Installation


    git clone https://github.com/yourusername/customer-churn-prediction
    cd customer-churn-prediction


Follow these steps to set up the project, train the model, and launch the Streamlit app:


###  1. Create a Virtual Environment
         python -m venv venv

### Activating it:

## On Windows:


      myenv\Scripts\activate
     
## On macOS/Linux:

     source myenv/bin/activate
### 3. Install Required Dependencies

    pip install -r requirements.txt
   
## requirements.txt should include:

streamlit

scikit-learn

pandas

numpy

### 4. Train the Model (Optional)

Run the training script to train the model and export plant_disease_detection_model.pkl:


    jupyter notebook customer churn predictio .ipynb
    
### 5. Run the Streamlit App
   

       streamlit run app.py
   
This will open the app in your web browser.


# 🔧 Deployment Stack:

Streamlit Cloud (for hosting the web app)

GitHub (code repository & version control)

requirements.txt to manage Python dependencies

Model serialized using pickle for efficient loading

---

# 🌐 Live App:

https://customer-churn-prediction-dglfuyswvrjkn6uxhuh4o4.streamlit.app/

---

# <u>🧪 TROUBLESHOOTING</u>

If streamlit is not recognized, reactivate your environment.

If plant_disease_detection_model.pkl is missing, ensure train_model.py ran successfully.

Confirm all libraries from requirements.txt are installed.



