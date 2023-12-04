# TF-IDF Information Retrieval System in Python
This repository contains a Python notebook that implements an information retrieval system using the Term Frequency-Inverse Document Frequency (TF-IDF) method. The system processes a dataset of documents and employs TF-IDF and cosine similarity (both implemented from scratch) for document retrieval based on user queries.

## Features
* XML Document Parsing: Reads and parses a dataset of documents in XML format.
* Preprocessing: Implements tokenization, stop words filtering, case folding, and stemming to preprocess the documents.
* TF-IDF Calculation: Calculates the TF-IDF matrix for the documents, implementing the TF-IDF algorithm from scratch.
* Cosine Similarity: Implements cosine similarity from scratch to evaluate the similarity between documents.
* Document Retrieval: Utilizes the similarity matrix, based on cosine similarity, to retrieve documents that are most similar to a given query.

## How to Use
* Clone the Repository: git clone git@github.com:saranabhani/information-retrieval.git
* Install Dependencies: Ensure Python is installed on your system and install any required dependencies.
* Run the Notebook: Open the notebook in your preferred environment (e.g., Jupyter Notebook) and execute the cells.
* Load Your Dataset: Place your XML dataset in the designated folder or adjust the path in the notebook accordingly.
* Enter a Query: Input your query in the provided cell to retrieve similar documents.
