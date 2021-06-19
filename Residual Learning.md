## Residual Learning 
### Paper: [Residual Learning](https://arxiv.org/pdf/1512.03385.pdf)
### Paper: [Wide Residual Network](https://arxiv.org/pdf/1605.07146.pdf)
### Paper: [ResNeXt](https://arxiv.org/pdf/1611.05431.pdf)

#### Motivation for Residual Network
-  Network depth is of crucial importance in neural network architectures, but deeper networks are more difficult to train.
-  The residual learning framework eases the training of these networks, and enables them to be substantially deeper 
-  Can be used for both visual and non-visual tasks
-  **The degradation problem in deeper networks**:- As network depth increases, accuracy gets saturated and then degrades
rapidly. This is not due to overfitting but adding more layers to network
- **ResNets tackle the issue of performance degradation associated with the deep neural networks as they go deeper into the network.**
- **Deep Residual architecture. With a depth of up to 152 layers, the model was able to achieve an error of 3.57% on the ImageNet test set and won 
1st place on the ILSVRC 2015 classification task. The architecture is known as the ResNet and is a stack of ‘Residual Blocks’.**

### Residual Network ResNet
- A residual network is formed by stacking several residual blocks together.
- ResNets are capable of forming an identity function that maps to an activation earlier in the network 
when a specific layer’s activation tends to zero deeper in the network.
-  in this activation of earlier layers (a) is added to deeper layers that prevent deeper layers's activation to get zero so prevent performance reduction
-  This does not improve performance but only stops performance degradation. 
-  Dimension of layer l should be same to l+2 layer for residual connection(skip connection)
-  Two types of Residual Blocks
1. Identical Residual Block : Dimensions are same
2. Convolution Residual Blocks: **In this type of residual block, the skip-connection consists of a convolutional layer to resize the output of the 
shortcut path to be of the same dimension as that of the main path.**


![image](https://user-images.githubusercontent.com/85448160/122653178-aded2e80-d160-11eb-9960-9045765762d2.png)
