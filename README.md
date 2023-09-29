# text-to-image generator

set up an environment for the program with following steps

1. conda create -n stable-diffusion python=3.10.6
2. conda install -c "nvidia/label/cuda-11.7.1" cuda-toolkit
3. conda install pytorch torchvision torchaudio pytorch-cuda=11.7 -c pytorch -c nvidia
4. pip install -r C:\code\repositories\text-to-image\requirements.txt   


for testing cuda and driver versions:
nvcc --version
nvidia-smi
python -c "import torch; print(torch.cuda.is_available())"