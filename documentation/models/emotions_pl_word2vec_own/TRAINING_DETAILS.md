# Training details

Word2Vec trained with our own emotion dataset

| Training no. | Data samples | Train set % | Val set % | Test set % | Batch size | Epochs | Best epoch | Fitting time | Train accuracy | Train loss | Val accuracy | Val loss | Test accuracy | Test loss |               Accuracy figure               |               Loss figure               |               Confusion matrix                |                                Notes                                 |
|:------------:|:------------:|:-----------:|:---------:|:----------:|:----------:|:------:|:----------:|:------------:|:--------------:|:----------:|:------------:|:--------:|:-------------:|:---------:|:-------------------------------------------:|:---------------------------------------:|:---------------------------------------------:|:--------------------------------------------------------------------:|
|      1       |     40k      |     80%     |    10%    |    10%     |     16     |   10   |     3      |     N.A.     |     0.4401     |   1.3693   |    0.4095    |  1.4657  |    0.4067     |  1.4703   | [figure](./figures/training_1_accuracy.png) | [figure](./figures/training_1_loss.png) | [figure](./figures/training_1_confmatrix.png) |                                  Ok                                  |
