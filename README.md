# NLP Foundations – Practical Assignments

This repository contains hands-on Natural Language Processing (NLP) assignments implemented as part of my academic coursework.  
The primary objective of this repository is to build a **strong foundational understanding of text preprocessing, language modeling, normalization techniques, and syntactic analysis** using Python.

Each assignment focuses on understanding core NLP concepts through practical implementation.

---

## 📌 Repository Overview

Natural Language Processing involves working with unstructured text data, which introduces challenges such as:

- Handling noisy and irregular text
- Extracting meaningful linguistic patterns
- Modeling word relationships probabilistically
- Measuring similarity between textual inputs
- Understanding grammatical structure

This repository demonstrates structured solutions to these challenges through progressively designed assignments.

---

# 📂 Assignment 1 – Tokenization & N-Gram Language Modeling

### 🔹 Implementations
- Text tokenization using **NLTK**
- Part-of-Speech (PoS) tagging using **spaCy**
- Text cleaning (lowercasing and punctuation removal)
- Construction of:
  - **Unigram Language Model**
  - **Bigram Language Model**
- Sentence generation using probabilistic N-gram models

### 🔹 Concepts Strengthened
- Text preprocessing pipelines
- Conditional probability for next-word prediction
- Statistical language modeling
- Limitations of N-gram models

---

# 📂 Assignment 2 – Tokenization Challenges & Edit Distance

### 🔹 Implementations
- Extraction of structured patterns using **Regular Expressions**
- Handling URLs, emails, hashtags, mentions, PAN numbers, mobile numbers
- Text normalization (repetitive character removal)
- Implementation of **Edit Distance (Levenshtein Distance)** using Dynamic Programming

### 🔹 Concepts Strengthened
- Real-world tokenization challenges
- Pattern-based text extraction
- String similarity measurement
- Application of dynamic programming in NLP

---

# 📂 Assignment 3 – Stemming & Lemmatization

### 🔹 Implementations
- Stemming using:
  - **Porter Stemmer**
  - **Lancaster Stemmer**
- Lemmatization using:
  - **WordNet Lemmatizer**
  - **spaCy Lemmatizer**
- Vocabulary size comparison before and after normalization
- Visualization of word reduction impact

### 🔹 Concepts Strengthened
- Word normalization techniques
- Aggressive vs conservative stemming
- Context-aware lemmatization
- Vocabulary reduction in NLP pipelines

---

# 📂 Assignment 4 – Part-of-Speech (PoS) Tagging

### 🔹 Problem Statement
Implement Part-of-Speech tagging to assign grammatical categories (noun, verb, adjective, etc.) to each word in a sentence.

### 🔹 Implementations
- Sentence tokenization
- Word tokenization
- PoS tagging using **NLTK**
- PoS tagging using **spaCy**
- Understanding Penn Treebank tag set
- Comparison between tagging approaches

### 🔹 Concepts Strengthened
- Syntactic structure of language
- Role of PoS tagging in NLP pipelines
- Differences between rule-based and statistical tagging
- Importance of grammar in downstream tasks (NER, parsing, sentiment analysis)

---

# 🧠 Overall Key Takeaways

- Text preprocessing is foundational to NLP systems
- Statistical models rely on probability rather than meaning
- Regex enables structured information extraction
- Word normalization reduces vocabulary complexity
- PoS tagging provides syntactic structure to text data

---

# 🛠 Technologies Used

- Python
- NLTK
- spaCy
- Regular Expressions
- Dynamic Programming
- Google Colab

---

# 📦 Repository Structure

NLP-Foundations 
│
├── Assignment-1-N-GRAMS/
│   ├── tokenization_pos_tagging.ipynb
│   ├── unigram_bigram_language_model.ipynb
│   └── README.md
│
├── Assignment-2-EDIT_DISTANCE/
│   ├── regex_tokenization.ipynb
│   ├── edit_distance.ipynb
│   └── README.md
|
├── Assignment-3-STEMMING_LEMMATIZATION/
│ ├── stemming.ipynb
│ ├── lemmatization.ipynb
│ ├── large_text_processing.ipynb
│ └── README.md
|
├── Assignment-4-RNN_CLASSIFICATION/
│ ├── lstm_model.ipynb
│ ├── gru_model.ipynb
│ └── README.md
│
├── requirements.txt
└── README.md

---
## 🛠 How to Run the Code

- All notebooks are implemented using **Google Colab**
- Required libraries are listed in `requirements.txt`
- Each notebook is self-contained and can be executed sequentially










---

## 🚀 ***THANKYOU***

