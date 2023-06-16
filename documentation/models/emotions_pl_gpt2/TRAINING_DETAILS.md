# Training details

All the trainings are fine-tuning of ***flax-community/papuGaPT2*** model. The used dataset is available in
the [dataset .json file](../../../data/translated/emotions/equalized_emotions_dataset_pl.json).
Originally it consists of 40000 data samples.

| Training no. | Data samples | Train set % | Val set % | Test set % | Batch size | Epochs | Best epoch |         Fitting time         | Train accuracy | Train loss | Val accuracy | Val loss | Test accuracy | Test loss |               Accuracy figure               |               Loss figure               |               Confusion matrix                |                                Notes                                 |
|:------------:|:------------:|:-----------:|:---------:|:----------:|:----------:|:------:|:----------:|:----------------------------:|:--------------:|:----------:|:------------:|:--------:|:-------------:|:---------:|:-------------------------------------------:|:---------------------------------------:|:---------------------------------------------:|:--------------------------------------------------------------------:|
|      1       |     40k      |     80%     |    10%    |    10%     |     16     |   10   |     2      | 20min 33s (***RTX 3070Ti***) |     0.8737     |   0.3686   |    0.8440    |  0.4908  |    0.8378     |  0.4626   | [figure](./figures/training_1_accuracy.png) | [figure](./figures/training_1_loss.png) | [figure](./figures/training_1_confmatrix.png) |                                  Ok                                  |
|      2       |     40k      |     80%     |    10%    |    10%     |     16     |   10   |     2      | 26min 03s (***RTX 3070Ti***) |     0.8846     |   0.3224   |    0.8590    |  0.4111  |    0.8595     |  0.4155   | [figure](./figures/training_2_accuracy.png) | [figure](./figures/training_2_loss.png) | [figure](./figures/training_2_confmatrix.png) | Dataset shuffled with seed 42 for same training/validation/test data |
