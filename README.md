# 📧 Email Spam Classifier

An **end-to-end Machine Learning project** that classifies emails and SMS messages as **Spam** or **Ham (Not Spam)**. It covers the complete workflow — from text preprocessing and model training to deployment via a **Flask web application** (Heroku-ready).

---

##  Features
- Text preprocessing (stopword removal, stemming, tokenization)
- Feature extraction using **CountVectorizer** / **TF-IDF**
- Model training and serialization (`model.pkl`, `vectorizer.pkl`)
- Real-time message classification through a **Flask web interface**
- Seamless deployment support for **Heroku**

---

## Tech Stack
- **Language:** Python  
- **Libraries:** scikit-learn, pandas, numpy, nltk, flask  
- **Deployment Platform:** Heroku  

---

## 📂 Project Structure
email-spam-classifier/  
│-- app.py → Flask app for deployment  
│-- sms-spam-detection.ipynb → Notebook for EDA & model training  
│-- spam.csv → Dataset used for training  
│-- model.pkl → Trained machine learning model  
│-- vectorizer.pkl → Saved CountVectorizer/TF-IDF object  
│-- requirements.txt → Dependencies list  
│-- Procfile → Heroku configuration file  
│-- setup.sh → Deployment setup script  
│-- nltk.txt → NLTK resource requirements  

---

## Usage
1️ **Clone the repository**  
git clone https://github.com/Aman-sys-ui/email-spam-classifier.git  
cd email-spam-classifier  

2️ **Install dependencies**  
pip install -r requirements.txt  

3️ **Run locally**  
python app.py  
Then open your browser and navigate to:  
👉 http://127.0.0.1:5000/

---


## 📊 Results
The model achieved an accuracy of **86.4%** on the `spam.csv` dataset, demonstrating reliable spam detection performance.

---

## Future Enhancements
- Enhance preprocessing using lemmatization  
- Experiment with deep learning models (LSTM, Transformer)  
- Improve front-end design for better UX  

---

## License
This project is licensed under the **MIT License**.

---

⭐ **If you found this helpful, consider giving the repo a star!**
