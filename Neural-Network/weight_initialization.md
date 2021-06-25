### Weight Initialization in Neural Networks
- The aim of weight initialization is to prevent layer activation outputs from exploding or vanishing during the 
course of a forward pass through a deep neural network. 
-  To sum it up, if weights are initialized too large, the network won’t learn well. The same happens when weights are initialized too small.
-   **keeping the standard deviation of layers’ activations around 1 will allow us to stack several more layers in a 
deep neural network without gradients exploding or vanishing.**
-  The initialization step can be critical to the model’s ultimate performance,
-  A too-large initialization leads to exploding gradients
-  A too-small initialization leads to vanishing gradients

- **To prevent the gradients of the network’s activations from vanishing or exploding, we will stick to the following rules of thumb:**
     1. **The mean of the activations should be zero.**
     2. **The variance of the activations should stay the same across every layer.**

### Method of weight initialization:
1. Constant value: --i.e zeros or once
2. Uniform or Normal initialization
3. Lecun Uniform/Normal-->limit = np.sqrt(3 / float(F_in)) 
4. Glorot/Xavier Uniform/Normal -->   limit = np.sqrt(2 / float(F_in + F_out))
    - maintain identical variance for all layers
    - Xavier initialization works with tanh activations. 
    - All bias parameters are initialized to zero.
    - 
6. Kaiming Uniform/normal --- used for very deep network (imit = np.sqrt(6 / float(F_in)))
     - when ReLu activation is used in case of Deep Networks
     - 
A too-small initialization leads to vanishing gradients
- To prevent the gradients of the network’s activations from vanishing or exploding, we will stick to the following rules of thumb:

The mean of the activations should be zero.
The variance of the activations should stay the same across every layer.
