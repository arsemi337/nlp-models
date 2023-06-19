# Training details

Sentence word2Vec trained with our own emotion dataset

| Training no. | Data samples | Train set % | Val set % | Test set % | Batch size | Epochs | Best epoch | Fitting time | Train accuracy | Train loss | Val accuracy | Val loss | Test accuracy | Test loss |               Accuracy figure               |               Loss figure               |               Confusion matrix                |                                Notes                                 |
|:------------:|:------------:|:-----------:|:---------:|:----------:|:----------:|:------:|:----------:|:------------:|:--------------:|:----------:|:------------:|:--------:|:-------------:|:---------:|:-------------------------------------------:|:---------------------------------------:|:---------------------------------------------:|:--------------------------------------------------------------------:|
|      1       |     40k      |     80%     |    10%    |    10%     |     16     |   50   |     16     |     N.A.     |     0.5029     |   1.2571   |    0.4588    |  1.3678  |    0.4600     |  1.3800   | [figure](./figures/training_1_accuracy.png) | [figure](./figures/training_1_loss.png) | [figure](./figures/training_1_confmatrix.png) |                                  Ok                                  |
