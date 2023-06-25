# Training details

Word2Vec trained with external word2vec model for classification of emotion 0 and 1 (https://github.com/sdadas/polish-nlp-resources#word2vec)

| Training no. | Data samples | Train set % | Val set % | Test set % | Batch size | Epochs | Best epoch | Fitting time | Train accuracy | Train loss | Val accuracy | Val loss | Test accuracy | Test loss |               Accuracy figure               |               Loss figure               |               Confusion matrix                |       Notes       |
|:------------:|:------------:|:-----------:|:---------:|:----------:|:----------:|:------:|:----------:|:------------:|:--------------:|:----------:|:------------:|:--------:|:-------------:|:---------:|:-------------------------------------------:|:---------------------------------------:|:---------------------------------------------:|:-----------------:|
|      2       |     13.334k      |     80%     |    10%    |    10%     |     16     |   20   |     4      |     N.A.     |     0.7439     |   0.5058   |    0.7202    |  0.5367  |    0.7226     |  0.5681   | [figure](./figures/training_2_accuracy.png) | [figure](./figures/training_2_loss.png) | [figure](./figures/training_2_confmatrix.png) | Sentence word2vec |
