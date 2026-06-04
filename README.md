# NLP-pipeline-for-the-disease-entity-recognition-task-
Biomedical NER pipeline benchmarking 15 combinations of tokenizers and embeddings (Word2Vec, GloVe, FastText, ELMo, BERT) on the BC5CDR disease dataset using BiLSTM-CRF.


A Named Entity Recognition (NER) pipeline for biomedical disease detection built on the BC5CDR dataset. Systematically compares 15 pipeline combinations across three tokenizers (Whitespace, NLTK, HuggingFace BPE/WordPiece) and five embedding methods (Word2Vec, GloVe, FastText, ELMo, BERT) using a BiLSTM-CRF sequence labeling architecture. Includes memory-optimised training with disk-based caching, dynamic padding, and gradient checkpointing to run within Google Colab's free-tier GPU constraints.
