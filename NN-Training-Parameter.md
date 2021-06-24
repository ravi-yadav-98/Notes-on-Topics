###Training Parameters in Neural Network
- [Read Link:](https://stats.stackexchange.com/users/64943/itdxer)
### Questions which may arrise:
1. **Why there is large gap between train and validation loss/accuracy ---overfitting??**
2. **Reason for fluctuating training/validation loss??**
3. **Reason for slow decrease of loss ??**
4. **How to Reduce overfitting ??**
5. **Reason for Validation accuracy constant but training accuracy improves??**
-----------------------------------------------------------------
### Q&A:1  Validation accuracy constant but training accuracy increases??
- Answer: [link:](https://stackoverflow.com/questions/52356068/validation-accuracy-constant-in-keras-cnn-for-multiclass-image-classification)
- Decrease Learning rate in Adam (1e-6), SGD( 1e-2/e-3)
- Decrease model complexity
- Make training data balance
- if data is imbalance: use class_weight in keras.fit()
- Extensive data augumentation
- [github issue](https://github.com/keras-team/keras/issues/1597)
- -------------------------------------------------------------------------------------------------------------


- epoch: one forward pass and one backward pass of all the training examples
- batch size = the number of training examples in one forward/backward pass. The higher the batch size, the more memory space you'll need.
- 1 pass = 1 farward pass + 1 backword pass
- iteration: total no of examoles/ batch size ---per epoch

### Gradient Descent Approaches:
1. Batch GD  ---> Entire data is used per update of gradient(low speed, fast accuracy convergence direction) 
2. Stochastic GD: --> one sample per update of gradeint (high speed, low accuracy convergence)


Significance:
### Batch Size 
- No. of samples per gradient update
- Keras.fit(batch_size= 32) --default
- require less memory
- The smaller the batch the less accurate the estimate of the gradient will be.
- 
