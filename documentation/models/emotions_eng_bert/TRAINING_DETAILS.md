# Training details

All the trainings are fine-tuning of ***bert-base-uncased*** model. The used dataset is available in the [dataset .pkl file](../../../data/dair-ai-emotions/merged_training.pkl). Originally it consists of 416809 data samples.

| Training no. | Data samples | Train set % | Val set % | Test set % | Batch size | Epochs | Best epoch | Fitting time | Train accuracy | Train loss | Val accuracy | Val loss | Test accuracy | Test loss |               Accuracy figure               |     Notes     |
|:------------:|:------------:|:-----------:|:---------:|:----------:|:----------:|:------:|:----------:|:------------:|:--------------:|:----------:|:------------:|:--------:|:-------------:|:---------:|:-------------------------------------------:|:-------------:|
|      1       |     40k      |     80%     |    10%    |    10%     |     16     |   10   |     5      |  20min 40s   |     0.9470     |   0.0882   |    0.9388    |  0.1089  |    0.9400     |  0.1220   | [figure](./figures/training_1_accuracy.png) |   Ok result   |
|      2       |     10k      |     80%     |    10%    |    10%     |     16     |   10   |     3      |   4min 34s   |     0.9524     |   0.1111   |    0.9310    |  0.1696  |    0.9130     |  0.2452   | [figure](./figures/training_2_accuracy.png) | Model overfit |
