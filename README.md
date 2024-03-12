# Deep Learning for Natural Language Processing

Sandbox playground building Deep Learning models from scratch:

- `TensorFlow`/`keras` for digit recognition
- `Gensim` for word embeddings
- `TensorFlow`/`keras` for text generation
- `TensorFlow` and `transformers` for GPT-2
- `transformers` for BERT

Note: the notebooks have different `requirements.txt` files to handle dependencies.

We recommend creating different `conda` environments for each project, for example:

```
conda create --name deep-learning-nlp --file requirements-nlp.txt
conda create --name deep-learning-gpt2 --file requirements-GPT2.txt
conda create --name deep-learning-bert --file requirements-BERT.txt
```