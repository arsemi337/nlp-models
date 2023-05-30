# Training details

All the trainings are fine-tuning of ***dkleczek/bert-base-polish-uncased-v1*** model. The used dataset is available in
the [dataset .json file](../../../data/translated/sarcasm/sarcasm_headlines_dataset_pl.json).
Originally it consists of 28619 data samples.

| Training no. | Data samples | Train set % | Val set % | Test set % | Batch size | Epochs | Best epoch |      Fitting time       | Train accuracy | Train loss | Val accuracy |     Val loss     | Test accuracy | Test loss |               Accuracy figure               |               Loss figure               |               Confusion matrix                | Notes |
|:------------:|:------------:|:-----------:|:---------:|:----------:|:----------:|:------:|:----------:|:-----------------------:|:--------------:|:----------:|:------------:|:----------------:|:-------------:|:---------:|:-------------------------------------------:|:---------------------------------------:|:---------------------------------------------:|:-----:|
|      1       |   28,619k    |     80%     |    10%    |    10%     |     8      |   10   |     1      | 21min 09s (***Colab***) |     0.8117     |   0.4108   |    0.8456    |      0.3432      |    0.8435     |  0.7200   | [figure](./figures/training_1_accuracy.png) | [figure](./figures/training_1_loss.png) | [figure](./figures/training_1_confmatrix.png) |  Ok   |
|      2       |     10k      |     80%     |    10%    |    10%     |     8      |   10   |     2      | 08min 30s (***Colab***) |     0.9101     |   0.2307   |    0.8310    | val_loss: 0.4310 |    0.8310     |  0.5558   | [figure](./figures/training_2_accuracy.png) | [figure](./figures/training_2_loss.png) | [figure](./figures/training_2_confmatrix.png) |  Ok   |