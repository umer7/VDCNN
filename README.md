# VDCNN
Keras Implementation of Very Deep Convolutional Neural Network for Text Classification.

## Note
This is the clone of origanal repository of VDCNN which is a simple Keras implementation of VDCNN model proposed by Conneau et al. [Paper](https://arxiv.org/abs/1606.01781) for VDCNN.

Note: Temporal batch norm not implemented. "Temp batch norm applies same kind of regularization as batch norm, except that the activations in a mini-batch are jointly normalized over temporal instead of spatial locations." Right now this project is using regular Tensorflow batch normalization only.

See another [VDCNN implementation in Pytorch](https://github.com/ArdalanM/nlp-benchmarks) if you feel more comfortable with Pytorch, in which the author is having detailed reproduced results as well. See the original [Tensorflow implementation](https://github.com/zonetrooper32/VDCNN/tree/tensorflow_version) as well.

It should be noted that the VDCNN paper states that the implementation is done originally in Touch 7.

## Prerequisites

 - Python3
 - Tensorflow 1.0 or higher
 - keras 2.1.5 or higher
 - Numpy


## Reference
[Orignal Repo of VDCNN](https://github.com/zonetrooper32/VDCNN)
[Original preprocessing codes and VDCNN Implementation By geduo15](https://github.com/geduo15/Very-Deep-Convolutional-Networks-for-Natural-Language-Processing-in-tensorflow)

[Train Script and data iterator from Convolutional Neural Network for Text Classification](https://github.com/dennybritz/cnn-text-classification-tf)

[NLP Datasets Gathered by ArdalanM and Others](https://github.com/ArdalanM/nlp-benchmarks)
