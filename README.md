# BERT Sentiment Analysis

`Bidirectional Encoder Representations from Transformers` (BERT) is a transformer-based machine learning technique for natural language processing (NLP) pre-training.

`Hugging Face` is having pre-trained model on English language using a `Masked Language Modelling` (MLM) objective. This model can be utilised for tasks like sentiment analysis, question answering, language structure acceptability etc with little fine-tuning of weights (`parameters`). These tasks are called `Downstream` tasks as model was originally built (`pre-trained`) for the task of masked language modelling. While learning the original task, model learns english language encoding. Model's this ability in general can be utilised for various downstream tasks as mentioned above.

Here, we have used `bert-base-uncased` model from `Hugging Face`. For more information on the model, please visit the [Link](https://huggingface.co/bert-base-uncased).

Loss value while training has been plotted in the following image. It can be observed that `Pre-trained BERT` model is highly effective in terms of learning the task of english language sentiment analysis.


![](https://github.com/kishanAk21/BERT_Sentiment_Analysis/blob/main/Train_loss.png)


This repository contains two python notebooks,
1. Fine_Tuning_BERT_for_Sentiment_Analysis.ipynb: It reads the sentiment dataset and fine-tunes the BERT model. It also saves the fine-tuned model as `my_model`.
2. Sentiment_prediction.ipynb: This notebook loads the fine-tuned model and predicts the sentiments for given sentence inputs.


Note: I would recommend to use `Google Colab`, if you are planning to fine-tune the model and get the first hand experience.
