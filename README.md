# How to install Tensorflow GPU on RTX 3060

1. Install Cuda-Toolkit [version 11.7] for Windows
2. Install CUDNN [version 8.4.1] for Windows
3. Install Anaconda for Windows
4. Execute these commands

```bash
conda create --name tf-gpu python=3.10
conda activate tf-gpu
conda install -c conda-forge cudatoolkit=11.7 cudnn=8.4.1
conda install -c conda-forge jupyter notebook pandas scikit-learn scikit-image matplotlib xmltodict scikit-learn-intelex
conda install -c pytorch -c conda-forge pytorch torchvision torchaudio
pip install tensorflow-gpu
```
