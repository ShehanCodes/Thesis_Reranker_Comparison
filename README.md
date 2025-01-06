# RAG Reranker Comparison: Thesis Code Implementation  

This repository contains the implementation code for my thesis titled:  
**"Enhancing Retrieval-Augmented Generation Pipelines for Improved Performance: A Comparative Analysis of Reranking Models."**  

The project focuses on evaluating the impact of different reranking models in Retrieval-Augmented Generation (RAG) pipelines, using varying configurations for initial retrieval (\(k\)).  

---

## **Table of Contents**
1. [Project Overview](#project-overview)  
2. [Key Features](#key-features)  
3. [Setup and Installation](#setup-and-installation)  

---

## **Project Overview**
This project compares different neural re-rankers, including:  
- **Cross-Encoder Rerankers**  
- **LLM-based Rerankers**  
- **Multi-vector Rerankers**  

The analysis involves three retrieval configurations where the initial retrieval set size (\(k\)) varies:  
- \(k = 10\)  
- \(k = 25\)  
- \(k = 50\)  

The code evaluates:  
- Retrieval quality (context recall, precision, etc.)  
- Response generation quality (faithfulness, relevance)  
- Trade-offs in retrieval latency and computational efficiency.  

---

## **Key Features**
- **Baseline Comparison**: FAISS dense retrieval as the benchmark model.  
- **Re-ranker Integration**: Easy-to-extend framework for adding additional rerankers.  
- **Configurable Retrieval**: Supports different initial retrieval \(k\) values for flexible experimentation.  
- **Comprehensive Evaluation**: Detailed metrics for retrieval and generation quality, latency, and efficiency.  

---

