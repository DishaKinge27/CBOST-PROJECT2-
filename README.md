# AI Semantic Research Paper Search

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![FAISS](https://img.shields.io/badge/FAISS-Vector_Search-green)
![SentenceTransformers](https://img.shields.io/badge/SentenceTransformers-NLP-orange)

## Overview

AI Semantic Research Paper Search is a semantic search system designed to find Machine Learning research papers based on meaning rather than exact keywords. It uses transformer embeddings along with FAISS vector indexing to retrieve the most relevant papers efficiently.

## Objective

Traditional keyword-based search often fails to capture the actual context of a query. This project improves search quality by converting both research papers and user queries into dense vector embeddings and comparing them using semantic similarity.

## Key Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Semantic embedding generation using **all-MiniLM-L6-v2**
- High-speed similarity search with **FAISS**
- Natural language query support
- Top-K relevant research paper retrieval

## Tech Stack

- Python
- Pandas
- NumPy
- Hugging Face Datasets
- Sentence Transformers
- FAISS
- Jupyter Notebook

## Project Structure

```text
EDA.ipynb
Search_Engine.ipynb
README.md
requirements.txt
dataset.md
```

## Installation

```bash
pip install -r requirements.txt
```

## Usage

1. Run `EDA.ipynb`
2. Execute `Search_Engine.ipynb`
3. Search using:

```python
search_paper("your research query")
```

## Future Enhancements

- Interactive Streamlit interface
- Advanced filtering by author and publication year
- PDF upload and indexing
- AI-powered research paper summarization

## Author

**Disha Kinge**
