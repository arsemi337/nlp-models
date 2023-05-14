# Training details

All the trainings are fine-tuning of ***bert-base-uncased*** model. The used dataset is available in the [dataset .pkl file](../../../data/dair-ai-emotions/merged_training.pkl). Originally it consists of 416809 data samples

| Training no. | Data samples | Train set % | Val set % | Test set % | Batch size | Epochs | Best epoch | Fitting time | Train accuracy | Train loss | Val accuracy | Val loss | Test accuracy | Test loss |               Accuracy figure               |      Notes    |
|:------------:|:------------:|:-----------:|:---------:|:----------:|:----------:|:------:|:----------:|:------------:|:--------------:|:----------:|:------------:|:--------:|:-------------:|:---------:|:-------------------------------------------:|:-------------:|
|      2       |     10k      |     80%     |    10%    |    10%     |     16     |   10   |     3      |   4min 34s   |     0.9524     |   0.1111   |    0.9310    |  0.1696  |    0.9130     |  0.2452   | [figure](./figures/training_2_accuracy.png) | Model overfit |
