### Neural Architecture Search: NAS
- Automated way of creating optimal neural network archtecture (Not manual)
- Neural Architecture Search (NAS), the key for creating new models, which is run underneath AutoML.
### [NAS Survey Paper](https://jmlr.org/papers/v20/18-598.html)
### Three steps of NAS:
1. Search Space
2. search strategy
3. performance estimation strategy

### NEW METHOD
- **BigNAS: find suitable models for suitable hardware**
- BigNAS is a novel paradigm for NAS, which has proved to surpass state-of-the-art ImageNet classification models 
searches in a wide range of hardware architectures.

-------------------------------------------------------------------------------------------------------------------
### NAS Survey Paper Summary: 
- [Link](https://jmlr.org/papers/volume20/18-598/18-598.pdf)
- Deep Learning has enabled remarkable progress over the last years on a variety of tasks,such as image recognition, speech recognition, and machine translation.
One crucial aspect for this progress are novel neural architectures. Currently employed architectures have
mostly been developed manually by human experts, which is a time-consuming and errorprone process. Because of this, 
there is growing interest in automated neural architecture search methods. We provide an overview of existing work in this field of 
research and categorize them according to three dimensions: search space, search strategy, and performance estimation strategy.
- The success of deep learning in perceptual tasks is largely due to its automation of the
feature engineering process: hierarchical feature extractors are learned in an end-to-end
fashion from data rather than manually designed.

- This success has been accompanied,
however, by a rising demand for architecture engineering, where increasingly more complex
neural architectures are designed manually
- Neural Architecture Search (NAS), the process
of automating architecture engineering, is thus a logical next step in automating machine
learning
- NAS can be a sub-field of AutoML
- Similar to hyper-parameter optimizationan meta-learning
- We categorize methods for NAS according to three dimensions: search space, search strategy,
and performance estimation strategy
- The objective of NAS is typically to find
architectures that achieve high predictive performance on unseen data


