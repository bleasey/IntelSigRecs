# Task 2C : Building a Closed and Extractive Question and Answer Language model based on provided Context

The goal of this task is to experiment and discover an language model that is suitable for the task of context based extractive question answering. The evaluation should be done on the validation dataset using Metrics like Exact Match(EM) smd F1 score. Calculate the F1 score for the whole validation set by aversging the score for each context,question and answer triplet.

In this task, I have build on top of the baseline model provided which is the following pre-trained model: [huggingface.co/deepset/roberta-base-squad2](https://huggingface.co/deepset/roberta-base-squad2)

The model_params_qna folder has been ignored as it is heavy.