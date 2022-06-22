# char-rnn-keras

Multi-layer recurrent neural networks for training and sampling from texts, inspired by [karpathy/char-rnn](https://github.com/karpathy/char-rnn).

### Requirements

This code is written in Python 2, and it requires the [Keras](https://keras.io) deep learning library.

### Usage

All input data should be placed in the `data/` directory. The example `input.txt` is taken from the [Nottingham Dataset (Cleaned)](https://github.com/jukedeck/nottingham-dataset).

To train the model with default settings:
```bash
$ python train.py
```

To sample the model:
```bash
$ python sample.py 100
```

Training loss/accuracy is stored in `logs/training_log.csv`.

### Output
Model 1 - 1 layer LSTM - trained for 50 Epochs:  https://soundcloud.com/aroona-atmaram/model1?utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing (Links to an external site.)

Model 2 - 1 layer LSTM - trained for 100 Epochs: https://soundcloud.com/aroona-atmaram/model2?utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing (Links to an external site.)

Model 3 - 2 layer LSTM - trained for 50 Epochs:  https://soundcloud.com/aroona-atmaram/model3?utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing (Links to an external site.)

Model 4 - 2 layer LSTM - trained for 100 Epochs: https://soundcloud.com/aroona-atmaram/model4?utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing (Links to an external site.)

Model 5- 3 layer LSTM - trained for 50 Epochs:  https://soundcloud.com/aroona-atmaram/model5?utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing (Links to an external site.)

Model 6 - 3 layer LSTM - trained for 100 Epochs: https://soundcloud.com/aroona-atmaram/model6?utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing
