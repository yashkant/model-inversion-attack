# Model-Inversion-Attack

This a TensorFlow Implementation of the Model Inversion Attack introduced with [Model Inversion Attacks that Exploit Confidence Information and Basic Countermeasures](https://dl.acm.org/citation.cfm?id=2813677) (Fredrikson Et al.)

I have preprocessed the gradient step and the final output of the attack loop with ZCA whitening and Global Contrast Normalization with Pylearn2, this helps to preserve the facial features present in the input dataset. 


The important dependencies of this project include: 
- TensorFlow 
- Pylearn2
- Matplotlib
