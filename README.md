# CIFAR-10 using CNNs

This project aims to predict the labels of the CIFAR-10 datset. This project uses Keras to implement deep learning. Almost all the code is in the form of IPython notebooks.
Final accuracy - [87.94%](https://nbviewer.jupyter.org/github/09rohanchopra/cifar10/blob/master/cifar10-improved-cnn.ipynb#Predictions)

## Mis-classifications

![Mis-classified outputs](http://imgur.com/AFJHiVd.png)

## Metric graphs

![Metrics](http://i.imgur.com/crmkpKg.png)

## Dependencies

* Jupyter 
* Keras
* Tensorflow
* Matplotlib
* Pickle

## Contents

1. Helper - Helper functions which decode and fetch the data to the IPython notebooks
2. Basic - IPython notebook to test helper functions and list images in the dataset
3. Simple CNN - IPython notebook with a simple implementation of CNN taken from the Keras examples
4. Improved CNN - IPython notebook which uses a pure CNN network with image augmentations to implove the accuracy of the model
5. Model files (.h5) - Different saved models

## Getting started

The quickest way to run these on a fresh Linux machine is to follow this tutorial: 
[![Kerai-Labs](https://i.imgur.com/bgDoo0z.png)](https://www.youtube.com/watch?v=yDIKSykkgOk)


Then clone this repo and start Jupyter Notebook:

```
git clone https://github.com/09rohanchopra/cifar10.git
cd cifar10
jupyter notebook
```

## Tutorial
[![Kerai-Labs](https://i.imgur.com/zSIGros.png)](https://www.youtube.com/playlist?list=PLYsZZgiwMqKQeEL-eibMXAkDIsm5pKrh1)

## Feedback
If you have ideas or find mistakes [please leave a note](https://github.com/09rohanchopra/cifar10/issues/new).

## License
[MIT](https://github.com/09rohanchopra/cifar10/blob/master/LICENSE)