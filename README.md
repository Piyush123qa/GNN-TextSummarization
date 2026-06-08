# Graph Neural Network Based Extractive Text Summarization

## Overview

This project implements an Extractive Text Summarization system using Graph Neural Networks (GNNs).

The approach converts documents into sentence-level graphs where:

- Nodes represent sentences
- Edges represent semantic similarity between sentences
- Sentence embeddings are used as node features
- Graph Convolution Networks learn sentence importance
- Important sentences are selected to generate summaries

---

## Workflow

1. Data Preprocessing
2. Sentence Segmentation
3. Sentence Embedding Generation
4. Graph Construction
5. Graph Neural Network Training
6. Sentence Classification
7. Summary Generation
8. ROUGE Evaluation

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NetworkX
- Sentence Transformers
- Pandas
- NumPy
- Scikit-learn
- GNN

---

## Model Architecture

Document
↓
Sentence Segmentation
↓
Sentence Embeddings
↓
Graph Construction
↓
Graph Convolution Layers
↓
Sentence Classification
↓
Summary Generation

---

## Evaluation Metrics

- ROUGE-1
- ROUGE-2
- ROUGE-L

---

## Sample Output

Input:
Long News Article

Generated Output:
Extractive Summary generated using Graph Neural Network

---

## Future Improvements

- Graph Attention Networks (GAT)
- Multilingual Summarization
- Abstractive Summarization
- Hybrid Transformer + GNN Models

---

## Author

Piyush Kumar Das

AI/ML Enthusiast | NLP | Graph Neural Networks
