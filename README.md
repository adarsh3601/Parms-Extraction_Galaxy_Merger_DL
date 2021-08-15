
# Parms-Extraction_Galaxy_Merger_DL

To Find Dynamical Parameters of Galaxy 

## Step 1: Clone or Download the repository
Use 

## Step 2: Installation of Libraries 
Installation of Autokeras
Can Refer to https://github.com/keras-team/autokeras
or can simply use 
```python
pip install git+https://github.com/keras-team/keras-tuner.git
pip install autokeras
```
For python3
```python
python3 -m pip install git+https://github.com/keras-team/keras-tuner.git
python3 -m pip install autokeras
```
Installation of Tensorflow
```python
pip install tensorflow
```

### Case 1: 
For using Pretrained Model or for gSa and gSb interaction: 

Run Detect.py for corresponding Images 

Note here:
1. Model is trained for Image of dimensions 64x64x3. To run model flawlessly please resize the image to the 64x64x3 dimensions
2. The folder "model" in cloned repository should be 94.8 MB (9,94,96,042 bytes). If it dosen't match, it is advised to download from [https://drive.google.com/drive/folders/1lwhV48n1PcURtrTygO_GF8nZYm1Xw5Go?usp=sharing]

### Case 2:
For training the model 
