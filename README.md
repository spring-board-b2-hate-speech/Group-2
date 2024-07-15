# Group-2

This project aims to develop a state-of-the-art machine learning model for detecting hate speech in Twitter posts using BERT (Bidirectional Encoder Representations from Transformers). BERT is a powerful transformer-based model that captures the context of words in a sentence by considering both their left and right context, making it highly effective for natural language processing tasks.


# Dataset Source

This project utilizes a dataset from the following source:

- Hate_Speech
- *Source:* Kaggle
- *Link to Dataset:* [https://www.kaggle.com/datasets/icon1c/hate-speech]

# Data Preprocessing
- Converted text to lowercase
- Decoded HTML entities and converted emojis to text equivalents
- Expanded abbreviations
- Removed special characters, punctuation, URLs
- 
# Tokenization and Embedding 
- Tokenization implemented using NLTK's word_tokenize
- TF-IDF (Term Frequency-Inverse Document Frequency
