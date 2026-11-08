# Product Review Sentiment Analysis

A small Python NLP project that classifies product reviews as positive or negative using text preprocessing, NLTK, and a Naive Bayes classifier.

## Contents

- `AI_Project_nebula_source_code(2).py` — preprocessing, feature extraction, model training, and evaluation.
- `product_reviews2.csv` — dataset expected by the script.

## Requirements

Use Python 3 and install the libraries used by the source:

```powershell
python -m pip install pandas nltk scikit-learn
```

The script downloads the NLTK Punkt tokenizer and English stopwords on first run, so an internet connection is needed for that initial setup.

## Run

From the repository directory:

```powershell
python "AI_Project_nebula_source_code(2).py"
```

The script expects `product_reviews2.csv` in the current directory. Review the dataset and source before use; this is a learning project rather than a packaged application.

## Project context

Originally prepared as a student group project. The source credits Fahad, Adildev, Arjun, Safin, and Alwin.
