# JHBot
The Jamia Hamdard Chatbot is a QA system fine-tuned on a custom university-specific SQuAD dataset. It uses Hugging Face’s RobertaForQuestionAnswering model to provide accurate, offline responses via Jupyter. Designed for educational support, it’s adaptable to other domains with minimal modifications.
# 🧠 Jamia Hamdard Chatbot – Domain-Specific QA Bot

<p align="center">
  <img src="https://img.shields.io/badge/NLP-Transformers-blueviolet" />
  <img src="https://img.shields.io/badge/Model-RoBERTa-green" />
  <img src="https://img.shields.io/badge/Python-3.9+-yellow" />
  <img src="https://img.shields.io/badge/Interface-Jupyter-orange" />
</p>

---

## ✨ Features

- 💬 Answers university-specific questions from a curated dataset
- 🤖 Fine-tuned on SQuAD-style JSON using `RobertaForQuestionAnswering`
- 🧠 Uses pretrained tokenizer + custom weights for accuracy
- 📦 All model and tokenizer assets are self-contained in this repo
- 📓 Jupyter interface for experimentation and live testing

---

## 🧠 Technologies Used

| Component      | Description                            |
|----------------|----------------------------------------|
| `transformers` | Hugging Face library for NLP models    |
| `PyTorch`      | Model training and inference backend   |
| `Jupyter`      | Interactive interface for testing      |
| `SQuAD Format` | JSON QA dataset format used for fine-tuning |

---

---

## 📁 Project Structure

```bash
jamia-chatbot/
│
├── Jamia_bot.ipynb              # Main notebook for testing
├── FeedBack.json                # QA dataset (SQuAD format)
├── model.safetensors            # Fine-tuned model weights
├── config.json                  # Model architecture config
├── tokenizer.json               # Tokenizer vocabulary
├── tokenizer_config.json        # Tokenizer setup
├── vocab.json                   # Token to ID mapping
├── special_tokens_map.json      # Special token definitions
├── requirements.txt             # Python dependencies
└── README.md                    # You're here!
