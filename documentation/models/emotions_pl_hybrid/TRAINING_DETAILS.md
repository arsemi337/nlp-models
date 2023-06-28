# Training details

Hybrid models composed of GPT2, BERT and Word2Vec models.

|                            Name                             | Test accuracy | Test loss |                        Confusion matrix                         | Notes |
|:-----------------------------------------------------------:|:-------------:|:---------:|:---------------------------------------------------------------:|:-----:|
|                            Basic                            |    0.8753     |  0.5304   |         [figure](./figures/basic_hybrid_confmatrix.png)         |  Ok   |
|                       Only BERT & GPT                       |    0.8755     |  0.4018   |        [figure](./figures/only_bert_gpt_confmatrix.png)         |  Ok   |
|                  Best from only BERT & GPT                  |    0.8668     |  0.4126   |   [figure](./figures/best_from_only_bert_gpt_confmatrix.png)    |  Ok   |
|            BERT & GPT with best w2v per emotion             |    0.8750     |  0.5375   |  [figure](./figures/best_word2vec_per_emotion_confmatrix.png)   |  Ok   |
| BERT & GPT with trusted binary 0/1 w2v when 1 is predicted  |    0.8435     |  0.5567   | [figure](./figures/binary_0_1_word2vec_trusted_confmatrix.png)  |  Ok   |
| BERT & GPT with weighted binary 0/1 w2v when 1 is predicted |    0.8755     |  0.5116   | [figure](./figures/binary_0_1_word2vec_weighted_confmatrix.png) |  Ok   |



