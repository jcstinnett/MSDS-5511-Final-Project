# MSDS-5511-Final-Project
Deep Learning Final Project

## Project Overview
This project applies deep learning techniques to classify medical texts, specifically abstracts and short research papers, into three cancer categories: thyroid, lung, and colon. We compare the performance of Bidirectional LSTM and GRU models using domain specific word embeddings.

## Models Used
BiLSTM
BiGRU with added Global Max Pooling 

## Evaluation Metrics
- Validation accuracy/loss
- Per class F1 score
- Macro F1 score
- Confusion matrix

## Word Embeddings
BioWordVec: Pre-trained embeddings built on PubMed and MIMIC-III

## Limitations
- Small dataset (~1000 articles after dedup)
- Class imbalance

## Future Improvements
- Fine-tuning BioWordVec embeddings
- Using BioBERT or other Transformer-based models
- Augmenting underrepresented classes
