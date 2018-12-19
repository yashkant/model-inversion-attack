# Model-Inversion-Attack

This a TensorFlow Implementation of the Model Inversion Attack introduced with [Model Inversion Attacks that Exploit Confidence Information and Basic Countermeasures](https://dl.acm.org/citation.cfm?id=2813677) (Fredrikson Et al.)

The gradient step and the final output of the attack loop is pre-processed with ZCA whitening and Global Contrast Normalization with Pylearn2, this helps to preserve the facial features present in the input dataset. 


The important dependencies of this project include: 
- TensorFlow 
- Pylearn2
- Matplotlib

In case you run into some trouble installing the dependencies take a look at this [issue](https://github.com/yashkant/Model-Inversion-Attack/issues/1). 

# Directions to Use 

1. Download the AT&T Face Dataset from [here](http://www.cl.cam.ac.uk/research/dtg/attarchive/facedatabase.html)
2. Extract the dataset and replace the path variable in the 3rd cell of the inversion notebook. 
