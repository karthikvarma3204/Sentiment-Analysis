# Text Sentiment Classification — NLP Learning Exercise

A beginner-friendly sentiment analysis notebook using text preprocessing, bag-of-words, TF-IDF, and Multinomial Naive Bayes.

## Approach
1. Read labeled text examples from `sentiment_dataset.csv`.
2. Normalize words and remove English stopwords.
3. Extract term-frequency and TF-IDF features.
4. Train a Naive Bayes classifier.
5. Report classification performance on a holdout set.

## Run
```bash
python -m pip install -r requirements.txt
jupyter notebook sentiment_analysis.ipynb
```
The notebook downloads NLTK English stopwords when run.

## Limitations
The dataset contains **only 10 labeled examples**, so measured accuracy is unreliable and the notebook is a proof of concept only. There are no pre-saved executed notebook outputs. For a stronger portfolio example, use a larger dataset, cross-validation, and report class-wise precision/recall.

## Stack
Python, pandas, NLTK, scikit-learn, Jupyter.
