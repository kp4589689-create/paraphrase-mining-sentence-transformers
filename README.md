# Paraphrase Mining using Sentence Transformers

## Overview
This project demonstrates how to perform paraphrase mining and semantic similarity analysis using the Sentence Transformers library. It generates sentence embeddings, calculates cosine similarity scores, identifies paraphrased sentence pairs, and detects semantic outliers from a collection of sentences.

The notebook uses pre-trained transformer models to understand sentence meaning beyond simple keyword matching.

## Features
- Generate sentence embeddings using Sentence Transformers
- Calculate cosine similarity between sentence pairs
- Perform paraphrase mining
- Detect highly similar sentence pairs
- Use multilingual transformer models
- Identify semantic outlier sentences

## Technologies Used
- Python
- Sentence Transformers
- Transformers
- PyTorch
- NumPy

## Models Used
- all-MiniLM-L6-v2
- distiluse-base-multilingual-cased-v1

## Project Workflow
1. Install required libraries.
2. Load a pre-trained Sentence Transformer model.
3. Encode text into vector embeddings.
4. Compute cosine similarity between sentences.
5. Perform paraphrase mining on a sentence collection.
6. Display the most similar sentence pairs.
7. Detect semantic outliers using similarity scores.

## Applications
- Duplicate question detection
- Semantic search
- Chatbots
- Text clustering
- Information retrieval
- NLP research
- Recommendation systems

## Installation

```bash
pip install sentence-transformers
pip install torch
pip install tf-keras
```

## Run the Project

Open the Jupyter Notebook and execute each cell in sequence.

```bash
jupyter notebook
```

## Example Output

- Sentence similarity score
- Ranked paraphrase pairs
- Semantic outlier detection
- Multilingual sentence embeddings

## Future Improvements

- Add larger datasets
- Build an interactive web application
- Support document-level similarity
- Visualize embeddings using PCA or t-SNE
- Add evaluation metrics

