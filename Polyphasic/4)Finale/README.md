# Task 2D: Designing Your Machine Learning System

The final system is a combination of the models trained in tasks 2B and 2C. The context and questions are fed into the [huggingface.co/deepset/roberta-base-squad2](https://huggingface.co/deepset/roberta-base-squad2) fine-tuned QnA model, the results are then tokenized again and passed into the translation model of task 2B  [huggingface.co/Helsinki-NLP/opus-mt-en-fr](https://huggingface.co/Helsinki-NLP/opus-mt-en-fr?text=In+1981%2C+he+founded+the+Astronomy+Club+of+Rimouski+in+Quebec.).

