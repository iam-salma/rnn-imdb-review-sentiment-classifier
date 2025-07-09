# 🎬 IMDB Movie Review Sentiment Classifier

This project is a **deep learning-based sentiment analysis app** built with **TensorFlow** and deployed using **Streamlit**. It classifies movie reviews from the IMDB dataset as either **Positive** or **Negative** using a trained **SimpleRNN model**.

---

## 🧠 Model Summary

- **Architecture**: SimpleRNN with ReLU activation
- **Dataset**: IMDB reviews dataset (from Keras)
- **Input**: Raw text reviews
- **Output**: Sentiment score & label
- **Activation**: Sigmoid
- **Max Length**: 500 tokens (padded)
- **Accuracy**: ~85% (baseline)

---

## ⚙️ Setup Instructions

### 1. Clone the repository:
   ```bash
   git clone https://github.com/iam-salma/rnn-imdb-review-sentiment-classifier.git
   cd imdb-rnn-sentiment
   ````
### 2. Install dependencies:
```bash
   pip install -r requirements.txt
   ````

### 3. Run the app:
```bash
   streamlit run main.py
   ````
