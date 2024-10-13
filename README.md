# Tokenizer From Scratch

This repository contains an implementation of a custom tokenizer built from scratch using the **Byte Pair Encoding (BPE)** algorithm. The tokenizer is trained on the WikiText-103 dataset and is designed to handle tokenization tasks for natural language processing applications.

## What is a Tokenizer?

In natural language processing (NLP), a tokenizer is a crucial component that converts text into a sequence of tokens. Tokens are smaller units of text, such as words or subwords, which are used by machine learning models for various tasks. Tokenization is the first step in processing text data and helps in breaking down complex text into manageable chunks that can be analyzed and understood by algorithms.

## What is the BPE Algorithm?

The Byte Pair Encoding (BPE) algorithm is a subword tokenization technique used to handle rare and out-of-vocabulary words by breaking down words into smaller, more frequent subword units. The BPE algorithm works by iteratively merging the most frequent pairs of characters or subwords in a corpus, thus building a vocabulary of subword units. This approach helps in handling large vocabularies efficiently and improves the performance of language models.

### How BPE Works:

1. **Initialization**: Start with a corpus where each word is treated as a sequence of characters.
2. **Pair Counting**: Count the frequency of all adjacent character pairs.
3. **Merging**: Replace the most frequent pair with a new, unique symbol.
4. **Iteration**: Repeat the counting and merging steps until the desired vocabulary size is reached.

## Setup and Installation

To get started with building and using the tokenizer, follow these steps:

### Clone the Repository

```bash
git clone https://github.com/agkavin/Tokenizer-From-Scratch.git
cd Tokenizer-From-Scratch
```

### Dataset

The tokenizer is trained using the WikiText-103 dataset. Ensure you have the dataset downloaded and placed in the appropriate directory. You can download the dataset from [HuggingFace🤗](https://huggingface.co/datasets/Salesforce/wikitext).
