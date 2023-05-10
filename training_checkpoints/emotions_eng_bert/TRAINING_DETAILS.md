# Training details

All the trainings are fine-tuning of ***bert-base-uncased*** model. The used datased is available in the [dataset .pkl file](../../data/dair-ai-emotions/merged_training.pkl). Originally it consists of 416809 data samples

| Training no. | Data samples | Train set % | Val set % | Test set % | Batch size | Epochs | Val accuracy | Val loss | Test accuracy | Test loss |
|:------------:|:------------:|:-----------:|:---------:|:----------:|:----------:|:------:|:------------:|:--------:|:-------------:|:---------:|
|      1       |     40k      |     80%     |    10%    |    10%     |     16     |   10   |    0.9327    |  0.1633  |     T.B.D     |   T.B.D   |

- *training 1* - first test training, with ***batch_size = 8***, ***train_epochs = 3*** and full dataset from the [dataset .pkl file](../../data/dair-ai-emotions/merged_training.pkl) (416809 data samples)
- *training 2* - training with ***batch_size = 32***, ***train_epochs = 10*** and dataset limited to 40k data samples. Additionally, an early stopping callback has been added
- *training 3* - training with ***batch_size = 16***, ***train_epochs = 10***.