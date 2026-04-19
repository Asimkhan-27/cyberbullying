
# 🛡️ Cyberbullying Detection System (AI/NLP)

An AI-powered web application that detects cyberbullying in text using a fine-tuned **DistilBERT transformer model**. The system classifies social media comments as **Bullying** or **Safe**, helping promote safer online communication.

---

## 🚀 Features

- Real-time cyberbullying detection
- Fine-tuned DistilBERT model (Transformer-based NLP)
- Text preprocessing (cleaning, normalization, noise removal)
- Confidence score for predictions
- Interactive web interface using Gradio
- End-to-end ML pipeline (training → evaluation → deployment)

---

## 🧠 Tech Stack

- Python 🐍
- PyTorch 🔥
- Hugging Face Transformers 🤗
- DistilBERT
- Gradio 🌐
- NLP (Natural Language Processing)

---

## 📂 Project Structure

```

├── app.py                  # Main Gradio application
├── model/                 # Saved trained model (or model files)
├── tokenizer/             # Tokenizer files (if saved separately)
├── requirements.txt       # Dependencies
└── README.md              # Project documentation

````

---

## ⚙️ How It Works

1. User enters a text comment
2. Text is preprocessed (cleaning, normalization, filtering)
3. Tokenized using DistilBERT tokenizer
4. Model predicts probability of bullying
5. Output is displayed as:
   - **Bullying** 🚨
   - **Safe** ✅  
   along with confidence score

---

## 🧪 Example Predictions

| Input Text | Output |
|------------|--------|
| "You are so stupid and ugly!" | 🚨 Bullying |
| "Have a great day, take care!" | ✅ Safe |

---


