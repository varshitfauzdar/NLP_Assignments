# NLP Foundations – Practical Assignments


This repository contains hands-on Natural Language Processing (NLP) assignments implemented as part of my academic coursework.  
The focus of this repository is to build **strong foundational understanding of text processing, tokenization challenges, statistical language modeling, and string similarity algorithms** using Python.

---

## 📌 Repository Overview

Natural Language Processing involves dealing with unstructured text data, which introduces challenges such as handling special symbols, extracting meaningful patterns, and understanding word relationships.  
This repository demonstrates practical solutions to these challenges through two structured assignments.

---

## 📂 Assignment 1 – Tokenization & Language Modeling

### 🔹 What Was Implemented
- Tokenization of text using **NLTK**
- Part-of-Speech (POS) tagging using **spaCy**
- Text cleaning (lowercasing and punctuation removal)
- Collection of a large text corpus (10,000+ words)
- Construction of:
  - **Unigram Language Model**
  - **Bigram Language Model**
- Sentence generation using probabilistic models

### 🔹 Concepts Learned
- How raw text is converted into tokens
- Importance of preprocessing in NLP pipelines
- Difference between unigram and bigram models
- Conditional probability for next-word prediction
- Limitations of statistical language models

### 🔹 Tools & Technologies Used
- Python
- NLTK
- spaCy
- TextBlob
- Google Colab

---

## 📂 Assignment 2 – Tokenization Challenges & Edit Distance

### 🔹 What Was Implemented
- Extraction of complex textual elements using **Regular Expressions**:
  - URLs
  - Email IDs
  - Hashtags
  - Mentions
  - Numbers
  - Punctuation marks
  - Indian PAN numbers
  - Indian mobile numbers
  - Capitalized words
- Text normalization by removing repetitive characters
- Implementation of **Edit Distance (Levenshtein Distance)** using Dynamic Programming

### 🔹 Concepts Learned
- Real-world tokenization challenges beyond simple word splitting
- Use of regex for pattern-based text extraction
- String similarity measurement using edit distance
- Role of dynamic programming in NLP algorithms

### 🔹 Tools & Technologies Used
- Python
- Regular Expressions (re module)
- Dynamic Programming
- Google Colab

---


## 📌 Assignment 3 – Stemming & Lemmatization

**Folder:** `Assignment-3-STEMMING_LEMMATIZATION/`

### 🔹 What This Assignment Covers
- Implementation of **Porter Stemmer** and **Lancaster Stemmer**
- Comparison of stemming outputs
- Lemmatization using:
  - **WordNet Lemmatizer**
  - **spaCy Lemmatizer**
- Application of stemming and lemmatization on a large text dataset
- Comparison of word counts before and after processing
- Visualization of vocabulary reduction

### 🔹 Key Learnings
- Difference between stemming and lemmatization
- Aggressive vs conservative word normalization
- Importance of context in lemmatization
- Impact of normalization on vocabulary size in NLP tasks

---

## 🚀 Conclusion

This repository reflects my journey in understanding the **core building blocks of Natural Language Processing**, focusing on practical implementation rather than black-box usage.  
These assignments strengthened my ability to work with real-world text data and prepared a solid foundation for advanced NLP and AI/ML applications.

---

## 🧠 Overall Key Takeaways

- Text preprocessing is a critical step in NLP systems
- Tokenization becomes complex in real-world text
- Statistical language models rely on probability, not meaning
- Regex is effective for structured pattern extraction
- Stemming and lemmatization help reduce vocabulary size
- Edit distance is fundamental for text similarity and correction tasks

---

## 🛠 Tools & Technologies Used

- Python
- NLTK
- spaCy
- Regular Expressions
- Dynamic Programming
- Google Colab

---

## 🛠 How to Run the Code

- All notebooks are implemented using **Google Colab**
- Required libraries are listed in `requirements.txt`
- Each notebook is self-contained and can be executed sequentially









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
├── requirements.txt
└── README.md

---
---

## 🚀 Conclusion

This repository represents my foundational work in Natural Language Processing, focusing on **practical implementations and core NLP concepts**.  
The assignments collectively strengthened my understanding of text preprocessing, normalization, language modeling, and similarity measurement, forming a solid base for advanced NLP and AI/ML applications.

