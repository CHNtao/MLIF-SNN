# MLIF-SNN

***Memristive Leaky Integrate-and-Fire Neuron and Learnable Straight-Through Estimator in Spiking Neural Networks***

This paper has been submitted to ***Cognitive Neurodynamics***. The complete code will be released when our paper is accepted.

## Figures


## Requirements
*  Python 3.9.7
*  Torch 1.10.1
*  Torchvision 0.11.2
*  Numpy 1.22.0


## Datasets
*  [CIFAR10](http://www.cs.toronto.edu/~kriz/cifar.html) 
*  [CIFAR100](http://www.cs.toronto.edu/~kriz/cifar.html)
*  [DVS-CIFAR10](https://figshare.com/s/d03a91081824536f12a8)
*  [DVS-Gesture](https://research.ibm.com/interactive/dvsgesture/)
## TO DO
The complete layers.py/models.py/train.py script will be release soon.
* This inference weight is to reproduce 84.40% on DVS-CIFAR10 with VGGSNN.[Inference model](https://drive.google.com/file/d/174q7vxH_dOUtlXE-YIsBIeEUToz--aiH/view?usp=drive_link)

## Usage
Run train.py to train MLIF-SNN from scratch, if T=2 for CIFAR10, it will take about six hours on GeForce RTX 3090.
