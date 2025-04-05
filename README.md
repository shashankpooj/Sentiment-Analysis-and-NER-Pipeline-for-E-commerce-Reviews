# 🧠 Sentiment Analysis & Named Entity Recognition (NER) Pipeline

This project demonstrates how to build a full Natural Language Processing (NLP) pipeline using Python to perform **Sentiment Analysis** and **Named Entity Recognition (NER)** on e-commerce customer reviews.

## 🚀 Features

- Clean and preprocess raw text reviews
- Convert text into numerical features using **TF-IDF**
- Train a **Logistic Regression** model for sentiment classification
- Perform **Named Entity Recognition (NER)** using **spaCy**
- Save and reuse models using **Pickle**
- Test the model with new review inputs
- Streamlit UI for real-time predictions

---

## 📁 Project Structure

```bash
.
├── app.py                    # Streamlit app
├── model_training.py         # TF-IDF + Logistic Regression training
├── ner_extraction.py         # spaCy-based Named Entity Recognition
├── preprocessing.py          # Text cleaning and preprocessing functions
├── sentiment_model.pkl       # Trained sentiment model (saved)
├── vectorizer.pkl            # Trained TF-IDF vectorizer (saved)
├── requirements.txt          # Required packages
└── README.md
```

---

## 🛠️ Installation

1. **Clone the repo**

```bash
git clone https://github.com/yourusername/sentiment-ner-pipeline.git
cd sentiment-ner-pipeline
```

2. **Create a virtual environment (optional)**

```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the App

Start the Streamlit app:

```bash
streamlit run app.py
```

If deploying with **ngrok**, expose the Streamlit app:

```bash
ngrok config add-authtoken YOUR_AUTH_TOKEN
ngrok http 8501
```

---

## 🧪 Example Inputs

- **"The delivery of the iPhone 14 Pro Max was fast and smooth."** → *Positive*
- **"I was very unhappy with the delayed delivery."** → *Negative*

---

## 📚 Libraries Used

- Python
- Scikit-learn
- spaCy
- Streamlit
- Pandas, NumPy
- Pickle

---

## 📌 Future Enhancements

- Add multi-class sentiment (positive, neutral, negative)
- Deploy using Hugging Face or Streamlit Cloud
- Extend NER with custom training

---

## 🤝 Contributing

Feel free to fork the repo and submit a pull request. Feedback and improvements are welcome!

---

## 📬 Contact

📧 Email: shashankpoojary678@gmail.com


---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---
