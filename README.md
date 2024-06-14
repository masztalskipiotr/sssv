# Self-supervised contrastive speaker verification

This is a jupyter notebook project for "Python for scientific research" course. You can use this template to train your own self-supervised models. The example provided is trained on a very small dataset (VoxCeleb2 [1] subset located also in this repository).

## Setup environment

Before running the notebook, create a virtual environment, activate it and install required packages.

```
virtualenv venv -p python3.10
source venv/bin/activate
pip install -r requirements.txt
```

## Run

The main code is located in the `main.ipynb` file. You can run it on your local machine or in Google Colab.

[1] A. Nagrani, J. S. Chung, A. Zisserman
VoxCeleb: a large-scale speaker identification dataset
INTERSPEECH, 2017
