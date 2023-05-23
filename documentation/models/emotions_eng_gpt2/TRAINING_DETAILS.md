# Training details

All the trainings are fine-tuning of ***gpt2*** model. The used dataset is available in
the [dataset .pkl file](../../../data/dair-ai-emotions/merged_training.pkl). Originally it consists of 416809 data
samples.

| Training no. | Data samples | Train set % | Val set % | Test set % | Batch size | Epochs | Best epoch |      Fitting time       | Train accuracy | Train loss | Val accuracy | Val loss | Test accuracy | Test loss |               Accuracy figure               |               Loss figure               |               Confusion matrix                |                         Notes                          |
|:------------:|:------------:|:-----------:|:---------:|:----------:|:----------:|:------:|:----------:|:-----------------------:|:--------------:|:----------:|:------------:|:--------:|:-------------:|:---------:|:-------------------------------------------:|:---------------------------------------:|:---------------------------------------------:|:------------------------------------------------------:|
|      1       |     40k      |     80%     |    10%    |    10%     |     16     |   10   |     5      |        28min 16s        |     0.9270     |   0.1753   |    0.9050    |  0.2359  |    0.9040     |  0.2448   | [figure](./figures/training_1_accuracy.png) | [figure](./figures/training_1_loss.png) | [figure](./figures/training_1_confmatrix.png) |              First attempt result is fine              |
|      2       |     10k      |     80%     |    10%    |    10%     |     16     |   10   |     10     | 25min 59s (***Colab***) |     0.9323     |   0.1658   |    0.8950    |  0.3023  |    0.7560     |  0.7237   | [figure](./figures/training_2_accuracy.png) | [figure](./figures/training_2_loss.png) | [figure](./figures/training_2_confmatrix.png) | 10k data samples is not enough (8k for training itself |
