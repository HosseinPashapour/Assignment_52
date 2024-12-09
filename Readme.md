# Assignment 52
# Hello Deep learning


* **In this notebook (`DeepLearnin_vs_MachineLearning.ipynb`) I trained and evaluated same MLP(MachineLearning) and CNN+MLP(DeepLearning) models with different datasets using [Tensorflow](https://github.com/tensorflow/tensorflow) Library**



## Description

+ For each dataset I've made a MLP model and a CNN+MLP model. The results of two model for each dataset are shown in four below part.
+ These dataset's names are mnist, fashion mnist, cifar10 and cifar100. 



# RESULTS 
these are test accuracy results :
We see that , in complex datasets like Cifar10 or Cifar100 , which contains more detailed and diverse images , using DeepLearning gives more test accuracy compared with MLP . 


### Accuracy in Test

|           |       MLP (Machine Learning)      |        CNN + MLP (Deep Learning)    |
|---------: | :----------------: |:----------------: |
|    Mnist            |       0.9778           |        0.9923           |
|    Fashion Mnist            |        0.8794           |        0.9153           |
|    Cifar 10            |       0.3937           |        0.7204           |
|    Cifar 100            |        0.2010         |        0.3756           |  


## How to Install
Run following commend :
```
pip install -r requirments.txt
```

## How to Run
```
Run DeepLearning_vs_MachineLearning.ipynb file in jupyter notebook
```


