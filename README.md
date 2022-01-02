# mlsec
Machine Learning Security

The purpose of this repository is to demonstrate attacks and defensive techniques to machine learning systems and algorithms. Also, it will provide tools to set up a Federated Machine Learning (FML) environment alongside implementations of FML algorithms with Independent and Identically Distributed (IID) Data.

Short term goal is to have an FML setup and a working implementation of the FedAVG Algorithm using Differential Privacy.

Later on, the repository will contain references to Papers, libraries, and resources.

The long-term goal is to have other algorithms implementations (e.g., FedSGD, FedProx, FedDANE) and demonstrate more sophisticated attacks and defense techniques for different data distributions scenarios other than IID, such as Non-IID and Non-IID Unbalanced.

## Env Setup and Deps

### Install anaconda
https://docs.anaconda.com/

### Create the environment and activate it

```
$ conda create -n mlsec python=3 -y
$ conda activate mlsec
```
### Install the dependencies

```
$ pip install notebook
$ pip install torch torchvision 
```

### Optional dependencies
```
$ pip install matplotlib ipynb
```

Or just run `!pip install <libname>` for matplotlib and ipynb inside the notebook when asked for

## Initialize the Notebook
```
$ jupyter notebook
```

Pick one of the existing notebooks or create a new notebook using python3 to run experiments.
