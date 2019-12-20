# Classification-using-Neural-Network
A Convolution Neural Network is a deep learning algorithm which can take in an input, assign weights to various features and be able to differentiate the inputs into various categories or classes. The architecture of CNN is analogous to that of the connectivity pattern of neurons in human brain and was inspired heavily by the visual cortex. In this project the baseline model has the following features -

- The first convolution layer has 6 feature maps and the convolution kernels are of size 3x3. This layer uses stride equal to 1. Stride denotes the number of pixels shifts over the input matrix. When stride is 1, the filters are moved by 1 pixel at a time. 

- The convolution layer is followed by a max pooling layer. The poling is 2x2 with stride equal to 1. 

- The max pooling layer is connected to the next convolution layer with 16 feature maps. The size of the kernel is 3x3 and this layer too uses stride equal to 1. 

- The second convolution layer is followed by a max pooling layer. The pooling is 2x2 and uses a stride equal to 1. 

- The max pooling layer is fully connected to the next hidden layer with 120 nodes and ReLU as the activation function. 

- The fully connected layer is followed by another fully connected layer with 84 nodes and ReLU as the activation function, then connected to a SoftMax layer with 10 output nodes which corresponds to 10 classes/categories present in the data.
