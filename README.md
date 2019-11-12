# CNN
1. Convolution : Convolution is an operation used in neural networks for feature extraction from original source eg: Image.

2. Filters/Kernels : Filters/kernels/feature extractors all means samething. They are used to extract features employing convolution operation.

3. Epochs : Epoch is number of times neural network is presented with complete set of training data. 1 epoch means entire data is presented once, 2 epoch means entire data is presented twice etc.

4. 1x1 Convolution : 1X1 convolution means we are using a kernel size of 1x1 for convolution operation. It is essentially used in transition layer. It is used to contextually link the channels together. eg: A 512 page book where all physics, chemistry, maths chapters are jumbled. 1X1 convolution will help to combine all physics channels into 1 channel, chemistry into 1 & maths into 1. Effectively 512 channels get reduced to 3 channels in this example.

5. 3x3 Convolution : 3X3 convolution is the most common kernel used for feature extraction. It uses 3X3 matrix for convolution. Helps to reduce the size of image by extracting only essential features. A 3x3 used on a 5x5 image will give us 3x3 image. 3X3 is most commonly used because of axis symmetry it can offer due to odd size. 

6. Feature maps : Feature map is the output of a convolution operation performed by a kernel. If we convolve a 3x3 kernel over 400x400 pixel image we will get 398x398 as output. This is the feature map. It is the place where extracted features at each layer after convolution operation are stored. This feature map will be the input of next kernel for further extractions.

7. Activation function : This will decide which neuron to be activated & on what magnitude based on the input it receives. This concept is inspired from idea of brain. All our brain neurons wont get triggered at same time. For example seeing a snake certain set of neurons will get activated  whereas seeing a puppy will activate different set of neurons. Commonly used activation functions are ReLu and sigmoid.

8. Receptive Field : Receptive field is the size/area through which Kernel can see an image at a time. There are 2 categories - local and Global. Local receptive field -> Size of kernel on that particular layer. Global receptive field -> Size of final kernel which means neural netrwork will see the entire image through this final sized kernel.
