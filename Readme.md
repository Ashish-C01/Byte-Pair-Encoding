# Byte Pair Encoder

Welcome to the Byte Pair Encoder (BPE) project! This repository contains the implementation of a basic and regex based Byte Pair Encoder algorithm, a popular subword tokenization method used in Natural Language Processing (NLP) to efficiently tokenize text data into smaller, more manageable units.


## Introduction

Byte Pair Encoding (BPE) is a subword tokenization technique that merges the most frequent pairs of bytes (or characters) iteratively. This method is particularly effective for handling rare words and out-of-vocabulary tokens, making it a staple in modern NLP tasks, especially in transformer-based models.

- Basic Tokenizer.ipynb: Implements the BasicTokenizer, the simplest implementation of the BPE algorithm that runs directly on text.
- Regex Based Tokenizer.ipynb: Implements the RegexTokenizer that further splits the input text by a regex pattern, which is a preprocessing stage that splits up the input text by categories (think: letters, numbers, punctuation) before tokenization. This ensures that no merges will happen across category boundaries. This was introduced in the GPT-2 paper and continues to be in use as of GPT-4.
## Features

- Efficient subword tokenization
- Handles rare and out-of-vocabulary words
- Customizable vocabulary size
- Easy integration with NLP models

