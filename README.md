# BERT-Word2Vec Hybrid Keyphrase Extractor

## Description
This Jupyter notebook is focused on extracting keyphrases from documents using both the pretrained KeyBERT model and Google's Word2Vec. It showcases methods for not only identifying keyphrases that are explicitly present in the text but also generating absent keyphrases and evaluating their relevance and accuracy.

## Features and Sections
- **Present Keyphrase Extraction:** Utilizes KeyBERT to identify key terms directly from the text.
- **Absent Keyphrase Generation:** Leverages a combination of BERT embeddings and Word2Vec models to generate relevant keyphrases not explicitly mentioned in the text.

## Dependencies
To run this notebook, ensure you have the following Python libraries installed:
- gensim (for `KeyedVectors` and `Word2Vec`)
- google.colab (for `drive` module, optional if running on Google Colab)
- keybert (`KeyBERT` for keyphrase extraction)
- pathlib (for `Path` handling)
- sentence_transformers (for `SentenceTransformer` and utilities)
- sklearn (for `cosine_similarity`)
- glob, os (for file and directory handling)

## Evaluation

The model was evaluated using the Inspec Dataset and performance was compared to various models from renowned research papers centered on keyphrase extraction and generation.
