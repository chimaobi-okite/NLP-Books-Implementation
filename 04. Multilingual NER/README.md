## Multilingual Named-Entity-Recognition

The notebook is based on chapter 4 of NLP with transformer book.

What happens when you want to fine tune a model on less popular dataset or your 
corpus contains text in different languages? For such tasks, some transformers has already been pretrained on a corpus with 100s of languages which enable zeroshot crosslingual transfer learning. An eample of such model is XLM_RoBERTa which we used  to tackle a multilingual NER task in this notebook.

The notebook in this folder gives insights on when to perform monolingual transfer learning, cross lingual transfer and factors influencing cross lingual transfer process to follow.

The nootbook also contains steps to prepare data for Named-Entity-Recognition and how to build a custom transformer head based on use-case task. 

