
# 🌍 Transformer-based Language Translation

This Jupyter Notebook implements a basic **Transformer model from scratch** using PyTorch to perform **English to French translation**. It’s designed as an foundatioal project to understand the inner workings of transformer-based architectures.

---

## 📚 Features

- Tokenization using NLTK
- Custom vocabulary generation
- Manual implementation of:
  - Scaled Dot-Product Attention
  - Multi-Head Attention
  - Positional Encoding
  - Encoder and Decoder blocks
- Basic training loop
- Translation inference on toy data

---

## 📦 Dataset

A small toy dataset of English-French sentence pairs is included directly in the notebook:

```python
data = [
    ("I am a student", "Je suis un étudiant"),
    ("She is reading a book", "Elle lit un livre"),
    ("The sun is shining", "Le soleil brille"),
    ("He loves football", "Il aime le football"),
]
```

---

## 🚀 Requirements

Install the required libraries before running:

```bash
pip install torch nltk tqdm
```

The notebook also downloads NLTK tokenizers automatically:

```python
nltk.download('punkt')
```

---

## 🧠 Model Overview

This implementation includes:

- Positional Encoding
- Multi-Head Attention from scratch
- Encoder & Decoder layers
- Final Linear + Softmax projection

---

## 🏃‍♂️ How to Run

1. Open the notebook in Jupyter or Colab.
2. Run all cells sequentially.
3. Observe model training on the toy dataset.
4. Check translation predictions like:

```text
Input: I am a student
Prediction: Je suis un étudiant
```

---

## 🔮 Improvements & Ideas

- Use a larger dataset (e.g., Tatoeba, Europarl)
- Implement subword tokenization (BPE, WordPiece)
- Add batching and masking
- Train on GPU for better performance
- Support more languages (e.g., English-German)

---

## 📜 License

MIT License.  
Feel free to use, modify, and share!

---

> ✍️ Author: *Your Name Here*
