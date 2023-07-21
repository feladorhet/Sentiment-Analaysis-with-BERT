# Sentiment-Analaysis-with-BERT
A simple project where I fine-tuned the DistilBERT-base-uncased model for sentiment analysis - emotion detection on "emotions" database with tweets.

It achieves the following results on the evaluation set:
- Loss: 0.2116
- Accuracy: 0.9275
- F1: 0.9275
### Training procedure
## Training hyperparameters

The following hyperparameters were used during training:

- learning_rate: 2e-05
- train_batch_size: 64
- eval_batch_size: 64
- seed: 42
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: linear
- num_epochs: 2

SEE THE MODEL CARD FOR MORE INFO AT
https://huggingface.co/feladorhet/distilbert-base-uncased-finetuned-emotion

