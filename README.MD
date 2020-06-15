# From Embedding to Language Model

---

## Description

An introduction of the development from encoding(One hot, tf-idf......) to embedding(Word2vec,Glove,Fasttext......) and language model(Elmo, GPT2, BERT......)

## Requirement and Startup


<pre>
python3.6
git clone https://github.com/aron3312/embedding2lm.git
pip install -r requirements.txt
Open FromEmbeddingToLM.pptx to learn with ppt
</pre>


## Structure

<pre>
word_encoding.ipynb 
</pre>
An example of title recommendation, using single news title to find the most related one from other news.
Including three method:
1. one hot encoding
    - DTM
    - TDM
2. TF-IDF encoding

3. sequence level related encoding

<pre>word_embedding.ipynb</pre>
An example of word embedding, using word2vec, GloVe, Fasttext
Including three method:

1. Word2Vec
2. GloVe
3. FastText
