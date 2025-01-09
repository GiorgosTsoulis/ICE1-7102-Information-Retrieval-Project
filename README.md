# Information Retrieval Project

This project is part of a University's project and implements a search engine based on wikipedia articles using the [Raw Wikipedia dataset](https://www.kaggle.com/datasets/ismaeldwikat/wikipedia) and evaluates various information retrieval (IR) algorithms using the [CISI dataset](https://www.kaggle.com/datasets/dmaso01dsta/cisi-a-dataset-for-information-retrieval).

## Features

- **Data Preprocessing:**
  - Tokenization, lemmatization, stopword removal, and special character removal.
  - Creation of tokenized document and query JSON files.
  - Generation of an inverted index for efficient retrieval.

- **Implemented Algorithms:**
  - Boolean Retrieval
  - Vector Space Model (VSM)
  - TF-IDF Ranking
  - Okapi BM25

- **Evaluation Metrics:**
  - Precision
  - Recall
  - F1-Score
  - Mean Average Precision (MAP)
