# Purpose:
the purpose of these files to use BERT to convert words into embedded vectors with contextual meaning and to use different pretrained transformer based models like BERT or DistillBert for different NLP tasks.

# 1) Basics_of_BERT.ipynb

This file contains the basic implementation of the Bert model to convert words into embedding vectors with their contextual meaning.  it is achieved with the use of the library called Tensorflow_Hub. when this library used, the input data is converted into a certain format with the help of preprocessing model so that it can be processed by the encoder

# 2) Transformer and BERT implementation with HuggingFace.ipynb:

This file uses Transformers library to download and use pretrained transformer based model like bert or distillbert. These model can be used in a variety of NLP tasks such as Sentiment analysis or text classification or movie review. However, a transformer based model can be created from scratch if these pretrained models don't give good accuracy. There are two ways to use this pretrained model in HuggingFace:

  # a) Using the Pipeline API:
  it combines the tokenizer and the pretrained model. you just need to pass the input to the classifier to     be able to get the output.
       
  # b) using tokenizer and model seperately:
  it allows you to download tokenizer and the pretrained model and load them into memory. here we have to use the tokenizer first to convert words into embedded vectors before we pass the input into the pre trained model. each model has different tokenizer as each model requires the input to be converted into a particular format. it provides more flexibility in terms of fine tuning the model on your data.


