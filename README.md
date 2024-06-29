# EMILLE Corpus Analysis: Differentiating Spoken and Written Hindi

This project focuses on analyzing the EMILLE corpus to distinguish between spoken and written Hindi texts. We utilized two datasets:

1. `mixed.csv`: Contains all text files with outputs labeled as 1 for spoken and 0 for written Hindi.
2. `balanced.csv`: Comprises an equal number of spoken and written Hindi texts.

## Datasets

We expect the balanced dataset (`balanced.csv`) to yield better results due to its equal representation of written and spoken texts from the corpora. This balance helps mitigate potential biases in the model training process.

## Feature Extraction

We explored feature extraction using two different NLP modules:

### 1. NLTK Module

Initially, we employed the Natural Language Toolkit (NLTK) for feature extraction. However, the results were suboptimal, likely due to NLTK's primary focus on English language processing.

### 2. Stanza Module

We achieved more promising results using the Stanza module, which incorporates a robust Hindi NLP model. This approach yielded significantly better performance in differentiating between spoken and written Hindi texts.


