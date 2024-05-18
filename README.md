# UIPA
This is the code respository of **UIPA**, which is a cross-platform recommendation framework based on user and item prototype alignment. 

The repository contains the following contents:

1. **Datasets**: This folder contains the dataset files necessary to run the code.
2. **Models**: This folder contains the models that have been trained.

## 1 Download
Due to the large size of the data files, we use Git LFS to store them. you can utilize the following script to download this repository.
```
# Initialize LFS
git lfs install

# Download this repository by LFS
git lfs clone # address of this repository
```

## 2 Setup
you can utilize the following script to install the required packages. The corresponding file `requirements.txt` is provided under the main directory.
```
# Create the virtualenv UIPA
conda create -n UIPA python=3.8

# Activate the virtualenv UIPA
conda activate UIPA

# Install requirements with pip
pip install -r requirements.txt
```

## 3 Quick Start
Please make sure the packages required in the `requirements.txt` are properly installed. Then you can utilize the following script to run the UIPA:
```
python main.py
```
If you want to skip the training part and use the trained model, you can utilize the following script:
```
python main.py --pretrained_model=1
```

## 4 Parameters setting
All the parameters along with their descriptions are in `parse.py`. You can also run UIPA with any combination of parameters you want.
