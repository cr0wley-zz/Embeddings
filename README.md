# Embeddings
The repository houses the code for intuitively understanding `Word Embeddings`. We take help of `tf.keras` to build word-embeddings.

We have documented all of the experiments with [wandb](https://wandb.ai) and have reports for the same published in their [gallery](https://wandb.ai/gallery).

## Articles for W&B:
- [Word2Vec](https://wandb.ai/authors/embeddings/reports/Word2Vec---VmlldzozMzIxNjQ)
- [GloVe](https://wandb.ai/authors/embeddings-2/reports/GloVe--VmlldzozNDg2NTQ)

## Folder Structure
The repository is structured in the following way:
- Word2Vec
    - `CBOW.ipynb`: The notebook which showcases the Bag of Word technique for word embeddings.
    - `Skip_gram.ipynb`: The notebook which showcases the Skip-Gram technique for word embeddings.
    - `Word2Vec_ablation.ipynb`: This notebook houses an ablation done on the tensorflow official word2vec guide. (This uses a different negative pair context)
- Glove
    - `Negative_Sampling.ipynb`: The process of negative sampling as a replacement of softmax.
    - `Glove.ipynb`: The notebook which showcases the GloVe embeddings.
- FastText
    - `enriching_fasttext.ipynb`: The notebook which showcases the Enriching Subwords process word embeddings.

## A study on Word Embeddings
The concept of words as vectors was an ingenius concept [introduced in 2013](https://arxiv.org/pdf/1301.3781.pdf) by Mikolov et.al. 
During the time of its conception, it blew open the possibilities and raised the bar of NLP. Through this repository and the accompanying  Weights and Biases report, we have segmented the concept thoroughly and in a such a way that all idelogical intuitions formed in transition of reading the report pave way for a better understanding of the underlying mathematics involved. We have also included a hands-on coding tutorial explaining each relevant steps invovled. 
