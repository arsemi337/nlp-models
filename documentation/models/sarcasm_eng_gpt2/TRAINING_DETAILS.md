# Training details

All the trainings are fine-tuning of ***gpt2*** model. The used dataset is available in
the [dataset .json file](../../../data/english_original/sarcasm/Sarcasm_Headlines_Dataset_v2.json).
Originally it consists of 28619 data samples.

| Training no. | Data samples | Train set % | Val set % | Test set % | Batch size | Epochs | Best epoch |         Fitting time         | Train accuracy | Train loss | Val accuracy | Val loss | Test accuracy | Test loss |               Accuracy figure               |               Loss figure               |               Confusion matrix                |            Notes            |
|:------------:|:------------:|:-----------:|:---------:|:----------:|:----------:|:------:|:----------:|:----------------------------:|:--------------:|:----------:|:------------:|:--------:|:-------------:|:---------:|:-------------------------------------------:|:---------------------------------------:|:---------------------------------------------:|:---------------------------:|
|      1       |   28,619k    |     80%     |    10%    |    10%     |     16     |   10   |     2      | 12min 29s (***RTX 3070Ti***) |     0.8888     |   0.2606   |    0.8784    |  0.3265  |    0.8697     |  0.3111   | [figure](./figures/training_1_accuracy.png) | [figure](./figures/training_1_loss.png) | [figure](./figures/training_1_confmatrix.png) |             Ok              |
|      2       |     10k      |     80%     |    10%    |    10%     |     16     |   10   |     3      | 6min 32s (***RTX 3070Ti***)  |     0.9405     |   0.1577   |    0.8710    |  0.4110  |    0.8070     |  0.4359   | [figure](./figures/training_2_accuracy.png) | [figure](./figures/training_2_loss.png) | [figure](./figures/training_2_confmatrix.png) | Insufficient amount of data |
