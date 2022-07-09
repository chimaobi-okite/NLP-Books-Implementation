## Building an Encoder Transformer From Scratch With Pytorch 

This notebook contains the implementation of an encoder based transformer from scratch with pytorch with insights from chapter 1 of Transformer for NLP and chapter 3 of NLP with transformers books respectively. 

The original transformer architecture from google brain was for sequence to sequence modelling tasks like machine translation, since then this transformer has been modified and adapted for different purposes. Based on the nlp or nlu task at hand, one of the three types of transformers canbe used:-

**Encoder Only:**

Used for tasks such as text classification, named_entity_recongnition etc where the whole input sequence is processed at once into hidden states that canbe adapted for a particular task eg BERT and its Variants.

**Decoder Only:**

Used for tasks like text generation where an output is based only on words or sentences before it eg GPT models.

**Encoder-Decoder:**

Mainly used for complex sequence to sequence modelling tasks like text summarization, machine translation etc. Examples are the BART and T5 models. 
