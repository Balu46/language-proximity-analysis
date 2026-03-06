# Language Proximity Analysis

This project focuses on analyzing linguistic similarity between languages using machine learning techniques and phonetic representations. The system extracts phonetic dictionaries from WikiPron and trains vector representations of words and phonemes using the Word2Vec Continuous Bag of Words (CBOW) algorithm.

The goal of the project is to explore relationships between languages by comparing their phonetic and character-level structures using learned embeddings.

### Key features

- Automated phoneme dictionary extraction from WikiPron
- Support for over 100 languages using Latin scripts
- Implementation of Word2Vec CBOW model in PyTorch
- Character-level and phoneme-level embeddings
- Cross-lingual word comparison
- Similarity metrics (cosine similarity and Euclidean distance)
- Visualization of embedding space using PCA and t-SNE

## The system consists of several modules:

**1. Data Extraction**
- Downloads phonetic dictionaries from WikiPron
- Filters invalid entries
- Stores phoneme data per language

**2. Dataset Layer**
- PyTorch datasets for multilingual character data
- PyTorch datasets for phoneme sequences

**3. Embedding Training**
- Implementation of Word2Vec CBOW from scratch
- Configurable hyperparameters
- Training using Adam optimizer and cross-entropy loss

**4. Word Comparison System**
- Combines phoneme and character embeddings
- Calculates similarity between words across languages
- Uses cosine similarity and Euclidean distance

**5. Visualization**
- PCA and t-SNE projections of embedding space
- Heatmaps for similarity analysis

## Technologies

- Python
- PyTorch
- Word2Vec (CBOW)
- Natural Language Processing
- WikiPron phonetic datasets
- PCA / t-SNE visualization

## Team Roles

This project was developed as part of a team collaboration.

- **Project Manager:** Jan Zakroczymski  
- **Report Preparation:** Krzysztof Olczyk  
- **Repository Maintenance:** Mateusz Cąkała  
- **Team Member:** Adrian Bagiński

