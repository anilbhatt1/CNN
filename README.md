# CNN
Convolution : Convolution is an operation used in neural networks for feature extraction from original source eg: Image.

Filters/Kernels : Filters/kernels/feature extractors all means samething. They are used to extract features employing convolution operation.

Epochs : Epoch is number of times neural network is presented with complete set of training data. 1 epoch means entire data is presented once, 2 epoch means entire data is presented twice etc.

1x1 Convolution : 1X1 convolution means we are using a kernel size of 1x1 for convolution operation. It is essentially used in transition layer. It is used to contextually link the channels together. eg: A 512 page book where all physics, chemistry, maths chapters are jumbled. 1X1 convolution will help to combine all physics channels into 1 channel, chemistry into 1 & maths into 1. Effectively 512 channels get reduced to 3 channels in this example.

3x3 Convolution : 3X3 convolution is the most common kernel used for feature extraction. It uses 3X3 matrix for convolution. Helps to reduce the size of image by extracting only essential features. A 3x3 used on a 5x5 image will give us 3x3 image. 3X3 is most commonly used because of axis symmetry it can offer due to odd size. 
