# NLU intent classification slot filling 
This repository is a individual project for the "Natural Language Understanding" course of the Master in Artificial Intelligent Systems at the University of Trento, a.y. 2022-2023.

In this project I implemented 2 models (and a baseline model) to perform intent classification and slot filling in a multitask learning setting.

Slot filling and intent detection play important roles in Natural Language Understanding (NLU) systems. These 2 tasks are usually dependent one from the other, that’s why a multitask learning setting is used a lot in order to do joint intent classification and slot filling. In this project I implemented 3 models, all
based on encoder/decoder paradigm, with hard parameter sharing on encoder. The first model is the baseline model, in which the encoder consists on a simple LSTM and 2 different classifiers for slot and intent tasks. The second model is an improved version of the first one, in which the encoder is a bidirectional 2 layer LSTM. The last model is based on BERT (Bidirectional Encoder Representations from Transformers), a multilayer bidirectional Transformer encoder based on the originalTransformer model 
