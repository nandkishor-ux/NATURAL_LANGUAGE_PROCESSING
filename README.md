# Natural Language Processing

A collection of NLP concepts and implementations in Python, covering tokenization, stemming, lemmatization, word embeddings, and more.

## Topics Covered

- **Tokenization** — Splitting text into words and sentences using NLTK
- **Stemming** — Reducing words to their root form
- **Lemmatization** — Converting words to their base/dictionary form
- **Word2Vec** — Word embeddings using Gensim
- **Text Preprocessing** — Cleaning and preparing text data for NLP tasks

## Tech Stack

- Python 3.x
- Jupyter Notebook
- NLTK
- Gensim
- Scipy
- NumPy

## ⚙️ Setup & Installation

### 1. Clone the repository
```bash
git clone https://github.com/nandkishor-ux/NATURAL_LANGUAGE_PROCESSING.git
cd NATURAL_LANGUAGE_PROCESSING
```

### 2. Create a virtual environment
```bash
python -m venv .venv
```

### 3. Activate the virtual environment

**Windows:**
```bash
.venv\Scripts\activate
```

**Mac/Linux:**
```bash
source .venv/bin/activate
```

### 4. Install dependencies
```bash
pip install nltk gensim numpy scipy --only-binary=:all:
```

### 5. Download NLTK data
```python
import nltk
nltk.download('punkt')
nltk.download('wordnet')
```

## 📁 Project Structure

```
NATURAL_LANGUAGE_PROCESSING/
│
├── word2vec.ipynb        # Word2Vec implementation using Gensim
├── .venv/                # Virtual environment (not tracked)
└── README.md             # Project documentation
```

## 🚀 Usage

Open any `.ipynb` file in Jupyter Notebook or VS Code and run the cells:

```bash
jupyter notebook
```

## 👨‍💻 Author

**Nandkishor** — [@nandkishor-ux](https://github.com/nandkishor-ux)

## ⭐ Show Your Support

If you found this helpful, please give a ⭐ to the repository!
