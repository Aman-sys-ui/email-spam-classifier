# 📧 Email Spam Classifier

This is an **end-to-end Machine Learning project** that classifies emails/SMS as **Spam** or **Ham (Not Spam)**.  
The project includes data preprocessing, model training, evaluation, and deployment using **Flask** (Heroku-ready).

---

## Features
- Dataset preprocessing (stopwords removal, stemming, tokenization)
- Feature extraction using **CountVectorizer / TF-IDF**
- Model training and saving (`model.pkl`, `vectorizer.pkl`)
- Interactive prediction through a **Flask web app**
- Ready for deployment on **Heroku**

---

## Tech Stack
- **Python**
- **Libraries:** scikit-learn, pandas, numpy, nltk, flask
- **Deployment:** Heroku (Procfile & setup.sh included)

---

## 📂 Project Structure
email-spam-classifier/
│-- app.py                   # Flask app for deployment
│-- sms-spam-detection.ipynb # Jupyter notebook for training & EDA
│-- spam.csv                 # Dataset
│-- model.pkl                # Trained ML model
│-- vectorizer.pkl           # TF-IDF/CountVectorizer object
│-- requirements.txt         # Project dependencies
│-- Procfile                 # For Heroku deployment
│-- setup.sh                 # Setup script for deployment
│-- nltk.txt                 # NLTK resource downloads

---

## Usage

### 1️⃣ Clone the repository
git clone https://github.com/Aman-sys-ui/email-spam-classifier.git
cd email-spam-classifier

### 2️⃣ Install dependencies
pip install -r requirements.txt

### 3️⃣ Run locally
python app.py
# Open browser at http://127.0.0.1:5000/

---

## Deployment on Heroku
heroku login
git init
heroku git:remote -a your-app-name
git add .
git commit -m "Deploy spam classifier"
git push heroku master

---

## Results
Model trained on `spam.csv` dataset with high accuracy ( 86.4 % ).

---

## Future Work
- Improve preprocessing with lemmatization
- Add deep learning models (LSTM/Transformer)
- Frontend UI enhancements

---

## License
This project is licensed under the MIT License.

