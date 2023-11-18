# Possible Exam Questions by Stella from Last Lecture

## General

- know the Euclidean Norm + Equation!!
- it's more important to understand concepts, some equation should be known, but they don't make or break the exam
- most likely no time for derivations in the exams

## Topic Specific

**Classification**

Q1: _Classification Methods discussed in this course:_
- SVM
- multinomial regression
- ...

**Supervised vs. Unsupervised**
Q2: _What is the difference between supervised vs. unsupervised methods?_
Q3: _Is ... an example of a supervised or unsupervised problem?_
Q4: _How can you tell if a method overfits?_

Note: there a also mixed methods:
- weakly supervised: noisy labels
- semi-supervised: partly labelled

**Linear Regression Models**

Q5: _linear in regard to what?_
-  the weights

Q6: _What are different effects of the L1 and L2 norm?_
- Lasso regularizes towards sparsity
- smoothness of the function changes
- ...

Q7: _What is the distribution of the error (in a standard linear regression model)?_ (s. slide 4)
- normal distribution with mean 0

Q8: if given two plots of errors: _Which follows more closely normal distribution?_
- look at mean (should be 0)
- std deviation (distance to axis) should be constant

Q9: _difference between Maximum Likelihood and MAP (Maximum...)?_
- for the posterior we have extra knowledge
- ...

**Bayesian Regression**
Q10: _How to retrieve a line estimate without data?_
- check out visualisation from bishop book (see slide)

**Linear models for classification:**

Q11: _Can you generate new examples with linear discriminant functions? (slide 7)_
- no generation, can only discriminate between classes

**Probabilistic Generative Model**

Q12: given a Gaussian Distribution for each class: _which assumptions can we make?_
- sth with correlation
Q13: _in which of the four cases can you assume that features are uncorrelated?_ (slide 8)
- case 4


**Kernel Methods & SVM**

Q14: _How can you use a Kernel function to create a feature function?_

Q15: _How can you train a SVM?_

Q16: _idea/concept of a SVM_
- find a hyperplane that best separates classes; you only need few datapoints to define this hyperplane


**PCA**

Q17: _what are the principal components and what properties do they have?_
- purpose of PCA: dimensionality reduction
- maximise variance
- components should be uncorrelated (shouldn't share much information)

Q18: _What is the difference between design matrix vs. data matrix?_
- data : collection of data vectors (x1 = cloumn 1)
- design: data matrix added column of 1 in the beginning

**GMM and EM**

--> unsurpervised models / clustering

Q19: _What are the steps E and M in EM (if we look at this specific problem)?_
Q20: _What are we maximising? What variables are we looking at?_
Q21: _How can GMM be used to generate data?_

**Neural Nets**

Q22: _Explain Backpropagation_
Q23: _Why do you need do perform it?_
- updating the weights
Q24: _What are common problems when training deep neural nets?_
Q25: When shown some sort of graph: _Did this one overfit?_ 

**Hyperparameter Optimisation & Interpretability**

Q26: _Effect of different choices of hyperparameters (e.g. high vs. low learning rate)_
Q27: _Detect biased models though heat maps_ (see pics on slide 13)

**Gradient-weighted Class Activation Mapping**
Q28: _How can you identify over- and underfitting?_ (e.g. when shown loss curve)


**Sequence Data & RNN**

Q29: _Types of tasks in sequence learning_
Q30: _explain concept of backpropagation through time_
Q31: _What is the difference between LSTM and GRU? What do these abbreviations mean? Why are they named like this?_
Q32: _What was a problem people wanted to solve by using LSTM?_

**HMMs**

Q33: _What is a Markov Chain?_
Q34: _What is the difference between Markov Chains and Hidden Markov Models? Or are both the same?_

**Embeddings & Transfer Learning**

Q35: _What is transfer learning?_

Q36: _What does it mean to freeze weights or layers?_


**Advanced Sequence Learning**

Q37: _What is the key component of a transformer?_
- attention heads
- equation on slide 20 helpful to have in mind

**Approximate Inference**

Q38: _What are different approaches?_
- Kullback Leibler
- Evidence Lower Bound

Q39: _What is the main idea behind the Mea Field Approach?_
- factorisation

**Autoencoder vs. Variational AUtoencoders**

Q40: _What is the difference between the two?_
Q41: _What is the reparamerization trick and why is it needed for VAE?_
- you cannot do backpropagation thorugh probabilistic nodes
- not expected to write down the math behind it

**GAN vs. Diffusion Models**

Q42: not expected to write down equation, _but where is it coming from? (Bernoulli)_
- be able to write down prob distribution of Bernoulli
- not expected to know pdf of Gaussian distribution

Q43: _Which component in a diffusion model is a Markov chain?_

**GNNs**

Q44: _What is an adjacency matrix?_

**Meta-Learning and Reinforcement Learning**

Q45: _What is meta-agnostic Meta-Learning?_
Q46: _How is reinforcement learning different from (un)supervised ML?_
