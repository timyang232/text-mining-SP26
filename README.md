# Text Mining — Spring 2026

Course materials and lab assignments for the Text Mining course at Vrije Universiteit Amsterdam.

**Team:** Tim Yang, Cristina Wang, Tina Yu, Lang Chen

## Repository Structure

```
├── Labs/
│   ├── lab1/   NLP Toolkits (NLTK & spaCy)
│   ├── lab2/   Machine Learning for NLP
│   ├── lab3/   Sentiment Analysis
│   ├── lab4/   Named Entity Recognition
│   ├── lab5/   Property Extraction
│   └── lab6/   Topic Modeling & Classification
├── Examples/           Supplementary notebooks
└── lexicon-samples/    Sample lexicon and XML files
```

## Labs

| Lab | Topic | Key Tools |
|-----|-------|-----------|
| 1 | Introduction to NLP toolkits | NLTK, spaCy |
| 2 | ML fundamentals for NLP | Linguistic features, embeddings, evaluation |
| 3 | Sentiment analysis | VADER, scikit-learn, Transformers |
| 4 | Named entity recognition & classification | CRF, Transformers, CoNLL-2003 |
| 5 | Property / relation extraction | Custom utilities, JSON knowledge bases |
| 6 | Topic modeling & classification | Gensim (LDA), scikit-learn, BERT |

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/timyang232/text-mining-SP26.git
   ```
2. Install dependencies (Python 3.9+):
   ```bash
   pip install nltk spacy scikit-learn transformers gensim vaderSentiment sklearn-crfsuite
   python -m spacy download en_core_web_sm
   ```
3. Open any lab notebook with Jupyter (recommend using an IDE):
   ```bash
   jupyter notebook Labs/lab1/Lab1.1-introduction.ipynb
   ```

Each lab folder contains instructional notebooks (numbered) and a graded assignment notebook.
