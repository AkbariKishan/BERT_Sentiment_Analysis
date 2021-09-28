# BERT Sentiment Analysis

`Bidirectional Encoder Representations from Transformers` (BERT) is a transformer-based machine learning technique for natural language processing (NLP) pre-training.

`Hugging Face` is having pre-trained model on English language using a `Masked Language Modelling` (MLM) objective. This model can be utilised for tasks like sentiment analysis, question answering, language structure acceptability etc with little fine-tuning of weights (`parameters`). These tasks are called `Downstream` tasks as model was originally built (`pre-trained`) for the task of masked language modelling. While learning the original task, model learns english language encoding. Model's this ability in general can be utilised for various downstream tasks as mentioned above.

Here, we have used `bert-base-uncased` model from `Hugging Face`. For more information on the model, please visit the [Link](https://huggingface.co/bert-base-uncased).
