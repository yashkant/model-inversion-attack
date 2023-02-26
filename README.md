# Model-Inversion-Attack

This a TensorFlow Implementation of the Model Inversion Attack introduced with [Model Inversion Attacks that Exploit Confidence Information and Basic Countermeasures](https://dl.acm.org/citation.cfm?id=2813677) (Fredrikson Et al.)

The gradient step and the final output of the attack loop is pre-processed with ZCA whitening and Global Contrast Normalization with Pylearn2, this helps to preserve the facial features present in the input dataset. 

# Directions to Use 

```bash
conda env create --prefix="./.venv" -f environment.yml
conda activate "./.venv"
jupyter notebook Inversion.ipynb
```

# Face dataset

The AT&T Face Dataset in this repository was downloaded from [here](https://www.kaggle.com/kasikrit/att-database-of-faces/data) (formerly available [here](http://www.cl.cam.ac.uk/research/dtg/attarchive/facedatabase.html)).

