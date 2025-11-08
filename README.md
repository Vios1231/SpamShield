# 🛡️ SpamShield – AI-Powered Email Spam Classifier

**SpamShield** is a machine learning web application that detects whether an email message is spam or not.  
It provides real-time spam detection using multiple trained models that users can compare directly through a simple Flask web interface.

---

## 🚀 Features
- 🔍 **Real-time spam detection** for user-input emails.  
- 🧠 **Multiple ML models** including Logistic Regression, Random Forest, XGBoost, SVC, and Stacking Classifier.  
- 🧩 **TF-IDF vectorization** for text preprocessing.  
- 🌐 **Flask web app interface** for live predictions.  
- 📊 **Model comparison** for performance evaluation.

---

## 🧰 Technologies
- **Python**
- **Flask**
- **Scikit-learn**

---

## 🧪 Installation & Setup

```bash
# 1. Clone this repository
git clone https://github.com/<your-username>/SpamShield.git
cd SpamShield

# 2. (Optional) Create a virtual environment
python -m venv venv
venv\Scripts\activate  # On Windows
# or
source venv/bin/activate  # On macOS/Linux

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Flask app
python app.py
