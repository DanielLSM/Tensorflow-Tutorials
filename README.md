# TensorFlow-Tutorials
A set of TensorFlow Tutorials in Jupyter Notebooks for the ISR reading group and ISR robotics team

# Requirements
	
- Python 3.6
- Anaconda
- TensorFlow
- Numpy

# Order of Tutorials

- TensorFlow Structure - Tensors, Operations, Nodes and Graphs
- Polinomial Regression
- Deep Reinforcement Learning
- Convolutional Networks

# To install on Ubuntu 16.04 from scratch

```bash
$ cd /tmp
```
```bash
$ curl -O https://repo.continuum.io/archive/Anaconda3-4.4.0-Linux-x86_64.sh
```
```bash
$ bash Anaconda3-4.4.0-Linux-x86_64.sh
```
Enter...yes.

```bash
$ source ~/.bashrc
```
# Create a conda environment

```bash
$ conda create --name tf-tut python=3.6
```
```bash
$ source activate tf-tut
```
# Install TensorFlow and run a Jupyter Notebook on custom Kernels

```bash
$ pip install tensorflow
```

```bash
$ conda install nb_conda
```

```bash
$ git clone https://github.com/DanielLSM/TensorFlow-Tutorials.git
```

```bash
$ cd && cd TensorFlow-Tutorials
```

```bash
$ jupyter notebook
```




