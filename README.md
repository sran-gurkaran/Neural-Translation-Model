# Neural-Translation-Model
An English-to-German Neural Translation Model based on Encoder-Decoder LSTM Architecture

A Machine Translation model is developed based on Deep Neural Network using TensorFlow2
For training the model, deu-eng dataset from Kaggle is used.

Model Architecture,
The model can be broadly divided into an Encoder Network- consisting of a pre-trained embedding layer, a masking layer, and an LSTM layer,
and a Decoder Network - consisting of an embedding layer with trainable parameters, an LSTM layer, and a Dense layer for output logits.

While building the Encoder and Decoder Networks, Custom Layer and Model Sub-classing functionality provided by TensorFlow2 is exploited.
