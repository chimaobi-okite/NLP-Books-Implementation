Bidirectional Encoder Representations from Transformers attends to tokens at the same time. There are two types available 

* The bert-base 
* The bert-large.

The differentiating factor between the two above is the size. Bert uses learned positional encodings unlike the original transformer and was pretrained on Masked language modelling and Next sentence prediction tasks. 

This folder contains a notebbok that walks through the steps involved in finetuning a bert model for Acceptability Judgements downstream task and measure the predictions with the Matthews Correlation Coefficient (MCC). 
