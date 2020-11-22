# [Implementing a foveal-pit inspired filter in a Spiking Convolutional Neural Network: a preliminary study ](https://ieeexplore.ieee.org/abstract/document/9207612/)
[Shriya T.P. Gupta](https://scholar.google.com/citations?user=3RRL_0QAAAAJ&hl=en&oi=ao) and [Basabdatta S. Bhattacharya](https://scholar.google.co.in/citations?user=M2PFto0AAAAJ&hl=en&oi=ao)

This repository contains code for the architecture presented in the [paper](https://ieeexplore.ieee.org/abstract/document/9207612/).

This code base is built using [Nengo-dl](https://www.nengo.ai/nengo-dl/) with Tensorflow as the underlying framework for the neuromorphic simulator. The code files are provided in the form jupyter notebooks which can be run as is on [Google Colaboratory](https://colab.research.google.com/notebooks/intro.ipynb).

The experiments have been carried out as described in the paper for the following datasets:

1) The MNIST digit recognition dataset
2) A subset of the Caltech dataset placed in the caltech_subset folder.

The following libraries need to be installed other than the basic libraries like numpy, scipy etc. to run the colaboratory notebooks (with installation commands and versions already provided in the files in this repository):

Nengo, Nengo-dl, Pillow, Skimage

The outputs plots from the network are stored as .png images in the results folder.

## Citation

If you find this project useful in your research, please consider citing:

```
@inproceedings{gupta2020implementing,
  title={Implementing a foveal-pit inspired filter in a Spiking Convolutional Neural Network: a preliminary study},
  author={Gupta, Shriya TP and Bhattacharya, Basabdatta Sen},
  booktitle={2020 International Joint Conference on Neural Networks (IJCNN)},
  pages={1--8},
  year={2020},
  organization={IEEE}
}
```
