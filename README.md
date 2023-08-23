# RED-Cluster-GPU
How to use Moffitt RED for GPU loads

srun -c 4 --mem 32g --gres=gpu:a30:1 --pty bash

% or use grab node



conda create --name dl3114 python=3.11.4

pip3 install torch torchvision torchaudio  # must use pip3

import torch
torch.cuda.is_available()
