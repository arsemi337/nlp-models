# Training details

All the trainings are fine-tuning of ***dkleczek/bert-base-polish-uncased-v1*** model. The used dataset is available in
the [dataset .json file](../../../data/translated/sarcasm/emotions_dataset_pl.json).
Originally it consists of 40000 data samples.

| Training no. | Data samples | Train set % | Val set % | Test set % | Batch size | Epochs | Best epoch |      Fitting time       | Train accuracy | Train loss | Val accuracy | Val loss | Test accuracy | Test loss |               Accuracy figure               |               Loss figure               |               Confusion matrix                | Notes |
|:------------:|:------------:|:-----------:|:---------:|:----------:|:----------:|:------:|:----------:|:-----------------------:|:--------------:|:----------:|:------------:|:--------:|:-------------:|:---------:|:-------------------------------------------:|:---------------------------------------:|:---------------------------------------------:|:-----:|
|      1       |    9,018k    |     80%     |    10%    |    10%     |     8      |   10   |     3      | 14min 23s (***Colab***) |     0.9206     |   0.2381   |    0.8348    |  0.5188  |    0.8359     |  0.5687   | [figure](./figures/training_1_accuracy.png) | [figure](./figures/training_1_loss.png) | [figure](./figures/training_1_confmatrix.png) |  Ok   |
|      2       |     40k      |     80%     |    10%    |    10%     |     8      |   10   |     1      | 37min 02s (***Colab***) |     0.8046     |   0.5450   |    0.8475    |  0.3800  |    0.8487     |  0.4046   | [figure](./figures/training_2_accuracy.png) | [figure](./figures/training_2_loss.png) | [figure](./figures/training_2_confmatrix.png) |  Ok   |