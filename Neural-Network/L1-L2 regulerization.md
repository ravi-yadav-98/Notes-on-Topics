## L1 and L2 Regulerization: 
- [Link](https://rawgit.com/danielkunin/Deeplearning-Visualizations/master/regularization/index.html)

### L2: 
   - The update rules are different. While the L2 “weight decay” 2 \alpha\lambda w2αλw penalty is proportional to the value of the weight to be updated, 
   - For L2, the smaller the ww, the smaller the penalty during the update of ww and vice-versa for larger ww
   - Too small” \lambdaλ constant: there’s no apparent effect.
   - Appropriate” \lambdaλ constant: the weight values decrease following a centered distribution that becomes more and more peaked throughout training.
   - “Too large” \lambdaλ constant: All the weights are rapidly collapsing to zeros, and the model obviously underfits because the weight values are too constrained.
   - 


### L1:
   - For L1, the penalty is independent of the value of ww, but the direction of the penalty (positive or negative) depends on the sign of ww
   - This results in an effect
   - “Too large” \lambdaλ constant: All the weights are rapidly collapsing to zeros, and the model obviously underfits because the weight values are too constrained.
   -  called “feature selection” or “weight sparsity”. L1 regularization makes the non-relevant weights 0.
   - Too small” \lambdaλ constant: there’s no apparent effect.
   - Appropriate” \lambdaλ constant: many of the weights become zeros. This is called “sparsity of the weights”
   - The value of the penalty is \alpha\lambdaαλ (generally very small). 
   -  It constrains the subset of weights that are “less useful to the model” to be equal to 0.
   -  **The weight sparsity effect caused by L1 regularization makes your model more compact in theory, and leads to storage-efficient 
   compact models that are commonly used in smart mobile devices.**
   - 
