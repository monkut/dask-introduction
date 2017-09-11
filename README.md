# Introduction to Dask README 

> Used for demo in pyconjp 2017 talk
> Talk available at: https://youtu.be/fJafLN8oCf0

The cluster setup steps for using EC2 available at: 
https://gist.github.com/monkut/025e720d703e4d220b6d15496ba3756a

This repository is for providing a jupyter notebook for introducing the basics of dask.
Dask is a parallel data processing library for python with strong intregration with Pandas and numpy.

## Installation

The dask library and related components can be installed `pip`, python's standard installation method:

> Note: This assumes that python3 is used.

1. Install core components:
```
python -m pip install numpy pandas h5py Pillow matplotlib scipy toolz pytables fastparquet
python -m pip dask[complete]
```

2. Install optional visualization components:
```
python -m pip install graphviz bokeh
```

> Note may need to install related graphviz base binaries:
> On MAC:
> brew install graphviz


