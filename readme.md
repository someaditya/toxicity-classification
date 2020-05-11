#Welcome tho Toxity Classification

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1pmM6iyZmrq5VLQUmfvTEFN1zMF-punUl?usp=sharing)

##Dataset
https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data 

##Embeddings

FastText : 2 million word vectors trained on Common Crawl (600B tokens) : crawl-300d-2M.vec.zip: https://dl.fbaipublicfiles.com/fasttext/vectors-english/crawl-300d-2M.vec.zip

GloVe:
Twitter (2B tweets, 27B tokens, 1.2M vocab, uncased, 25d, 50d, 100d, & 200d vectors, 1.42 GB download): glove.twitter.27B.zip http://nlp.stanford.edu/data/glove.twitter.27B.zip

Project Setup
This machine learning project uses relatively smaller datasets, so development was performed locally using a Jupyter .ipynb notebook on a Conda environment.

##Jupyter Notebook file:
toxicity_classification.ipynb

##Python libraries required:
numpy
pandas
matplotlib.pyplot
IPython.display
seaborn
sklearn
scipy
keras
skmultilearn
scikitplot
