# Training details

All the trainings are fine-tuning of ***bert-base-uncased*** model. The used dataset is available in the [dataset .json file](../../../data/news_headlines_for_sarcasm_detection/Sarcasm_Headlines_Dataset_v2.json). Originally it consists of 28619 data samples.

| Training no. | Data samples | Train set % | Val set % | Test set % | Batch size | Epochs | Best epoch | Fitting time | Train accuracy | Train loss | Val accuracy | Val loss | Test accuracy | Test loss |               Accuracy figure               |             Notes              |
|:------------:|:------------:|:-----------:|:---------:|:----------:|:----------:|:------:|:----------:|:------------:|:--------------:|:----------:|:------------:|:--------:|:-------------:|:---------:|:-------------------------------------------:|:------------------------------:|
|      1       |     10k      |     80%     |    10%    |    10%     |     16     |   10   |     2      |   2min 33s   |     0.9571     |   0.1203   |    0.8910    |  0.2818  |    0.8860     |  0.2503   | [figure](./figures/training_1_accuracy.png) | First attempt, could be better |
