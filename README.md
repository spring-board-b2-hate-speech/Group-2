# Group-2

Detecting hate speech on Twitter involves using machine learning to identify tweets that promote hatred or violence based on protected characteristics. Twitter faces the challenge of balancing free expression with preventing harm, and automated detection helps flag harmful content for human review. This process involves analyzing text for patterns and sentiment indicative of hate speech, with models trained on labeled data.


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

# Tokenization and Embedding 
- Tokenization implemented using NLTK's word_tokenize
- TF-IDF (Term Frequency-Inverse Document Frequency
