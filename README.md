# Syntax Tree Parsing using the CKY Algorithm
This project implements a syntactic parser using the CKY (Cocke–Kasami–Younger) algorithm trained on the ATIS (Air Travel Information System) dataset from the Penn Treebank. It applies key concepts in Natural Language Processing (NLP) such as grammar induction, Chomsky Normal Form (CNF) conversion, and probabilistic parsing using NLTK.

## 📚 Overview
The goal of this project is to:
- Parse real-world flight-related queries using a context-free grammar
- Convert syntax trees to Chomsky Normal Form
- Extract grammatical productions
- Induce a Probabilistic Context-Free Grammar (PCFG)
- Apply the CKY algorithm with Viterbi parsing to analyze unseen sentences

## Step-by-Step Workflow:
1. Load and Inspect Syntax Trees
2. Visualize Sample Trees
3. Convert Trees to CNF
4. Extract Production Rules
5. Induce a PCFG
6. Read and Preprocess Development Sentences
7. Apply CKY Parsing with Viterbi Algorithm
8. Export Grammar with pickle

## 🛠️ Key Features
- ATIS Treebank Training: Utilizes train.trees.pre.unk for supervised grammar induction
- Chomsky Normal Form: Transforms tree structures to fit CKY constraints
- Grammar Induction: Generates a PCFG using frequency-based production rule probabilities
- Robust Parsing: Handles unknown words using <unk> substitution
- Viterbi Parsing: Implements probabilistic parsing to find the most likely syntax tree

## Requirements
This project uses a jupyter notebook. Make sure to have these installed before opening the .ipynb file:
- Python 3.7 or above
- Jupyter Notebooks

**If you don't have the above installed, I've also included a pdf copy of the file**

