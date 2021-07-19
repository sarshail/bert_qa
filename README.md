# bert_qa

The goal of this project is to explore BERT and use it for the task of Question Answering.

This project consists of 3 notebooks:

1. explore_BERT_embeddings.ipynb
This notebook explores the following:
* the BERT model, tokenizer, hidden layer outputs
* How to got token embeddings for our text from BERT hidden states
* Creating word and sentence vectors from token embeddings

2. explore_BERT_for_question_answering.ipynb
Here we download a BERT-large model that has already been fine-tuned for Question Answering task.
And use it for answering questions based on the context we provide. 
This notebook explores the following:
* BERT input format for Question Answering
* Supplying our own context-question pairs and getting answers


3.finetuning_bert_for_question_answering.ipynb
This notebook covers:
* Explore Stanford Question Answering Dataset (SQuAD) 2.0 Dataset
* Prepare data for BERT training for question answering
* Fine-tune the DistilBert model using this data for question answering
* Evaluate performance on validation set