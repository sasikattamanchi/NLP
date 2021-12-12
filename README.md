This repository has jupyter notebooks  that demonstrate the use of a few popular techniques in Natural Language Processing like word embeddings, Language modelling, Neural machine translation using Seq2Seq, Attention, Transformers etc.

1) word2vec: Generate word2vec embeddings for telugu language. The skipgram word2vec model is trained on a corpus of telugu wikipedia articles. This corpus is provided in the folder Data. [Pytorch]
2) fasttext: Subword embeddings for telugu language. Same data as in word2vec is used. [Pytorch]
3) Language model: An RNN (LSTM) based language model. [Pytorch]
4) NMT_Attention: An attention based model for neural machine translation from german to english. The model is trained on [Multi30k](https://pytorch.org/text/stable/datasets.html#torchtext.datasets.Multi30k) dataset. [PyTorch+ Tensorboard logging]
5) NMT_Transformer: An neural machine translation model based on transformer architecture. Same data as in NMT_Attention. [Pytorch + WandB logging]

