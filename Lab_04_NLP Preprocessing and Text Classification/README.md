# NLP Preprocessing and Text Classification

This repository contains a lab assignment notebook for NLP preprocessing and machine learning based text classification.

## Assignment Title
NLP Preprocessing and Text Classification

## Objective
Implement NLP preprocessing techniques and build a text classification model using machine learning techniques.

## Learning Outcomes
- Apply NLP preprocessing:
  - Tokenization
  - Stopword removal
  - Stemming
  - Lemmatization
- Implement text vectorization:
  - CountVectorizer
  - TF-IDF (TfidfVectorizer)
- Build text classification models
- Evaluate model performance using standard metrics

## Dataset
The notebook uses the **SMS Spam Collection** dataset loaded from:
- https://raw.githubusercontent.com/justmarkham/pycon-2016-tutorial/master/data/sms.tsv

Target classes:
- ham (0)
- spam (1)

## Project Files
- `NLP_Preprocessing_Text_Classification.ipynb` : main assignment notebook
- `requirements.txt` : Python dependencies
- `.gitignore` : excludes virtual environment and temporary files

## Environment Setup
1. Create and activate a virtual environment (recommended):

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

2. Install dependencies:

```powershell
pip install -r requirements.txt
```

3. Open the notebook and run all cells in order.

## Notebook Workflow
The notebook is organized step by step:
1. Import libraries and download NLTK resources
2. Load and inspect data
3. Apply preprocessing:
   - cleaning
   - tokenization
   - stopword removal
   - stemming
   - lemmatization
4. Vectorize text using CountVectorizer and TF-IDF
5. Train models:
   - Multinomial Naive Bayes
   - Logistic Regression
6. Evaluate with:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion Matrix
7. Compare all experiments and identify the best pipeline

## Current Best Result (from notebook run)
- Best pipeline: **CountVectorizer + Multinomial Naive Bayes**
- Accuracy: **0.9812**
- Precision: **0.9571**
- Recall: **0.8993**
- F1-score: **0.9273**


