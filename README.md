# English-Hindi-Nlp-Translation
The code focuses on implementing English-to-Hindi translation using the MBart model and tokenizer from the Hugging Face Transformers library.

1. Import necessary libraries and sets up the environment, including data loading from a CSV file containing English and Hindi sentence pairs.
2. Visualized the data using FastEda Library.
3. Performed extensive data preprocessing steps such as text cleaning, tokenization, and adding special tokens to mark sentence boundaries.
4. Calculated various metrics like sentence lengths and word frequencies in preparation for model training.
5. The core of the code involves initializing the MBart model and tokenizer for Hindi translation. Created a translation function that takes an English input sentence, tokenizes it using the tokenizer, generates Hindi translations using the pre-trained MBart model, and formats the output.
The translation results are demonstrated by applying the function to a sample of English sentences and printing both the original Hindi sentences from the dataset and their translated counterparts.
