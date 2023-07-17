## Audio MNIST: Speech Classification ##

This Colab notebook provides an example of processing the [Audio MNIST](https://www.kaggle.com/datasets/sripaadsrinivasan/audio-mnist) dataset from Kaggle.
The dataset contains 30,000 total audio recordings of spoken digits (0-9) from 60 different speakers (500 recordings per speaker).

The experiments are organized in a K-folds manner (K=4), where splits are with respect to speakers (as opposed to individual samples). 
This means there will be no overlap of speakers represented in the training & validation sets.

Like the original MNIST, the goal is classification, but now with spoken audio data.
