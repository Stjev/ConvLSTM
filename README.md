# ConvLSTM
An implementation of the ConvLSTM layer proposed in [Convolutional LSTM Network: A Machine Learning Approach for Precipitation Nowcasting](https://arxiv.org/abs/1506.04214) where the implementation was based on [this post](https://sladewinter.medium.com/video-frame-prediction-using-convlstm-network-in-pytorch-b5210a6ce582).

- The `lstm.ipynb` shows an example of a default [PyTorch LSTM layer](https://pytorch.org/docs/stable/generated/torch.nn.LSTM.html). The task is to sum elements from a sequence.
- The `conv_lstm.ipynb` shows the ConvLSTM layer implementation. The task in this notebook is summing 3-channel images of random numbers. 
