# MiniSqueezeNet
Build a CNN for multiclass classification using an architecture inspired by the SqueezeNet1 model. The SqueezeNet model produces an accuracy equal to that found with the
AlexNet model but with 50 times fewer parameters thanks to the Fire Module concept.
A Fire Module comprises a first 1*1 convolution followed by two convolutions, a 1*1 and another 3*3, the output volumes of these two convolutions are concatenated. This allows the number of parameters to be considerably reduced.
In this project, it is a question of building a reduced version, "miniSqueezeNet", which contains 4 Fire modules instead of 8 as in the original model.
