# Word Sense Disambiguation Project

## Team Members
- Arjun Dosajh
- Mihika Sanghi

## Introduction
This project focuses on Word Sense Disambiguation (WSD), a crucial challenge in Natural Language Processing. WSD aims to resolve lexical ambiguity by determining the appropriate meaning or sense of a polysemous word within a given context. This study presents a comprehensive investigation of different approaches to WSD, including both traditional algorithms and state-of-the-art neural network models.

## Datasets
- **Brown Corpus**: A collection of text samples in American English, compiled by Brown University in the 1960s.
- **SemCor 3.0**: A sense-tagged subset of the Brown Corpus, labeled with WordNet 2.0 senses.
- **SemEval datasets**: Used for testing (SemEval-2007, SemEval-2013, and SemEval-2015).

## Models Implemented

### Baseline Models
1. **K-Nearest Neighbor (KNN)**
2. **Naive Bayes Classifier**
3. **Lesk Algorithm** (Simple and Extended versions)

### Advanced Models
4. **BiLSTM**
5. **BERT Fine-Tuned Model**

## Results

### Baseline Models (on SemCor 3.0)
- K-Nearest Neighbor: 69.75%
- Naive Bayes: 22.4%
- Simple Lesk: 34.65%
- Extended Lesk: 49.42%

### BiLSTM (on SemCor 3.0)
- Accuracy: 66.33%

### BERT-Based Model
- SemEval-2013: 74.63%
- SemEval-2015: 78.49%
- Combined: 74.13%

## Conclusion
The BERT-based Word Sense Disambiguation (BERT-WSD) model outperformed all other models, demonstrating the effectiveness of transformer-based architectures for this task. The success of BERT can be attributed to its bidirectional context modeling, attention mechanism, and pre-training on large-scale data.
