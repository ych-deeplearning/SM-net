# Enhanced Positional Awareness in Camouflaged Object Segmentation via ShuffleSSM [The Visual Computer 2025]

## Installation
pip install torch==1.13.0 torchvision==0.14.0 torchaudio==0.13.0 --extra-index-url https://download.pytorch.org/whl/cu117\n
pip install packaging
pip install timm==0.4.12
pip install pytest chardet yacs termcolor
pip install submitit tensorboardX
pip install triton==2.0.0
pip install causal_conv1d==1.0.0  # causal_conv1d-1.0.0+cu118torch1.13cxx11abiFALSE-cp38-cp38-linux_x86_64.whl
pip install mamba_ssm==1.0.1  # mmamba_ssm-1.0.1+cu118torch1.13cxx11abiFALSE-cp38-cp38-linux_x86_64.whl
pip install scikit-learn matplotlib thop h5py SimpleITK scikit-image medpy yacs

## Other requirements
Linux System
NVIDIA GPU
CUDA 12.0+

## Dataset
COD-10K:https://aistudio.baidu.com/datasetdetail/100128
COD-FSS:https://github.com/CAM-FSS/FSS-COD


## Train
python train.py


