## Setup

This project is implemented in python 3.7 and torch 1.13.0. Follow these steps to setup your environment:

1. [Download and install Conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html "Download and install Conda")
2. Create a Conda environment with Python 3.7
```
conda create -n c3 python=3.7
```
3. Activate the Conda environment.
```
conda activate c3
```
4. Install the base requirements:
```
conda install ipykernel
ipython kernel install --user --name=c3
pip3 install -r requirements.txt
conda install -c conda-forge ipympl
```
5. Open jupyterlab
```
jupyter-lab
```