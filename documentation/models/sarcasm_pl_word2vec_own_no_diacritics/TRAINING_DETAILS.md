# Training details

Word2Vec trained with our own emotion dataset but with diacritics removed

| Training no. | Data samples | Train set % | Val set % | Test set % | Batch size | Epochs | Best epoch | Fitting time | Train accuracy | Train loss | Val accuracy | Val loss | Test accuracy | Test loss |               Accuracy figure               |               Loss figure               |               Confusion matrix                |                                Notes                                 |
|:------------:|:------------:|:-----------:|:---------:|:----------:|:----------:|:------:|:----------:|:------------:|:--------------:|:----------:|:------------:|:--------:|:-------------:|:---------:|:-------------------------------------------:|:---------------------------------------:|:---------------------------------------------:|:--------------------------------------------------------------------:|
|      1       |     40k      |     80%     |    10%    |    10%     |     16     |   10   |     3      |     N.A      |     0.6651     |   0.5996   |    0.6342    |  0.6253  |    0.6502     |  0.6130   | [figure](./figures/training_1_accuracy.png) | [figure](./figures/training_1_loss.png) | [figure](./figures/training_1_confmatrix.png) |                                  Ok                                  |
